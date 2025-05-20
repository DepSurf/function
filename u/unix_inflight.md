# Function: <code>unix_inflight</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/garbage.c (ffffffff817c22d0)
Location: net/unix/garbage.c:119
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff817c22d0-ffffffff817c23a6: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/garbage.c (ffffffff8182f2f0)
Location: net/unix/garbage.c:119
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff8182f2f0-ffffffff8182f3ca: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/garbage.c (ffffffff81860d70)
Location: net/unix/garbage.c:119
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff81860d70-ffffffff81860e4a: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/garbage.c (ffffffff818854d0)
Location: net/unix/garbage.c:119
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff818854d0-ffffffff8188559c: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/garbage.c (ffffffff81906680)
Location: net/unix/garbage.c:119
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff81906680-ffffffff8190674c: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/garbage.c (ffffffff8195d670)
Location: net/unix/garbage.c:119
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff8195d670-ffffffff8195d739: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/garbage.c (ffffffff819921b0)
Location: net/unix/garbage.c:119
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_scm_to_skb
```
**Symbols:**

```
ffffffff819921b0-ffffffff81992279: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff819fde90)
Location: net/unix/scm.c:47
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffff819fde90-ffffffff819fdf36: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81a34a80)
Location: net/unix/scm.c:47
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffff81a34a80-ffffffff81a34b26: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81b298c0)
Location: net/unix/scm.c:47
Inline: False
Direct callers:
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffff81b298c0-ffffffff81b29966: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81b381f0)
Location: net/unix/scm.c:48
Inline: False
Direct callers:
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffff81b381f0-ffffffff81b38296: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81b25e90)
Location: net/unix/scm.c:48
Inline: False
Direct callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:__io_sqe_files_scm
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffff81b25e90-ffffffff81b25f36: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81bebae0)
Location: net/unix/scm.c:48
Inline: False
Direct callers:
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffff81bebae0-ffffffff81bebb96: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81d83fc0)
Location: net/unix/scm.c:48
Inline: False
Direct callers:
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffff81d83fc0-ffffffff81d84080: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81f51840)
Location: net/unix/scm.c:48
Inline: False
Direct callers:
  - io_uring/rsrc.c:__io_scm_file_account
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffff81f51840-ffffffff81f51900: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81fb11c0)
Location: net/unix/scm.c:49
Inline: False
Direct callers:
  - io_uring/rsrc.c:__io_scm_file_account
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffff81fb11c0-ffffffff81fb128e: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff8207e8d0)
Location: net/unix/scm.c:47
Inline: False
Direct callers:
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffff8207e8d0-ffffffff8207e9aa: unix_inflight (STB_GLOBAL)
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
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffff800010cf5220)
Location: net/unix/scm.c:47
Inline: False
Direct callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffff800010cf5220-ffff800010cf5354: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (c0dfbd60)
Location: net/unix/scm.c:47
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
c0dfbd60-c0dfbe48: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (c000000000e1b320)
Location: net/unix/scm.c:47
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
c000000000e1b320-c000000000e1b490: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffe000840d94)
Location: net/unix/scm.c:47
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffe000840d94-ffffffe000840e7e: unix_inflight (STB_GLOBAL)
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
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff819d4110)
Location: net/unix/scm.c:47
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffff819d4110-ffffffff819d41b6: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81990ed0)
Location: net/unix/scm.c:47
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffff81990ed0-ffffffff81990f76: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81a3eb90)
Location: net/unix/scm.c:47
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffff81a3eb90-ffffffff81a3ec36: unix_inflight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unix_inflight(struct user_struct *user, struct file *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/scm.c (ffffffff81a4a650)
Location: net/unix/scm.c:47
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - net/unix/scm.c:unix_attach_fds
```
**Symbols:**

```
ffffffff81a4a650-ffffffff81a4a6f4: unix_inflight (STB_GLOBAL)
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
