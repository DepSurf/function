# Function: <code>watch_queue_pipe_buf_release</code>

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
void watch_queue_pipe_buf_release(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8124c570)
Location: kernel/watch_queue.c:37
Inline: False
```
**Symbols:**

```
ffffffff8124c570-ffffffff8124c59f: watch_queue_pipe_buf_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void watch_queue_pipe_buf_release(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff812569d0)
Location: kernel/watch_queue.c:37
Inline: False
```
**Symbols:**

```
ffffffff812569d0-ffffffff812569ff: watch_queue_pipe_buf_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void watch_queue_pipe_buf_release(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8125ae70)
Location: kernel/watch_queue.c:37
Inline: False
```
**Symbols:**

```
ffffffff8125ae70-ffffffff8125ae9f: watch_queue_pipe_buf_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void watch_queue_pipe_buf_release(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81296c60)
Location: kernel/watch_queue.c:37
Inline: False
```
**Symbols:**

```
ffffffff81296c60-ffffffff81296c94: watch_queue_pipe_buf_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void watch_queue_pipe_buf_release(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff812ecd30)
Location: kernel/watch_queue.c:58
Inline: False
```
**Symbols:**

```
ffffffff812ecd30-ffffffff812ecd72: watch_queue_pipe_buf_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void watch_queue_pipe_buf_release(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81357080)
Location: kernel/watch_queue.c:58
Inline: False
```
**Symbols:**

```
ffffffff81357080-ffffffff813570c2: watch_queue_pipe_buf_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void watch_queue_pipe_buf_release(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81388900)
Location: kernel/watch_queue.c:57
Inline: False
```
**Symbols:**

```
ffffffff81388900-ffffffff81388942: watch_queue_pipe_buf_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void watch_queue_pipe_buf_release(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff813b2360)
Location: kernel/watch_queue.c:57
Inline: False
```
**Symbols:**

```
ffffffff813b2360-ffffffff813b23a2: watch_queue_pipe_buf_release (STB_LOCAL)
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
