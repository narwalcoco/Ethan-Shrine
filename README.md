# The Shrine of Ethan

Welcome to the **Shrine of Ethan**, a dedicated digital space where students can come together to offer prayers for good grades! 

## How to Use It

1. Open the website.
2. Click and hold the **Offer Prayer** button (or hold down your **Spacebar**) for 3 seconds.
3. Watch the progress bar fill up as your prayer is sent to the heavens.
4. Once complete, your prayer is added to the global counter, and you will receive a divine Ivy League blessing!
5. Watch the global counter update in real-time as other students around the world pray alongside you.

## How It Works (Under the Hood)

This project is a lightweight, frontend-focused web application designed to be fast, interactive, and completely contained within a single screen without scrolling.

* **Frontend:** Built completely with vanilla **HTML, CSS, and JavaScript**. Flexbox is used to auto-adjust the layout flawlessly to any screen.
* **Global Counter:** Powered by **Firebase Realtime Database**. When a user successfully finishes a prayer, the JavaScript sends a payload to Firebase, which instantly syncs the new total count and any active announcements to every single person currently viewing the site using WebSocket connections. 
* **Interaction Logic:** The "hold-to-pray" mechanic uses standard DOM event listeners (`mousedown`, `mouseup`, `keydown`, `keyup`) paired with JavaScript timers (`setTimeout` and `setInterval`) to track how long the user interacts with the button before firing off the database request.
* **Styling & Assets:** Custom CSS handles the gradient themes, modal pop-ups, background fade-ins, and locked viewport sizing. 

## Built With

* Vanilla HTML, CSS, and JavaScript
* [Firebase](https://firebase.google.com/) (Realtime Database for live syncing)
* [Lucide Icons](https://lucide.dev/) (For crisp, lightweight vector graphics)
* [Supabase](https://supabase.com/)
* Wikipedia (Media assets)
* [GitHub](https://github.com/) (Hosting & Version Control)

---

*Made by **narwalcoco** and **Gemini**.*