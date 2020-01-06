# How to get Involved
We are all volunteering in our free time to help provide a user-friendly ecosystem of packages, so the process might take a while. It takes effort to develop and maintain a package, and we'll like to make sure that we don't get over-extended in promising functionality that we cannot deliver/maintain. For that reason, it is recommended for every package listed in JuliaGeo to go through a review process, so that they run a lower risk of being abandoned/neglected.

Here's a set of guidelines if you want to

## Develop your own package
1. Familiarize yourself with the julia manual on [working with packages](http://docs.julialang.org/en/latest/manual/packages/).
2. If you don't have the intention of fixing bugs, or maintaining the package, you're good to go! New users can use your package with a call to `Pkg.clone(<insert-your-git-repo>)`.
3. If you intend to maintain the package, and would like to make it more widely known/usable, depending on your target audience: announce on [julia-users](https://groups.google.com/forum/#!forum/julia-users) and/or [julia-geo](https://groups.google.com/forum/#!forum/julia-geo). It is common/recommended practice to prefix the title with `[ANN]` to stand for "announcement".

## Register your package under the JuliaGeo organization
If you have written a package, and would like to have it listed under the JuliaGeo organization, you're agreeing to

- take responsibility/ownership for the continued maintenance of the package
- let the current owners of JuliaGeo have joint ownership of the package (so that they can help you review/merge pull requests, and to develop new features)
- go through a joint review/decision on a suitable package name (which is usually the original package name, but might be renamed to something more official/discoverable, if it is contentious/non-standard)

The steps to take are as follows:

1. Announce your package on the julia-geo mailing list.
2. See if any of the existing JuliaGeo members are willing to adopt/mentor/vouch-for the package. Settle on a suitable name.
3. Get the package up to standard (provide tests/build-scripts/documentation/registered-in-METADATA) for inclusion into JuliaGeo.
4. Transfer ownership to JuliaGeo

## Join the JuliaGeo organization
Get any of the current owners to add you. They will generally be willing to do so if you have

- registered a new package under JuliaGeo, or
- submitted and made significant/important pull-requests

None of these are set in stone, and it's mainly to verify that you're familiar with the process of filing-bugs/surfacing-issues/providing-documentation/reviewing-pull-requests, and are willing to do so. Any other avenue for demonstrating them might be be sufficient justification for your inclusion.

## Help out, but don't know where to begin
Have a look at the following [guide for contributions](https://github.com/IainNZ/ContributeToJulia), written by Iain.

## Ask questions for how a given package should work

Open a new thread in the julia-geo mailing list if

- you want to know if developers have been working on packages that they haven't yet announced, to

   - avoid duplication of effort, or
   - [if they're busy] be directed to resources/existing-work/etc

- it is a broad/general discussion about geospatial packages in julia, or
- it requires coordination/consensus from broader audience

File an issue in the github repo of any given package if

- it is specific to that package
- it can be resolved by a specific decision (i.e. it is not a poll/discussion)

## Announce an event or initiative

Post it in the julia-geo mailing list, and add `[ANN]` to the title of the thread.
