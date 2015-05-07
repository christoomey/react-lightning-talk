React
=====

What exactly is it?
-------------------

---

React is not FRP
================

> Reactive programming is programming with asynchronous data streams.

-- André Staltz

[The introduction to Reactive Programming you've been missing][]

[The introduction to Reactive Programming you've been missing]: https://gist.github.com/staltz/868e7e9bc2a7b8c1f754

---

Challenge Best Practces
=======================

----

Render Everything
=================

Re-render the entire app (in memory) on all changes, then efficiently update
the UI to match.

---

Components all the Way Down
===========================

^ Demo a simple list app with App -> List -> Element component hierarchy

---

Functional UI
=============

Things

Each component of your UI is isolated and is rendered directly as a function
of the props passed into it, and it's own internal state.

[React Hot Loader][]

[React Hot Loader]: https://gaearon.github.io/react-hot-loader/

---

The right abstraction
=====================

- [canvas render target][]
- [Netflix's gibbon widget system][]
- [Server side / isometric rendering][] -
- [react native][]

^ - react mego router demo
^ - `curl http://localhost:5000/contact/pete | xmllint --html - | vim -`
^ - compare to `curl https://order.sweetgreen.com/ | xmllint --html - | vim -`

Ember is borrowing with [Glimmer][]

[canvas render target]: http://engineering.flipboard.com/2015/02/mobile-web/
[Netflix's gibbon widget system]: http://conf.reactjs.com/schedule.html#beyond-the-dom-how-netflix-plans-to-enhance-your-television-experience
[react native]: https://facebook.github.io/react-native/
[Server side / isometric rendering]: https://github.com/mhart/react-server-example
[Glimmer]: https://github.com/emberjs/ember.js/pull/10501
