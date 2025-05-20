# Function: <code>io_uring_del_tctx_node</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_uring_del_tctx_node(long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dda40)
Location: fs/io_uring.c:9752
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:io_tctx_exit_cb
```
**Symbols:**

```
ffffffff813dda40-ffffffff813ddaf5: io_uring_del_tctx_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_uring_del_tctx_node(long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8e516)
Location: io_uring/io_uring.c:11142
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_tctx_exit_cb
```
**Symbols:**

```
ffffffff81e8e516-ffffffff81e8e5ca: io_uring_del_tctx_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_uring_del_tctx_node(long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/tctx.c (ffffffff8179be90)
Location: io_uring/tctx.c:155
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_tctx_exit_cb
  - io_uring/tctx.c:io_uring_clean_tctx
```
**Symbols:**

```
ffffffff8179be90-ffffffff8179bf4f: io_uring_del_tctx_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_uring_del_tctx_node(long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/tctx.c (ffffffff817dcfc0)
Location: io_uring/tctx.c:155
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_tctx_exit_cb
  - io_uring/tctx.c:io_uring_clean_tctx
```
**Symbols:**

```
ffffffff817dcfc0-ffffffff817dd07f: io_uring_del_tctx_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_uring_del_tctx_node(long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/tctx.c (ffffffff81821310)
Location: io_uring/tctx.c:155
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_tctx_exit_cb
  - io_uring/tctx.c:io_uring_clean_tctx
```
**Symbols:**

```
ffffffff81821310-ffffffff818213cf: io_uring_del_tctx_node (STB_GLOBAL)
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
