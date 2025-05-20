# Function: <code>anon_pipe_buf_try_steal</code>

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
bool anon_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8131ec20)
Location: fs/pipe.c:125
Inline: False
```
**Symbols:**

```
ffffffff8131ec20-ffffffff8131ec7b: anon_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool anon_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8132a140)
Location: fs/pipe.c:125
Inline: False
```
**Symbols:**

```
ffffffff8132a140-ffffffff8132a199: anon_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool anon_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813300f0)
Location: fs/pipe.c:140
Inline: False
```
**Symbols:**

```
ffffffff813300f0-ffffffff81330149: anon_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool anon_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8137d8b0)
Location: fs/pipe.c:140
Inline: False
```
**Symbols:**

```
ffffffff8137d8b0-ffffffff8137d906: anon_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool anon_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813fe5a0)
Location: fs/pipe.c:141
Inline: False
```
**Symbols:**

```
ffffffff813fe5a0-ffffffff813fe660: anon_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool anon_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81488240)
Location: fs/pipe.c:141
Inline: False
```
**Symbols:**

```
ffffffff81488240-ffffffff81488300: anon_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool anon_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814bd140)
Location: fs/pipe.c:141
Inline: False
```
**Symbols:**

```
ffffffff814bd140-ffffffff814bd208: anon_pipe_buf_try_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool anon_pipe_buf_try_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814ef5e0)
Location: fs/pipe.c:141
Inline: False
```
**Symbols:**

```
ffffffff814ef5e0-ffffffff814ef6a2: anon_pipe_buf_try_steal (STB_LOCAL)
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
