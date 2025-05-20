# Function: <code>io_sync_cancel</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_sync_cancel(struct io_ring_ctx *ctx, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/cancel.c (ffffffff8179e7f0)
Location: io_uring/cancel.c:233
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff8179e7f0-ffffffff8179eb7c: io_sync_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_sync_cancel(struct io_ring_ctx *ctx, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/cancel.c (ffffffff817df9e0)
Location: io_uring/cancel.c:230
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff817df9e0-ffffffff817dfd6c: io_sync_cancel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_sync_cancel(struct io_ring_ctx *ctx, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/cancel.c (ffffffff81823e70)
Location: io_uring/cancel.c:267
Inline: False
Direct callers:
  - io_uring/register.c:__io_uring_register
```
**Symbols:**

```
ffffffff81823e70-ffffffff81824243: io_sync_cancel (STB_GLOBAL)
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
