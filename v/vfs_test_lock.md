# Function: <code>vfs_test_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81260310)
Location: fs/locks.c:1980
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81260310-ffffffff8126033e: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128c4e0)
Location: fs/locks.c:2006
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8128c4e0-ffffffff8128c50e: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a1280)
Location: fs/locks.c:2044
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff812a1280-ffffffff812a12bc: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b0000)
Location: fs/locks.c:2042
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff812b0000-ffffffff812b003c: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d35a0)
Location: fs/locks.c:2052
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff812d35a0-ffffffff812d35df: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fe7e0)
Location: fs/locks.c:2050
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff812fe7e0-ffffffff812fe81f: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81314500)
Location: fs/locks.c:2164
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81314500-ffffffff81314531: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133be40)
Location: fs/locks.c:2182
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8133be40-ffffffff8133be71: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81354380)
Location: fs/locks.c:2271
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81354380-ffffffff813543b1: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139dbcb)
Location: fs/locks.c:2274
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8139ab40-ffffffff8139ab71: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813af57b)
Location: fs/locks.c:2275
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff813ac600-ffffffff813ac631: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b683b)
Location: fs/locks.c:2278
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff813b3cb0-ffffffff813b3ce1: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8140653b)
Location: fs/locks.c:2181
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81403990-ffffffff814039c1: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8147b03e)
Location: fs/locks.c:2167
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81477ac0-ffffffff81477b05: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150db8e)
Location: fs/locks.c:2147
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8150a350-ffffffff8150a39f: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8154536e)
Location: fs/locks.c:2124
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff81541ad0-ffffffff81541b22: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8157a8a2)
Location: fs/locks.c:2131
Inline: True
Inline callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff815770a0-ffffffff815770f2: vfs_test_lock (STB_GLOBAL)
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
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff8000104169a0)
Location: fs/locks.c:2271
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffff8000104169a0-ffff800010416a00: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e1ef0)
Location: fs/locks.c:2271
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk64
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
c05e1ef0-c05e1f30: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c0000000005248f0)
Location: fs/locks.c:2271
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
c0000000005248f0-c000000000524968: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bdada)
Location: fs/locks.c:2271
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffe0002bdada-ffffffe0002bdb28: vfs_test_lock (STB_GLOBAL)
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
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134c960)
Location: fs/locks.c:2271
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8134c960-ffffffff8134c991: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133d640)
Location: fs/locks.c:2271
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8133d640-ffffffff8133d671: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134a430)
Location: fs/locks.c:2271
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8134a430-ffffffff8134a461: vfs_test_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_test_lock(struct file *filp, struct file_lock *fl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135cb90)
Location: fs/locks.c:2271
Inline: False
Direct callers:
  - fs/locks.c:fcntl_getlk
```
**Symbols:**

```
ffffffff8135cb90-ffffffff8135cbc1: vfs_test_lock (STB_GLOBAL)
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
