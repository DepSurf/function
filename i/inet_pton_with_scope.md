# Function: <code>inet_pton_with_scope</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff817e74b0)
Location: net/core/utils.c:373
Inline: False
```
**Symbols:**

```
ffffffff817e74b0-ffffffff817e758a: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818623f0)
Location: net/core/utils.c:373
Inline: False
```
**Symbols:**

```
ffffffff818623f0-ffffffff818624ca: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818ae070)
Location: net/core/utils.c:373
Inline: False
```
**Symbols:**

```
ffffffff818ae070-ffffffff818ae150: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818d22e0)
Location: net/core/utils.c:373
Inline: False
```
**Symbols:**

```
ffffffff818d22e0-ffffffff818d23c0: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/utils.c (0)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffff8191f667-ffffffff8191f680: inet_pton_with_scope.cold (STB_LOCAL)
ffffffff8191f570-ffffffff8191f651: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/utils.c (0)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffff819518a7-ffffffff819518c0: inet_pton_with_scope.cold (STB_LOCAL)
ffffffff819517b0-ffffffff81951891: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/utils.c (0)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffff81a22717-ffffffff81a22730: inet_pton_with_scope.cold (STB_LOCAL)
ffffffff81a22620-ffffffff81a22701: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/utils.c (0)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffff81c31730-ffffffff81c31749: inet_pton_with_scope.cold (STB_LOCAL)
ffffffff81a229a0-ffffffff81a22a81: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/utils.c (0)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffff81c23a39-ffffffff81c23a52: inet_pton_with_scope.cold (STB_LOCAL)
ffffffff81a09cd0-ffffffff81a09db1: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/utils.c (0)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffff81d36f78-ffffffff81d36f91: inet_pton_with_scope.cold (STB_LOCAL)
ffffffff81abc1d0-ffffffff81abc2b1: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/utils.c (0)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffff81f038c8-ffffffff81f038e1: inet_pton_with_scope.cold (STB_LOCAL)
ffffffff81c36c30-ffffffff81c36d0f: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81dea360)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffff81dea360-ffffffff81dea438: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81e5bb50)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffff81e5bb50-ffffffff81e5bc28: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81f1af10)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffff81f1af10-ffffffff81f1afe8: inet_pton_with_scope (STB_GLOBAL)
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
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffff800010bf3438)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffff800010bf3438-ffff800010bf3538: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (c0d0bcc4)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
c0d0bcc4-c0d0bdcc: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (c000000000cd84c0)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
c000000000cd84c0-c000000000cd860c: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffe000774d64)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffe000774d64-ffffffe000774e22: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/utils.c (0)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffff818f1877-ffffffff818f1890: inet_pton_with_scope.cold (STB_LOCAL)
ffffffff818f1780-ffffffff818f1861: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/utils.c (0)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffff818ab6b7-ffffffff818ab6d0: inet_pton_with_scope.cold (STB_LOCAL)
ffffffff818ab5c0-ffffffff818ab6a1: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/utils.c (0)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffff819428a7-ffffffff819428c0: inet_pton_with_scope.cold (STB_LOCAL)
ffffffff819427b0-ffffffff81942891: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int inet_pton_with_scope(struct net *net, __kernel_sa_family_t af, const char *src, const char *port, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/utils.c (0)
Location: net/core/utils.c:369
Inline: False
```
**Symbols:**

```
ffffffff819641a7-ffffffff819641c0: inet_pton_with_scope.cold (STB_LOCAL)
ffffffff819640b0-ffffffff81964191: inet_pton_with_scope (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
