# Function: <code>io_ring_submit</code>

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
int io_ring_submit(struct io_ring_ctx *ctx, unsigned int to_submit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81330280)
Location: fs/io_uring.c:2429
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81330280-ffffffff81330401: io_ring_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_ring_submit(struct io_ring_ctx *ctx, unsigned int to_submit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81343a30)
Location: fs/io_uring.c:2863
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81343a30-ffffffff81343c26: io_ring_submit (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int io_ring_submit(struct io_ring_ctx *ctx, unsigned int to_submit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010405808)
Location: fs/io_uring.c:2863
Inline: False
Direct callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
```
**Symbols:**

```
ffff800010405808-ffff8000104059d8: io_ring_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_ring_submit(struct io_ring_ctx *ctx, unsigned int to_submit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d53c4)
Location: fs/io_uring.c:2863
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
```
**Symbols:**

```
c05d53c4-c05d5594: io_ring_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_ring_submit(struct io_ring_ctx *ctx, unsigned int to_submit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050e360)
Location: fs/io_uring.c:2863
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
```
**Symbols:**

```
c00000000050e360-c00000000050e618: io_ring_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int io_ring_submit(struct io_ring_ctx *ctx, unsigned int to_submit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002af848)
Location: fs/io_uring.c:2863
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
```
**Symbols:**

```
ffffffe0002af848-ffffffe0002af9aa: io_ring_submit (STB_LOCAL)
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
int io_ring_submit(struct io_ring_ctx *ctx, unsigned int to_submit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133c010)
Location: fs/io_uring.c:2863
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff8133c010-ffffffff8133c206: io_ring_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_ring_submit(struct io_ring_ctx *ctx, unsigned int to_submit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132cce0)
Location: fs/io_uring.c:2863
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff8132cce0-ffffffff8132ced6: io_ring_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_ring_submit(struct io_ring_ctx *ctx, unsigned int to_submit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81339ae0)
Location: fs/io_uring.c:2863
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff81339ae0-ffffffff81339cd6: io_ring_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_ring_submit(struct io_ring_ctx *ctx, unsigned int to_submit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134c710)
Location: fs/io_uring.c:2863
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_enter
  - fs/io_uring.c:__x64_sys_io_uring_enter
```
**Symbols:**

```
ffffffff8134c710-ffffffff8134c906: io_ring_submit (STB_LOCAL)
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
