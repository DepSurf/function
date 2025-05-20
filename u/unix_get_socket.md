# Function: <code>unix_get_socket</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/garbage.c (ffffffff817c1fe6)
Location: net/unix/garbage.c:98
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/garbage.c:unix_inflight
  - net/unix/garbage.c:unix_notinflight
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff817c2280-ffffffff817c22c8: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/garbage.c (ffffffff8182eff6)
Location: net/unix/garbage.c:98
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/garbage.c:unix_notinflight
  - net/unix/garbage.c:unix_inflight
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff8182f2a0-ffffffff8182f2e8: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/garbage.c (ffffffff81860a76)
Location: net/unix/garbage.c:98
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/garbage.c:unix_notinflight
  - net/unix/garbage.c:unix_inflight
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff81860d20-ffffffff81860d68: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/garbage.c (ffffffff818851ca)
Location: net/unix/garbage.c:98
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/garbage.c:unix_notinflight
  - net/unix/garbage.c:unix_inflight
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff81885480-ffffffff818854c4: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/garbage.c (ffffffff81906376)
Location: net/unix/garbage.c:98
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/garbage.c:unix_notinflight
  - net/unix/garbage.c:unix_inflight
```
**Symbols:**

```
ffffffff81906630-ffffffff81906674: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/garbage.c (ffffffff8195d40a)
Location: net/unix/garbage.c:98
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/garbage.c:unix_notinflight
  - net/unix/garbage.c:unix_inflight
```
**Symbols:**

```
ffffffff8195d620-ffffffff8195d668: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/garbage.c (ffffffff81991f4a)
Location: net/unix/garbage.c:98
Inline: True
Inline callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/garbage.c:unix_notinflight
  - net/unix/garbage.c:unix_inflight
```
**Symbols:**

```
ffffffff81992160-ffffffff819921a8: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff819fde40)
Location: net/unix/scm.c:23
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffff819fde40-ffffffff819fde8a: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81a34a30)
Location: net/unix/scm.c:23
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffff81a34a30-ffffffff81a34a7a: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81b29870)
Location: net/unix/scm.c:23
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffff81b29870-ffffffff81b298ba: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81b381a0)
Location: net/unix/scm.c:24
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffff81b381a0-ffffffff81b381ea: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81b25e40)
Location: net/unix/scm.c:24
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffff81b25e40-ffffffff81b25e8a: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81beba90)
Location: net/unix/scm.c:24
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffff81beba90-ffffffff81bebada: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81d83f50)
Location: net/unix/scm.c:24
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_rsrc_file_put
  - io_uring/io_uring.c:io_file_get_flags
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffff81d83f50-ffffffff81d83fba: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81f517c0)
Location: net/unix/scm.c:24
Inline: False
Direct callers:
  - io_uring/filetable.c:io_install_fixed_file
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:io_rsrc_file_put
  - io_uring/rsrc.c:__io_scm_file_account
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - io_uring/rsrc.c:__io_sqe_files_update
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffff81f517c0-ffffffff81f5182a: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81fb1140)
Location: net/unix/scm.c:24
Inline: False
Direct callers:
  - io_uring/filetable.c:io_install_fixed_file
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:__io_scm_file_account
  - io_uring/rsrc.c:__io_sqe_files_unregister
  - io_uring/rsrc.c:__io_sqe_files_update
  - io_uring/rsrc.c:io_rsrc_node_ref_zero
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffff81fb1140-ffffffff81fb11a7: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff8207e850)
Location: net/unix/scm.c:24
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffff8207e850-ffffffff8207e8b3: unix_get_socket (STB_GLOBAL)
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
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffff800010cf51a8)
Location: net/unix/scm.c:23
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffff800010cf51a8-ffff800010cf5220: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (c0dfbcf4)
Location: net/unix/scm.c:23
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
c0dfbcf4-c0dfbd60: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (c000000000e1b280)
Location: net/unix/scm.c:23
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
c000000000e1b280-c000000000e1b314: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffe000840d30)
Location: net/unix/scm.c:23
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffe000840d30-ffffffe000840d94: unix_get_socket (STB_GLOBAL)
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
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff819d40c0)
Location: net/unix/scm.c:23
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffff819d40c0-ffffffff819d410a: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81990e80)
Location: net/unix/scm.c:23
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffff81990e80-ffffffff81990eca: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81a3eb40)
Location: net/unix/scm.c:23
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffff81a3eb40-ffffffff81a3eb8a: unix_get_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *unix_get_socket(struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81a4a600)
Location: net/unix/scm.c:23
Inline: False
Direct callers:
  - net/unix/garbage.c:scan_inflight
  - net/unix/scm.c:unix_notinflight
  - net/unix/scm.c:unix_inflight
```
**Symbols:**

```
ffffffff81a4a600-ffffffff81a4a64a: unix_get_socket (STB_GLOBAL)
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
