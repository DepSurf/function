# Function: <code>user_page_pipe_buf_try_steal</code>

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
bool user_page_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81350190)
Location: fs/splice.c:148
Inline: False
```
**Symbols:**

```
ffffffff81350190-ffffffff813501b1: user_page_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool user_page_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135ce20)
Location: fs/splice.c:147
Inline: False
```
**Symbols:**

```
ffffffff8135ce20-ffffffff8135ce41: user_page_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool user_page_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813638d0)
Location: fs/splice.c:147
Inline: False
```
**Symbols:**

```
ffffffff813638d0-ffffffff813638f1: user_page_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool user_page_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b20d0)
Location: fs/splice.c:147
Inline: False
```
**Symbols:**

```
ffffffff813b20d0-ffffffff813b20f1: user_page_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool user_page_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81437080)
Location: fs/splice.c:147
Inline: False
```
**Symbols:**

```
ffffffff81437080-ffffffff814370b5: user_page_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool user_page_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c5120)
Location: fs/splice.c:147
Inline: False
```
**Symbols:**

```
ffffffff814c5120-ffffffff814c5155: user_page_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool user_page_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fa560)
Location: fs/splice.c:165
Inline: False
```
**Symbols:**

```
ffffffff814fa560-ffffffff814fa595: user_page_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool user_page_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8152ee50)
Location: fs/splice.c:162
Inline: False
```
**Symbols:**

```
ffffffff8152ee50-ffffffff8152ee85: user_page_pipe_buf_try_steal (STB_LOCAL)
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
