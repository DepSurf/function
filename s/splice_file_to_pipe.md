# Function: <code>splice_file_to_pipe</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int splice_file_to_pipe(struct file *in, struct pipe_inode_info *opipe, loff_t *offset, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813653c0)
Location: fs/splice.c:1008
Inline: False
Direct callers:
  - fs/read_write.c:do_sendfile
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff813653c0-ffffffff8136547a: splice_file_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int splice_file_to_pipe(struct file *in, struct pipe_inode_info *opipe, loff_t *offset, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b3cb0)
Location: fs/splice.c:1010
Inline: False
Direct callers:
  - fs/read_write.c:do_sendfile
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff813b3cb0-ffffffff813b3d6a: splice_file_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int splice_file_to_pipe(struct file *in, struct pipe_inode_info *opipe, loff_t *offset, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81438fb0)
Location: fs/splice.c:1006
Inline: False
Direct callers:
  - fs/read_write.c:do_sendfile
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff81438fb0-ffffffff8143907c: splice_file_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int splice_file_to_pipe(struct file *in, struct pipe_inode_info *opipe, loff_t *offset, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c7290)
Location: fs/splice.c:1005
Inline: False
Direct callers:
  - fs/read_write.c:do_sendfile
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff814c7290-ffffffff814c735c: splice_file_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int splice_file_to_pipe(struct file *in, struct pipe_inode_info *opipe, loff_t *offset, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fd070)
Location: fs/splice.c:1226
Inline: False
Direct callers:
  - fs/read_write.c:do_sendfile
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff814fd070-ffffffff814fd13c: splice_file_to_pipe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t splice_file_to_pipe(struct file *in, struct pipe_inode_info *opipe, loff_t *offset, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81531ca0)
Location: fs/splice.c:1285
Inline: False
Direct callers:
  - fs/read_write.c:do_sendfile
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff81531ca0-ffffffff81531d6c: splice_file_to_pipe (STB_GLOBAL)
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
<code>long int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
</li>
</ul>
