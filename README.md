# CSSSJ Website

Welcome! If you can read this, it's because you've been invited to help care
for the website of the Cactus and Succulent Society of San Jose, a.k.a. the
CSSSJ. Our hope is that, just as with the plants we love, a little attention
and love will have it thriving.

For the time being, this repository will have two principal branches, `master`
and `dev`. The content of `master` will live in [csssj.org][], while the `dev`
branch will be deployed to [dev.csssj.org][].

For the time being, those deployments will be manual, i.e. someone logs into
[csssj.org][] and performs a `git pull`. If our updates ever become voluminous
enough, we'll revisit that.

[csssj.org]: https://csssj.org
[dev.csssj.org]: https://dev.csssj.org

---

# Plans

Here are the things I'd like to do in the near future. There will very likely
be some overlap between different phases. (In particular, between **Phase 3** and
its neighbors.)

- **Phase 1: Culling**

    There seem to be a number of files on the inherited site that, when they
    outlived their usefulness, were simply renamed. We should scan the HTML
    files, collect the names of the files they refer to, and remove the rest.

- **Phase 2: Content Organization**

    It also seems that many files, notably gifs, were stored in the top-level
    directory. We should devise a scheme for grouping files. This might be by
    type (e.g. `photos`) or by intended use (e.g. `public_docs`, for flyers and
    other documents that we encourage visitors and members to download and
    print).

- **Phase 3: URL Schema**

    Right now, to take one example, the informational Show and Sale page for
    non-members resides in `show-and-sale`. What do we do when the Show and
    Sale is over? It seems like we should archive that page, so that people can
    look back through history. Maybe we should come up with an organization
    that lets us incorporate the date into the URL from the beginning, and use
    internal symlinks to provide shortcuts.

- **Phase 4: Overhaul**

    This is where we dig and revise the appearance and organization of the
    site. It will involve, among other things, more generous use of photos.
    It's also going to involve the use of modern tools to generate "responsive"
    pages, and to generate new pages from templates.

    My current plan is to use a combination of [Bootstrap][] and [Hugo][] for
    much of the heavy lifting: Bootstrap for flexible control of page layout,
    and Hugo to help uniformly apply navbars and styling.

    Last but certainly not least, it's going to require the skill of designers
    to pick the colors, typography, and layout that please the eye.

[Bootstrap]: https://getbootstrap.com
[Hugo]: https://gohugo.io

- **Phase 5: ???**

    Assuming we get all of those, y'know, trivial little tasks out of the way,
    we can start to think about future expansion, like the long-sought store
    that lets people register and pay for their membership on-line.

