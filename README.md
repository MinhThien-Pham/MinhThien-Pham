# Minh Thien Pham

Computer Science student at UCF building full-stack and desktop applications, from offline
software a small business runs every day to deployed web apps with tested, layered backends.
Looking for **software engineering internships and new-grad roles**.

[Portfolio](https://minhthienpham.me) · [LinkedIn](https://www.linkedin.com/in/minhthienpham/) · [Email](mailto:phamminhthien065@gmail.com)

## Featured projects

### [Nail Salon POS](https://github.com/MinhThien-Pham/nail-salon-pos) · in daily use at a nail salon

[![Payment screen with the paired customer tablet showing the customer's points](https://raw.githubusercontent.com/MinhThien-Pham/nail-salon-pos/main/docs/images/payment.jpg)](https://github.com/MinhThien-Pham/nail-salon-pos)

An offline point-of-sale desktop app that runs a nail salon's front desk: technician turn
rotation, checkout, payroll, loyalty and gift cards, with a customer check-in tablet on the salon
Wi-Fi.

- **Real users:** built for one salon and used there every day; installer releases ship from the
  repository.
- **Business rules in code:** fair turn rotation with three turn types, one ticket split across
  technicians, mixed payments and tips, commission payroll and profit reporting.
- **Engineering:** Clean Architecture modules with ports and repositories, atomic SQLite
  transactions, versioned migrations with verified backups, Zod validation at every IPC boundary,
  and architecture tests that fail the build when a dependency points the wrong way.

**Electron · React · TypeScript · SQLite · Express + WebSocket · Vitest**

[Live demo](https://minh-nail-pos.vercel.app) · [Source code](https://github.com/MinhThien-Pham/nail-salon-pos)

### [IDX Exchange](https://github.com/MinhThien-Pham/IDX-exchange) · property search over 55,000 listings

[![Search results for San Diego with filters and listing cards](https://raw.githubusercontent.com/MinhThien-Pham/IDX-exchange/main/docs/images/listings.jpg)](https://github.com/MinhThien-Pham/IDX-exchange)

A residential property search built for the IDX Exchange Software Development Engineer
Internship. Visitors filter about 55,000 MLS listings by location, budget, rooms and home type,
then open a listing for photos, facts and open houses.

- **Full stack, deployed:** React web app and Express API on Vercel, PostgreSQL on Neon, with
  shared Zod contracts validating every request and response.
- **Data:** a streaming importer normalizes the MLS export into PostgreSQL; indexed queries return
  filtered, sorted pages in about 200 ms in production.
- **Quality:** modular Clean Architecture API, CI with PostgreSQL integration tests, Playwright
  end-to-end tests with automated accessibility checks, and coverage gates.

**TypeScript · React · Express · PostgreSQL · Drizzle · Playwright · Vercel**

[Live demo](https://idx-exchange-three.vercel.app) · [Source code](https://github.com/MinhThien-Pham/IDX-exchange)

### [Volunteer Social Hub](https://github.com/MinhThien-Pham/Volunteer-Social-Hub)

A volunteer-focused community forum for sharing opportunities, experiences, questions, and
resources.

Built with **React, Supabase (PostgreSQL, Auth, and Storage), and Vite**. Includes user accounts,
public profiles, categorized posts, multi-image uploads, comments, search and filtering, and
responsive desktop/mobile layouts.

[Live demo](https://volunteer-social-hub.netlify.app/) · [Source code](https://github.com/MinhThien-Pham/Volunteer-Social-Hub)

![Volunteer Social Hub demo](https://raw.githubusercontent.com/MinhThien-Pham/Volunteer-Social-Hub/master/walkthrough.gif)

### [MLC-CLI Build Service](https://github.com/MinhThien-Pham/fastapi-mlc-docker)

A FastAPI and Docker service that turns an LLM build workflow into repeatable APIs for model
preparation, quantization, compilation, runtime checks, and local chat.

Built with **Python, FastAPI, Docker, CUDA, and Server-Sent Events**.

## Skills

| Area | Tools |
| --- | --- |
| Languages | TypeScript, JavaScript, Python, C, SQL |
| Frontend | React, Vite, Tailwind CSS, TanStack Query |
| Backend | Node.js, Express, FastAPI, Electron |
| Data | PostgreSQL, SQLite, Supabase, Drizzle ORM |
| Testing and delivery | Jest, Vitest, Playwright, GitHub Actions, Docker, Vercel |
