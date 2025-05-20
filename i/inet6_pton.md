# Function: <code>inet6_pton</code>

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
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff817e72b0)
Location: net/core/utils.c:324
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff817e72b0-ffffffff817e744c: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818621f0)
Location: net/core/utils.c:324
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff818621f0-ffffffff8186238c: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818ade70)
Location: net/core/utils.c:324
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff818ade70-ffffffff818ae00e: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818d20e0)
Location: net/core/utils.c:324
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff818d20e0-ffffffff818d227e: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff8191f370)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff8191f370-ffffffff8191f50a: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff819515b0)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff819515b0-ffffffff8195174a: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81a22420)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81a22420-ffffffff81a225ba: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81a227a0)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81a227a0-ffffffff81a2293a: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81a09ad0)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81a09ad0-ffffffff81a09c69: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81abbfb0)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81abbfb0-ffffffff81abc167: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81c369e0)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81c369e0-ffffffff81c36bbe: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81dea170)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81dea170-ffffffff81dea350: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81e5b960)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81e5b960-ffffffff81e5bb40: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81f1ad20)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81f1ad20-ffffffff81f1af00: inet6_pton (STB_LOCAL)
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
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffff800010bf32c0)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffff800010bf32c0-ffff800010bf3438: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (c0d0bae4)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
c0d0bae4-c0d0bc4c: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (c000000000cd8220)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
c000000000cd8220-c000000000cd840c: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffe000774c38)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffe000774c38-ffffffe000774d64: inet6_pton (STB_LOCAL)
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
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818f1580)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff818f1580-ffffffff818f171a: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818ab3c0)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff818ab3c0-ffffffff818ab55a: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff819425b0)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff819425b0-ffffffff8194274a: inet6_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet6_pton(struct net *net, const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81963eb0)
Location: net/core/utils.c:320
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81963eb0-ffffffff8196404a: inet6_pton (STB_LOCAL)
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
