# Function: <code>ext4_ioctl_setproject</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff812cf3ca)
Location: fs/ext4/ioctl.c:301
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff812e5204)
Location: fs/ext4/ioctl.c:307
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813090bd)
Location: fs/ext4/ioctl.c:309
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8132da19)
Location: fs/ext4/ioctl.c:318
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8135c0db)
Location: fs/ext4/ioctl.c:315
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8137449d)
Location: fs/ext4/ioctl.c:382
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8139e005)
Location: fs/ext4/ioctl.c:431
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813b68a4)
Location: fs/ext4/ioctl.c:431
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81400980)
Location: fs/ext4/ioctl.c:457
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81400980-ffffffff81400c0f: ext4_ioctl_setproject.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81413290)
Location: fs/ext4/ioctl.c:459
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff81413290-ffffffff8141351f: ext4_ioctl_setproject.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ioctl_setproject(struct inode *inode, __u32 projid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81419500)
Location: fs/ext4/ioctl.c:464
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
```
**Symbols:**

```
ffffffff81419500-ffffffff8141978f: ext4_ioctl_setproject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_ioctl_setproject(struct inode *inode, __u32 projid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8146c6f0)
Location: fs/ext4/ioctl.c:463
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
```
**Symbols:**

```
ffffffff8146c6f0-ffffffff8146c97f: ext4_ioctl_setproject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_ioctl_setproject(struct inode *inode, __u32 projid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff814ecd30)
Location: fs/ext4/ioctl.c:692
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
```
**Symbols:**

```
ffffffff814ecd30-ffffffff814ecfd0: ext4_ioctl_setproject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_ioctl_setproject(struct inode *inode, __u32 projid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81586b40)
Location: fs/ext4/ioctl.c:704
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
```
**Symbols:**

```
ffffffff81586b40-ffffffff81586df7: ext4_ioctl_setproject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_ioctl_setproject(struct inode *inode, __u32 projid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff815bd0a0)
Location: fs/ext4/ioctl.c:702
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
```
**Symbols:**

```
ffffffff815bd0a0-ffffffff815bd357: ext4_ioctl_setproject (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_ioctl_setproject(struct inode *inode, __u32 projid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff815f5e70)
Location: fs/ext4/ioctl.c:712
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
```
**Symbols:**

```
ffffffff815f5e70-ffffffff815f6115: ext4_ioctl_setproject (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffff80001048c028)
Location: fs/ext4/ioctl.c:431
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (c064e568)
Location: fs/ext4/ioctl.c:431
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (c0000000005b3328)
Location: fs/ext4/ioctl.c:431
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffe000312234)
Location: fs/ext4/ioctl.c:431
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813aee84)
Location: fs/ext4/ioctl.c:431
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8139f914)
Location: fs/ext4/ioctl.c:431
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813ac6e4)
Location: fs/ext4/ioctl.c:431
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813c1084)
Location: fs/ext4/ioctl.c:431
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
