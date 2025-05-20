# Function: <code>__dquot_alloc_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81274460)
Location: fs/quota/dquot.c:1646
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81274460-ffffffff812746a8: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812a08e0)
Location: fs/quota/dquot.c:1654
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff812a08e0-ffffffff812a0b20: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812b6290)
Location: fs/quota/dquot.c:1651
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff812b6290-ffffffff812b64d0: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812c3550)
Location: fs/quota/dquot.c:1677
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff812c3550-ffffffff812c3778: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812e71a0)
Location: fs/quota/dquot.c:1642
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff812e71a0-ffffffff812e7431: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813117e0)
Location: fs/quota/dquot.c:1639
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff813117e0-ffffffff81311a47: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813297b0)
Location: fs/quota/dquot.c:1639
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff813297b0-ffffffff81329a17: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81351330)
Location: fs/quota/dquot.c:1649
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81351330-ffffffff813515fb: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813696b0)
Location: fs/quota/dquot.c:1651
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff813696b0-ffffffff8136997b: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b1f10)
Location: fs/quota/dquot.c:1649
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff813b1f10-ffffffff813b2262: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c34f0)
Location: fs/quota/dquot.c:1650
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff813c34f0-ffffffff813c3842: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c9ad0)
Location: fs/quota/dquot.c:1648
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff813c9ad0-ffffffff813c9e22: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8141a400)
Location: fs/quota/dquot.c:1653
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff8141a400-ffffffff8141a7c8: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81493420)
Location: fs/quota/dquot.c:1663
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81493420-ffffffff8149381a: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff815270f0)
Location: fs/quota/dquot.c:1663
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff815270f0-ffffffff815274ea: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8155f5c0)
Location: fs/quota/dquot.c:1721
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff8155f5c0-ffffffff8155f9b2: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81595cb0)
Location: fs/quota/dquot.c:1675
Inline: False
Direct callers:
  - mm/shmem.c:shmem_inode_acct_blocks
  - mm/shmem.c:shmem_inode_acct_blocks
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81595cb0-ffffffff815960a2: __dquot_alloc_space (STB_GLOBAL)
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
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffff8000104329f0)
Location: fs/quota/dquot.c:1651
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffff8000104329f0-ffff800010432d98: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c05fc188)
Location: fs/quota/dquot.c:1651
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
c05fc188-c05fc56c: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c000000000546430)
Location: fs/quota/dquot.c:1651
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
c000000000546430-c0000000005468b0: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffe0002cdc7a)
Location: fs/quota/dquot.c:1651
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffe0002cdc7a-ffffffe0002cdf9a: __dquot_alloc_space (STB_GLOBAL)
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
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81361c90)
Location: fs/quota/dquot.c:1651
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81361c90-ffffffff81361f5b: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81352930)
Location: fs/quota/dquot.c:1651
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81352930-ffffffff81352bfb: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135f760)
Location: fs/quota/dquot.c:1651
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff8135f760-ffffffff8135fa2b: __dquot_alloc_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __dquot_alloc_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81374ad0)
Location: fs/quota/dquot.c:1651
Inline: False
Direct callers:
  - fs/ext4/balloc.c:ext4_new_meta_blocks
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81374ad0-ffffffff81374d9e: __dquot_alloc_space (STB_GLOBAL)
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
