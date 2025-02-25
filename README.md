This project is a simple Education Form built using HTML and Tailwind CSS. The form collects user details about their academic background and interests.

📌 Features
✅ Responsive design using Tailwind CSS
✅ Select dropdowns for institution, education level, and interests
✅ Progress bar indicating the current step
✅ WESPoints reward system for completing steps
✅ Simple form validation for required fields


/project-root
│── index.html       # Main education form file
│── js/
│   ├── script.js    # JavaScript for form validation (optional)
│── css/
│   ├── styles.css   # (If needed for custom styles)
│── README.md        # Project documentation (this file)




📜 Code Breakdown
1️⃣ Progress Bar
Displays the user's current step progress.

html
Copy
Edit
<div class="h-1 w-full bg-gray-200 rounded-full mb-2">
  <div class="h-1 bg-blue-600 w-1/4 rounded-full"></div>
</div>
🔹 w-1/4 means only 25% progress is filled.

2️⃣ Form Fields
Includes institution selection, level selection, GPA input, and interests.

html
Copy
Edit
<label class="block mb-2 text-sm font-medium">Name of Institution *</label>
<select class="w-full p-2 border rounded-md bg-gray-100 text-gray-600">
  <option>WESOnline</option>
</select>
3️⃣ Submit & Skip Buttons
User can skip or submit the form.

html
Copy
Edit
<div class="flex justify-between items-center mt-6">
  <button type="button" class="text-gray-500 text-sm">Skip For Now</button>
  <button type="submit" class="bg-blue-600 text-white px-6 py-2 rounded-md">Continue</button>
</div>

🚀 How to Run
Clone the repository:
bash
Copy
Edit
git clone https://github.com/your-username/your-repo.git
Open index.html in a browser.
Modify script.js (if needed) to handle form submissions.
📌 To-Do
🔹 Add form validation in script.js
🔹 Improve mobile responsiveness
🔹 Store form data in a backend database

💡 Contributing
Want to improve this project? Fork it and submit a pull request! 🚀
