# Function: <code>splice_to_pipe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8123d7e0)
Location: fs/splice.c:182
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - mm/shmem.c:shmem_file_splice_read
  - fs/splice.c:__generic_file_splice_read
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:vmsplice_to_pipe
  - net/core/skbuff.c:skb_socket_splice
  - net/unix/af_unix.c:skb_unix_socket_splice
```
**Symbols:**

```
ffffffff8123d7e0-ffffffff8123da07: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812658a0)
Location: fs/splice.c:182
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - mm/shmem.c:shmem_file_splice_read
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:__generic_file_splice_read
  - net/core/skbuff.c:skb_socket_splice
  - net/unix/af_unix.c:skb_unix_socket_splice
```
**Symbols:**

```
ffffffff812658a0-ffffffff81265ad4: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81278e10)
Location: fs/splice.c:183
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff81278e10-ffffffff81278f2d: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81286380)
Location: fs/splice.c:185
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff81286380-ffffffff8128648e: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812a8e60)
Location: fs/splice.c:185
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff812a8e60-ffffffff812a8f73: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812cf990)
Location: fs/splice.c:185
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff812cf990-ffffffff812cfaa1: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e4d80)
Location: fs/splice.c:185
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff812e4d80-ffffffff812e4e91: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81303560)
Location: fs/splice.c:184
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff81303560-ffffffff81303670: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813165e0)
Location: fs/splice.c:184
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff813165e0-ffffffff813166f0: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8134ff90)
Location: fs/splice.c:183
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff8134ff90-ffffffff813500af: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135cc20)
Location: fs/splice.c:182
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff8135cc20-ffffffff8135cd3f: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813636d0)
Location: fs/splice.c:182
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff813636d0-ffffffff813637f2: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b1ed0)
Location: fs/splice.c:182
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff813b1ed0-ffffffff813b1ff2: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81436e50)
Location: fs/splice.c:182
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff81436e50-ffffffff81436f87: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c4ed0)
Location: fs/splice.c:182
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff814c4ed0-ffffffff814c5007: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fa310)
Location: fs/splice.c:200
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff814fa310-ffffffff814fa447: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8152ec00)
Location: fs/splice.c:197
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff8152ec00-ffffffff8152ed33: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103ccee0)
Location: fs/splice.c:184
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffff8000103ccee0-ffff8000103cd04c: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05a8ad0)
Location: fs/splice.c:184
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
c05a8ad0-c05a8c28: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004ceb30)
Location: fs/splice.c:184
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
c0000000004ceb30-c0000000004ced2c: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028a36c)
Location: fs/splice.c:184
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffe00028a36c-ffffffe00028a460: splice_to_pipe (STB_GLOBAL)
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
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130ebc0)
Location: fs/splice.c:184
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff8130ebc0-ffffffff8130ecd0: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812ff7d0)
Location: fs/splice.c:184
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff812ff7d0-ffffffff812ff8e0: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130c9b0)
Location: fs/splice.c:184
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff8130c9b0-ffffffff8130cac0: splice_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t splice_to_pipe(struct pipe_inode_info *pipe, struct splice_pipe_desc *spd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8131e1c0)
Location: fs/splice.c:184
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - net/core/skbuff.c:skb_splice_bits
```
**Symbols:**

```
ffffffff8131e1c0-ffffffff8131e2d0: splice_to_pipe (STB_GLOBAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
