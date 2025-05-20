# Function: <code>io_register_files_update</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139e95f)
Location: fs/io_uring.c:9947
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
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
In fs/io_uring.c (ffffffff813ee8fe)
Location: fs/io_uring.c:10620
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
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
In io_uring/io_uring.c (ffffffff816d8b04)
Location: io_uring/io_uring.c:12310
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_register_files_update(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a19d0)
Location: io_uring/rsrc.c:610
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff817a19d0-ffffffff817a1a94: io_register_files_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_register_files_update(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e2b70)
Location: io_uring/rsrc.c:498
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff817e2b70-ffffffff817e2c24: io_register_files_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_register_files_update(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81826ad0)
Location: io_uring/rsrc.c:493
Inline: False
Direct callers:
  - io_uring/register.c:__io_uring_register
```
**Symbols:**

```
ffffffff81826ad0-ffffffff81826b84: io_register_files_update (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
