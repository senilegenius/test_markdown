test_markdown
=============

test_markdown

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

I think you should use an

```
lava.
     servers.
             api-admin.
             api-pub1.
             api-pub2.
             ...

nova.    <<-- this is what this PR would create
     hypervisors.
                 14-128-10-432786.
                 14-128-11-432789.
                 14-128-12-432790.
                 ...

cbd.
    (future)

networking.
           (future)

cbs.
    (future)

```

One question, the next metrics we're about to collect...
Where would capacity numbers go?
Under lava or nova or cbd?
