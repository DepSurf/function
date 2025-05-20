# Function: <code>page_cache_pipe_buf_try_steal</code>

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
bool page_cache_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813506a0)
Location: fs/splice.c:47
Inline: False
```
**Symbols:**

```
ffffffff813506a0-ffffffff81350759: page_cache_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool page_cache_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135d970)
Location: fs/splice.c:46
Inline: False
```
**Symbols:**

```
ffffffff8135d970-ffffffff8135da29: page_cache_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool page_cache_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81364410)
Location: fs/splice.c:46
Inline: False
```
**Symbols:**

```
ffffffff81364410-ffffffff813644c9: page_cache_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool page_cache_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b2c80)
Location: fs/splice.c:46
Inline: False
```
**Symbols:**

```
ffffffff813b2c80-ffffffff813b2d39: page_cache_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool page_cache_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81437ed0)
Location: fs/splice.c:46
Inline: False
```
**Symbols:**

```
ffffffff81437ed0-ffffffff81437fc5: page_cache_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool page_cache_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c6af0)
Location: fs/splice.c:46
Inline: False
```
**Symbols:**

```
ffffffff814c6af0-ffffffff814c6bf3: page_cache_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool page_cache_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fbb90)
Location: fs/splice.c:64
Inline: False
```
**Symbols:**

```
ffffffff814fbb90-ffffffff814fbc93: page_cache_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool page_cache_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8152efb0)
Location: fs/splice.c:64
Inline: False
```
**Symbols:**

```
ffffffff8152efb0-ffffffff8152f0a4: page_cache_pipe_buf_try_steal (STB_LOCAL)
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
