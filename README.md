<!-- # GithubUserSearch

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.3.16.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page. -->


DevScope ->

A scalable GitHub developer dashboard built with Angular 17, RxJS, and Tailwind CSS.
DevScope allows users to search GitHub developers, explore repositories, analyze profiles, and manage favorite developers in a modern dashboard experience.

✨ Features
🔍 Developer Search
Search GitHub users by username
Real-time API integration
Debounced search using RxJS
👤 Developer Profile
Avatar
Bio
Followers / Following
Public repositories
Location & GitHub profile link
📁 Repository Explorer
Repository cards
Stars & forks count
Programming language badges
Open repositories directly on GitHub
⭐ Favorites System
Save favorite developers
Persistent local storage
🕘 Recent Searches
Track previously searched users
🌙 Dark Mode
Toggle between light and dark themes
📊 Future Analytics
Most used languages
Repository statistics
Developer comparison
Charts & activity tracking
🛠️ Tech Stack
Angular 17
TypeScript
RxJS
Tailwind CSS
GitHub REST API
🏗️ Project Architecture
src/app
│
├── core
├── shared
├── features
├── layouts
Architecture Principles
Feature-based structure
Reusable shared components
Separation of concerns
Scalable and maintainable codebase
📡 API

This project uses the official GitHub REST API.

Example endpoints:

https://api.github.com/users/{username}
https://api.github.com/users/{username}/repos
⚡ Performance Optimizations
RxJS debounced search
Lazy loading (planned)
Optimized API requests
Modular architecture
Reusable UI components
📱 Responsive Design

DevScope is designed to work across:

Desktop
Tablet
Mobile devices
🚀 Getting Started
Clone the repository
git clone <https://github.com/AhmedGhopish1/DevScope.git>
Install dependencies
npm install
Run the development server
ng serve

Navigate to:

http://localhost:4200
🧠 Learning Goals

This project focuses on:

Real-world Angular architecture
API integration
Reactive programming with RxJS
Clean code practices
Frontend scalability
Performance optimization

📌 Roadmap
 Project architecture setup
 Search functionality
 GitHub API integration
 User profile view
 Repository filtering
 Favorites system
 Dark mode
 Analytics dashboard
 GitHub OAuth
 Deployment
🌐 Deployment

Planned deployment platforms:

Vercel
Netlify
📄 License

This project is built for educational and portfolio purposes.

👨‍💻 Author

Ahmed Mohamed
Frontend Developer | Angular Enthusiast 🚀