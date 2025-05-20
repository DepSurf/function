# Function: <code>fuse_perm_getattr</code>

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
In fs/fuse/dir.c (ffffffff81314477)
Location: fs/fuse/dir.c:1059
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81348ad7)
Location: fs/fuse/dir.c:1064
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135d2d0)
Location: fs/fuse/dir.c:1078
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
ffffffff8135d2d0-ffffffff8135d2ff: fuse_perm_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81371cb0)
Location: fs/fuse/dir.c:1078
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
ffffffff81371cb0-ffffffff81371cdf: fuse_perm_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813969b0)
Location: fs/fuse/dir.c:1074
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
ffffffff813969b0-ffffffff813969df: fuse_perm_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c5580)
Location: fs/fuse/dir.c:1083
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
ffffffff813c5580-ffffffff813c55af: fuse_perm_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813de720)
Location: fs/fuse/dir.c:1085
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
ffffffff813de720-ffffffff813de74f: fuse_perm_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81409c40)
Location: fs/fuse/dir.c:1072
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
ffffffff81409c40-ffffffff81409c71: fuse_perm_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81424350)
Location: fs/fuse/dir.c:1130
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
ffffffff81424350-ffffffff81424381: fuse_perm_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81474d7b)
Location: fs/fuse/dir.c:1130
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148f837)
Location: fs/fuse/dir.c:1230
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
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
In fs/fuse/dir.c (ffffffff814952a6)
Location: fs/fuse/dir.c:1247
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814ecd36)
Location: fs/fuse/dir.c:1195
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8157ba93)
Location: fs/fuse/dir.c:1275
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81621468)
Location: fs/fuse/dir.c:1308
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff816598b8)
Location: fs/fuse/dir.c:1374
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81693528)
Location: fs/fuse/dir.c:1475
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
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
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffff800010507a98)
Location: fs/fuse/dir.c:1130
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
ffff800010507a98-ffff800010507ae4: fuse_perm_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c3a74)
Location: fs/fuse/dir.c:1130
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
c06c3a74-c06c3ab4: fuse_perm_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c00000000064d170)
Location: fs/fuse/dir.c:1130
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
c00000000064d170-c00000000064d1d8: fuse_perm_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffe000373932)
Location: fs/fuse/dir.c:1130
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
ffffffe000373932-ffffffe00037397a: fuse_perm_getattr (STB_LOCAL)
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
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141c930)
Location: fs/fuse/dir.c:1130
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
ffffffff8141c930-ffffffff8141c961: fuse_perm_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140d3b0)
Location: fs/fuse/dir.c:1130
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
ffffffff8140d3b0-ffffffff8140d3e1: fuse_perm_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81418ad0)
Location: fs/fuse/dir.c:1130
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
ffffffff81418ad0-ffffffff81418b01: fuse_perm_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fuse_perm_getattr(struct inode *inode, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8142f840)
Location: fs/fuse/dir.c:1130
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
ffffffff8142f840-ffffffff8142f871: fuse_perm_getattr (STB_LOCAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
