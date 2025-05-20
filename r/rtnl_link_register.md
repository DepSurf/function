# Function: <code>rtnl_link_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81729dd0)
Location: net/core/rtnetlink.c:324
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
```
**Symbols:**

```
ffffffff81729dd0-ffffffff81729dfd: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81793910)
Location: net/core/rtnetlink.c:346
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff81793910-ffffffff8179393d: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c11e0)
Location: net/core/rtnetlink.c:347
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff817c11e0-ffffffff817c120d: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817df9a0)
Location: net/core/rtnetlink.c:349
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff817df9a0-ffffffff817df9cd: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185a200)
Location: net/core/rtnetlink.c:318
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff8185a200-ffffffff8185a22d: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a5a80)
Location: net/core/rtnetlink.c:391
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff818a5a80-ffffffff818a5ac8: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818c9030)
Location: net/core/rtnetlink.c:401
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff818c9030-ffffffff818c9078: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:396
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff8191e655-ffffffff8191e66e: rtnl_link_register.cold (STB_LOCAL)
ffffffff81916010-ffffffff81916058: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81948640)
Location: net/core/rtnetlink.c:396
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff81948640-ffffffff8194868f: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1a2b0)
Location: net/core/rtnetlink.c:396
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff81a1a2b0-ffffffff81a1a379: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a1a4a0)
Location: net/core/rtnetlink.c:398
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff81a1a4a0-ffffffff81a1a569: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a014b0)
Location: net/core/rtnetlink.c:398
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff81a014b0-ffffffff81a01579: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab38a0)
Location: net/core/rtnetlink.c:398
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_init
```
**Symbols:**

```
ffffffff81ab38a0-ffffffff81ab38f3: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2cb40)
Location: net/core/rtnetlink.c:435
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_init
```
**Symbols:**

```
ffffffff81c2cb40-ffffffff81c2cb9a: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ddfc60)
Location: net/core/rtnetlink.c:436
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_init
```
**Symbols:**

```
ffffffff81ddfc60-ffffffff81ddfcba: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e50f80)
Location: net/core/rtnetlink.c:439
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
  - drivers/net/wwan/wwan_core.c:wwan_init
```
**Symbols:**

```
ffffffff81e50f80-ffffffff81e50fda: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f10020)
Location: net/core/rtnetlink.c:434
Inline: False
Direct callers:
  - drivers/net/netkit.c:netkit_init
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff81f10020-ffffffff81f1007a: rtnl_link_register (STB_GLOBAL)
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
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bea260)
Location: net/core/rtnetlink.c:396
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffff800010bea260-ffff800010bea2d8: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d02c14)
Location: net/core/rtnetlink.c:396
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
c0d02c14-c0d02c8c: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccc9b0)
Location: net/core/rtnetlink.c:396
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
c000000000ccc9b0-c000000000ccca5c: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076dad8)
Location: net/core/rtnetlink.c:396
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffe00076dad8-ffffffe00076db44: rtnl_link_register (STB_GLOBAL)
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
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e8610)
Location: net/core/rtnetlink.c:396
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff818e8610-ffffffff818e865f: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a2450)
Location: net/core/rtnetlink.c:396
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/vxlan.c:vxlan_init_module
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff818a2450-ffffffff818a249f: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81939640)
Location: net/core/rtnetlink.c:396
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff81939640-ffffffff8193968f: rtnl_link_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtnl_link_register(struct rtnl_link_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195ad20)
Location: net/core/rtnetlink.c:396
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_init
  - drivers/net/ppp/ppp_generic.c:ppp_init
```
**Symbols:**

```
ffffffff8195ad20-ffffffff8195ad6f: rtnl_link_register (STB_GLOBAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
