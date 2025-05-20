# Function: <code>ip6_autoflowlabel</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8190c55d)
Location: net/ipv6/ip6_output.c:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81908f40-ffffffff81908f64: ip6_autoflowlabel.part.39 (STB_LOCAL)
ffffffff8190ad90-ffffffff8190adaf: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819639f1)
Location: net/ipv6/ip6_output.c:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81960210-ffffffff81960231: ip6_autoflowlabel.part.48 (STB_LOCAL)
ffffffff81962280-ffffffff8196229f: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81998993)
Location: net/ipv6/ip6_output.c:177
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81994ff0-ffffffff81995011: ip6_autoflowlabel.part.52 (STB_LOCAL)
ffffffff81997250-ffffffff8199726f: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a047fb)
Location: net/ipv6/ip6_output.c:181
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81a00a90-ffffffff81a00aaa: ip6_autoflowlabel.part.0 (STB_LOCAL)
ffffffff81a03230-ffffffff81a0324f: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a3b3eb)
Location: net/ipv6/ip6_output.c:181
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81a37660-ffffffff81a3767a: ip6_autoflowlabel.part.0 (STB_LOCAL)
ffffffff81a39e00-ffffffff81a39e1f: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b309c5)
Location: net/ipv6/ip6_output.c:182
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81b2f630-ffffffff81b2f65a: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3f5f5)
Location: net/ipv6/ip6_output.c:221
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81b3e080-ffffffff81b3e0aa: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2d48d)
Location: net/ipv6/ip6_output.c:250
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81b2b530-ffffffff81b2b55a: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81bf365e)
Location: net/ipv6/ip6_output.c:231
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81bf1660-ffffffff81bf168a: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81d8c232)
Location: net/ipv6/ip6_output.c:234
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81d89fb0-ffffffff81d89fea: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81f5a1f2)
Location: net/ipv6/ip6_output.c:234
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
**Symbols:**

```
ffffffff81f57f30-ffffffff81f57f6a: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81fb9ea5)
Location: net/ipv6/ip6_output.c:235
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
**Symbols:**

```
ffffffff81fb7b10-ffffffff81fb7b4a: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff82087354)
Location: net/ipv6/ip6_output.c:250
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
**Symbols:**

```
ffffffff82085140-ffffffff82085188: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cfc50c)
Location: net/ipv6/ip6_output.c:181
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffff800010cf81f0-ffff800010cf8224: ip6_autoflowlabel.part.0 (STB_LOCAL)
ffff800010cfada8-ffff800010cfade8: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (c0e03914)
Location: net/ipv6/ip6_output.c:181
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
c0dfec10-c0dfec3c: ip6_autoflowlabel.part.0 (STB_LOCAL)
c0e016ac-c0e016dc: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e24034)
Location: net/ipv6/ip6_output.c:181
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
c000000000e1f210-c000000000e1f230: ip6_autoflowlabel.part.0 (STB_LOCAL)
c000000000e22220-c000000000e2224c: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe000846da8)
Location: net/ipv6/ip6_output.c:181
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffe0008436d8-ffffffe000843704: ip6_autoflowlabel.part.0 (STB_LOCAL)
ffffffe00084594c-ffffffe00084599a: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819daa7b)
Location: net/ipv6/ip6_output.c:181
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff819d6cf0-ffffffff819d6d0a: ip6_autoflowlabel.part.0 (STB_LOCAL)
ffffffff819d9490-ffffffff819d94af: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8199783b)
Location: net/ipv6/ip6_output.c:181
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81993ab0-ffffffff81993aca: ip6_autoflowlabel.part.0 (STB_LOCAL)
ffffffff81996250-ffffffff8199626f: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a454fb)
Location: net/ipv6/ip6_output.c:181
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81a41770-ffffffff81a4178a: ip6_autoflowlabel.part.0 (STB_LOCAL)
ffffffff81a43f10-ffffffff81a43f2f: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ip6_autoflowlabel(struct net *net, const struct ipv6_pinfo *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a511cb)
Location: net/ipv6/ip6_output.c:181
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
Direct callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
**Symbols:**

```
ffffffff81a4d3d0-ffffffff81a4d3ea: ip6_autoflowlabel.part.0 (STB_LOCAL)
ffffffff81a4fbb0-ffffffff81a4fbcf: ip6_autoflowlabel (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sock *sk</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct ipv6_pinfo *np</code>
</li>
</ul>
</details>
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
