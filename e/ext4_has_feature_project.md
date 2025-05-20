# Function: <code>ext4_has_feature_project</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812d6f1a)
Location: fs/ext4/ext4.h:1757
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812dd333)
Location: fs/ext4/ext4.h:1757
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff812e5056)
Location: fs/ext4/ext4.h:1757
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff812fecbf)
Location: fs/ext4/ext4.h:1757
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812f524a)
Location: fs/ext4/ext4.h:1762
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812ff125)
Location: fs/ext4/ext4.h:1762
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff81308947)
Location: fs/ext4/ext4.h:1762
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81333a30)
Location: fs/ext4/ext4.h:1762
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813199a8)
Location: fs/ext4/ext4.h:1722
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813238ca)
Location: fs/ext4/ext4.h:1722
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff8132d4e3)
Location: fs/ext4/ext4.h:1722
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81357f40)
Location: fs/ext4/ext4.h:1722
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81347718)
Location: fs/ext4/ext4.h:1725
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81351df1)
Location: fs/ext4/ext4.h:1725
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff8135ba7d)
Location: fs/ext4/ext4.h:1725
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8138612e)
Location: fs/ext4/ext4.h:1725
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8135f8c8)
Location: fs/ext4/ext4.h:1738
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813698b6)
Location: fs/ext4/ext4.h:1738
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff81373df6)
Location: fs/ext4/ext4.h:1738
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8139ec6b)
Location: fs/ext4/ext4.h:1738
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81388a7e)
Location: fs/ext4/ext4.h:1758
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81392d37)
Location: fs/ext4/ext4.h:1758
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff8139e00b)
Location: fs/ext4/ext4.h:1758
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_fill_fsxattr
```
```
In fs/ext4/super.c (ffffffff813c8ec9)
Location: fs/ext4/ext4.h:1758
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813a13f0)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813ab6ad)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff813b68aa)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_fill_fsxattr
```
```
In fs/ext4/super.c (ffffffff813e2279)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813ed6d1)
Location: fs/ext4/ext4.h:1911
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813faada)
Location: fs/ext4/ext4.h:1911
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff814006ce)
Location: fs/ext4/ext4.h:1911
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_fill_fsxattr
```
```
In fs/ext4/super.c (ffffffff8142f5df)
Location: fs/ext4/ext4.h:1911
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813ffe1c)
Location: fs/ext4/ext4.h:2036
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8140d124)
Location: fs/ext4/ext4.h:2036
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff81412fde)
Location: fs/ext4/ext4.h:2036
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_fill_fsxattr
```
```
In fs/ext4/super.c (ffffffff814482ff)
Location: fs/ext4/ext4.h:2036
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff814061ce)
Location: fs/ext4/ext4.h:2045
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff814132c5)
Location: fs/ext4/ext4.h:2045
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff8141b640)
Location: fs/ext4/ext4.h:2045
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
  - fs/ext4/ioctl.c:ext4_fileattr_get
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/super.c (ffffffff8144db56)
Location: fs/ext4/ext4.h:2045
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81458a2e)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8146660b)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff8146e960)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
  - fs/ext4/ioctl.c:ext4_fileattr_get
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/super.c (ffffffff814a1c16)
Location: fs/ext4/ext4.h:2111
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff814d65f6)
Location: fs/ext4/ext4.h:2113
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff814e614c)
Location: fs/ext4/ext4.h:2113
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff814ef320)
Location: fs/ext4/ext4.h:2113
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
  - fs/ext4/ioctl.c:ext4_fileattr_get
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/super.c (ffffffff815278a7)
Location: fs/ext4/ext4.h:2113
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8156f3b0)
Location: fs/ext4/ext4.h:2123
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8157f8d4)
Location: fs/ext4/ext4.h:2123
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff81589570)
Location: fs/ext4/ext4.h:2123
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
  - fs/ext4/ioctl.c:ext4_fileattr_get
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/super.c (ffffffff815c5997)
Location: fs/ext4/ext4.h:2123
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff815a71ef)
Location: fs/ext4/ext4.h:2117
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff815b6dab)
Location: fs/ext4/ext4.h:2117
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff815bfd90)
Location: fs/ext4/ext4.h:2117
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
  - fs/ext4/ioctl.c:ext4_fileattr_get
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/super.c (ffffffff815fd747)
Location: fs/ext4/ext4.h:2117
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff815e0041)
Location: fs/ext4/ext4.h:2135
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff815efb4b)
Location: fs/ext4/ext4.h:2135
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff815f8b30)
Location: fs/ext4/ext4.h:2135
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
  - fs/ext4/ioctl.c:ext4_fileattr_get
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
```
```
In fs/ext4/super.c (ffffffff816361f7)
Location: fs/ext4/ext4.h:2135
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffff800010474c34)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffff80001047ff3c)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffff80001048c03c)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_fill_fsxattr
```
```
In fs/ext4/super.c (ffff8000104bb60c)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c063622c)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (c06412d0)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (c064e568)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_fill_fsxattr
```
```
In fs/ext4/super.c (c067edb8)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c000000000596418)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (c0000000005a3d3c)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (c0000000005b333c)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_fill_fsxattr
```
```
In fs/ext4/super.c (c0000000005f1460)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffe00030067a)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffe000308c50)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffe00031224c)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_fill_fsxattr
```
```
In fs/ext4/super.c (ffffffe000337996)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813999d0)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813a3c8d)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff813aee8a)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_fill_fsxattr
```
```
In fs/ext4/super.c (ffffffff813da859)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8138a460)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8139471d)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff8139f91a)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_fill_fsxattr
```
```
In fs/ext4/super.c (ffffffff813cb2d9)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81397230)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813a14ed)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff813ac6ea)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_fill_fsxattr
```
```
In fs/ext4/super.c (ffffffff813d7cd9)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813ab556)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813b60fe)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_projid
```
```
In fs/ext4/ioctl.c (ffffffff813c108a)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_fill_fsxattr
```
```
In fs/ext4/super.c (ffffffff813ecf99)
Location: fs/ext4/ext4.h:1814
Inline: True
Inline callers:
  - fs/ext4/super.c:parse_options
```
</details>
</li>
</ul>

## Differences
