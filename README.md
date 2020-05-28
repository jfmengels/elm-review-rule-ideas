# Rule ideas for elm-review

Discuss rule ideas for [`elm-review`].

If you think of an idea, look through the issues to see if someone found a similar idea already, and create an issue otherwise.
You may also want to look for rules in the [Elm packages registry](https://package.elm-lang.org/) and in the [GitHub `elm-review` topic](https://github.com/topics/elm-review).

## Motivations

### 1. Lasting discussions

A lot of these discussions can be had on the Elm Slack in the #elm-review channel, but those don't remain visible for a long time, and are hard to search for. Being able to search for rule proposals will be useful to see what was thought of already, how they evolved and potentially where an implementation can be found.

I also hope that having people watch these public issues will lead to discussions that will ultimately raise the quality of the rules. Maybe the discussion will lead to the rule not being implemented, which can be a good thing too, because not all rules are valuable to have!

### 2. Grouping rules in discoverable ways

We are in the exploratory phase of `elm-review` as a community and as an ecosystem. People will want to write rules and publish them, and I imagine a lot of them will end up in packages that only contain a single rule. While those are valuable, having the users add one dependency for each rule does not make for a great experience and makes it hard to explore the available rules in the community. While the rule from a single-rule package can later be moved into a package that contains similar rules, that means the rule will be duplicated, and it would be nice if we could avoid that.

If you see someone propose a rule, apart from figuring out how to make it great, it can be useful to figure out with which other rules it can fit into a single package. I hope that this will lead to a more cohesive ecosystem.

### 3. Getting people excited

`elm-review` is still young, and a lot of people don't see its potential yet. I think that these discussions can make people think of use-cases where `elm-review` can add a lot of value. I know some people look for high-quality examples to figure out how to implement some ideas, and I think these can lead them to those (in the discussion or in a link to the end result).

Also, I know that some are eager to write rules (to try it out or because they have a lot of fun doing so), so maybe you will find someone really eager to help out (That is how I got started with review rules!).

## Code of conduct

I would like this community to be healthy, and I would like to request a few additional things in addition to the usual code of conduct (TODO create one!).

1. Respect a maintainer's decision to refuse adding a rule to their package. Adding a rule in a package means more maintenance in the future (documentation, more configuration options, updating to new versions of Elm of `elm-review`, ...), and not wanting to add that burden is a reasonable reason. Ultimately, the package is under a name, meaning that it should somewhat reflect that person's choices and opinions, and they should not have to maintain they strongly disagree with.

  Similarly, don't disrespectfully ask them why something hasn't been fixed even after years of waiting. I made `elm-review` in a way that makes it easy to fork rules into your project, which should prevent you from being blocked.

2. It is fine to *ask* others to write a rule in your stead (but you should try it yourself though, it's fun to do!), but don't *demand* others to spend their free time for you. Be respectful of other's time, priorities and situations. If they help you out, don't forget to thank them!

3. I have seen a lot of people write rules (for other languages) and later abandon them, even though issues and pull requests pile up. I have personally done so on still-popular projects. If that happens to you as a maintainer, please consider giving someone edit (admin?) accesses to the repository. Until we have a better place to discuss this, please open an issue here to search for new maintainers if you are able to.

[`elm-review`]: https://github.com/topics/elm-review
