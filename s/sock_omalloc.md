# Function: <code>sock_omalloc</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182de20)
Location: net/core/sock.c:1944
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff8182de20-ffffffff8182de7f: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81878200)
Location: net/core/sock.c:1964
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff81878200-ffffffff81878262: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818986e0)
Location: net/core/sock.c:1960
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff818986e0-ffffffff81898742: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e2ca0)
Location: net/core/sock.c:2101
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff818e2ca0-ffffffff818e2cfc: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81914e80)
Location: net/core/sock.c:2116
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff81914e80-ffffffff81914edc: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e7fa0)
Location: net/core/sock.c:2225
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff819e7fa0-ffffffff819e7fff: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e7a70)
Location: net/core/sock.c:2217
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff819e7a70-ffffffff819e7acf: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cda40)
Location: net/core/sock.c:2240
Inline: False
Direct callers:
  - net/core/skbuff.c:msg_zerocopy_alloc
```
**Symbols:**

```
ffffffff819cda40-ffffffff819cda9f: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7d250)
Location: net/core/sock.c:2364
Inline: False
Direct callers:
  - net/core/skbuff.c:msg_zerocopy_alloc
```
**Symbols:**

```
ffffffff81a7d250-ffffffff81a7d2af: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bf0870)
Location: net/core/sock.c:2531
Inline: False
Direct callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
**Symbols:**

```
ffffffff81bf0870-ffffffff81bf08dd: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9ce20)
Location: net/core/sock.c:2610
Inline: False
Direct callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
**Symbols:**

```
ffffffff81d9ce20-ffffffff81d9ce8d: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0b670)
Location: net/core/sock.c:2670
Inline: False
Direct callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
**Symbols:**

```
ffffffff81e0b670-ffffffff81e0b6db: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec8060)
Location: net/core/sock.c:2650
Inline: False
Direct callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
```
**Symbols:**

```
ffffffff81ec8060-ffffffff81ec80cf: sock_omalloc (STB_GLOBAL)
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
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010badc18)
Location: net/core/sock.c:2116
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffff800010badc18-ffff800010badcc4: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0ccb73c)
Location: net/core/sock.c:2116
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
c0ccb73c-c0ccb7cc: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c835d0)
Location: net/core/sock.c:2116
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
c000000000c835d0-c000000000c8369c: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073fd58)
Location: net/core/sock.c:2116
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffe00073fd58-ffffffe00073fdca: sock_omalloc (STB_GLOBAL)
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
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b4e80)
Location: net/core/sock.c:2116
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff818b4e80-ffffffff818b4edc: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186edd0)
Location: net/core/sock.c:2116
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff8186edd0-ffffffff8186ee2c: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81905e80)
Location: net/core/sock.c:2116
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff81905e80-ffffffff81905edc: sock_omalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *sock_omalloc(struct sock *sk, long unsigned int size, gfp_t priority);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81926eb0)
Location: net/core/sock.c:2116
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff81926eb0-ffffffff81926f0c: sock_omalloc (STB_GLOBAL)
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
