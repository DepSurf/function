# Function: <code>get_net_ns_by_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81710b50)
Location: net/core/net_namespace.c:250
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
**Symbols:**

```
ffffffff81710b50-ffffffff81710bc9: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81778480)
Location: net/core/net_namespace.c:250
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
**Symbols:**

```
ffffffff81778480-ffffffff817784f9: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817a54b0)
Location: net/core/net_namespace.c:255
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
**Symbols:**

```
ffffffff817a54b0-ffffffff817a5520: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817c3720)
Location: net/core/net_namespace.c:258
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
```
**Symbols:**

```
ffffffff817c3720-ffffffff817c377a: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8183d1c0)
Location: net/core/net_namespace.c:259
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:get_target_net
```
**Symbols:**

```
ffffffff8183d1c0-ffffffff8183d23e: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81887a70)
Location: net/core/net_namespace.c:279
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:get_target_net
```
**Symbols:**

```
ffffffff81887a70-ffffffff81887aed: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818a82e0)
Location: net/core/net_namespace.c:279
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_sk_lookup
```
**Symbols:**

```
ffffffff818a82e0-ffffffff818a835d: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818f3860)
Location: net/core/net_namespace.c:298
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff818f3860-ffffffff818f38bb: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81925810)
Location: net/core/net_namespace.c:299
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff81925810-ffffffff8192586b: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(const struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f9990)
Location: net/core/net_namespace.c:305
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/devlink.c:devlink_netns_get
```
**Symbols:**

```
ffffffff819f9990-ffffffff819f99ef: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(const struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f94d0)
Location: net/core/net_namespace.c:306
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/devlink.c:devlink_netns_get
```
**Symbols:**

```
ffffffff819f94d0-ffffffff819f953a: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(const struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819df630)
Location: net/core/net_namespace.c:294
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff819df630-ffffffff819df696: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(const struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81a8fa10)
Location: net/core/net_namespace.c:289
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81a8fa10-ffffffff81a8fa76: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(const struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81c03d00)
Location: net/core/net_namespace.c:283
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81c03d00-ffffffff81c03d83: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(const struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81db33d0)
Location: net/core/net_namespace.c:290
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/devlink.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81db33d0-ffffffff81db3453: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(const struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81e23a90)
Location: net/core/net_namespace.c:291
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/devlink/dev.c:devlink_nl_cmd_reload
```
**Symbols:**

```
ffffffff81e23a90-ffffffff81e23b0f: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(const struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81ee19f0)
Location: net/core/net_namespace.c:291
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
  - net/xfrm/xfrm_state_bpf.c:bpf_xdp_get_xfrm_state
  - net/devlink/dev.c:devlink_nl_reload_doit
```
**Symbols:**

```
ffffffff81ee19f0-ffffffff81ee1a6f: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffff800010bc1b90)
Location: net/core/net_namespace.c:299
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffff800010bc1b90-ffff800010bc1c00: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c0cdd090)
Location: net/core/net_namespace.c:299
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
c0cdd090-c0cdd0e0: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c000000000c9b300)
Location: net/core/net_namespace.c:299
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
c000000000c9b300-c000000000c9b3a8: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffe00074ec46)
Location: net/core/net_namespace.c:299
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffe00074ec46-ffffffe00074eca8: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818c5810)
Location: net/core/net_namespace.c:299
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff818c5810-ffffffff818c586b: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8187f750)
Location: net/core/net_namespace.c:299
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff8187f750-ffffffff8187f7ab: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81916810)
Location: net/core/net_namespace.c:299
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff81916810-ffffffff8191686b: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct net *get_net_ns_by_id(struct net *net, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81937a10)
Location: net/core/net_namespace.c:299
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
  - net/core/filter.c:__bpf_skc_lookup
```
**Symbols:**

```
ffffffff81937a10-ffffffff81937a7f: get_net_ns_by_id (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct net *net</code> ➡️ <code>const struct net *net</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
