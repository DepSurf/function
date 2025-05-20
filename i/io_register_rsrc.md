# Function: <code>io_register_rsrc</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_register_rsrc(struct io_ring_ctx *ctx, void *arg, unsigned int size, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81398b80)
Location: fs/io_uring.c:9974
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff81398b80-ffffffff81398c3c: io_register_rsrc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_register_rsrc(struct io_ring_ctx *ctx, void *arg, unsigned int size, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813eca80)
Location: fs/io_uring.c:10647
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff813eca80-ffffffff813ecb3c: io_register_rsrc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_register_rsrc(struct io_ring_ctx *ctx, void *arg, unsigned int size, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e91689)
Location: io_uring/io_uring.c:12339
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff81e91689-ffffffff81e9175b: io_register_rsrc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_register_rsrc(struct io_ring_ctx *ctx, void *arg, unsigned int size, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a2df0)
Location: io_uring/rsrc.c:639
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff817a2df0-ffffffff817a2ed6: io_register_rsrc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_register_rsrc(struct io_ring_ctx *ctx, void *arg, unsigned int size, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e3d90)
Location: io_uring/rsrc.c:527
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff817e3d90-ffffffff817e3e7a: io_register_rsrc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_register_rsrc(struct io_ring_ctx *ctx, void *arg, unsigned int size, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81827e40)
Location: io_uring/rsrc.c:522
Inline: False
Direct callers:
  - io_uring/register.c:__io_uring_register
  - io_uring/register.c:__io_uring_register
```
**Symbols:**

```
ffffffff81827e40-ffffffff81827f2a: io_register_rsrc (STB_GLOBAL)
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
