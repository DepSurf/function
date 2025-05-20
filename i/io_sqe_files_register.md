# Function: <code>io_sqe_files_register</code>

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
In fs/io_uring.c (ffffffff81331d41)
Location: fs/io_uring.c:2659
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
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
In fs/io_uring.c (ffffffff81345901)
Location: fs/io_uring.c:3171
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_sqe_files_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81380df0)
Location: fs/io_uring.c:6731
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff81380df0-ffffffff81381295: io_sqe_files_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_sqe_files_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138e280)
Location: fs/io_uring.c:7820
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff8138e280-ffffffff8138e6f1: io_sqe_files_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_sqe_files_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args, u64 *tags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81398740)
Location: fs/io_uring.c:7661
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_rsrc
```
**Symbols:**

```
ffffffff81398740-ffffffff81398b7e: io_sqe_files_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_sqe_files_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args, u64 *tags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813ec730)
Location: fs/io_uring.c:8292
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_rsrc
```
**Symbols:**

```
ffffffff813ec730-ffffffff813eca79: io_sqe_files_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int io_sqe_files_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args, u64 *tags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:9612
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_register_rsrc
```
**Symbols:**

```
ffffffff816d4760-ffffffff816d48f9: io_sqe_files_register (STB_LOCAL)
ffffffff81e914fe-ffffffff81e91689: io_sqe_files_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_sqe_files_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args, u64 *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a1cf0)
Location: io_uring/rsrc.c:952
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/rsrc.c:io_register_rsrc
```
**Symbols:**

```
ffffffff817a1cf0-ffffffff817a1fed: io_sqe_files_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_sqe_files_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args, u64 *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e2e50)
Location: io_uring/rsrc.c:846
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/rsrc.c:io_register_rsrc
```
**Symbols:**

```
ffffffff817e2e50-ffffffff817e3102: io_sqe_files_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_sqe_files_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args, u64 *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81826f30)
Location: io_uring/rsrc.c:700
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_register_rsrc
  - io_uring/register.c:__io_uring_register
```
**Symbols:**

```
ffffffff81826f30-ffffffff818271b1: io_sqe_files_register (STB_GLOBAL)
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
In fs/io_uring.c (ffff800010403ac0)
Location: fs/io_uring.c:3171
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
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
In fs/io_uring.c (c05d77d8)
Location: fs/io_uring.c:3171
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
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
In fs/io_uring.c (c000000000510930)
Location: fs/io_uring.c:3171
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
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
In fs/io_uring.c (ffffffe0002b11ee)
Location: fs/io_uring.c:3171
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
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
In fs/io_uring.c (ffffffff8133dee1)
Location: fs/io_uring.c:3171
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
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
In fs/io_uring.c (ffffffff8132eba1)
Location: fs/io_uring.c:3171
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
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
In fs/io_uring.c (ffffffff8133b9b1)
Location: fs/io_uring.c:3171
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
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
In fs/io_uring.c (ffffffff8134eb61)
Location: fs/io_uring.c:3171
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 *tags</code>
</li>
</ul>
</details>
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
