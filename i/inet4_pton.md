# Function: <code>inet4_pton</code>

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
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff817e7450)
Location: net/core/utils.c:305
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff817e7450-ffffffff817e74ad: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81862390)
Location: net/core/utils.c:305
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81862390-ffffffff818623ed: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818ae010)
Location: net/core/utils.c:305
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff818ae010-ffffffff818ae06d: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818d2280)
Location: net/core/utils.c:305
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff818d2280-ffffffff818d22dd: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff8191f510)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff8191f510-ffffffff8191f56d: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81951750)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81951750-ffffffff819517ad: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81a225c0)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81a225c0-ffffffff81a2261d: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81a22940)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81a22940-ffffffff81a2299d: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81a09c70)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81a09c70-ffffffff81a09ccd: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81abc170)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81abc170-ffffffff81abc1cd: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81c36bc0)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81c36bc0-ffffffff81c36c2c: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81de9ca0)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81de9ca0-ffffffff81de9d0d: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81e5b4b0)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81e5b4b0-ffffffff81e5b51d: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81f1a870)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81f1a870-ffffffff81f1a8dd: inet4_pton (STB_LOCAL)
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
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffff800010bf2ef8)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffff800010bf2ef8-ffff800010bf2f74: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (c0d0bc4c)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
c0d0bc4c-c0d0bcc4: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (c000000000cd8410)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
c000000000cd8410-c000000000cd84b8: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffe0007748e6)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffe0007748e6-ffffffe000774952: inet4_pton (STB_LOCAL)
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
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818f1720)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff818f1720-ffffffff818f177d: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff818ab560)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff818ab560-ffffffff818ab5bd: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81942750)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81942750-ffffffff819427ad: inet4_pton (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inet4_pton(const char *src, u16 port_num, struct __kernel_sockaddr_storage *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81964050)
Location: net/core/utils.c:301
Inline: False
Direct callers:
  - net/core/utils.c:inet_pton_with_scope
  - net/core/utils.c:inet_pton_with_scope
```
**Symbols:**

```
ffffffff81964050-ffffffff819640ad: inet4_pton (STB_LOCAL)
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
