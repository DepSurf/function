# Function: <code>pipe_wait_writable</code>

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
void pipe_wait_writable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81320710)
Location: fs/pipe.c:1035
Inline: False
Direct callers:
  - fs/splice.c:wait_for_space
```
**Symbols:**

```
ffffffff81320710-ffffffff81320807: pipe_wait_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pipe_wait_writable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8132bc80)
Location: fs/pipe.c:1034
Inline: False
```
**Symbols:**

```
ffffffff8132bc80-ffffffff8132bd77: pipe_wait_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pipe_wait_writable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81331cc0)
Location: fs/pipe.c:1048
Inline: False
```
**Symbols:**

```
ffffffff81331cc0-ffffffff81331db4: pipe_wait_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pipe_wait_writable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8137f440)
Location: fs/pipe.c:1051
Inline: False
```
**Symbols:**

```
ffffffff8137f440-ffffffff8137f534: pipe_wait_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pipe_wait_writable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813ff520)
Location: fs/pipe.c:1052
Inline: False
```
**Symbols:**

```
ffffffff813ff520-ffffffff813ff63e: pipe_wait_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pipe_wait_writable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814892e0)
Location: fs/pipe.c:1052
Inline: False
```
**Symbols:**

```
ffffffff814892e0-ffffffff814893fe: pipe_wait_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pipe_wait_writable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814be210)
Location: fs/pipe.c:1057
Inline: False
```
**Symbols:**

```
ffffffff814be210-ffffffff814be32e: pipe_wait_writable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pipe_wait_writable(struct pipe_inode_info *pipe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814f0690)
Location: fs/pipe.c:1073
Inline: False
```
**Symbols:**

```
ffffffff814f0690-ffffffff814f07ae: pipe_wait_writable (STB_GLOBAL)
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
