# Frontend Project Developer Assignment

## 1. **Tamoor**
**Files:**  
- `components/auth/LoginForm.jsx`  
- `pages/LoginPage.jsx`  
- `styles/auth.css`  

**Details:**  
Tamoor is responsible for building the login page UI, including the login form, and styling it properly using `auth.css`.

---

## 2. **M.Imran**
**Files:**  
- `components/auth/SignupForm.jsx`  
- `pages/SignupPage.jsx`  
- `styles/auth.css`  

**Details:**  
M.Imran will create the signup page UI, handle the signup form fields, and style the page using `auth.css`.

---

## 3. **Hammad Ali**
**Files:**  
- `components/chat/ChatBox.jsx`  
- `pages/ChatPage.jsx`  
- `styles/chat.css`  

**Details:**  
Hammad Ali will build the main chat interface, including ChatBox layout and chat page styling using `chat.css`.

---

## 4. **Abdul Saboor**
**Files:**  
- `components/chat/ChatInput.jsx`  
- `components/chat/Message.jsx`  
- `styles/chat.css`  

**Details:**  
Abdul Saboor is responsible for the chat input field, sending messages, and rendering individual messages with proper styling.

---

## 5. **Naseer Nawaz**
**Files:**  
- `components/layout/Navbar.jsx`  
- `styles/layout.css`  

**Details:**  
Naseer Nawaz will create the site’s navbar and handle its layout and design using `layout.css`.

---

## 6. **M.Arslan**
**Files:**  
- `components/ui/Button.jsx`  
- `components/ui/Input.jsx`  
- `styles/ui.css`  

**Details:**  
M.Arslan will build reusable UI components like buttons and input fields and style them in `ui.css` for consistent look across the app.

---

## Notes on Styles
- All `.css` files (`auth.css`, `chat.css`, `layout.css`, `ui.css`) are used for **component/page-specific styling**.  
- Developers should link their respective CSS files in their components/pages to maintain a consistent UI across the project.



## 7. **Abdul Rasheed**
**Files:**  
- `All project files`  

**Details:**  
Abdul Rasheed is responsible for managing the entire frontend code, reviewing and testing all developers' contributions after each push, and ensuring everything works correctly and integrates smoothly.



## 8. **Ali Raza**
**Files:**  
- `App.jsx`  
- `index.jsx`  

**Details:**  
Ali Raza is responsible for managing the `App.jsx` and `index.jsx` files, setting up routing, rendering the root component, and ensuring the overall app structure works correctly with all other components.











# AI Chatbot Frontend Project

## Objective
Build a **ChatGPT-style AI chatbot frontend** using React.  
The website should have a **clean and responsive layout** similar to ChatGPT:  

1. **Login Page** – Users can enter email and password to login.  
2. **Signup Page** – New users can register with name, email, and password.  
3. **Chat Page** – Users can type messages in a chatbox and see AI responses.  

The design should follow a **modern, minimal, and user-friendly layout**.

---

## Design Guidelines
- Use **Bootstrap** for consistent layout and responsive design.  
- Follow the **component structure** provided:  
  - `auth` → `LoginForm`, `SignupForm`  
  - `chat` → `ChatBox`, `ChatInput`, `Message`  
  - `layout` → `Navbar`  
  - `ui` → `Button`, `Input`  
- Components must be **modular and reusable**.  
- Chat interface should be **centered**, with messages stacked vertically and scrollable if needed.  
- Input box at the bottom, send button aligned to input.  
- Navbar at top, visible on all pages.  

---

## Developer Instructions
1. **Work only on your assigned components/files** as listed in the developer assignments.  
2. **Use CSS files** (`auth.css`, `chat.css`, `layout.css`, `ui.css`) for styling your components.  
3. **Ensure integration** with `App.jsx` and `index.jsx`.  
4. **Push code to the shared repository** after finishing your component.  
5. **Abdul Rasheed** will manage, review, and test all contributions after each push.  

---

## Component Integration
- **LoginPage** → Uses `LoginForm` and `Button`/`Input` components.  
- **SignupPage** → Uses `SignupForm` and `Button`/`Input` components.  
- **ChatPage** → Uses `ChatBox` which contains multiple `Message` components and a `ChatInput`.  
- **Navbar** → Displayed on all pages.  

---

## Notes on Chat Functionality
- Chat interface should **look and behave like ChatGPT**, with:  
  - User messages aligned to right  
  - AI responses aligned to left  
  - Scrollable chat history  
  - Input box at bottom with send button  
- **Google login / OAuth** can be added later without affecting the current structure.  

---

## Assets
- All images (like logos or flowcharts) should go in `assets/images/`.  
- Use Bootstrap classes for layout consistency.  
- CSS files handle **component/page-specific styling**.

---

## Developer Assignments
**(Refer to the individual assignment section for each developer and their files)**

- 8 developers are assigned specific components and CSS files.  
- Each developer builds their component according to this ChatGPT-style layout.  
