# Function: <code>__io_uring_show_fdinfo</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __io_uring_show_fdinfo(struct io_ring_ctx *ctx, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137f980)
Location: fs/io_uring.c:7999
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_show_fdinfo
```
**Symbols:**

```
ffffffff8137f980-ffffffff8137fbf8: __io_uring_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __io_uring_show_fdinfo(struct io_ring_ctx *ctx, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138dd30)
Location: fs/io_uring.c:9475
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_show_fdinfo
```
**Symbols:**

```
ffffffff8138dd30-ffffffff8138e068: __io_uring_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __io_uring_show_fdinfo(struct io_ring_ctx *ctx, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81397cc0)
Location: fs/io_uring.c:9446
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_show_fdinfo
```
**Symbols:**

```
ffffffff81397cc0-ffffffff8139801f: __io_uring_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __io_uring_show_fdinfo(struct io_ring_ctx *ctx, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:10122
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_show_fdinfo
```
**Symbols:**

```
ffffffff813e3820-ffffffff813e3b70: __io_uring_show_fdinfo (STB_LOCAL)
ffffffff81cc5a6f-ffffffff81cc5a8d: __io_uring_show_fdinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __io_uring_show_fdinfo(struct io_ring_ctx *ctx, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8fe46)
Location: io_uring/io_uring.c:11706
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_show_fdinfo
```
**Symbols:**

```
ffffffff81e8fe46-ffffffff81e90355: __io_uring_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __io_uring_show_fdinfo(struct io_ring_ctx *ctx, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/fdinfo.c (0)
Location: io_uring/fdinfo.c:51
Inline: False
Direct callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
**Symbols:**

```
ffffffff8179b1b0-ffffffff8179b8fe: __io_uring_show_fdinfo (STB_LOCAL)
ffffffff82077809-ffffffff82077827: __io_uring_show_fdinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __io_uring_show_fdinfo(struct io_ring_ctx *ctx, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/fdinfo.c (0)
Location: io_uring/fdinfo.c:49
Inline: False
Direct callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
**Symbols:**

```
ffffffff817dc2c0-ffffffff817dca26: __io_uring_show_fdinfo (STB_LOCAL)
ffffffff820f788b-ffffffff820f78a7: __io_uring_show_fdinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
