# The Python Exercise

**Welcome to our Python exercise!**

You are going to build a Python web application which implements a key/value
store inspired by the [Redis](https://en.wikipedia.org/wiki/Redis) database.
Don't worry, we are not going to implement the whole database. We want a simple
application which you can hopefully develop in a single evening. All the data is
stored within the application memory. There is no need to persist it to the
disk.

The application should provide an API for the following operations:

- `SET key value`
- `GET key`
- `EXISTS key`
- `DEL key`
- `INCRBY key increment`

The above operations are written as a pseudocode. You should decide how do you
expose them within your API. You can lookup the semantics of the operations in
[Redis commands reference](https://redis.io/docs/latest/commands/). Treat it as
inspiration. We are only implementing a subset of each command semantics.

Please create a Github repository containing your work. Structure it as you
would do if it would be a real work project. This exercise is in software
engineering, not in algorithms. We don't expect you to invent sophisticated data
structures, but we do expect you to produce a clean, readable, maintanable code.

Optional deliverables for bonus points:

- top-level README file describing your application very briefly
- shell script demonstrating your application usage using `curl` tool
- Dockerfile wrapping the application
- Github workflow combining other deliverables in a sensible way

We would be happy to hear your feedback about this exercise! To help us to gauge
its size and complexity please include the following in the README file (or
communicate via your recruiter)

- your subjective measure of the complexity of the exercise: very easy, easy, medium, hard, very hard
- how much time have you spent on it in total and per each part
- any comments about the exercise and suggestions for improvement

We understand that such an exercise requires your personal time investment and
we appreciate your effort! Hope to see your soon at the interview!
