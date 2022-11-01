# next.js13Demo
## app/ Directory (beta)
* * One of the most-loved features of Next.js is our file-system router. Drop a file inside a folder, and you're able to instantly create routes in your application. No configuration required.

Today, we're improving the routing and layouts experience in Next.js with the introduction of the app/ directory (beta). This is the result of the Layouts RFC previously published for community feedback. The new router includes support for:

Layouts: Easily share UI between routes while preserving state and avoiding expensive re-renders.
Server Components: Making server-first the default for the most dynamic applications.
Streaming: Display instant loading states and stream in units of UI as they are rendered.
Support for Data Fetching: async Server Components and extended fetch API enables component-level fetching.
While you don't need to use the app/ directory when upgrading to Next.js 13, the app/ directory can coexist with the existing pages directory for incremental adoption. * *
***![alt text](https://nextjs.org/_next/image?url=%2Fstatic%2Fblog%2Flayouts-rfc%2Fapp-folder.png&w=3840&q=75)***
