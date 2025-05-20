# Function: <code>sk_get_meminfo</code>

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
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b6410)
Location: net/core/sock.c:2959
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff817b6410-ffffffff817b6494: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182e9d0)
Location: net/core/sock.c:3020
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff8182e9d0-ffffffff8182ea54: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81878e50)
Location: net/core/sock.c:3095
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff81878e50-ffffffff81878ed4: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81899800)
Location: net/core/sock.c:3046
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff81899800-ffffffff81899884: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e3e00)
Location: net/core/sock.c:3194
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff818e3e00-ffffffff818e3e84: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81915fe0)
Location: net/core/sock.c:3209
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff81915fe0-ffffffff81916064: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e764a)
Location: net/core/sock.c:3338
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
Direct callers:
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff819e9580-ffffffff819e9604: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e7818)
Location: net/core/sock.c:3290
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
Direct callers:
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff819e9430-ffffffff819e94b4: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cd1e9)
Location: net/core/sock.c:3313
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
Direct callers:
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff819cf550-ffffffff819cf5d4: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7cafd)
Location: net/core/sock.c:3439
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
Direct callers:
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff81a7f090-ffffffff81a7f114: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bf25d0)
Location: net/core/sock.c:3624
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff81bf25d0-ffffffff81bf265e: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9fe00)
Location: net/core/sock.c:3715
Inline: False
Direct callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff81d9fe00-ffffffff81d9fe8e: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0e5c0)
Location: net/core/sock.c:3746
Inline: False
Direct callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff81e0e5c0-ffffffff81e0e64e: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ecb050)
Location: net/core/sock.c:3754
Inline: False
Direct callers:
  - net/core/sock.c:sk_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff81ecb050-ffffffff81ecb109: sk_get_meminfo (STB_GLOBAL)
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
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010baef88)
Location: net/core/sock.c:3209
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffff800010baef88-ffff800010baf008: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cccab4)
Location: net/core/sock.c:3209
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
c0cccab4-c0cccb2c: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c84cd0)
Location: net/core/sock.c:3209
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
c000000000c84cd0-c000000000c84d40: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe000740ab4)
Location: net/core/sock.c:3209
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffe000740ab4-ffffffe000740b22: sk_get_meminfo (STB_GLOBAL)
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
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b5fe0)
Location: net/core/sock.c:3209
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff818b5fe0-ffffffff818b6064: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186ff30)
Location: net/core/sock.c:3209
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff8186ff30-ffffffff8186ffb4: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81906fe0)
Location: net/core/sock.c:3209
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff81906fe0-ffffffff81907064: sk_get_meminfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sk_get_meminfo(const struct sock *sk, u32 *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81928010)
Location: net/core/sock.c:3209
Inline: False
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
**Symbols:**

```
ffffffff81928010-ffffffff81928094: sk_get_meminfo (STB_GLOBAL)
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
