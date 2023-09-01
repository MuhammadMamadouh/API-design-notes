# API-design-notes
Summary points of API Design

# REST API Caching Summary

This section provides an overview of REST API caching concepts, benefits, and implementation considerations.

## Caching Overview
Caching involves storing frequently used data to improve API performance and scalability. It occurs at various touch points along the request path.

## Benefits of Caching
- Improves response times and user experience
- Reduces load on backend systems
- Enhances scalability and throughput

## Caching Strategy
- Cache closer to the consumer for better performance
- Consider data characteristics:
  1. speed of change
  1. time sensitivity
  1. security requirements  
- Examples: stock market data (rapidly changing, time-sensitive, security-sensitive), news articles (not time-sensitive, no security issue), customer profiles (varying time sensitivity, security)

## API Designer's Role
- Make decisions about caching behavior
- Control caching components, cached data, and cache duration
- Use HTTP cache control directive to manage cache behavior

## HTTP Cache Control Directive
Manage caching behavior using the HTTP cache control directive. Specify cache duration, freshness, and validation rules.

## Useful Links
- [HTTP Caching - MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTTP/Caching)
- [Caching Best Practices - Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)
- [Caching Tutorial - TutorialsPoint](https://www.tutorialspoint.com/http/http_caching.htm)

