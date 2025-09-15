# CmpDeepDive

CmpDeepDive is an Angular 18 demo application showcasing advanced component techniques, signals, and standalone components. The project features a dashboard with server status, traffic analytics, and support ticket management, using modern Angular patterns.

## Features

- **Dashboard**: Displays server status, traffic data, and support tickets.
- **Standalone Components**: All components are standalone for modularity.
- **Signals**: Uses Angular signals for reactive state management.
- **Custom Controls & Buttons**: Includes reusable UI components.
- **Responsive Design**: Optimized for desktop and mobile screens.

## Project Structure

```
src/
	app/
		dashboard/
			dashboard-item/
			server-status/
			tickets/
				new-ticket/
				ticket/
			traffic/
		header/
		shared/
			button/
			control/
	index.html
	main.ts
	styles.css
```

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- Angular CLI (`npm install -g @angular/cli`)

### Installation

```sh
npm install
```

### Development Server

```sh
npm start
```

Open [http://localhost:4200](http://localhost:4200) in your browser.

### Build

```sh
npm run build
```

### Running Unit Tests

```sh
npm test
```
