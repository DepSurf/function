# Function: <code>io_ring_ctx_free</code>

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
In fs/io_uring.c (ffffffff8132edf3)
Location: fs/io_uring.c:3063
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (ffffffff813448cc)
Location: fs/io_uring.c:3616
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void io_ring_ctx_free(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81385040)
Location: fs/io_uring.c:7456
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff81385040-ffffffff8138529e: io_ring_ctx_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_ring_ctx_free(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138fa00)
Location: fs/io_uring.c:8687
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff8138fa00-ffffffff8138fc06: io_ring_ctx_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_ring_ctx_free(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139ab70)
Location: fs/io_uring.c:8624
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff8139ab70-ffffffff8139afd6: io_ring_ctx_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_ring_ctx_free(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e50f0)
Location: fs/io_uring.c:9327
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff813e50f0-ffffffff813e5605: io_ring_ctx_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_ring_ctx_free(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e91067)
Location: io_uring/io_uring.c:10704
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff81e91067-ffffffff81e913c0: io_ring_ctx_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_ring_ctx_free(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178b8c0)
Location: io_uring/io_uring.c:2708
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff8178b8c0-ffffffff8178bc0f: io_ring_ctx_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_ring_ctx_free(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cca60)
Location: io_uring/io_uring.c:2865
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff817cca60-ffffffff817ccd62: io_ring_ctx_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_ring_ctx_free(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff818111c0)
Location: io_uring/io_uring.c:2876
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
```
**Symbols:**

```
ffffffff818111c0-ffffffff818114a1: io_ring_ctx_free (STB_LOCAL)
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
In fs/io_uring.c (ffff800010402c90)
Location: fs/io_uring.c:3616
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (c05d6174)
Location: fs/io_uring.c:3616
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (c00000000050f55c)
Location: fs/io_uring.c:3616
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (ffffffe0002b04bc)
Location: fs/io_uring.c:3616
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (ffffffff8133ceac)
Location: fs/io_uring.c:3616
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (ffffffff8132db70)
Location: fs/io_uring.c:3616
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (ffffffff8133a97c)
Location: fs/io_uring.c:3616
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (ffffffff8134db2d)
Location: fs/io_uring.c:3616
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
