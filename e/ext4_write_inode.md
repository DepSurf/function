# Function: <code>ext4_write_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8129a810)
Location: fs/ext4/inode.c:4621
Inline: False
```
**Symbols:**

```
ffffffff8129a810-ffffffff8129a963: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c8700)
Location: fs/ext4/inode.c:4960
Inline: False
```
**Symbols:**

```
ffffffff812c8700-ffffffff812c8853: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812de2d0)
Location: fs/ext4/inode.c:5101
Inline: False
```
**Symbols:**

```
ffffffff812de2d0-ffffffff812de423: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81302360)
Location: fs/ext4/inode.c:5208
Inline: False
```
**Symbols:**

```
ffffffff81302360-ffffffff813024a0: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81326cf0)
Location: fs/ext4/inode.c:5265
Inline: False
```
**Symbols:**

```
ffffffff81326cf0-ffffffff81326e30: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5355
Inline: False
```
**Symbols:**

```
ffffffff8135b004-ffffffff8135b013: ext4_write_inode.cold.86 (STB_LOCAL)
ffffffff81355130-ffffffff81355252: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5402
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff813732c4-ffffffff813732ce: ext4_write_inode.cold.88 (STB_LOCAL)
ffffffff8136d440-ffffffff8136d58d: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5415
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff8139c72b-ffffffff8139c73b: ext4_write_inode.cold (STB_LOCAL)
ffffffff81396a30-ffffffff81396b8b: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5421
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff813b51e6-ffffffff813b51f6: ext4_write_inode.cold (STB_LOCAL)
ffffffff813af460-ffffffff813af5bb: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5136
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff81400636-ffffffff81400646: ext4_write_inode.cold (STB_LOCAL)
ffffffff813fb4d0-ffffffff813fb631: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5202
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff81bec447-ffffffff81bec457: ext4_write_inode.cold (STB_LOCAL)
ffffffff8140dc00-ffffffff8140dd9d: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5197
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff81bde4f2-ffffffff81bde502: ext4_write_inode.cold (STB_LOCAL)
ffffffff81413dc0-ffffffff81413f5f: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5137
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff81ccae8d-ffffffff81ccae9d: ext4_write_inode.cold (STB_LOCAL)
ffffffff81467140-ffffffff814672a1: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5217
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff81e7dd29-ffffffff81e7dd33: ext4_write_inode.cold (STB_LOCAL)
ffffffff814e6cf0-ffffffff814e6e7e: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81580500)
Location: fs/ext4/inode.c:5318
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff81580500-ffffffff81580695: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b7ac0)
Location: fs/ext4/inode.c:5130
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff815b7ac0-ffffffff815b7c55: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815f0850)
Location: fs/ext4/inode.c:5152
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff815f0850-ffffffff815f09de: ext4_write_inode (STB_GLOBAL)
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
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010483d80)
Location: fs/ext4/inode.c:5421
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffff800010483d80-ffff800010483eec: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c064538c)
Location: fs/ext4/inode.c:5421
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
c064538c-c0645558: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a8e30)
Location: fs/ext4/inode.c:5421
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
c0000000005a8e30-c0000000005a9060: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030c35c)
Location: fs/ext4/inode.c:5421
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffe00030c35c-ffffffe00030c494: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5421
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff813ad7c6-ffffffff813ad7d6: ext4_write_inode.cold (STB_LOCAL)
ffffffff813a7a40-ffffffff813a7b9b: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5421
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff8139e256-ffffffff8139e266: ext4_write_inode.cold (STB_LOCAL)
ffffffff813984d0-ffffffff8139862b: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5421
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff813ab026-ffffffff813ab036: ext4_write_inode.cold (STB_LOCAL)
ffffffff813a52a0-ffffffff813a53fb: ext4_write_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ext4_write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5421
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_nfs_commit_metadata
```
**Symbols:**

```
ffffffff813bf976-ffffffff813bf986: ext4_write_inode.cold (STB_LOCAL)
ffffffff813b99e0-ffffffff813b9b3b: ext4_write_inode (STB_GLOBAL)
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
