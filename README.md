# Technical Test

## Done by Faouzi Bakkali

---

### Bugs Found and How I Solved Them


**Bug 1:** When adding a new user, the password field was displaying the actual password as text. The solution was to use the `type="password"` attribute for this input to hide the actual password.

**Bug 2:** On the people's page, the username field was not displaying because the field was named "name" instead of "username" in the code.

**Bug 3:** The update button in the user view page was set to `onChange` instead of `onClick`, causing issues with updates. Fixed to `onClick` to ensure proper functionality.

**Bug 4:** "Days worked", "Cost per day", and "Sell per day" could have negative values. To address this, I created a function to verify that the values passed are positive.

**Bug 5:** Clicking to view project details after adding a project on the projects tab resulted in a crash error. This was caused by the fact that the fetched project came in array format. The issue was fixed by assigning `project = u[0]` and then using the new variable called "project".

---

### Features added and why

**Feature 1:** The availability of the user can now be directly changed from the user form, allowing managers to conveniently update team members' availability status.

**Feature 2:** A progress bar for projects with the maximum known budget, against the budget consumption, was added. This feature provides managers and users with a visual representation of the project budget utilization.

**Feature 3:** Users can now update their profile avatar using a URL from the account page. This feature was added to let users customize their profile and improve the overall user experience.


---


Thanks for considering my internship application. I'm excited to join your team and learn from experienced professionals. Hope to hear from you soon!


