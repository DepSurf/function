# Function: <code>posix_lock_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81260c50)
Location: fs/locks.c:1162
Inline: True
```
**Symbols:**

```
ffffffff81260c50-ffffffff81260c64: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128d140)
Location: fs/locks.c:1192
Inline: True
```
**Symbols:**

```
ffffffff8128d140-ffffffff8128d154: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a2b60)
Location: fs/locks.c:1216
Inline: True
```
**Symbols:**

```
ffffffff812a2b60-ffffffff812a2b78: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b1d40)
Location: fs/locks.c:1216
Inline: True
```
**Symbols:**

```
ffffffff812b1d40-ffffffff812b1d58: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d5890)
Location: fs/locks.c:1226
Inline: True
```
**Symbols:**

```
ffffffff812d5890-ffffffff812d58a8: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81300350)
Location: fs/locks.c:1226
Inline: True
```
**Symbols:**

```
ffffffff81300350-ffffffff81300368: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81315ed0)
Location: fs/locks.c:1348
Inline: True
```
**Symbols:**

```
ffffffff81315ed0-ffffffff81315ee4: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133d6b0)
Location: fs/locks.c:1344
Inline: True
```
**Symbols:**

```
ffffffff8133d6b0-ffffffff8133d6c4: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81355c60)
Location: fs/locks.c:1368
Inline: True
```
**Symbols:**

```
ffffffff81355c60-ffffffff81355c74: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139d643)
Location: fs/locks.c:1368
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
Direct callers:
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff8139ccc0-ffffffff8139ccd4: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813af001)
Location: fs/locks.c:1369
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
Direct callers:
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff813ae690-ffffffff813ae6a4: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b6361)
Location: fs/locks.c:1369
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
Direct callers:
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff813b5c30-ffffffff813b5c44: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8140605e)
Location: fs/locks.c:1369
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
Direct callers:
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff81405930-ffffffff81405944: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8147986b)
Location: fs/locks.c:1344
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
Direct callers:
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff81479500-ffffffff8147951e: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150c1fb)
Location: fs/locks.c:1330
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
Direct callers:
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff8150be40-ffffffff8150be5e: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81543971)
Location: fs/locks.c:1331
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
Direct callers:
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff815435a0-ffffffff815435c1: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81578e71)
Location: fs/locks.c:1345
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
Direct callers:
  - fs/fuse/file.c:fuse_file_lock
```
**Symbols:**

```
ffffffff81578aa0-ffffffff81578ac1: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010418738)
Location: fs/locks.c:1368
Inline: True
```
**Symbols:**

```
ffff800010418738-ffff80001041877c: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e3168)
Location: fs/locks.c:1368
Inline: True
```
**Symbols:**

```
c05e3168-c05e3188: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000526280)
Location: fs/locks.c:1368
Inline: True
```
**Symbols:**

```
c000000000526280-c000000000526298: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bf1de)
Location: fs/locks.c:1368
Inline: True
```
**Symbols:**

```
ffffffe0002bf1de-ffffffe0002bf218: posix_lock_file (STB_GLOBAL)
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
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134e240)
Location: fs/locks.c:1368
Inline: True
```
**Symbols:**

```
ffffffff8134e240-ffffffff8134e254: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133ef20)
Location: fs/locks.c:1368
Inline: True
```
**Symbols:**

```
ffffffff8133ef20-ffffffff8133ef34: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134bd10)
Location: fs/locks.c:1368
Inline: True
```
**Symbols:**

```
ffffffff8134bd10-ffffffff8134bd24: posix_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int posix_lock_file(struct file *filp, struct file_lock *fl, struct file_lock *conflock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135db60)
Location: fs/locks.c:1368
Inline: True
```
**Symbols:**

```
ffffffff8135db60-ffffffff8135db74: posix_lock_file (STB_GLOBAL)
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
