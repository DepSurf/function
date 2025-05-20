# Function: <code>page_cache_pipe_buf_steal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8123e790)
Location: fs/splice.c:43
Inline: False
```
**Symbols:**

```
ffffffff8123e790-ffffffff8123e84f: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812664d0)
Location: fs/splice.c:43
Inline: False
```
**Symbols:**

```
ffffffff812664d0-ffffffff812665b2: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8127a230)
Location: fs/splice.c:44
Inline: False
```
**Symbols:**

```
ffffffff8127a230-ffffffff8127a312: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81287740)
Location: fs/splice.c:46
Inline: False
```
**Symbols:**

```
ffffffff81287740-ffffffff81287813: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812a9c60)
Location: fs/splice.c:46
Inline: False
```
**Symbols:**

```
ffffffff812a9c60-ffffffff812a9d3a: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812d16b0)
Location: fs/splice.c:46
Inline: False
```
**Symbols:**

```
ffffffff812d16b0-ffffffff812d1790: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e6b10)
Location: fs/splice.c:46
Inline: False
```
**Symbols:**

```
ffffffff812e6b10-ffffffff812e6bf0: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/splice.c (0)
Location: fs/splice.c:47
Inline: False
```
**Symbols:**

```
ffffffff81305790-ffffffff8130584c: page_cache_pipe_buf_steal (STB_LOCAL)
ffffffff81305f24-ffffffff81305f37: page_cache_pipe_buf_steal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81318820)
Location: fs/splice.c:47
Inline: False
```
**Symbols:**

```
ffffffff81318820-ffffffff813188dc: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103cf450)
Location: fs/splice.c:47
Inline: False
```
**Symbols:**

```
ffff8000103cf450-ffff8000103cf57c: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05a9e68)
Location: fs/splice.c:47
Inline: False
```
**Symbols:**

```
c05a9e68-c05a9fb8: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004d14b0)
Location: fs/splice.c:47
Inline: False
```
**Symbols:**

```
c0000000004d14b0-c0000000004d1628: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028b6ca)
Location: fs/splice.c:47
Inline: False
```
**Symbols:**

```
ffffffe00028b6ca-ffffffe00028b7ac: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81310e00)
Location: fs/splice.c:47
Inline: False
```
**Symbols:**

```
ffffffff81310e00-ffffffff81310ebc: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81301a10)
Location: fs/splice.c:47
Inline: False
```
**Symbols:**

```
ffffffff81301a10-ffffffff81301acc: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130ebf0)
Location: fs/splice.c:47
Inline: False
```
**Symbols:**

```
ffffffff8130ebf0-ffffffff8130ecac: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int page_cache_pipe_buf_steal(struct pipe_inode_info *pipe, struct pipe_buffer *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813203f0)
Location: fs/splice.c:47
Inline: False
```
**Symbols:**

```
ffffffff813203f0-ffffffff813204a7: page_cache_pipe_buf_steal (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
