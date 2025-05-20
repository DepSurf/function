# Function: <code>__anon_inode_getfile</code>

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
struct file *__anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags, const struct inode *context_inode, bool secure);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81383c80)
Location: fs/anon_inodes.c:78
Inline: False
Direct callers:
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/anon_inodes.c:anon_inode_getfile
```
**Symbols:**

```
ffffffff81383c80-ffffffff81383dfa: __anon_inode_getfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *__anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags, const struct inode *context_inode, bool secure);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff813d0f20)
Location: fs/anon_inodes.c:78
Inline: False
Direct callers:
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/anon_inodes.c:anon_inode_getfile
```
**Symbols:**

```
ffffffff813d0f20-ffffffff813d109a: __anon_inode_getfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *__anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags, const struct inode *context_inode, bool secure);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8145a110)
Location: fs/anon_inodes.c:78
Inline: False
Direct callers:
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/anon_inodes.c:anon_inode_getfile_secure
  - fs/anon_inodes.c:anon_inode_getfile
```
**Symbols:**

```
ffffffff8145a110-ffffffff8145a29f: __anon_inode_getfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *__anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags, const struct inode *context_inode, bool secure);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff814e95b0)
Location: fs/anon_inodes.c:78
Inline: False
Direct callers:
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/anon_inodes.c:anon_inode_getfile_secure
  - fs/anon_inodes.c:anon_inode_getfile
```
**Symbols:**

```
ffffffff814e95b0-ffffffff814e973f: __anon_inode_getfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *__anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags, const struct inode *context_inode, bool secure);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81520350)
Location: fs/anon_inodes.c:78
Inline: False
Direct callers:
  - fs/anon_inodes.c:anon_inode_getfd_secure
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/anon_inodes.c:anon_inode_getfile_secure
  - fs/anon_inodes.c:anon_inode_getfile
```
**Symbols:**

```
ffffffff81520350-ffffffff815204df: __anon_inode_getfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *__anon_inode_getfile(const char *name, const struct file_operations *fops, void *priv, int flags, const struct inode *context_inode, bool make_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81554960)
Location: fs/anon_inodes.c:78
Inline: False
Direct callers:
  - fs/anon_inodes.c:anon_inode_create_getfd
  - fs/anon_inodes.c:anon_inode_getfd
  - fs/anon_inodes.c:anon_inode_create_getfile
  - fs/anon_inodes.c:anon_inode_getfile
```
**Symbols:**

```
ffffffff81554960-ffffffff81554aef: __anon_inode_getfile (STB_LOCAL)
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
<b>Param added. </b>
<code>bool make_inode</code>
</li>
<li>
<b>Param removed. </b>
<code>bool secure</code>
</li>
</ul>
</details>
</li>
</ul>
