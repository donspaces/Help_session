# Website map (future)

Here is a map of the major website structure on domain ```*.donspaces.com```:

```mermaid
flowchart TB
A([donspaces.com]) ==> |Main| B([www.donspaces.com])
A ==> |AI| C([ai.donspaces.com])
A -.-> |Blog| D([blog.donspaces.com])
B --> |Games| Ba([/games])
B --> |Help| Bb([/help])
B -.-> |etc| Bc((( )))
D -.-> |Self Intro| Da([/intro])
D -.-> |Wishing Tree| Db([/tree])
D -.-> |etc| Dc((( )))
```

Here is a map of websites that served for other functions on domain ```*.donspaces.com``` 
(***mostly private, operated by site manager***):
```mermaid
flowchart TB
A([donspaces.com]) ==> B{{Container Base}}
A([donspaces.com]) ==> C{{Game servers}}
A([donspaces.com]) ==> D{{Codespaces}}
B --> |Portainer| Ba(ptn.*)
B --> |Portainer for Rpi| Bb(ptn-rpi.*)
B --> |Proxy| Bc(pm.*)
C --> |AMP| Ca(amp.*)
C --> |Minecraft| Cb(mc.*)
C --> |MC for Rpi| Cc(mc-rpi.*)
D --> |Coder| Da(coder.*)
D --> |Code| Db(code.*)
D --> |Storage| Dc(snap.*)
```

> Except all these websites, there will be many more interesting features that will be 
> integrated to our domain. 
> For more information, please contact us through our 
> [email](https://www.donspaces.com/welcome.html#contact-us).
>
{style="note"}
