# Why Gitea?

If you're reading this book, there's a good chance that you already understand the value of a good version-control system, and you are probably already familiar with `git` and GitHub. So then, why Gitea?

When Gitea (and Gogs) first started, GitHub was absolutely free, but only for public respositories. You had to pay if you wanted private respositories. Since that time, Microsoft has acquired GitHub, and now anyone, anywhere, can create unlimited free private respositories. There's still a limitation, though, in that you can only have 3 collaborators on a private repository. "Well," you might ask, "what about GitLab? They offer free unlimited private respositories with unlimited collaborators."

What GitHub and GitLab don't offer you, however, is total control over your data.

Do you **_need_** total control over your data? Only you can truly answer that question. In truth, 95+% of the time, GitHub and GitLab may be more than adequate for the vast majority of use cases. I trust GitHub with some of my private respositories, in part because I suspect that their reliability and robustness will far exceed what I can achieve with the 10-year-old hardware I happen to have running in a closet at home.

But sometimes, as a software engineer, I want to do things myself. I **_want_** to run my own version control system on 10-year-old hardware in my closet. And on those occasions, I need a solution that's not a resource hog, one that's small, lightweight, and quick. Being written in Go[^go], Gitea is both small and fast.

[^go]: Go (sometimes Golang or go-lang) is a small, fast, fun (in my opinion!) language created to bring the ease-of-use and productivity of Javascript and Python to the efficienct execution of the C/C++ world. Find out more at <https://golang.org/doc/faq>.
