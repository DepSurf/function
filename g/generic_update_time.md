# Function: <code>generic_update_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81227530)
Location: fs/inode.c:1563
Inline: False
```
**Symbols:**

```
ffffffff81227530-ffffffff812275f5: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124fc50)
Location: fs/inode.c:1572
Inline: False
```
**Symbols:**

```
ffffffff8124fc50-ffffffff8124fd15: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262c80)
Location: fs/inode.c:1621
Inline: False
```
**Symbols:**

```
ffffffff81262c80-ffffffff81262d45: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81270520)
Location: fs/inode.c:1621
Inline: False
```
**Symbols:**

```
ffffffff81270520-ffffffff812705e3: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81292e60)
Location: fs/inode.c:1634
Inline: False
```
**Symbols:**

```
ffffffff81292e60-ffffffff81292f23: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8980)
Location: fs/inode.c:1624
Inline: False
```
**Symbols:**

```
ffffffff812b8980-ffffffff812b8a42: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cdad0)
Location: fs/inode.c:1632
Inline: False
```
**Symbols:**

```
ffffffff812cdad0-ffffffff812cdb92: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ea870)
Location: fs/inode.c:1645
Inline: False
```
**Symbols:**

```
ffffffff812ea870-ffffffff812ea92d: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fc2a0)
Location: fs/inode.c:1656
Inline: False
```
**Symbols:**

```
ffffffff812fc2a0-ffffffff812fc35d: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81337b10)
Location: fs/inode.c:1743
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff81335230-ffffffff813352ed: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8134346c)
Location: fs/inode.c:1744
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff81340ba0-ffffffff81340c5d: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81349779)
Location: fs/inode.c:1751
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff81346fc0-ffffffff81347080: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813974c9)
Location: fs/inode.c:1755
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff813949f0-ffffffff81394ab0: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814196d6)
Location: fs/inode.c:1836
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff81416c80-ffffffff81416d64: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a5116)
Location: fs/inode.c:1838
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
Direct callers:
  - fs/inode.c:file_modified_flags
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff814a1cf0-ffffffff814a1db5: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814da396)
Location: fs/inode.c:1882
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
Direct callers:
  - fs/inode.c:file_modified_flags
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff814d6e40-ffffffff814d6efd: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81509f70)
Location: fs/inode.c:1896
Inline: False
Direct callers:
  - fs/inode.c:kiocb_modified
  - fs/inode.c:file_modified
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81509f70-ffffffff81509fcf: generic_update_time (STB_GLOBAL)
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
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ac810)
Location: fs/inode.c:1656
Inline: False
```
**Symbols:**

```
ffff8000103ac810-ffff8000103ac904: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058da8c)
Location: fs/inode.c:1656
Inline: False
```
**Symbols:**

```
c058da8c-c058dba4: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a83c0)
Location: fs/inode.c:1656
Inline: False
```
**Symbols:**

```
c0000000004a83c0-c0000000004a84e8: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe0002711ec)
Location: fs/inode.c:1656
Inline: False
```
**Symbols:**

```
ffffffe0002711ec-ffffffe0002712ba: generic_update_time (STB_GLOBAL)
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
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4880)
Location: fs/inode.c:1656
Inline: False
```
**Symbols:**

```
ffffffff812f4880-ffffffff812f493d: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e54a0)
Location: fs/inode.c:1656
Inline: False
```
**Symbols:**

```
ffffffff812e54a0-ffffffff812e555d: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2690)
Location: fs/inode.c:1656
Inline: False
```
**Symbols:**

```
ffffffff812f2690-ffffffff812f274d: generic_update_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int generic_update_time(struct inode *inode, struct timespec64 *time, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81303da0)
Location: fs/inode.c:1656
Inline: False
```
**Symbols:**

```
ffffffff81303da0-ffffffff81303e5d: generic_update_time (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct timespec64 *time</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, time, flags</code> ➡️ <code>inode, flags</code>
</li>
</ul>
</details>
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
