# Backend-RateLimiter
In .NET Core, a rate limiter is a mechanism used to control the rate at which requests are processed by an application. It helps to prevent overloading the system by limiting the number of requests a user can make within a specified period.

#Types of Rate Limiters in .NET Core
**Fixed Window Rate Limiter**: Limits the number of requests in fixed time windows (e.g., 100 requests per minute). Limits requests based on a fixed time window, such as 100 requests per minute.

**Sliding Window Rate Limiter**: A more flexible approach that allows for request bursts by smoothing the limits over a time window. Smooths out request limits over a sliding time window to allow for bursts.

**Token Bucket Rate Limiter**: Uses tokens to control the rate of requests, allowing a burst of requests as long as tokens are available. Allows bursts by using tokens to control request rates.

**Concurrency Rate Limiter**: Limits the number of concurrent requests being processed at any given time. Limits the number of concurrent requests to control load on the system.




Each type of rate limiter serves different use cases and helps in maintaining the stability and performance of the application by preventing abuse or overuse.









