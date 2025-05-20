# Function: <code>nf_route</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff818e1ce0)
Location: net/netfilter/utils.c:53
Inline: True
```
**Symbols:**

```
ffffffff818e1ce0-ffffffff818e1d1f: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff8190eb80)
Location: net/netfilter/utils.c:162
Inline: True
```
**Symbols:**

```
ffffffff8190eb80-ffffffff8190ebbf: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81970750)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffff81970750-ffffffff8197077d: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff819a7140)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffff819a7140-ffffffff819a716d: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a904a0)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffff81a904a0-ffffffff81a904cd: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a9a370)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffff81a9a370-ffffffff81a9a39d: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81a85660)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffff81a85660-ffffffff81a8568d: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81b3fd50)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffff81b3fd50-ffffffff81b3fd7d: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81ccc5a0)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffff81ccc5a0-ffffffff81ccc5eb: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81e8c4b0)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffff81e8c4b0-ffffffff81e8c4fb: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81eea540)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffff81eea540-ffffffff81eea58b: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81fae2f0)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffff81fae2f0-ffffffff81fae33b: nf_route (STB_GLOBAL)
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
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffff800010c56bd8)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffff800010c56bd8-ffff800010c56c6c: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (c0d66354)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
c0d66354-c0d66394: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (c000000000d57840)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
c000000000d57840-c000000000d578c0: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffe0007c0b80)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffe0007c0b80-ffffffe0007c0bec: nf_route (STB_GLOBAL)
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
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81946fb0)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffff81946fb0-ffffffff81946fdd: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81900aa0)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffff81900aa0-ffffffff81900acd: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff81998140)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffff81998140-ffffffff8199816d: nf_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nf_route(struct net *net, struct dst_entry **dst, struct flowi *fl, bool strict, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/utils.c (ffffffff819bae20)
Location: net/netfilter/utils.c:163
Inline: False
```
**Symbols:**

```
ffffffff819bae20-ffffffff819bae4d: nf_route (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
