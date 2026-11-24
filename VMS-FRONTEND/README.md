# VMS Frontend

React and Vite interface for Vendor, Supplier and Buyer account registration and login.

## Run

Start the Spring Boot API on `http://localhost:8080`, then run `npm install` and `npm run dev` from this folder. Open `http://localhost:3000`.

The API base URL defaults to `http://localhost:8080/api/v1`; override it with `VITE_API_BASE_URL` when needed. Registration requires name, company, email, account type and a password of at least 10 characters containing a letter and a number. New accounts remain pending admin approval.
