## DIB Prototype Site

Lab website. Notes for maintenance:

* To add a new member, just have them put their info in _data/members.yml. They can write a
  paragraph under "about" if they want. The attribute should at least exist.
* Help github out with resolution by prefixing relative links with `{{github.site.url}}`.
* The graph animation pulls its data from `public/graph.json`. It uses a kludge to put the nodes in
    predictable positions; see `function grabity(alpha)` which sets `cx` and `cy` based on node
    group.

## Credit

This site is based on [poole/hyde](https://github.com/poole/poole)
