# Function: <code>posix_test_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81260260)
Location: fs/locks.c:763
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffffffff81260260-ffffffff8126030c: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128c430)
Location: fs/locks.c:790
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffffffff8128c430-ffffffff8128c4dc: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a11d0)
Location: fs/locks.c:810
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffffffff812a11d0-ffffffff812a1280: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812aff50)
Location: fs/locks.c:810
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffffffff812aff50-ffffffff812b0000: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d3500)
Location: fs/locks.c:822
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffffffff812d3500-ffffffff812d359d: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fe740)
Location: fs/locks.c:822
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffffffff812fe740-ffffffff812fe7dd: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81314460)
Location: fs/locks.c:932
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffffffff81314460-ffffffff813144f9: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133bda0)
Location: fs/locks.c:928
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffffffff8133bda0-ffffffff8133be3a: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813542e0)
Location: fs/locks.c:952
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffffffff813542e0-ffffffff8135437a: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139aa70)
Location: fs/locks.c:952
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff8139aa70-ffffffff8139ab34: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813ac530)
Location: fs/locks.c:952
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff813ac530-ffffffff813ac5f7: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b3be0)
Location: fs/locks.c:952
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff813b3be0-ffffffff813b3ca7: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814038c0)
Location: fs/locks.c:952
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff814038c0-ffffffff81403987: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81477970)
Location: fs/locks.c:900
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff81477970-ffffffff81477aba: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150a1f0)
Location: fs/locks.c:886
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff8150a1f0-ffffffff8150a33a: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81541970)
Location: fs/locks.c:887
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff81541970-ffffffff81541abd: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81576ef0)
Location: fs/locks.c:901
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff81576ef0-ffffffff8157708d: posix_test_lock (STB_GLOBAL)
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
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010416890)
Location: fs/locks.c:952
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffff800010416890-ffff8000104169a0: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e1e28)
Location: fs/locks.c:952
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
c05e1e28-c05e1ef0: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c0000000005247a0)
Location: fs/locks.c:952
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
c0000000005247a0-c0000000005248f0: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bd9f0)
Location: fs/locks.c:952
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffffffe0002bd9f0-ffffffe0002bdada: posix_test_lock (STB_GLOBAL)
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
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134c8c0)
Location: fs/locks.c:952
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffffffff8134c8c0-ffffffff8134c95a: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133d5a0)
Location: fs/locks.c:952
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffffffff8133d5a0-ffffffff8133d63a: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134a390)
Location: fs/locks.c:952
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffffffff8134a390-ffffffff8134a42a: posix_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void posix_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135caf0)
Location: fs/locks.c:952
Inline: False
Direct callers:
  - fs/locks.c:vfs_test_lock
```
**Symbols:**

```
ffffffff8135caf0-ffffffff8135cb88: posix_test_lock (STB_GLOBAL)
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
