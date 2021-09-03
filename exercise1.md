11.1 Warming up
For linting, testing, and building in Python, I suppose there are many options to choose from. Pylint is probably one of the most popular ones for linting, unittest and nose for testing, and PyBuilder for building. I haven't set up CI/CD in a Python ecosystem (and did only a little professional development beyond simple tooling in Python altogether), so this is a bit fuzzy area in my knowledge.

As for alternatives to setting up the CI besides Jenkins and GitHub Actions, I'm personally familiar with Azure DevOps, which has pipelines and other related tools, and so does GitLab. AWS has a similar set of services for repos, pipelines, etc., too. Azure DevOps seemed fairly intuitive to use, but since Microsoft acquired GitHub some time ago, it's probably going to be the leading CI/CD in enterprise use, too.

I'd definitely set up CI using a cloud-based environment. That would save a lot of time and let the team focus on development and spend less time setting up and maintaining a server. Frankly, most of the CI environments mentioned above have enterprise-grade options, which should be enough for most teams and companies, so why bother hosting it yourself.
