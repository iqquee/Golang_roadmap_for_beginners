![go](/static/golang.png)

# Golang roadmap for beginners
This repo was created to serve as a guide to developers who intend to go into backend developemt with GOLANG. It contains reference to the resources I used while I started out my journey as a Go developer

# Git
- ### Git is free and open source software for distributed version control: tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems) 

# Go Basics
- ### There is no best place to learn about Golang other than [Golang's](https://go.dev/doc/) own official docs

- ### You can read this book [introducing go](/static/books/book1.pdf) . I found it quit interesting as it is very much beginners friendly with some excercise at the end of each chapter

# JWT 
- ### [JWT](https://github.com/golang-jwt/jwt) :  Authorization is the most common scenario for using JWT. Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token. Single Sign On is a feature that widely uses JWT nowadays, because of its small overhead and its ability to be easily used across different domains.
# Database
- ### SQL Database: SQL stands for Structured Query Language. It's used for relational databases. A SQL database is a collection of tables that stores a specific set of structured data. Example: MySQL, PostgreSQL e.t.c 
- -  ### [Gorm](https://gorm.io/docs/) : The GORM is fantastic ORM library for Golang, aims to be developer friendly. It is an ORM library for dealing with relational databases. This gorm library is developed on the top of database/sql package.
- ### NoSQL Database: NoSQL databases (aka "not only SQL") are non-tabular databases and store data differently than relational tables. NoSQL databases come in a variety of types based on their data model. The main types are document, key-value, wide-column, and graph. They provide flexible schemas and scale easily with large amounts of data and high user loads. Example: MongoDB, couchDB e.t.c

# Go Frameworks
## Gin

### [Gin](https://gin-gonic.com) is a web framework written in Golang. It features a Martini-like API, but with performance up to 40 times faster than Martini. If you need performance and productivity, you will love Gin. 
I must say that this is actually my favourite as I have built lots of APIs using Gin
- You can head over to [docs](https://gin-gonic.com) for gin documentation or  [gin github repo](https://github.com/gin-gonic/gin)

## Gorilla/mux

### [Gorilla/mux](https://github.com/gorilla/mux) is a powerful HTTP router and URL matcher for building Go web servers 
- You can head over to [mux](https://github.com/gorilla/mux) for gorilla/mux documentation

## Beego
### Beego is used for rapid development of enterprise application in Go, including RESTful APIs, web apps and backend services.
- You can head over to [beego](https://github.com/beego/beego) for beego documentation

## Ravel 
### A high productivity, full-stack web framework for the Go language.
- You can head over to [ravel](https://github.com/revel/revel) for ravel documentation

## Chi 
### chi is a lightweight, idiomatic and composable router for building Go HTTP services. It's especially good at helping you write large REST API services that are kept maintainable as your project grows and changes. chi is built on the new context package introduced in Go 1.7 to handle signaling, cancelation and request-scoped values across a handler chain.
- You can head over to [chi](https://github.com/go-chi/chi) for chi documentation

## Echo
### High performance, minimalist Go web framework 
- You can head over to [echo](https://github.com/labstack/echo) for echo documentation

## Fiber
### Fiber is an Express inspired web framework built on top of Fasthttp, the fastest HTTP engine for Go. Designed to ease things up for fast development with zero memory allocation and performance in mind. 
- You can head over to [fiber](https://github.com/gofiber/fiber) for fiber documentation

## Goji
### Goji is a HTTP request multiplexer, similar to net/http.ServeMux. It compares incoming requests to a list of registered Patterns, and dispatches to the http.Handler that corresponds to the first matching Pattern. Goji also supports Middleware (composable shared functionality applied to every request) and uses the standard context package to store request-scoped values.
- You can head over to [goji](https://github.com/goji/goji) for goji documentation

# Logging
- ### [Zap](https://github.com/uber-go/zap) : Blazing fast, structured, leveled logging in Go.
- ### [Zerolog](https://github.com/rs/zerolog) : The zerolog package provides a fast and simple logger dedicated to JSON output.

## As a developer always remeber that [Google](https://google.com/) is like your best friend and as such you can always get more resources with a proper google search.

- ### Watch out, there is such a thing as TUTORIAL HELL and alot of us get stuck in it for a very long time including myself (I was when I started out as a Go developer). So watch out and try not to get stuck on going through a tutorial over and over again because you still feel incompetent. You wouldnt know what you are capable of just yet not until you have built something with the current knowledge you already acquired. It is always said that the best way to learn is actually by doing (atleast that was true in my own case). So build something.

- ### You can get other Go books from [books](/static/books/)

### I know how difficult this part can be especially when you are just starting out as a beginner and as such I wouldn't mind putting you through to get to where I am in development with golang. So please feel free to reach out. I would be glad to help.