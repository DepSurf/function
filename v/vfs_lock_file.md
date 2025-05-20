# Function: <code>vfs_lock_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812611e0)
Location: fs/locks.c:2104
Inline: True
```
**Symbols:**

```
ffffffff812611e0-ffffffff81261211: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128d370)
Location: fs/locks.c:2130
Inline: True
```
**Symbols:**

```
ffffffff8128d370-ffffffff8128d3a1: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a2b80)
Location: fs/locks.c:2168
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff812a2b80-ffffffff812a2bc0: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b1d60)
Location: fs/locks.c:2159
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff812b1d60-ffffffff812b1da0: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d58b0)
Location: fs/locks.c:2195
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff812d58b0-ffffffff812d58f3: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81300370)
Location: fs/locks.c:2200
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff81300370-ffffffff813003b3: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81315ef0)
Location: fs/locks.c:2314
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff81315ef0-ffffffff81315f24: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133d6d0)
Location: fs/locks.c:2332
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff8133d6d0-ffffffff8133d704: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81355c80)
Location: fs/locks.c:2421
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff81355c80-ffffffff81355cb4: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139d5a4)
Location: fs/locks.c:2424
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff8139d320-ffffffff8139d354: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813aef74)
Location: fs/locks.c:2425
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff813aecf0-ffffffff813aed24: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b62d4)
Location: fs/locks.c:2427
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff813b6050-ffffffff813b6084: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81405fd4)
Location: fs/locks.c:2330
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff81405d50-ffffffff81405d84: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814797c0)
Location: fs/locks.c:2316
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff81479520-ffffffff81479576: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150c150)
Location: fs/locks.c:2297
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff8150be70-ffffffff8150bed0: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815438c6)
Location: fs/locks.c:2274
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff815435e0-ffffffff81543646: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81578dc6)
Location: fs/locks.c:2284
Inline: True
Inline callers:
  - fs/locks.c:locks_remove_posix
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff81578ae0-ffffffff81578b46: vfs_lock_file (STB_GLOBAL)
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
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010418780)
Location: fs/locks.c:2421
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffff800010418780-ffff8000104187f4: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e3188)
Location: fs/locks.c:2421
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
c05e3188-c05e31cc: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (c0000000005262a0)
Location: fs/locks.c:2421
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
c0000000005262a0-c000000000526304: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bf218)
Location: fs/locks.c:2421
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffe0002bf218-ffffffe0002bf276: vfs_lock_file (STB_GLOBAL)
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
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134e260)
Location: fs/locks.c:2421
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff8134e260-ffffffff8134e294: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133ef40)
Location: fs/locks.c:2421
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff8133ef40-ffffffff8133ef74: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134bd30)
Location: fs/locks.c:2421
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff8134bd30-ffffffff8134bd64: vfs_lock_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfs_lock_file(struct file *filp, unsigned int cmd, struct file_lock *fl, struct file_lock *conf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135db80)
Location: fs/locks.c:2421
Inline: True
Direct callers:
  - fs/locks.c:locks_remove_posix
```
**Symbols:**

```
ffffffff8135db80-ffffffff8135dbb4: vfs_lock_file (STB_GLOBAL)
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
