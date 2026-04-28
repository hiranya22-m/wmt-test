# wmt-test
personal email-nethmihiranya22@gmail.com      password- OA647316 /
GitHub email address-nethmihiranya22@gmail.com   password- nha@200305 /
MongoDB- hiruabeywickrama22@gmail.com     password- nha@200305 /
railway(backend)- Sign in- Github /
vercel(frontend)- Sign in- nethmihiranya22@gmail.com /
Netlify(frontend) - Sign in- nethmihiranya22@gmail.com

zip eka extract krla vs eken open krnna. auto save. extensions- github copilot chat
create git repostory - repo name, add README, Add .gitignore - Node
mongodb- create cluster hdla password copypaste, backend eke .env file hdla   
MONGO_URI=mongodb+srv://hiruabeywickrama22_db_user:NJu8hyjNWfLLIKxT@cluster0.tel8o2k.mongodb.net/?appName=Cluster0
PORT=5000
IP Address-0.0.0.0/0      cmd eke- netstat -ano | findstr :5000    taskkill /PID <PID> /F

backend- open terminal- npm install express moongose dotenv cors
                        npm install nodemon --save-dev
                        npm run dev
frontend- open terminal- npm install
                         npm run dev

Modify code- backend- models- Item.js - 
    quantity: {
      type: Number,
      required: [true, "Quantity is required"],
      min: [0, "Quantity cannot be negative"],
    },
    description: {
      type: String,
      required: [true, "Description is required"],
      trim: true,
    },

    frontend- components- ItemCard.jsx- 
      <p><strong>Quantity:</strong> {item.quantity}</p>
      <p><strong>Description:</strong> {item.description}</p>

    frontend- components- ItemForm.jsx-
       quantity: "",
       description: "",

       label>Quantity</label>
      <input
        type="number"
        name="quantity"
        value={formData.quantity}
        onChange={handleChange}
        required
      />

      <label>Description</label>
      <textarea name="description" value={formData.description} onChange={handleChange} required />

Commit to github- backend eke node_modules cut krla repo ekta upload file gihin backend drag krla Add backend files, then vs close and drag node_modules
                  frontnd eke node_modules cut krla repo ekta upload file gihin frontend drag krla Add backend files, then vs close and drag node_modules
Then run backend and frontend in vscode

Railway - Project- select repostory- variables- New variable   PORT = 5000 , MONGO_URI = mongodb+srv://hiruabeywickrama22_db_user:NJu8hyjNWfLLIKxT@cluster0.tel8o2k.mongodb.net/?appName=Cluster0
settings- add Root Directory- /backend  - Deploy  then Generate Domian - copy backend domain-  wmt-item-add-production.up.railway.app

Vercel - Add New- Project- Continue with GitHub- select what repostory import- Root Directory- frontend   VITE_API_URL = https://wmt-item-add-production.up.railway.app/api

Netlify- Add new project- GitHub- select github repostory- Project name-, Base Directory- frontend, Build command- npm run build, public directory- frontend/dist, Add Environment variables- Key- VITE_API_URL, Value- https://wmt-item-add-production.up.railway.app/api  , Deploy, Click Deploys- Deploy project- click open production deploy

                        
