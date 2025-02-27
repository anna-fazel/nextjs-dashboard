## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application on the Next.js Website.(https://nextjs.org/learn) "# nextjs-dashboard" 



NOTES:
using pnpm as your package manager, as it's faster and more efficient than npm or yarn. 

to install pnpm in terminal
npm install -g pnpm

pnpm run dev  => Starts the development server.

pnpm run build  => Builds the app for production.

pnpm start => Runs the built app in production mode.

pnpm i =>  install the project's packages
pnpm dev  => start the development server.

npx create-next-app@latest  => create a new Next.js app
ex: npx create-next-app@latest nextjs-dashboard --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example" --use-pnpm


---- notes from https://nextjs.org/learn/dashboard-app ----

 use the next/image component to automatically optimize your images.

/app/ui/global.css  for css styles
 using Tailwind as a CSS framework that speeds up the development process by allowing you to quickly write utility classes directly in your React code.

 Using the clsx library to toggle class names

 we create a new file called fonts.tsunder /app/ui folder fot fonts

 The <Image> Component is an extension of the HTML <img> tag, and comes with automatic image optimization,

 Next.js uses file-system routing where folders are used to create nested routes. Each folder represents a route segment that maps to a URL segment. 
 we create page.tsx and layout.tsx under each folder as page layout.

 we use the <Link /> Component to link between pages and allows you to do client-side navigation with JavaScript.

 we use React hook called usePathname() that you can use to check the path of url

 Add React's "use client" directive to the top of the file to to turn file into a Client Component
