# Function: <code>put_pipe_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81215740)
Location: fs/pipe.c:536
Inline: False
Direct callers:
  - fs/pipe.c:pipe_release
  - fs/pipe.c:fifo_open
```
**Symbols:**

```
ffffffff81215740-ffffffff812157a3: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8123c5a0)
Location: fs/pipe.c:551
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
ffffffff8123c5a0-ffffffff8123c5fc: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8124f300)
Location: fs/pipe.c:548
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
ffffffff8124f300-ffffffff8124f35c: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8125b250)
Location: fs/pipe.c:548
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
ffffffff8125b250-ffffffff8125b2ac: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8127d620)
Location: fs/pipe.c:549
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
ffffffff8127d620-ffffffff8127d67c: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812a45b0)
Location: fs/pipe.c:544
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
ffffffff812a45b0-ffffffff812a4613: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812b9710)
Location: fs/pipe.c:558
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
ffffffff812b9710-ffffffff812b9773: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d6360)
Location: fs/pipe.c:570
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
ffffffff812d6360-ffffffff812d63c3: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e7ed0)
Location: fs/pipe.c:570
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
ffffffff812e7ed0-ffffffff812e7f33: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81320299)
Location: fs/pipe.c:683
Inline: True
Inline callers:
  - fs/pipe.c:pipe_release
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
```
**Symbols:**

```
ffffffff8131fe60-ffffffff8131fec3: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8132b7d9)
Location: fs/pipe.c:683
Inline: True
Inline callers:
  - fs/pipe.c:pipe_release
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
```
**Symbols:**

```
ffffffff8132b3a0-ffffffff8132b403: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8133148c)
Location: fs/pipe.c:697
Inline: True
Inline callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8137ec0c)
Location: fs/pipe.c:698
Inline: True
Inline callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813feca7)
Location: fs/pipe.c:699
Inline: True
Inline callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814889d7)
Location: fs/pipe.c:699
Inline: True
Inline callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814bd9d2)
Location: fs/pipe.c:701
Inline: True
Inline callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814efe72)
Location: fs/pipe.c:717
Inline: True
Inline callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
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
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffff800010390c80)
Location: fs/pipe.c:570
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
ffff800010390c80-ffff800010390d3c: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c0577760)
Location: fs/pipe.c:570
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
c0577760-c05777cc: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c000000000488b60)
Location: fs/pipe.c:570
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
c000000000488b60-c000000000488c30: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffe000260432)
Location: fs/pipe.c:570
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
ffffffe000260432-ffffffe0002604d2: put_pipe_info (STB_LOCAL)
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
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e04b0)
Location: fs/pipe.c:570
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
ffffffff812e04b0-ffffffff812e0513: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d10f0)
Location: fs/pipe.c:570
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
ffffffff812d10f0-ffffffff812d1153: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812de2c0)
Location: fs/pipe.c:570
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
ffffffff812de2c0-ffffffff812de323: put_pipe_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void put_pipe_info(struct inode *inode, struct pipe_inode_info *pipe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812ef240)
Location: fs/pipe.c:570
Inline: False
Direct callers:
  - fs/pipe.c:fifo_open
  - fs/pipe.c:create_pipe_files
  - fs/pipe.c:pipe_release
```
**Symbols:**

```
ffffffff812ef240-ffffffff812ef29c: put_pipe_info (STB_LOCAL)
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
