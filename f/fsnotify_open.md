# Function: <code>fsnotify_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8120b7eb)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff812121c6)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
```
In fs/fhandle.c (ffffffff812703b8)
Location: include/linux/fsnotify.h:230
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81231518)
Location: include/linux/fsnotify.h:209
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff81238c8b)
Location: include/linux/fsnotify.h:209
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
```
In fs/fhandle.c (ffffffff8129bbfd)
Location: include/linux/fsnotify.h:209
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81243ac4)
Location: include/linux/fsnotify.h:213
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff8124b937)
Location: include/linux/fsnotify.h:213
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
```
In fs/fhandle.c (ffffffff812b07b9)
Location: include/linux/fsnotify.h:213
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124f2ea)
Location: include/linux/fsnotify.h:213
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff81257a7f)
Location: include/linux/fsnotify.h:213
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
```
In fs/fhandle.c (ffffffff812bdc47)
Location: include/linux/fsnotify.h:213
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8127126a)
Location: include/linux/fsnotify.h:214
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff81279d52)
Location: include/linux/fsnotify.h:214
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:SyS_uselib
```
```
In fs/fhandle.c (ffffffff812e1337)
Location: include/linux/fsnotify.h:214
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81296e82)
Location: include/linux/fsnotify.h:214
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff812a0919)
Location: include/linux/fsnotify.h:214
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fhandle.c (ffffffff8130d57d)
Location: include/linux/fsnotify.h:214
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812abb26)
Location: include/linux/fsnotify.h:222
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff812b58d5)
Location: include/linux/fsnotify.h:222
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fhandle.c (ffffffff8132316c)
Location: include/linux/fsnotify.h:222
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c832d)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff812d26aa)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fhandle.c (ffffffff8134ab60)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d9d3d)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff812e41ba)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fhandle.c (ffffffff81362d48)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130fa60)
Location: include/linux/fsnotify.h:263
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
```
```
In fs/exec.c (ffffffff8131c68b)
Location: include/linux/fsnotify.h:263
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/io_uring.c (ffffffff81384076)
Location: include/linux/fsnotify.h:263
Inline: True
Inline callers:
  - fs/io_uring.c:io_openat2
```
```
In fs/fhandle.c (ffffffff813a89e0)
Location: include/linux/fsnotify.h:263
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131bd1a)
Location: include/linux/fsnotify.h:261
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
```
```
In fs/exec.c (ffffffff813281d7)
Location: include/linux/fsnotify.h:261
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/io_uring.c (ffffffff81392859)
Location: include/linux/fsnotify.h:261
Inline: True
Inline callers:
  - fs/io_uring.c:io_openat2
```
```
In fs/fhandle.c (ffffffff813b9d2a)
Location: include/linux/fsnotify.h:261
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81321e8a)
Location: include/linux/fsnotify.h:261
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
```
```
In fs/exec.c (ffffffff8132e0fb)
Location: include/linux/fsnotify.h:261
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/io_uring.c (ffffffff81396153)
Location: include/linux/fsnotify.h:261
Inline: True
Inline callers:
  - fs/io_uring.c:io_openat2
```
```
In fs/fhandle.c (ffffffff813c0e8a)
Location: include/linux/fsnotify.h:261
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136f36a)
Location: include/linux/fsnotify.h:306
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
```
```
In fs/exec.c (ffffffff8137b8ef)
Location: include/linux/fsnotify.h:306
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/io_uring.c (ffffffff813eb119)
Location: include/linux/fsnotify.h:306
Inline: True
Inline callers:
  - fs/io_uring.c:io_openat2
```
```
In fs/fhandle.c (ffffffff81410f45)
Location: include/linux/fsnotify.h:306
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813edd9e)
Location: include/linux/fsnotify.h:323
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
```
```
In fs/exec.c (ffffffff813fc18c)
Location: include/linux/fsnotify.h:323
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/fhandle.c (ffffffff81486925)
Location: include/linux/fsnotify.h:323
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In io_uring/io_uring.c (ffffffff816d42c9)
Location: include/linux/fsnotify.h:323
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_openat2
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8147651e)
Location: include/linux/fsnotify.h:323
Inline: True
Inline callers:
  - fs/open.c:do_sys_openat2
```
```
In fs/exec.c (ffffffff81485bfc)
Location: include/linux/fsnotify.h:323
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__do_sys_uselib
```
```
In fs/fhandle.c (ffffffff8151a285)
Location: include/linux/fsnotify.h:323
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
```
In io_uring/openclose.c (ffffffff817947b9)
Location: include/linux/fsnotify.h:323
Inline: True
Inline callers:
  - io_uring/openclose.c:io_openat2
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
In fs/open.c (ffffffff814a8744)
Location: include/linux/fsnotify.h:325
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
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
In fs/open.c (ffffffff814d9824)
Location: include/linux/fsnotify.h:363
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037f0cc)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffff80001038d074)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__arm64_sys_uselib
```
```
In fs/fhandle.c (ffff800010429594)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (c05699c0)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (c0573984)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
```
```
In fs/fhandle.c (c05f2334)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000474ff8)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (c0000000004833b0)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
```
```
In fs/fhandle.c (c000000000539ab4)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000254caa)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffe00025d16a)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__se_sys_uselib
```
```
In fs/fhandle.c (ffffffe0002c758a)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d231d)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff812dc79a)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fhandle.c (ffffffff8135b328)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c2f9d)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff812cd41a)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fhandle.c (ffffffff8134bfc8)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d012d)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff812da5aa)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fhandle.c (ffffffff81358df8)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812e0f3d)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/open.c:do_sys_open
```
```
In fs/exec.c (ffffffff812eb459)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
  - fs/exec.c:__ia32_sys_uselib
  - fs/exec.c:__x64_sys_uselib
```
```
In fs/fhandle.c (ffffffff8136c4f8)
Location: include/linux/fsnotify.h:262
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
</ul>

## Differences
