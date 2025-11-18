# TODO: Fix Login/Signup Form Submission Issues

## Steps to Complete

1. **Update BACKEND_URL for local development**
   - Change `courseapp/frontend/src/utils/utils.js` to use "http://localhost:3000/api/v1" instead of deployed URL.
   - [x] Completed

2. **Fix login controller bug**
   - In `courseapp/backend/controllers/user.controller.js`, add check for user existence before bcrypt.compare to prevent TypeError.
   - [x] Completed

3. **Add required attribute to firstName input**
   - In `courseapp/frontend/src/components/Signup.jsx`, add `required` to the firstName input field.
   - [x] Completed

4. **Improve error handling in Login and Signup components**
   - Update catch blocks in `courseapp/frontend/src/components/Login.jsx` and `Signup.jsx` to display a fallback error message for network errors.
   - [x] Completed

5. **Fix typo in Signup component**
   - Correct "Sugnup" to "Signup" in console.log in `courseapp/frontend/src/components/Signup.jsx`.
   - [x] Completed

## Followup Steps
- Run backend locally: `cd courseapp/backend ; npm start`
- Run frontend locally: `cd courseapp/frontend ; npm run dev`
- Test login/signup forms to ensure submission works and errors display properly.
