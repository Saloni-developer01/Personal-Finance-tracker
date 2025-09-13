<h1>Finance Tracker ❤️ ₊‧.°.⋆✮⋆.°.₊ </h1>

<p>Welcome to the Finance Tracker application. This project helps you manage your personal finances by tracking income and expenses.</p>

<h3>Features *ੈ✩‧₊˚</h3>

<li>Dashboard: A comprehensive overview of your financial records.</li>

<li>Add Records: Easily add new income and expense entries.</li>

<li>Edit & Delete: Modify or remove existing records.</li>

<li>Interactive Charts: Visualize your income and expenses with dynamic charts.</li>

<li>Data Filtering: Filter records by category, payment method, month, and year. </li>

<li>User Authentication: Secure access with Clerk for user management. </li>


<h4>Tech Stack ⋆⭒˚.⋆</h4>

<h3>Frontend ⋆.˚ </h3>

<li>React: A JavaScript library for building user interfaces.</li>

<li>TypeScript: A typed superset of JavaScript that compiles to plain JavaScript. </li>

<li>React Table: A powerful library for building fast and extensible data tables. </li>

<li>Recharts: A composable charting library built on React components. </li>

<li>Clerk: A complete user management and authentication solution. </li>

<h3>Backend ⋆.˚ </h3>

<li>Node.js: A JavaScript runtime for building server-side applications. </li>

<li>Express.js: A fast, unopinionated, minimalist web framework for Node.js. </li>

<li>MongoDB: A NoSQL database for flexible data storage. </li>

<li>Mongoose: A MongoDB object modeling tool. </li>


<h4>Setup Instructions .｡*ﾟ+.*.｡ଘ( ᐛ ) ଓ+..｡*ﾟ+</h4>

<h3>1. Prerequisites </h3>

<p>Make sure you have Node.js and npm (or yarn) installed on your system. </p>

<h3>2. Clone the Repository </h3>

git clone <apni-repository-ka-link-yahan-dalen>
cd <apni-repository-ka-naam>

<h3>3. Backend Setup </h3>

cd backend
npm install


<p> Create a .env file in the backend folder and add your MongoDB connection URI: </p>

MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/myfinances

<p>Start the backend server: </p>

npm start

<p>The backend will run on http://localhost:5000. </p>

<p>4. Frontend Setup </p>

cd ../frontend
npm install

<p>Create a .env.local file in the frontend folder. </p>
Important: Get your publishable key from Clerk and paste your backend API URL.

NEXT_PUBLIC_API_URL=http://localhost:5000
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<apni-Clerk-key-yahan-dalen>


<p>Start the frontend development server: </p>

npm run dev

<p>The frontend will run on http://localhost:3000. </p>

<h4>API Endpoints </h4>

<h3>The following are the main API endpoints for the application: </h3>

<li>POST /api/records/add: To add a new financial record. </li>

<li>GET /api/records/all: To fetch all financial records for a user. </li>

<li>PUT /api/records/:id: To update an existing record. </li>

<li>DELETE /api/records/:id: To delete a record.</li>
