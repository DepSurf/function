# Function: <code>pipe_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81214cd0)
Location: fs/pipe.c:109
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/splice.c:splice_to_pipe
```
**Symbols:**

```
ffffffff81214cd0-ffffffff81214d82: pipe_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8123bb60)
Location: fs/pipe.c:110
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/splice.c:splice_to_pipe
```
**Symbols:**

```
ffffffff8123bb60-ffffffff8123bc12: pipe_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8124e900)
Location: fs/pipe.c:110
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
ffffffff8124e900-ffffffff8124e9b2: pipe_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8125a830)
Location: fs/pipe.c:110
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
ffffffff8125a830-ffffffff8125a8e2: pipe_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8127cbc0)
Location: fs/pipe.c:111
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
ffffffff8127cbc0-ffffffff8127cc72: pipe_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812a3b50)
Location: fs/pipe.c:106
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
ffffffff812a3b50-ffffffff812a3c04: pipe_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812b8ca0)
Location: fs/pipe.c:106
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
ffffffff812b8ca0-ffffffff812b8d54: pipe_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d5890)
Location: fs/pipe.c:107
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
ffffffff812d5890-ffffffff812d5946: pipe_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e7400)
Location: fs/pipe.c:107
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
ffffffff812e7400-ffffffff812e74b6: pipe_wait (STB_GLOBAL)
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
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffff800010390100)
Location: fs/pipe.c:107
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
ffff800010390100-ffff8000103901d0: pipe_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c0576b7c)
Location: fs/pipe.c:107
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
c0576b7c-c0576c58: pipe_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c000000000487b30)
Location: fs/pipe.c:107
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
c000000000487b30-c000000000487c48: pipe_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffe00025fb20)
Location: fs/pipe.c:107
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
ffffffe00025fb20-ffffffe00025fbd0: pipe_wait (STB_GLOBAL)
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
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812df9e0)
Location: fs/pipe.c:107
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
ffffffff812df9e0-ffffffff812dfa96: pipe_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d0620)
Location: fs/pipe.c:107
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
ffffffff812d0620-ffffffff812d06d6: pipe_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812dd7f0)
Location: fs/pipe.c:107
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
ffffffff812dd7f0-ffffffff812dd8a6: pipe_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pipe_wait(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812ee770)
Location: fs/pipe.c:107
Inline: False
Direct callers:
  - fs/pipe.c:wait_for_partner
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
**Symbols:**

```
ffffffff812ee770-ffffffff812ee826: pipe_wait (STB_GLOBAL)
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
