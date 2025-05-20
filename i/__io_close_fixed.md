# Function: <code>__io_close_fixed</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cb0e0)
Location: io_uring/io_uring.c:9757
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_files_update
  - io_uring/io_uring.c:io_close
```
**Symbols:**

```
ffffffff816cb0e0-ffffffff816cb25d: __io_close_fixed.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __io_close_fixed(struct io_ring_ctx *ctx, unsigned int issue_flags, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/openclose.c (ffffffff81794c5a)
Location: io_uring/openclose.c:176
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
Direct callers:
  - io_uring/rsrc.c:io_files_update
```
**Symbols:**

```
ffffffff81794a30-ffffffff81794aa3: __io_close_fixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __io_close_fixed(struct io_ring_ctx *ctx, unsigned int issue_flags, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/openclose.c (ffffffff817d58be)
Location: io_uring/openclose.c:183
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
Direct callers:
  - io_uring/rsrc.c:io_files_update
```
**Symbols:**

```
ffffffff817d5690-ffffffff817d5703: __io_close_fixed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __io_close_fixed(struct io_ring_ctx *ctx, unsigned int issue_flags, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/openclose.c (ffffffff81819715)
Location: io_uring/openclose.c:188
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
Direct callers:
  - io_uring/rsrc.c:io_files_update
```
**Symbols:**

```
ffffffff818194e0-ffffffff81819553: __io_close_fixed (STB_GLOBAL)
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
