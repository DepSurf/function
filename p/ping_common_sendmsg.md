# Function: <code>ping_common_sendmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff817a32a0)
Location: net/ipv4/ping.c:656
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff817a32a0-ffffffff817a333a: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff818102c0)
Location: net/ipv4/ping.c:658
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff818102c0-ffffffff8181035a: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff818417b0)
Location: net/ipv4/ping.c:655
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff818417b0-ffffffff81841852: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81863440)
Location: net/ipv4/ping.c:656
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81863440-ffffffff818634ef: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff818e3580)
Location: net/ipv4/ping.c:656
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff818e3580-ffffffff818e362f: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81939e10)
Location: net/ipv4/ping.c:656
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81939e10-ffffffff81939ebf: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81969c60)
Location: net/ipv4/ping.c:654
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81969c60-ffffffff81969d0f: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff819d0920)
Location: net/ipv4/ping.c:649
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff819d0920-ffffffff819d09c6: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81a07470)
Location: net/ipv4/ping.c:649
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a07470-ffffffff81a07516: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81af6ce0)
Location: net/ipv4/ping.c:649
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81af6ce0-ffffffff81af6d86: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81b03b70)
Location: net/ipv4/ping.c:637
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81b03b70-ffffffff81b03c16: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81aef7b0)
Location: net/ipv4/ping.c:639
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81aef7b0-ffffffff81aef863: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81baf7b0)
Location: net/ipv4/ping.c:646
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81baf7b0-ffffffff81baf872: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81d42cb0)
Location: net/ipv4/ping.c:653
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81d42cb0-ffffffff81d42daf: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81f0bc90)
Location: net/ipv4/ping.c:660
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81f0bc90-ffffffff81f0bd8f: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81f6b900)
Location: net/ipv4/ping.c:650
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81f6b900-ffffffff81f6b9ff: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff82031ec0)
Location: net/ipv4/ping.c:650
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff82031ec0-ffffffff82031fbf: ping_common_sendmsg (STB_GLOBAL)
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
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffff800010cc03a0)
Location: net/ipv4/ping.c:649
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffff800010cc03a0-ffff800010cc0494: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (c0dcc6d4)
Location: net/ipv4/ping.c:649
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
c0dcc6d4-c0dcc7a0: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (c000000000ddb5d0)
Location: net/ipv4/ping.c:649
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
c000000000ddb5d0-c000000000ddb71c: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffe000816c38)
Location: net/ipv4/ping.c:649
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffe000816c38-ffffffe000816ce6: ping_common_sendmsg (STB_GLOBAL)
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
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff819a7210)
Location: net/ipv4/ping.c:649
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff819a7210-ffffffff819a72b6: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81960cd0)
Location: net/ipv4/ping.c:649
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81960cd0-ffffffff81960d76: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81a11ab0)
Location: net/ipv4/ping.c:649
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a11ab0-ffffffff81a11b56: ping_common_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ping_common_sendmsg(int family, struct msghdr *msg, size_t len, void *user_icmph, size_t icmph_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81a1c420)
Location: net/ipv4/ping.c:649
Inline: True
Direct callers:
  - net/ipv4/ping.c:ping_v4_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a1c420-ffffffff81a1c4c6: ping_common_sendmsg (STB_GLOBAL)
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
