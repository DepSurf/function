# Function: <code>update_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81227717)
Location: fs/inode.c:1587
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124fe27)
Location: fs/inode.c:1596
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff8124f010-ffffffff8124f036: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262f46)
Location: fs/inode.c:1645
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81262020-ffffffff81262046: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812707f9)
Location: fs/inode.c:1645
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff8126f8d0-ffffffff8126f8f6: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81293139)
Location: fs/inode.c:1658
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812921f0-ffffffff81292219: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8d98)
Location: fs/inode.c:1652
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812b80f0-ffffffff812b8119: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cded8)
Location: fs/inode.c:1660
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812cd240-ffffffff812cd269: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ead11)
Location: fs/inode.c:1673
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812e9ec0-ffffffff812e9ee9: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fc841)
Location: fs/inode.c:1684
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812fb950-ffffffff812fb979: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813359a9)
Location: fs/inode.c:1771
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff813352f0-ffffffff81335317: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81341329)
Location: fs/inode.c:1772
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81340c60-ffffffff81340c87: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81347669)
Location: fs/inode.c:1781
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ac2d0)
Location: fs/inode.c:1684
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffff8000103ab730-ffff8000103ab78c: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058d5dc)
Location: fs/inode.c:1684
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
c058c1fc-c058c230: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a789c)
Location: fs/inode.c:1684
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
c0000000004a60b0-c0000000004a6124: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe00027181a)
Location: fs/inode.c:1684
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffe000270986-ffffffe0002709ca: update_time (STB_GLOBAL)
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
int update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4e21)
Location: fs/inode.c:1684
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812f3f30-ffffffff812f3f59: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e5a41)
Location: fs/inode.c:1684
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812e4b60-ffffffff812e4b89: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2c31)
Location: fs/inode.c:1684
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812f1d40-ffffffff812f1d69: update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81304341)
Location: fs/inode.c:1684
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81303310-ffffffff81303339: update_time (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *time</code> ➡️ <code>struct timespec64 *time</code>
</li>
</ul>
</details>
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
