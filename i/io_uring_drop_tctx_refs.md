# Function: <code>io_uring_drop_tctx_refs</code>

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
void io_uring_drop_tctx_refs(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81cc591e)
Location: fs/io_uring.c:1763
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:tctx_task_work
```
**Symbols:**

```
ffffffff81cc591e-ffffffff81cc5989: io_uring_drop_tctx_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_uring_drop_tctx_refs(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8f828)
Location: io_uring/io_uring.c:2193
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:tctx_task_work
```
**Symbols:**

```
ffffffff81e8f828-ffffffff81e8f889: io_uring_drop_tctx_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_uring_drop_tctx_refs(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178a930)
Location: io_uring/io_uring.c:715
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:tctx_task_work
```
**Symbols:**

```
ffffffff8178a930-ffffffff8178a9be: io_uring_drop_tctx_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_uring_drop_tctx_refs(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cb3d0)
Location: io_uring/io_uring.c:765
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:tctx_task_work
```
**Symbols:**

```
ffffffff817cb3d0-ffffffff817cb45e: io_uring_drop_tctx_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_uring_drop_tctx_refs(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180f8c0)
Location: io_uring/io_uring.c:773
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:tctx_task_work
```
**Symbols:**

```
ffffffff8180f8c0-ffffffff8180f94e: io_uring_drop_tctx_refs (STB_LOCAL)
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
