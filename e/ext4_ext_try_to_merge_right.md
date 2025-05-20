# Function: <code>ext4_ext_try_to_merge_right</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c4580)
Location: fs/ext4/extents.c:1761
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff812c4580-ffffffff812c470a: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f3dd0)
Location: fs/ext4/extents.c:1773
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff812f3dd0-ffffffff812f3f5c: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81309d80)
Location: fs/ext4/extents.c:1773
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff81309d80-ffffffff81309f0c: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812e84a0)
Location: fs/ext4/extents.c:1773
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff812e84a0-ffffffff812e85df: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130cf40)
Location: fs/ext4/extents.c:1773
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff8130cf40-ffffffff8130d07f: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133c140)
Location: fs/ext4/extents.c:1767
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff8133c140-ffffffff8133c26a: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813537f0)
Location: fs/ext4/extents.c:1767
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff813537f0-ffffffff8135391a: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:1784
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff8137d350-ffffffff8137d453: ext4_ext_try_to_merge_right (STB_LOCAL)
ffffffff81382616-ffffffff8138265a: ext4_ext_try_to_merge_right.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81395a50)
Location: fs/ext4/extents.c:1784
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff81395a50-ffffffff81395b75: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813dd9f0)
Location: fs/ext4/extents.c:1752
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
**Symbols:**

```
ffffffff813dd9f0-ffffffff813ddb18: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813ef2e0)
Location: fs/ext4/extents.c:1751
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
**Symbols:**

```
ffffffff813ef2e0-ffffffff813ef408: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f57a0)
Location: fs/ext4/extents.c:1754
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
**Symbols:**

```
ffffffff813f57a0-ffffffff813f58c8: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814474f0)
Location: fs/ext4/extents.c:1792
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
**Symbols:**

```
ffffffff814474f0-ffffffff8144761d: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c3bc0)
Location: fs/ext4/extents.c:1793
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
**Symbols:**

```
ffffffff814c3bc0-ffffffff814c3d01: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8155c070)
Location: fs/ext4/extents.c:1801
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
**Symbols:**

```
ffffffff8155c070-ffffffff8155c1b1: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81593e80)
Location: fs/ext4/extents.c:1801
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
**Symbols:**

```
ffffffff81593e80-ffffffff81593fbd: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815ccb70)
Location: fs/ext4/extents.c:1801
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
**Symbols:**

```
ffffffff815ccb70-ffffffff815cccad: ext4_ext_try_to_merge_right (STB_LOCAL)
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
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010468840)
Location: fs/ext4/extents.c:1784
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffff800010468840-ffff8000104689ac: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c06295b8)
Location: fs/ext4/extents.c:1784
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
c06295b8-c062973c: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000586d60)
Location: fs/ext4/extents.c:1784
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_try_to_merge
```
**Symbols:**

```
c000000000586d60-c000000000586f38: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f63c6)
Location: fs/ext4/extents.c:1784
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffe0002f63c6-ffffffe0002f651e: ext4_ext_try_to_merge_right (STB_LOCAL)
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
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138e030)
Location: fs/ext4/extents.c:1784
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff8138e030-ffffffff8138e155: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137eac0)
Location: fs/ext4/extents.c:1784
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff8137eac0-ffffffff8137ebe5: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138b990)
Location: fs/ext4/extents.c:1784
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff8138b990-ffffffff8138bab5: ext4_ext_try_to_merge_right (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_ext_try_to_merge_right(struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139f6e0)
Location: fs/ext4/extents.c:1784
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_extents
  - fs/ext4/extents.c:ext4_ext_shift_extents
```
**Symbols:**

```
ffffffff8139f6e0-ffffffff8139f805: ext4_ext_try_to_merge_right (STB_LOCAL)
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
