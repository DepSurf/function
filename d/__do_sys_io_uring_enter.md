# Function: <code>__do_sys_io_uring_enter</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81330451)
Location: fs/io_uring.c:3172
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
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
In fs/io_uring.c (ffffffff81343c6d)
Location: fs/io_uring.c:3725
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const sigset_t *sig, size_t sigsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81388f30)
Location: fs/io_uring.c:7892
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81388f30-ffffffff81389275: __do_sys_io_uring_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const void *argp, size_t argsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139a2b0)
Location: fs/io_uring.c:9346
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff8139a2b0-ffffffff8139a6bb: __do_sys_io_uring_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const void *argp, size_t argsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813a1570)
Location: fs/io_uring.c:9318
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff813a1570-ffffffff813a1af9: __do_sys_io_uring_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const void *argp, size_t argsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813eff80)
Location: fs/io_uring.c:9994
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff813eff80-ffffffff813f0506: __do_sys_io_uring_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const void *argp, size_t argsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d68d0)
Location: io_uring/io_uring.c:11538
Inline: False
Direct callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_enter
  - io_uring/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff816d68d0-ffffffff816d6f4f: __do_sys_io_uring_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const void *argp, size_t argsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:3282
Inline: False
Direct callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_enter
  - io_uring/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81791f80-ffffffff81792433: __do_sys_io_uring_enter (STB_LOCAL)
ffffffff820776d8-ffffffff820776ed: __do_sys_io_uring_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const void *argp, size_t argsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:3568
Inline: False
Direct callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_enter
  - io_uring/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff817d2c20-ffffffff817d30c0: __do_sys_io_uring_enter (STB_LOCAL)
ffffffff820f771d-ffffffff820f7732: __do_sys_io_uring_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __do_sys_io_uring_enter(unsigned int fd, u32 to_submit, u32 min_complete, u32 flags, const void *argp, size_t argsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:3591
Inline: False
Direct callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_enter
  - io_uring/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81815f20-ffffffff818163b7: __do_sys_io_uring_enter (STB_LOCAL)
ffffffff821d50d3-ffffffff821d50e8: __do_sys_io_uring_enter.cold (STB_LOCAL)
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
In fs/io_uring.c (ffff800010405a18)
Location: fs/io_uring.c:3725
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
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
In fs/io_uring.c (c05d71c4)
Location: fs/io_uring.c:3725
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
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
In fs/io_uring.c (c00000000050e658)
Location: fs/io_uring.c:3725
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
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
In fs/io_uring.c (ffffffe0002b0d08)
Location: fs/io_uring.c:3725
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
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
In fs/io_uring.c (ffffffff8133c24d)
Location: fs/io_uring.c:3725
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
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
In fs/io_uring.c (ffffffff8132cf1d)
Location: fs/io_uring.c:3725
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
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
In fs/io_uring.c (ffffffff81339d1d)
Location: fs/io_uring.c:3725
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
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
In fs/io_uring.c (ffffffff8134d6dd)
Location: fs/io_uring.c:3725
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void *argp</code>
</li>
<li>
<b>Param added. </b>
<code>size_t argsz</code>
</li>
<li>
<b>Param removed. </b>
<code>const sigset_t *sig</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t sigsz</code>
</li>
</ul>
</details>
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
