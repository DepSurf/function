# Function: <code>ext4_expand_extra_isize</code>

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
In fs/ext4/inode.c (ffffffff8129b957)
Location: fs/ext4/inode.c:5060
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff812c9377)
Location: fs/ext4/inode.c:5401
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff812def7e)
Location: fs/ext4/inode.c:5545
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81302ef0)
Location: fs/ext4/inode.c:5782
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81302ef0-ffffffff813030a4: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813278e0)
Location: fs/ext4/inode.c:5835
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813278e0-ffffffff81327a94: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81355590)
Location: fs/ext4/inode.c:5931
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81355590-ffffffff81355737: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136d8c0)
Location: fs/ext4/inode.c:5984
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8136d8c0-ffffffff8136da67: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81396ed0)
Location: fs/ext4/inode.c:6006
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81396ed0-ffffffff81397082: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813af900)
Location: fs/ext4/inode.c:6035
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813af900-ffffffff813afabf: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fb940)
Location: fs/ext4/inode.c:5755
Inline: False
```
**Symbols:**

```
ffffffff813fb940-ffffffff813fbb04: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140e0b0)
Location: fs/ext4/inode.c:5848
Inline: False
```
**Symbols:**

```
ffffffff8140e0b0-ffffffff8140e248: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81414270)
Location: fs/ext4/inode.c:5845
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
**Symbols:**

```
ffffffff81414270-ffffffff8141440b: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814675e0)
Location: fs/ext4/inode.c:5785
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
**Symbols:**

```
ffffffff814675e0-ffffffff81467785: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e7220)
Location: fs/ext4/inode.c:5863
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
**Symbols:**

```
ffffffff814e7220-ffffffff814e73f5: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81580bd0)
Location: fs/ext4/inode.c:6007
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
**Symbols:**

```
ffffffff81580bd0-ffffffff81580da9: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b8180)
Location: fs/ext4/inode.c:5819
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
**Symbols:**

```
ffffffff815b8180-ffffffff815b835d: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815f0f20)
Location: fs/ext4/inode.c:5839
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
**Symbols:**

```
ffffffff815f0f20-ffffffff815f10fd: ext4_expand_extra_isize (STB_GLOBAL)
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
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010484390)
Location: fs/ext4/inode.c:6035
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffff800010484390-ffff800010484590: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0645990)
Location: fs/ext4/inode.c:6035
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
c0645990-c0645b54: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a9570)
Location: fs/ext4/inode.c:6035
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
c0000000005a9570-c0000000005a9834: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030c83e)
Location: fs/ext4/inode.c:6035
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffe00030c83e-ffffffe00030c9b4: ext4_expand_extra_isize (STB_GLOBAL)
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
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a7ee0)
Location: fs/ext4/inode.c:6035
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813a7ee0-ffffffff813a809f: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81398970)
Location: fs/ext4/inode.c:6035
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81398970-ffffffff81398b2f: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a5740)
Location: fs/ext4/inode.c:6035
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813a5740-ffffffff813a58ff: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b9e80)
Location: fs/ext4/inode.c:6035
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813b9e80-ffffffff813ba03f: ext4_expand_extra_isize (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
