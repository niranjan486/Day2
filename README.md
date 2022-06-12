Q1.Write a blog on Difference between HTTP1.1 vs HTTP2

Ans: Differences betwwen HTTP1 & HTTP2.
1.HTTP2 is much faster and more reliable than HTTP1. HTTP1 loads single request for every TCP connection, while HTTP2 avoids network delay by using multiplexing.
2.HTTP1 can define 16 status codes, the error prompt is not specific enough, but in HTTP2 underlying sematics of HTTP such as headers, status codes remain same.
3.HTTP1 uses basic authentication scheme which is unsafe since user name and passwords are transmitted in clear text or base64 encoded. In HTTP2 better equipped to deal with due to new TCS features like connection error of type Inadequate-Security.
4.HTTP1 provides support for caching vai the If-Modified_Since header. HTTP2 does not change much in terms of caching. With the server push feature if the client finds the resources are already present in the cache, it can cancel the pushed stream. 


Q2.Write a blog about objects and its internal representation in Javascript

Ans: In javascript an object is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object with properties. A cup has a color, a design, weight, a material it is made of, etc. THe same way Javascript objects can have properties which define their characteristics.
