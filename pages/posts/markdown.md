---
title: Interview Exercise Questions & Answers
date: 2024/3/12
description: Learn more about how I think - Exercise Questions & Answers
tag: web development
author: You
---

# The Exercise

From this list, rank your 5 most favorite and 5 least favorite support tasks. Provide a brief explanation for each.

# 5 most favorite 
1. Manage a support team - This is my favorite activity, where I can lean on my leadership experience to develop a team that provides quality support experiences
2. Find and recruit teammates for the support team - I enjoy interviewing and hiring new folks that will bring value to the team
3. Help train and onboard new support teammates - I enjoy enabling new hires to be successful with training and onboarding  
4. Work with engineering teams during incidents and provide updates to internal and external stakeholders - I have experience with incident management best practice and being the point of contact for stakeholders
5. Scheduling time-off coverage and collaborating as part of a growing cohesive support team - My leadership strengths are based in collaboration and developing a cohesive support team that does their best work together. 
# 5 least favorite
1. Help resolve billing issues for customers - There’s value and a need to resolve these issues asap for customers, but I have a learning mindset and enjoy innovating through new issue types when possible. 
2. Respond to 50+ support requests via email every day - As a manager I am comfortable rolling up my sleeves to work alongside the team where needed but I would rather focus on how to enable self-service for customers as we scale through automation, AI, documentation / knowledge, videos / tutorials etc. 
3. Analyze hundreds of support tickets to spot trends the product team can use - Support has critical insight into top trends for product and this brings value cross functionally. Instead of analyzing hundreds of tickets, I would rather focus on the top 5 product reasons a customer has to open a ticket and make recommendations to close gaps. 
4. Respond to queries on Twitter, Reddit, Hacker News and other 3rd party sites - Social support is important for protecting brand image and enabling self-service of customers. That said, I would opt for a CSE or someone very familiar with product feature functionality to ensure the right tone and message across various platforms. 
5. Act as a dedicated CSE for a handful of key customers to ensure their success using Vercel - Similar response to my answer for #2 and #4. I definitely have the capability to support a handful of customers as a dedicated CSE but would rather take on a leadership role within the team. 

# What do you want to learn or do more of at work? 

- I want to learn more about the intersection of generative AI solutions for supporting customers through self-service while maintaining high-quality experiences. I want to spend more time developing scalable ways of addressing future growth and building tools that make it easier for support engineers to focus on solving complex problems. 

# Describe how you solved a challenge or technical issue that you faced in a previous role (preferably in a previous support role). How did you determine that your solution was successful?

- A previous Auth0 customer wanted more granular reporting capabilities than what the product functionality allowed out of the box. This reporting was important for their customer base and without it their team was spending development time pulling together data from different systems. After partnering cross-functionally with Product and Engineering to add granular reporting into the product roadmap for the following quarter, I was able to work with the customer to leverage an undocumented API that equipped them with the ability to reduce development time for their team while they awaited product enhancements. I hopped on a call with the customer’s development team to walk them through the API and ensured it would meet their needs. Finally, I worked with Product to document the API so that it would be publicly available for all customers to benefit from. 

# When would you choose to use Edge Functions, Serverless Functions, or Edge Middleware with Vercel?

Edge Functions: Generally more efficient and faster than traditional serverless functions. Operate with leaner runtime, deployed globally and run in the region closest to the request for lowest latency possible. They run after the cache and therefore are great for data fetching and rewrites. Can be more cost-effective than serverless. Vercel Functions enable server-side code execution on Vercel's Managed Infrastructure, removing the need for server management or resource provisioning. These functions scale automatically with user demand and can interact with APIs, databases, and other resources as part of your project's deployment.

Serverless Functions: Region-first. For functions needing to query a database, global compute can be quicker than Edge based on the region. Suited to computationally intense or large functions. 

Edge Middleware: Runs before the cache. Effective way to provide personalization to statically generated content. 

# Imagine a customer writes in requesting help with a build issue on a framework or technology that you've not seen before. How would you begin troubleshooting this and what questions would you ask the customer to understand the situation better? 

There’s still so much that you can look at and assist the customer with related to potential build issues, even if you aren’t familiar with the framework or technology. For example; I would start with gathering more information from the customer related to the framework/technology they are using, how they are initializing the Vercel deployment and what the specific issue is they are encountering during the build. 
From there, I would use these two articles to review the build process and determine where the customer might be getting stuck: https://vercel.com/docs/deployments/builds, https://vercel.com/docs/deployments/configure-a-build#build-command. 

# The customer from question 5 replies to your response with the below:
“I’m so frustrated. I’ve been trying to make this work for hours and I just can’t figure it out. It must be a platform issue so just fix it for me instead of asking me questions.”
Please write a follow-up reply to the customer.

Hey Jim, 
It sounds like you’ve spent quite a bit of time on this issue and I can definitely understand why that would be frustrating. My goal is to get you set up and running quickly so that you can continue leveraging Vercel’s capabilities. 
I’ve taken a look at our platform status page and confirmed that as of right now we do not have any outages reported. In order to get a better sense of the issue you are encountering, I took a look at your account logs and noticed that you have encountered a canceled build due to build duration. A build can last a maximum of 45 minutes before it is canceled. We’ve outlined how you can reduce your build duration in this helpful article. After reviewing options for how to reduce your build time, let me know if you have any additional questions. 
Looking forward to hearing if this gets you up and running. 

# Note: There are a few questions from the end of the exercise that I did not provide a response to given time and overall consideration of the type of leadership role I’m looking to step into but I’m including them below for reference. I shared my feedback regarding the exercise focus which was the final question and happy to discuss in more detail to provide context. 

1. A customer writes in to the Helpdesk asking "How do I do a redirect from the /blog path to https://example.com?" Please write a reply to the customer. Feel free to add any information about your decision making process after the reply.
2. A customer is creating a site and would like their project not to be indexed by search engines. Please write a reply to the customer. Feel free to add any information about your decision making process after the reply.
3. What do you think is one of the most common problems which customers ask Vercel for help with? How would you help customers to overcome common problems, short-term and long-term?
4. How could we improve or alter this familiarization exercise?


