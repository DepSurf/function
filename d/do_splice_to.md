# Function: <code>do_splice_to</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8123db80)
Location: fs/splice.c:1131
Inline: False
Direct callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
```
**Symbols:**

```
ffffffff8123db80-ffffffff8123dbf9: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81265c40)
Location: fs/splice.c:1132
Inline: False
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff81265c40-ffffffff81265cc6: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81279300)
Location: fs/splice.c:878
Inline: False
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff81279300-ffffffff81279386: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81286870)
Location: fs/splice.c:874
Inline: False
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff81286870-ffffffff812868f7: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812a9330)
Location: fs/splice.c:858
Inline: False
Direct callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff812a9330-ffffffff812a93ba: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812cfe70)
Location: fs/splice.c:859
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff812cfe70-ffffffff812cfef9: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e5280)
Location: fs/splice.c:858
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff812e5280-ffffffff812e5309: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81303a80)
Location: fs/splice.c:855
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff81303a80-ffffffff81303b0a: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81316b00)
Location: fs/splice.c:855
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff81316b00-ffffffff81316b8a: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81351e90)
Location: fs/splice.c:853
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff81351e90-ffffffff81351f2e: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135cf10)
Location: fs/splice.c:771
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff8135cf10-ffffffff8135cfad: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813639c0)
Location: fs/splice.c:773
Inline: False
Direct callers:
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff813639c0-ffffffff81363a6f: do_splice_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b21b0)
Location: fs/splice.c:774
Inline: False
Direct callers:
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff813b21b0-ffffffff813b225f: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814371a0)
Location: fs/splice.c:773
Inline: False
Direct callers:
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff814371a0-ffffffff8143727c: do_splice_to (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c5270)
Location: fs/splice.c:770
Inline: False
Direct callers:
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff814c5270-ffffffff814c534c: do_splice_to (STB_LOCAL)
```
</details>
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
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103cd4a0)
Location: fs/splice.c:855
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffff8000103cd4a0-ffff8000103cd55c: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05a8ff0)
Location: fs/splice.c:855
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
c05a8ff0-c05a9090: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004cf320)
Location: fs/splice.c:855
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
c0000000004cf320-c0000000004cf418: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028a814)
Location: fs/splice.c:855
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffe00028a814-ffffffe00028a89e: do_splice_to (STB_GLOBAL)
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
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130f0e0)
Location: fs/splice.c:855
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff8130f0e0-ffffffff8130f16a: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812ffcf0)
Location: fs/splice.c:855
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff812ffcf0-ffffffff812ffd7a: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130ced0)
Location: fs/splice.c:855
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff8130ced0-ffffffff8130cf5a: do_splice_to (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_splice_to(struct file *in, loff_t *ppos, struct pipe_inode_info *pipe, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8131e6c0)
Location: fs/splice.c:855
Inline: False
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_direct_to_actor
```
**Symbols:**

```
ffffffff8131e6c0-ffffffff8131e74a: do_splice_to (STB_GLOBAL)
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
