# Function: <code>tctx_task_work</code>

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
void tctx_task_work(struct callback_head *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81398fd0)
Location: fs/io_uring.c:1910
Inline: False
```
**Symbols:**

```
ffffffff81398fd0-ffffffff8139919b: tctx_task_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tctx_task_work(struct callback_head *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:2173
Inline: False
```
**Symbols:**

```
ffffffff813e8210-ffffffff813e837e: tctx_task_work (STB_LOCAL)
ffffffff81cc5b8f-ffffffff81cc5bb6: tctx_task_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tctx_task_work(struct callback_head *cb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:2725
Inline: False
```
**Symbols:**

```
ffffffff816d5f30-ffffffff816d60dc: tctx_task_work (STB_LOCAL)
ffffffff81e91c13-ffffffff81e91c3a: tctx_task_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tctx_task_work(struct callback_head *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178fcf0)
Location: io_uring/io_uring.c:1191
Inline: False
```
**Symbols:**

```
ffffffff8178fcf0-ffffffff8178fe6f: tctx_task_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tctx_task_work(struct callback_head *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1267
Inline: False
```
**Symbols:**

```
ffffffff820f76b5-ffffffff820f76ca: tctx_task_work.cold (STB_LOCAL)
ffffffff817d1650-ffffffff817d1940: tctx_task_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tctx_task_work(struct callback_head *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1271
Inline: False
```
**Symbols:**

```
ffffffff821d506b-ffffffff821d5080: tctx_task_work.cold (STB_LOCAL)
ffffffff81814970-ffffffff81814c60: tctx_task_work (STB_GLOBAL)
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
