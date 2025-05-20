# Function: <code>extract_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817ca250)
Location: net/ipv6/addrconf.c:4052
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
```
**Symbols:**

```
ffffffff817ca250-ffffffff817ca2b0: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81837380)
Location: net/ipv6/addrconf.c:4304
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
ffffffff81837380-ffffffff818373e1: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81868e80)
Location: net/ipv6/addrconf.c:4347
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
ffffffff81868e80-ffffffff81868ee1: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8188d540)
Location: net/ipv6/addrconf.c:4421
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
ffffffff8188d540-ffffffff8188d5a0: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8190e5b0)
Location: net/ipv6/addrconf.c:4425
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
ffffffff8190e5b0-ffffffff8190e610: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819656f0)
Location: net/ipv6/addrconf.c:4471
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
ffffffff819656f0-ffffffff81965753: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199ab70)
Location: net/ipv6/addrconf.c:4492
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
ffffffff8199ab70-ffffffff8199abd3: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a06aa0)
Location: net/ipv6/addrconf.c:4530
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
ffffffff81a06aa0-ffffffff81a06b02: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a3d610)
Location: net/ipv6/addrconf.c:4536
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
ffffffff81a3d610-ffffffff81a3d672: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3c734)
Location: net/ipv6/addrconf.c:4553
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b4b448)
Location: net/ipv6/addrconf.c:4580
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b38faa)
Location: net/ipv6/addrconf.c:4584
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bff74a)
Location: net/ipv6/addrconf.c:4620
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d99235)
Location: net/ipv6/addrconf.c:4626
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f67f55)
Location: net/ipv6/addrconf.c:4639
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc7fa4)
Location: net/ipv6/addrconf.c:4645
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff820956c6)
Location: net/ipv6/addrconf.c:4696
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
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
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010cfe930)
Location: net/ipv6/addrconf.c:4536
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
ffff800010cfe930-ffff800010cfe9a4: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e070a4)
Location: net/ipv6/addrconf.c:4536
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
c0e070a4-c0e07118: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e27a70)
Location: net/ipv6/addrconf.c:4536
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
c000000000e27a70-c000000000e27b44: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe0008494ee)
Location: net/ipv6/addrconf.c:4536
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
ffffffe0008494ee-ffffffe00084954c: extract_addr (STB_LOCAL)
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
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819dcca0)
Location: net/ipv6/addrconf.c:4536
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
ffffffff819dcca0-ffffffff819dcd02: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81999a60)
Location: net/ipv6/addrconf.c:4536
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
ffffffff81999a60-ffffffff81999ac2: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a47720)
Location: net/ipv6/addrconf.c:4536
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
ffffffff81a47720-ffffffff81a47782: extract_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct in6_addr *extract_addr(struct nlattr *addr, struct nlattr *local, struct in6_addr **peer_pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a53620)
Location: net/ipv6/addrconf.c:4536
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_deladdr
```
**Symbols:**

```
ffffffff81a53620-ffffffff81a53682: extract_addr (STB_LOCAL)
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
