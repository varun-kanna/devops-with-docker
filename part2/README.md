# Introduction to Part 2

This part introduces container orchestration with Docker Compose and relevant concepts such as docker network. By the end of this part you are able to:

-   Run a group of containerized applications that interact with each other via HTTP

-   Run a group of containerized applications that interact with each other via volumes

-   Manually scale applications

-   Use 3rd party services, such as databases, inside containers as part of your project

## Summary

Again we started from the ground up by learning how to translate non-compose setup into docker-compose.yml and ran with it. Compose gave us also a few handy completely new features that we didn't even know we needed, networks.

Now we've learned how to setup up vastly more complex applications with up to 5 different programs running at the same time and they only expose the used ports to the outside world (or even to our machine).

Are we ready for production yet? Short answer: no. Long answer: depends on the situation. Good thing we have part 3
