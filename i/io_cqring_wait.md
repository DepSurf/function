# Function: <code>io_cqring_wait</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int io_cqring_wait(struct io_ring_ctx *ctx, int min_events, const sigset_t *sig, size_t sigsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:2477
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff8132d3d0-ffffffff8132d547: io_cqring_wait (STB_LOCAL)
ffffffff81332346-ffffffff8133235f: io_cqring_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_cqring_wait(struct io_ring_ctx *ctx, int min_events, const sigset_t *sig, size_t sigsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813403a0)
Location: fs/io_uring.c:2958
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff813403a0-ffffffff81340558: io_cqring_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_cqring_wait(struct io_ring_ctx *ctx, int min_events, const sigset_t *sig, size_t sigsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81386b10)
Location: fs/io_uring.c:6299
Inline: False
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81386b10-ffffffff81386dfc: io_cqring_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_cqring_wait(struct io_ring_ctx *ctx, int min_events, const sigset_t *sig, size_t sigsz, struct __kernel_timespec *uts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391f40)
Location: fs/io_uring.c:7254
Inline: False
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81391f40-ffffffff8139230c: io_cqring_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_cqring_wait(struct io_ring_ctx *ctx, int min_events, const sigset_t *sig, size_t sigsz, struct __kernel_timespec *uts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81395560)
Location: fs/io_uring.c:7035
Inline: False
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81395560-ffffffff81395942: io_cqring_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_cqring_wait(struct io_ring_ctx *ctx, int min_events, const sigset_t *sig, size_t sigsz, struct __kernel_timespec *uts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e5610)
Location: fs/io_uring.c:7618
Inline: False
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
```
**Symbols:**

```
ffffffff813e5610-ffffffff813e5a01: io_cqring_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_cqring_wait(struct io_ring_ctx *ctx, int min_events, const sigset_t *sig, size_t sigsz, struct __kernel_timespec *uts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cf650)
Location: io_uring/io_uring.c:8927
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
**Symbols:**

```
ffffffff816cf650-ffffffff816cfb07: io_cqring_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_cqring_wait(struct io_ring_ctx *ctx, int min_events, const sigset_t *sig, size_t sigsz, struct __kernel_timespec *uts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81791a00)
Location: io_uring/io_uring.c:2511
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81791a00-ffffffff81791f69: io_cqring_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_cqring_wait(struct io_ring_ctx *ctx, int min_events, const sigset_t *sig, size_t sigsz, struct __kernel_timespec *uts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d0c30)
Location: io_uring/io_uring.c:2549
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
**Symbols:**

```
ffffffff817d0c30-ffffffff817d1253: io_cqring_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_cqring_wait(struct io_ring_ctx *ctx, int min_events, const sigset_t *sig, size_t sigsz, struct __kernel_timespec *uts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81813790)
Location: io_uring/io_uring.c:2580
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81813790-ffffffff81813d52: io_cqring_wait (STB_LOCAL)
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
In fs/io_uring.c (ffff800010405ae0)
Location: fs/io_uring.c:2958
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
In fs/io_uring.c (c05d7298)
Location: fs/io_uring.c:2958
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
In fs/io_uring.c (c00000000050e7ac)
Location: fs/io_uring.c:2958
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
In fs/io_uring.c (ffffffe0002b0ec0)
Location: fs/io_uring.c:2958
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
<summary>In <code>aws</code>: ✅</summary>

```c
int io_cqring_wait(struct io_ring_ctx *ctx, int min_events, const sigset_t *sig, size_t sigsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81338980)
Location: fs/io_uring.c:2958
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81338980-ffffffff81338b38: io_cqring_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_cqring_wait(struct io_ring_ctx *ctx, int min_events, const sigset_t *sig, size_t sigsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813296b0)
Location: fs/io_uring.c:2958
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff813296b0-ffffffff81329868: io_cqring_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_cqring_wait(struct io_ring_ctx *ctx, int min_events, const sigset_t *sig, size_t sigsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81336450)
Location: fs/io_uring.c:2958
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81336450-ffffffff81336608: io_cqring_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_cqring_wait(struct io_ring_ctx *ctx, int min_events, const sigset_t *sig, size_t sigsz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81349520)
Location: fs/io_uring.c:2958
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81349520-ffffffff813496d8: io_cqring_wait (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct __kernel_timespec *uts</code>
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
<b>Arch</b>
<ul>
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
