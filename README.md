# Build native Web Components without using a framework

Everyone knows it: Encapsulating and reusing UI components on the web is challenging. It is usually a copy & paste of HTML, CSS, and JavaScript, often spread over one or more files. If you forget a part, it does not look as desired, or the interaction does not work. Enough of that!
Web Components open up new ways on the web to implement and (re-)use UI components in a standardized manner and without any framework. In this sample, i want to show the essential points to create a completely native Web Component with standards HTML Templates, Custom Elements, and Shadow DOM.

To run the sample, following the next steps.

## Install dependencies
Run `npm i` to install all dependencies.

## Development server
Run `npm start` for a dev server. Navigate to http://localhost:8080/. The app will not automatically reload if you change any of the source files.

## Build
Run `npm run build-wc:webpack` to build the web component. The build artifacts will be stored in the dist/ directory.