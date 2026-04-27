# wmt-test
personal email-nethmihiranya22@gmail.com      password- OA647316
GitHub email address-nethmihiranya22@gmail.com   password- nha@200305
MongoDB- hiruabeywickrama22@gmail.com     password- nha@200305

vercel(frontend)
      

railway(backend)


Netlify(frontend)



zip eka extract krla vs eken open krnna. auto save
create git repostory
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



                        
