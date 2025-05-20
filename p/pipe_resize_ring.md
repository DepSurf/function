# Function: <code>pipe_resize_ring</code>

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
int pipe_resize_ring(struct pipe_inode_info *pipe, unsigned int nr_slots);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81320840)
Location: fs/pipe.c:1231
Inline: False
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff81320840-ffffffff81320990: pipe_resize_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pipe_resize_ring(struct pipe_inode_info *pipe, unsigned int nr_slots);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8132bdc0)
Location: fs/pipe.c:1231
Inline: False
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff8132bdc0-ffffffff8132bf10: pipe_resize_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pipe_resize_ring(struct pipe_inode_info *pipe, unsigned int nr_slots);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81331e00)
Location: fs/pipe.c:1245
Inline: False
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff81331e00-ffffffff81331f50: pipe_resize_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pipe_resize_ring(struct pipe_inode_info *pipe, unsigned int nr_slots);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8137f590)
Location: fs/pipe.c:1248
Inline: False
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff8137f590-ffffffff8137f6e0: pipe_resize_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pipe_resize_ring(struct pipe_inode_info *pipe, unsigned int nr_slots);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813ff6a0)
Location: fs/pipe.c:1253
Inline: False
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff813ff6a0-ffffffff813ff82a: pipe_resize_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pipe_resize_ring(struct pipe_inode_info *pipe, unsigned int nr_slots);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81489480)
Location: fs/pipe.c:1253
Inline: False
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff81489480-ffffffff8148960a: pipe_resize_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pipe_resize_ring(struct pipe_inode_info *pipe, unsigned int nr_slots);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814be3b0)
Location: fs/pipe.c:1258
Inline: False
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff814be3b0-ffffffff814be53a: pipe_resize_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pipe_resize_ring(struct pipe_inode_info *pipe, unsigned int nr_slots);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814f0830)
Location: fs/pipe.c:1274
Inline: False
Direct callers:
  - kernel/watch_queue.c:watch_queue_set_size
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff814f0830-ffffffff814f09d5: pipe_resize_ring (STB_GLOBAL)
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
