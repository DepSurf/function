# Function: <code>fl6_merge_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff817f5bf0)
Location: net/ipv6/ip6_flowlabel.c:294
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff817f5bf0-ffffffff817f5c70: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81864cd0)
Location: net/ipv6/ip6_flowlabel.c:294
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81864cd0-ffffffff81864d4d: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff818973b0)
Location: net/ipv6/ip6_flowlabel.c:294
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff818973b0-ffffffff8189742d: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff818bd7c0)
Location: net/ipv6/ip6_flowlabel.c:294
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff818bd7c0-ffffffff818bd83d: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81940f60)
Location: net/ipv6/ip6_flowlabel.c:294
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81940f60-ffffffff81940fe3: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81999e10)
Location: net/ipv6/ip6_flowlabel.c:294
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81999e10-ffffffff81999e93: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff819d09e0)
Location: net/ipv6/ip6_flowlabel.c:294
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff819d09e0-ffffffff819d0a63: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81a3f450)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81a3f450-ffffffff81a3f4d3: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81a760c0)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81a760c0-ffffffff81a76143: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6fcd0)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81b6fcd0-ffffffff81b6fd53: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7e800)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81b7e800-ffffffff81b7e883: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6d410)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81b6d410-ffffffff81b6d48f: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81c35330)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81c35330-ffffffff81c353af: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd2cf0)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81dd2cf0-ffffffff81dd2d7b: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa41c0)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81fa41c0-ffffffff81fa424b: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff82004a80)
Location: net/ipv6/ip6_flowlabel.c:315
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff82004a80-ffffffff82004b0b: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff820d3850)
Location: net/ipv6/ip6_flowlabel.c:315
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff820d3850-ffffffff820d38db: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffff800010d3e918)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffff800010d3e918-ffff800010d3e9b8: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (c0e41d40)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
c0e41d40-c0e41de0: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (c000000000e73890)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
c000000000e73890-c000000000e73948: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffe00087b026)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffe00087b026-ffffffe00087b0a6: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81a15750)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81a15750-ffffffff81a157d3: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff819d2510)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff819d2510-ffffffff819d2593: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81a801d0)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81a801d0-ffffffff81a80253: fl6_merge_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct ipv6_txoptions *fl6_merge_options(struct ipv6_txoptions *opt_space, struct ip6_flowlabel *fl, struct ipv6_txoptions *fopt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffff81a8cb80)
Location: net/ipv6/ip6_flowlabel.c:312
Inline: True
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81a8cb80-ffffffff81a8cc03: fl6_merge_options (STB_GLOBAL)
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
