# Function: <code>io_iopoll_check</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int io_iopoll_check(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132eac0)
Location: fs/io_uring.c:818
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff8132eac0-ffffffff8132eb94: io_iopoll_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_iopoll_check(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81341fd0)
Location: fs/io_uring.c:889
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81341fd0-ffffffff813420ab: io_iopoll_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff81384f20)
Location: fs/io_uring.c:1930
Inline: True
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81384f20-ffffffff81385031: io_iopoll_check.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_iopoll_check(struct io_ring_ctx *ctx, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81397600)
Location: fs/io_uring.c:2590
Inline: False
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81397600-ffffffff81397749: io_iopoll_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813a1969)
Location: fs/io_uring.c:2389
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813f036b)
Location: fs/io_uring.c:2586
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d6c4d)
Location: io_uring/io_uring.c:3105
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int io_iopoll_check(struct io_ring_ctx *ctx, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1535
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
**Symbols:**

```
ffffffff8178f8d0-ffffffff8178faa1: io_iopoll_check (STB_LOCAL)
ffffffff82077626-ffffffff82077641: io_iopoll_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int io_iopoll_check(struct io_ring_ctx *ctx, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1615
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
**Symbols:**

```
ffffffff817d1270-ffffffff817d1456: io_iopoll_check (STB_LOCAL)
ffffffff820f7671-ffffffff820f768c: io_iopoll_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int io_iopoll_check(struct io_ring_ctx *ctx, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1636
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81814520-ffffffff81814707: io_iopoll_check (STB_LOCAL)
ffffffff821d5027-ffffffff821d5042: io_iopoll_check.cold (STB_LOCAL)
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
In fs/io_uring.c (ffff800010405c40)
Location: fs/io_uring.c:889
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
In fs/io_uring.c (c05d740c)
Location: fs/io_uring.c:889
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
In fs/io_uring.c (c00000000050e944)
Location: fs/io_uring.c:889
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
In fs/io_uring.c (ffffffe0002b0de2)
Location: fs/io_uring.c:889
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
int io_iopoll_check(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133a5b0)
Location: fs/io_uring.c:889
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff8133a5b0-ffffffff8133a68b: io_iopoll_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_iopoll_check(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132b2c0)
Location: fs/io_uring.c:889
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff8132b2c0-ffffffff8132b39b: io_iopoll_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_iopoll_check(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81338080)
Location: fs/io_uring.c:889
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81338080-ffffffff8133815b: io_iopoll_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_iopoll_check(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134cf60)
Location: fs/io_uring.c:889
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff8134cf60-ffffffff8134d03b: io_iopoll_check (STB_LOCAL)
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
