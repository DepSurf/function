# Function: <code>fuse_get_root_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *fuse_get_root_inode(struct super_block *sb, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8131c050)
Location: fs/fuse/inode.c:644
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff8131c050-ffffffff8131c0be: fuse_get_root_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *fuse_get_root_inode(struct super_block *sb, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81350b30)
Location: fs/fuse/inode.c:654
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81350b30-ffffffff81350b9e: fuse_get_root_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *fuse_get_root_inode(struct super_block *sb, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81366490)
Location: fs/fuse/inode.c:655
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81366490-ffffffff813664fe: fuse_get_root_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *fuse_get_root_inode(struct super_block *sb, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8137ab50)
Location: fs/fuse/inode.c:648
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff8137ab50-ffffffff8137abc5: fuse_get_root_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *fuse_get_root_inode(struct super_block *sb, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8139f9f0)
Location: fs/fuse/inode.c:648
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff8139f9f0-ffffffff8139fa65: fuse_get_root_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *fuse_get_root_inode(struct super_block *sb, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813ced90)
Location: fs/fuse/inode.c:651
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff813ced90-ffffffff813cee05: fuse_get_root_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *fuse_get_root_inode(struct super_block *sb, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813e8200)
Location: fs/fuse/inode.c:654
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff813e8200-ffffffff813e8275: fuse_get_root_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *fuse_get_root_inode(struct super_block *sb, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814142d0)
Location: fs/fuse/inode.c:652
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff814142d0-ffffffff8141433f: fuse_get_root_inode (STB_LOCAL)
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
In fs/fuse/inode.c (ffffffff8142e630)
Location: fs/fuse/inode.c:654
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (ffffffff8147e30f)
Location: fs/fuse/inode.c:669
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (ffffffff8149966a)
Location: fs/fuse/inode.c:745
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (ffffffff8149e895)
Location: fs/fuse/inode.c:785
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (ffffffff814f6bc5)
Location: fs/fuse/inode.c:838
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (ffffffff81586a08)
Location: fs/fuse/inode.c:880
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (ffffffff8162cc80)
Location: fs/fuse/inode.c:893
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (ffffffff81664ead)
Location: fs/fuse/inode.c:893
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (ffffffff8169f1a6)
Location: fs/fuse/inode.c:969
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (ffff800010512cd8)
Location: fs/fuse/inode.c:654
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (c06cddec)
Location: fs/fuse/inode.c:654
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (c00000000065aad0)
Location: fs/fuse/inode.c:654
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (ffffffe00037cc72)
Location: fs/fuse/inode.c:654
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (ffffffff81426c10)
Location: fs/fuse/inode.c:654
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (ffffffff81417690)
Location: fs/fuse/inode.c:654
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (ffffffff81422db0)
Location: fs/fuse/inode.c:654
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
In fs/fuse/inode.c (ffffffff81439be0)
Location: fs/fuse/inode.c:654
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
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
</ul>
