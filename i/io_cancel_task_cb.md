# Function: <code>io_cancel_task_cb</code>

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
bool io_cancel_task_cb(struct io_wq_work *work, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813798c0)
Location: fs/io_uring.c:7799
Inline: False
```
**Symbols:**

```
ffffffff813798c0-ffffffff813798d2: io_cancel_task_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool io_cancel_task_cb(struct io_wq_work *work, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138a2a0)
Location: fs/io_uring.c:8869
Inline: False
```
**Symbols:**

```
ffffffff8138a2a0-ffffffff8138a329: io_cancel_task_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool io_cancel_task_cb(struct io_wq_work *work, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81392bd0)
Location: fs/io_uring.c:8895
Inline: False
```
**Symbols:**

```
ffffffff81392bd0-ffffffff81392cdd: io_cancel_task_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool io_cancel_task_cb(struct io_wq_work *work, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:9593
Inline: False
```
**Symbols:**

```
ffffffff813e7140-ffffffff813e717e: io_cancel_task_cb (STB_LOCAL)
ffffffff81cc5b41-ffffffff81cc5b5c: io_cancel_task_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool io_cancel_task_cb(struct io_wq_work *work, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:10978
Inline: False
```
**Symbols:**

```
ffffffff816c90a0-ffffffff816c90e8: io_cancel_task_cb (STB_LOCAL)
ffffffff81e8f3a7-ffffffff81e8f3c2: io_cancel_task_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool io_cancel_task_cb(struct io_wq_work *work, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:2972
Inline: False
```
**Symbols:**

```
ffffffff8178d1d0-ffffffff8178d218: io_cancel_task_cb (STB_LOCAL)
ffffffff820775b3-ffffffff820775ce: io_cancel_task_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool io_cancel_task_cb(struct io_wq_work *work, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:3187
Inline: False
```
**Symbols:**

```
ffffffff817ce310-ffffffff817ce358: io_cancel_task_cb (STB_LOCAL)
ffffffff820f75f7-ffffffff820f7612: io_cancel_task_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool io_cancel_task_cb(struct io_wq_work *work, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:3174
Inline: False
```
**Symbols:**

```
ffffffff818115c0-ffffffff81811608: io_cancel_task_cb (STB_LOCAL)
ffffffff821d4fad-ffffffff821d4fc8: io_cancel_task_cb.cold (STB_LOCAL)
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
