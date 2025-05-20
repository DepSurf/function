# Function: <code>iov_iter_pipe</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_pipe(struct iov_iter *i, int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8145fe30)
Location: lib/iov_iter.c:831
Inline: True
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff8145fe30-ffffffff8145fe9c: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_pipe(struct iov_iter *i, int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81464f20)
Location: lib/iov_iter.c:957
Inline: True
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff81464f20-ffffffff81464f63: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_pipe(struct iov_iter *i, int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81490ea0)
Location: lib/iov_iter.c:959
Inline: True
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff81490ea0-ffffffff81490ee3: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_pipe(struct iov_iter *i, int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c60f0)
Location: lib/iov_iter.c:1089
Inline: True
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff814c60f0-ffffffff814c6133: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814da850)
Location: lib/iov_iter.c:1143
Inline: True
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff814da850-ffffffff814da892: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (ffffffff8150612d)
Location: lib/iov_iter.c:1157
Inline: True
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff8150ad05-ffffffff8150ad28: iov_iter_pipe.cold (STB_LOCAL)
ffffffff815060e0-ffffffff8150612f: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815240f0)
Location: lib/iov_iter.c:1157
Inline: True
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff815240f0-ffffffff8152412d: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81586d70)
Location: lib/iov_iter.c:1191
Inline: False
Direct callers:
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff81586d70-ffffffff81586da5: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a4040)
Location: lib/iov_iter.c:1198
Inline: False
Direct callers:
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff815a4040-ffffffff815a4075: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815aaf30)
Location: lib/iov_iter.c:1300
Inline: False
Direct callers:
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff815aaf30-ffffffff815aaf65: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81614540)
Location: lib/iov_iter.c:1159
Inline: False
Direct callers:
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff81614540-ffffffff81614576: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e10d0)
Location: lib/iov_iter.c:1211
Inline: False
Direct callers:
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff816e10d0-ffffffff816e1122: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d1560)
Location: lib/iov_iter.c:1029
Inline: False
Direct callers:
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff817d1560-ffffffff817d15b2: iov_iter_pipe (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062dad8)
Location: lib/iov_iter.c:1157
Inline: True
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffff80001062dad8-ffff80001062db24: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d46f4)
Location: lib/iov_iter.c:1157
Inline: True
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
c07d46f4-c07d4780: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d0cf0)
Location: lib/iov_iter.c:1157
Inline: False
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
c0000000007d0cf0-c0000000007d0d50: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045dbaa)
Location: lib/iov_iter.c:1157
Inline: True
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffe00045dbaa-ffffffe00045dbe6: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151c6d0)
Location: lib/iov_iter.c:1157
Inline: True
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff8151c6d0-ffffffff8151c70d: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150c9c0)
Location: lib/iov_iter.c:1157
Inline: True
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff8150c9c0-ffffffff8150c9fd: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81518760)
Location: lib/iov_iter.c:1157
Inline: True
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff81518760-ffffffff8151879d: iov_iter_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iov_iter_pipe(struct iov_iter *i, unsigned int direction, struct pipe_inode_info *pipe, size_t count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81531f50)
Location: lib/iov_iter.c:1157
Inline: True
Direct callers:
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:generic_file_splice_read
```
**Symbols:**

```
ffffffff81531f50-ffffffff81531f8d: iov_iter_pipe (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int direction</code> ➡️ <code>unsigned int direction</code>
</li>
</ul>
</details>
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
