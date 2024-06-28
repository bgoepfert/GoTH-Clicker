### Getting started with Go, htmx, and templates: Part 2

Learning advanced Golang and htmx techniques to build a real-time multiplayer clicker game.

__IMG__

Welcome back! This is part 2 in the Go + htmx series. We'll be picking up where we left of from Part 1 (https://medium.com/dev-genius/getting-started-with-go-htmx-and-templates-part-1-86bc3a0d92da).

In Part 1, you built a very simple mouse counter. Today, we'll be taking that idea further to learn more advanced concepts in both Go and htmx by building a real-time, multiplayer clicker game!

**Note:** htmx 2.0 has been released since Part 1! You can find the 2.0 file here: `https://unpkg.com/htmx.org@2.0.0/dist/htmx.min.js`, and we will be using a 2.0 feature, so please make sure you upgrade if you're continuing on from Part 1.

#### Off we... Go?
Complete code repo: __link__

If you've already completed Part 1, you already have everything you need to follow along. Since this is a much more involved example than our Hello, World!, lets take a look at the core concepts you'll learn:

- Using htmx extensions
  - You'll use the htmx ws extension to broadcast messages to users via WebSockets for real-time updates.
- Concurrency in Go
  - To handle user interactions, you'll learn how to use goroutines, locks, and channels.
- Working with css transitions and animations in htmx

**Note:** This is definitely not the best way to build this, and other technologies might be better suited to the job, however I think it's a more interesting way to learn these ideas than yet another TODO app 📝.
