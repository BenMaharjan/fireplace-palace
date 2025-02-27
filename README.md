## Important Note: This website is currently configured for mobile view. Please view in mobile view for optimal results
<br><br>



<a href="https://fireplace-palace-5ng525r5k-benmaharjan-hotmailcous-projects.vercel.app//">
  <img src="https://raw.githubusercontent.com/BenMaharjan/fireplace-palace/main/public/assets/Fireplace%20Palace%20Banner.png" alt="Fireplace Palace Banner" />
</a>
<br>
<i>click on the banner and visit our website!</i>

## Client Brief

Our clients, Mike and Mandy, approached us with a project proposal. They were seeking a landing page website to help generate new leads for their fireplace business. The initial brief outlined a basic home page with the potential for a consultation booking form.

As discussions progressed, the brief was refined to include multiple pages: a Home page and an About Us page. 

Finally, Mike and Mandy requested the implementation of a consultation form to collect information from potential leads.

## Our Solution

Our approach began with the development of an initial boilerplate using pure HTML and CSS. After completing this prototype, we presented it to Mike and Mandy for approval, receiving their go-ahead to proceed.

With their approval secured, we immediately began porting our HTML and CSS into a React application using Vite. We chose Vite for its efficiency in setting up React apps, appreciating its low-bloat configuration and rapid response times.

Upon completion of the React version, we again presented our creation to Mike and Mandy for feedback. As is often the case in client work, they had a change of mind. However, we were prepared for this eventuality. The clients now expressed a desire for a consultation booking form capable of collecting potential customer data and storing it for future use.

To meet this new requirement, we converted our Vite app to a Next.js application. This allowed us to take advantage of Next.js's directory-based routing for pages and layouts, as well as its directory-based API routes for handling form submission requests . We implemented a system where each POST request would receive the details from the submission form and update a bookingData.json file accordingly.
