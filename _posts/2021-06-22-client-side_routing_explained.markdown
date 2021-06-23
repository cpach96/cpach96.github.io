---
layout: post
title:      "Client-side Routing explained "
date:       2021-06-23 03:48:36 +0000
permalink:  client-side_routing_explained
---


Client-Side routing is an extremely important aspect of any React application which helps the user navigate seamlessly through you're project. Not to be confused with your backend rails routing, these routes are all handled by your front end aka the Client-Side. This leaves your backend to focus more on the database data.  To start you will need to import your Browser-Router, Switch and Route components from your Router module.  BrowserRouter being  a wrapper component for all the components that will be using client-side routing, Switch ensuring that only one route is handled at a time, and the Route telling us which component will be rendered on which route. The Route tag takes in two properties aka props. One is path, which will be the route which that path is taking you to and a component prop that outputs that component or renders it when the user goes to that particular route.
    For my particular project using Client-Side routing shines for my single page application look showing seamless navigation between my components for that single page feel. From the back when clicking from my landing page it hops between a dispach to my store and gathers all of my objects and back to and displays them to the user only taking mere miliseconds to show up even after running through several of my components. Not to mention it saves you from unneccesary  re renders which as your application grows frees up resources cutting down on load times across the board. 


