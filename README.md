# **FRIENDS OF 16: FRONTEND DOCUMENTATION**
## **Introduction**
### Purpose
The "OG Friends" is the first set of members for the Friends of 16 program. They will be manually onboarded and given access to the app where they can view upcoming events, access codes for coworking, account details, discount codes for room bookings, and invoices for payment.

### Scope
This project involves the development of a website's graphical user interface, which enables registered users to access various features. Users can check out upcoming events, access coworking access codes, view their account information, access room booking discount codes, and check their payment invoices.

### Technologies Used
* Javascript Framework - Vue JS
* Build tool - Vite
* CSS Framework - Tailwind CSS

### Key Contributor: Emmanuel Olusola


## **Getting Started**
### Prerequisites
* Software: Node.js, Git, VSCode
* Operating System: Windows/MacOS/Linux
* Package Manager: Yarn

### Installation
To get started with the project, you need to set up your development environment. Follow these steps to install the required software and dependencies using Yarn:

### 1. Node.js and Yarn

- **Download and Install Node.js**: Visit the official Node.js website (https://nodejs.org/) and download the LTS (Long-Term Support) version for your operating system. Follow the installation instructions.

- **Verify Installation**: Open your terminal or command prompt and run the following commands to ensure that Node.js and Yarn are installed correctly:

   ```bash
   node -v
   yarn -v
   ```

   You should see the version numbers displayed.

### 2. Git

- **Download and Install Git**: Download the Git installer for your operating system from the official Git website (https://git-scm.com/downloads) and follow the installation instructions.

- **Verify Installation**: Open your terminal or command prompt and run the following command to confirm that Git is installed:

   ```bash
   git --version
   ```

   You should see the Git version displayed.

### 3. Code Editor (Visual Studio Code recommended)

- **Download and Install Visual Studio Code (VS Code)**: Download VS Code from the official website (https://code.visualstudio.com/) and follow the installation instructions. We recommend using VS Code for its excellent support for web development.

### 4. Clone the Project Repository

- **Open your terminal or command prompt**.

- **Navigate to the directory where you want to store the project**:

   ```bash
   cd /path/to/your/project/directory
   ```

- **Clone the project repository from GitHub**:

   ```bash
   git clone https://github.com/emmanuelolusola/friends-of-16.git
   ```

### 5. Install Project Dependencies

- **Navigate to the project directory**:

   ```bash
   cd friends-of-16
   ```

- **Install project dependencies using Yarn**:

   ```bash
   yarn install
   ```

### 6. Start the Development Server

- **Start the development server**:

   ```bash
   yarn run dev
   ```

- The project will be available at `http://localhost:5173/` in your web browser.

You have successfully installed the project and are ready to start development.


## **Project Structure**
### Overview of Directory Structure

The project's directory structure is organized to promote a clear separation of concerns and easy navigation. Below is an overview of the main directories and their contents:

### **`src/`**

   - **`components/`**: This directory contains reusable Vue components. Each component is typically organized in its own folder, including its Vue component file and any associated assets.

   ```plaintext
   src/
   ├── components/
   │   ├── Navbar/
   │   │   ├── Navbar.vue
   │   └── ...
   ```

   - **`pages/`**: Views or route components are located here. Each view corresponds to a page or route in the application.

   ```plaintext
   src/
   ├── pages/
   │   ├── Today.vue
   │   ├── My16.vue
   |   ├── Events.vue
   |   ├── Profile.vue
   │   └── ...
   ```

   - **`assets/`**: This directory contains accessible assets like images, icons and vectors.

   ```plaintext
   src/
   ├── assets/
   └── ...
   ```

### Explanation of Key Files and Folders

Understanding the role of key files and folders in the project is essential for efficient development and maintenance. Here are explanations of some of the most important files and directories:

### 1. **`src/` Directory**

   - **`components/`**: This directory contains reusable Vue components used throughout the project. Each component is organized in its own folder, which includes the following files:
     - `Navbar.vue`: A Single File Component that showcases the navigation menu, including elements such as the logo, today, my 16, events, and profile.