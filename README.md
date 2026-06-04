# Future Interns

A web platform connecting students with internship opportunities across various industries. Built with Next.js and deployed on Vercel.

🌐 **Live Site:** [futureinterns.vercel.app](https://futureinterns.vercel.app)

## About the Project

Future Interns is an internship-providing platform. It bridges the gap between students and industry by offering real work environment experiences across fields like Web Development, Business, CS & SE, Textile Engineering, and Banking.

The platform includes:
- 🔍 **Internship Listings** — Browse available internships by category
- 📝 **Internship Test Portal** — Assessments to prepare students for professional roles
- 🏢 **Company Registration** — Companies can register and post opportunities
- 👤 **Admin Dashboard** — Manage listings, users, and applications
- 📧 **Contact & Email** — SendGrid-powered communication

## Getting Started

First, clone the repo and install dependencies:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
npm install
```

Then run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Environment Variables

Create a `.env` file in the root of your project and add the following:

```env
MONGODB_URL=mongodb+srv://<username>:<password>@cluster0.ywrv0or.mongodb.net/<db_name>
SENDGRID_API_KEY=your_sendgrid_api_key
NEXTAUTH_URL=https://your-deployment-url/api/auth
NEXTAUTH_SECRET=your_nextauth_secret
```

## Tech Stack

- **Framework:** Next.js
- **Database:** MongoDB Atlas
- **Auth:** NextAuth.js
- **Email:** SendGrid
- **Deployment:** Vercel

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [NextAuth.js Documentation](https://next-auth.js.org)
- [MongoDB Atlas](https://www.mongodb.com/atlas)

## License

2024 © Future Interns — All rights reserved.
