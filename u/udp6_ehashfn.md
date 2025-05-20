# Function: <code>udp6_ehashfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 udp6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff817e3310)
Location: net/ipv6/udp.c:56
Inline: False
Direct callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff817e3310-ffffffff817e34b6: udp6_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 udp6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff818518a0)
Location: net/ipv6/udp.c:58
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
**Symbols:**

```
ffffffff818518a0-ffffffff81851a3f: udp6_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 udp6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81883660)
Location: net/ipv6/udp.c:58
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
**Symbols:**

```
ffffffff81883660-ffffffff818837ff: udp6_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 udp6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff818a98f0)
Location: net/ipv6/udp.c:69
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
**Symbols:**

```
ffffffff818a98f0-ffffffff818a9a8f: udp6_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 udp6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff8192c2d0)
Location: net/ipv6/udp.c:69
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
**Symbols:**

```
ffffffff8192c2d0-ffffffff8192c473: udp6_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 udp6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81984740)
Location: net/ipv6/udp.c:69
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
**Symbols:**

```
ffffffff81984740-ffffffff819848e0: udp6_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819badfc)
Location: net/ipv6/udp.c:70
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a28c93)
Location: net/ipv6/udp.c:57
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a5f7d7)
Location: net/ipv6/udp.c:57
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 udp6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b592e0)
Location: net/ipv6/udp.c:57
Inline: False
```
**Symbols:**

```
ffffffff81b592e0-ffffffff81b59483: udp6_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 udp6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b67910)
Location: net/ipv6/udp.c:57
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81b67910-ffffffff81b67ab3: udp6_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 udp6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b55af0)
Location: net/ipv6/udp.c:57
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81b55af0-ffffffff81b55c97: udp6_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 udp6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81c1b5b0)
Location: net/ipv6/udp.c:58
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
**Symbols:**

```
ffffffff81c1b5b0-ffffffff81c1b757: udp6_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 udp6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81db7cd0)
Location: net/ipv6/udp.c:59
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
**Symbols:**

```
ffffffff81db7cd0-ffffffff81db7e96: udp6_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 udp6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81f87d00)
Location: net/ipv6/udp.c:73
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
**Symbols:**

```
ffffffff81f87d00-ffffffff81f87ec6: udp6_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 udp6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81fea760)
Location: net/ipv6/udp.c:75
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
**Symbols:**

```
ffffffff81fea760-ffffffff81fea976: udp6_ehashfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 udp6_ehashfn(const struct net *net, const struct in6_addr *laddr, const u16 lport, const struct in6_addr *faddr, const __be16 fport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff820b8680)
Location: net/ipv6/udp.c:76
Inline: False
```
**Symbols:**

```
ffffffff820b8680-ffffffff820b8896: udp6_ehashfn (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffff800010d23c74)
Location: net/ipv6/udp.c:57
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c0e29764)
Location: net/ipv6/udp.c:57
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c000000000e55c20)
Location: net/ipv6/udp.c:57
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffe000866798)
Location: net/ipv6/udp.c:57
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819fee67)
Location: net/ipv6/udp.c:57
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bbc27)
Location: net/ipv6/udp.c:57
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a698e7)
Location: net/ipv6/udp.c:57
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a75ecb)
Location: net/ipv6/udp.c:57
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
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
