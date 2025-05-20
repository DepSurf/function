# Function: <code>iter_to_pipe</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81279ef0)
Location: fs/splice.c:1210
Inline: False
Direct callers:
  - fs/splice.c:vmsplice_to_pipe
```
**Symbols:**

```
ffffffff81279ef0-ffffffff8127a108: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81287440)
Location: fs/splice.c:1206
Inline: False
Direct callers:
  - fs/splice.c:vmsplice_to_pipe
```
**Symbols:**

```
ffffffff81287440-ffffffff8128760e: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812a9d40)
Location: fs/splice.c:1190
Inline: False
Direct callers:
  - fs/splice.c:vmsplice_to_pipe
```
**Symbols:**

```
ffffffff812a9d40-ffffffff812a9f4c: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812d01d0)
Location: fs/splice.c:1191
Inline: False
```
**Symbols:**

```
ffffffff812d01d0-ffffffff812d03e8: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e6520)
Location: fs/splice.c:1195
Inline: False
```
**Symbols:**

```
ffffffff812e6520-ffffffff812e6738: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81305180)
Location: fs/splice.c:1201
Inline: False
```
**Symbols:**

```
ffffffff81305180-ffffffff813053b2: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81318210)
Location: fs/splice.c:1209
Inline: False
```
**Symbols:**

```
ffffffff81318210-ffffffff81318442: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81350760)
Location: fs/splice.c:1197
Inline: False
```
**Symbols:**

```
ffffffff81350760-ffffffff813509a3: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135d730)
Location: fs/splice.c:1151
Inline: False
Direct callers:
  - fs/splice.c:vmsplice_to_pipe
```
**Symbols:**

```
ffffffff8135d730-ffffffff8135d970: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813641d0)
Location: fs/splice.c:1156
Inline: False
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff813641d0-ffffffff81364403: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b29c0)
Location: fs/splice.c:1158
Inline: False
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff813b29c0-ffffffff813b2c7a: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814379c0)
Location: fs/splice.c:1154
Inline: False
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff814379c0-ffffffff81437ca8: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c5c90)
Location: fs/splice.c:1153
Inline: False
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffff814c5c90-ffffffff814c5fe6: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fb180)
Location: fs/splice.c:1385
Inline: False
Direct callers:
  - fs/splice.c:vmsplice_to_pipe
```
**Symbols:**

```
ffffffff814fb180-ffffffff814fb4c9: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8152fe80)
Location: fs/splice.c:1448
Inline: False
Direct callers:
  - fs/splice.c:vmsplice_to_pipe
```
**Symbols:**

```
ffffffff8152fe80-ffffffff815301b9: iter_to_pipe (STB_LOCAL)
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
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103ce350)
Location: fs/splice.c:1209
Inline: False
```
**Symbols:**

```
ffff8000103ce350-ffff8000103ce520: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05a9ab8)
Location: fs/splice.c:1209
Inline: False
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
c05a9ab8-c05a9c70: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004d1630)
Location: fs/splice.c:1209
Inline: False
```
**Symbols:**

```
c0000000004d1630-c0000000004d18fc: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028b3ce)
Location: fs/splice.c:1209
Inline: False
Direct callers:
  - fs/splice.c:__do_sys_vmsplice
```
**Symbols:**

```
ffffffe00028b3ce-ffffffe00028b538: iter_to_pipe (STB_LOCAL)
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
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813107f0)
Location: fs/splice.c:1209
Inline: False
```
**Symbols:**

```
ffffffff813107f0-ffffffff81310a22: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81301400)
Location: fs/splice.c:1209
Inline: False
```
**Symbols:**

```
ffffffff81301400-ffffffff81301632: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130e5e0)
Location: fs/splice.c:1209
Inline: False
```
**Symbols:**

```
ffffffff8130e5e0-ffffffff8130e812: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iter_to_pipe(struct iov_iter *from, struct pipe_inode_info *pipe, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8131fde0)
Location: fs/splice.c:1209
Inline: False
```
**Symbols:**

```
ffffffff8131fde0-ffffffff81320012: iter_to_pipe (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
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
