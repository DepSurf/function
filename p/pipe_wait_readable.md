# Function: <code>pipe_wait_readable</code>

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
void pipe_wait_readable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81320630)
Location: fs/pipe.c:1028
Inline: False
```
**Symbols:**

```
ffffffff81320630-ffffffff8132070e: pipe_wait_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pipe_wait_readable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8132bba0)
Location: fs/pipe.c:1027
Inline: False
```
**Symbols:**

```
ffffffff8132bba0-ffffffff8132bc7e: pipe_wait_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pipe_wait_readable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81331be0)
Location: fs/pipe.c:1041
Inline: False
```
**Symbols:**

```
ffffffff81331be0-ffffffff81331cbe: pipe_wait_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pipe_wait_readable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8137f360)
Location: fs/pipe.c:1044
Inline: False
```
**Symbols:**

```
ffffffff8137f360-ffffffff8137f43e: pipe_wait_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pipe_wait_readable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813ff400)
Location: fs/pipe.c:1045
Inline: False
Direct callers:
  - fs/splice.c:splice_from_pipe_next
```
**Symbols:**

```
ffffffff813ff400-ffffffff813ff514: pipe_wait_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pipe_wait_readable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814891b0)
Location: fs/pipe.c:1045
Inline: False
Direct callers:
  - fs/splice.c:splice_from_pipe_next
```
**Symbols:**

```
ffffffff814891b0-ffffffff814892c4: pipe_wait_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pipe_wait_readable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814be0e0)
Location: fs/pipe.c:1050
Inline: False
Direct callers:
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_from_pipe_next
```
**Symbols:**

```
ffffffff814be0e0-ffffffff814be1f4: pipe_wait_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pipe_wait_readable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814f0560)
Location: fs/pipe.c:1066
Inline: False
Direct callers:
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_from_pipe_next
```
**Symbols:**

```
ffffffff814f0560-ffffffff814f0674: pipe_wait_readable (STB_GLOBAL)
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
