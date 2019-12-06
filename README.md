# Go

<img src="https://github.com/egonelbre/gophers/blob/master/.thumb/animation/gopher-dance-long-3x.gif ">

By Jonathan Burns, Tristan Chilvers, and Matthew Parnham

## Hello World

```golang
package main

import "fmt"

func main() {
    fmt.Println("hello world")
}
```
 
## Looping

```golang
package main

import "fmt"

func main() {
	
    i := 1
    for i <= 3 {
        fmt.Println(i)
        i = i + 1
    }
}
```
 
## WHY
Why we chose Go is a question of what we could all agree on since we are a group of three. The qualities we wanted in a language is that it is relatively established, and has a lot of material. Go fulfills these standards, as it recently celebrated its 10 year birthday (https://blog.golang.org/10years) and is ranked 15th currently on the PYLP index (http://pypl.github.io/PYPL.html). PopularitY of Programming Language (PYLP) measures how much a language is searched for online, and its ranking indicates that it is one of the more popular out of our options. Additionally, the Go community is good at creating resources for developers learning the language. There is “A Tour of Go” (https://tour.golang.org/welcome/1) that you can use to learn go in browser without having to download or install anything. Also, there is Go by Example (https://gobyexample.com/) which provides snippets of commonly used parts of the language, and Codecademy’s free tutorials to learn go (https://www.codecademy.com/learn/learn-go). Finally, the go gopher is no contest the best programming language mascot (https://blog.golang.org/gopher). 
 
## HISTORY
Go was designed in 2007 at Google by Robert Griesemer, Rob Pike and Ken Thompson to improve programming productivity. It then became an open source project in 2012. The influences for the language stem from the following languages: C++, Python, and JavaScript. The developers sought to keep the useful characteristic of those languages, such as static typing and run-time efficiency from C++ and readability and usability from Python and JavaScript. Additionally, they wanted to address the characteristics that they disliked of C++ in Go. It was eventually released in March 2012 and is still supported today by Google.
https://blog.learngoprogramming.com/about-go-language-an-overview-f0bee143597c
https://opensource.googleblog.com/2009/11/hey-ho-lets-go.html
 
## TASKS
Developers at Google engineered Go to address the modern IT infrastructure. This was in regards to multicore processors, cloud services, computation clusters, and networked systems. Due to the amount problems Google has to address on the daily, Go works well for an organization with projects that involve large and complex back-end technologies. Issues such as slow builds, costly updates, messy documentation, and uncontrolled dependencies can be solved with Go.
https://www.upwork.com/hiring/development/golang-programming-language/
 
## EXAMPLES
Go is a general purpose language, but has mostly be successful in use in cloud technologies. Kubernetes (https://kubernetes.io/), written in Go, is a popular container orchestration solution, with AWS (https://aws.amazon.com/eks/getting-started/), Azure (https://azure.microsoft.com/en-us/services/kubernetes-service/), and GCP (https://cloud.google.com/kubernetes-engine/) all having managed services for it. Docker (https://www.docker.com/) is another ubiquitous cloud technology for managing containers, along with others that may be less know: etcd (https://github.com/etcd-io/etcd), Terraform (https://www.terraform.io/), and Caddy (https://caddyserver.com/). Besides Google, other notable companies are known to use Go for their backend, such as Twitch (https://blog.twitch.tv/en/2016/07/05/gos-march-to-low-latency-gc-a6fa96f06eb7/#.wykex6pkr) and Dropbox (https://blogs.dropbox.com/tech/2014/07/open-sourcing-our-go-libraries/). 
 
## WHY USE GO
Go is still trying to find its niche in the programming world.  Google says that Go is best used in “Google-sized” projects.  Due to Go’s fantastic concurrency, it is well suited for scalable back-end systems.  It is also great for legacy systems where development has a lot of turn over.  Since the code is so easy to read, new developers should have no problem jumping right into updating legacy code.  If your project involves cloud services, distributed systems, or some other large scale back-end, Go could be for you.  Otherwise, you might want to pick something else.
 
## INTERESTING FEATURES
Go’s most notable feature is its ‘goroutines’.  Goroutines are essentially just green threads (scheduled by Go during runtime instead of by the OS).  The reason they are so good stems from their size on the heap.  Goroutines used approximately 2KB of memory from the heap.  This is a major improvement over the approximately 1MB threads used in Java.  This allows users to spin up significantly more goroutines at any given time.  Unlike many other modern programming languages that are compiled or built on a VM, Go is compiled directly into binaries, negating the need for extra software to execute and potentially giving a speed boost to Go programs.  It is apparent that Go is intended for large, scalable, concurrent systems however, as it lacks many common features.  Go has structs instead of classes and only allows for interfaces instead of full inheritance.

## Extra Links

Handout https://drive.google.com/file/d/1VMSRV0u3oOmtlFjJlKUj_qg4vYH_LPiP/view?usp=sharing

Presentation https://docs.google.com/presentation/d/1-fqnT-W-rwRgdcQKWuy4zNfnJbI7SCyrm7u_Vqck__c/edit?usp=sharing

<img src="https://blog.golang.org/gopher/header.jpg" >

