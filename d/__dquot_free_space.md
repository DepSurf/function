# Function: <code>__dquot_free_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81272e40)
Location: fs/quota/dquot.c:1800
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81272e40-ffffffff81273106: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8129da80)
Location: fs/quota/dquot.c:1808
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8129da80-ffffffff8129dd46: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812b33c0)
Location: fs/quota/dquot.c:1805
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff812b33c0-ffffffff812b3686: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812c3150)
Location: fs/quota/dquot.c:1831
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffff812c3150-ffffffff812c33d5: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812e6d30)
Location: fs/quota/dquot.c:1843
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff812e6d30-ffffffff812e6feb: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813113a0)
Location: fs/quota/dquot.c:1840
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffff813113a0-ffffffff81311637: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81328330)
Location: fs/quota/dquot.c:1840
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffff81328330-ffffffff813285c7: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8134fea0)
Location: fs/quota/dquot.c:1848
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffff8134fea0-ffffffff81350142: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813681b0)
Location: fs/quota/dquot.c:1850
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffff813681b0-ffffffff81368452: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b0450)
Location: fs/quota/dquot.c:1848
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813b0450-ffffffff813b074a: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c1a50)
Location: fs/quota/dquot.c:1849
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813c1a50-ffffffff813c1d4a: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c8430)
Location: fs/quota/dquot.c:1847
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813c8430-ffffffff813c872a: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81418ae0)
Location: fs/quota/dquot.c:1852
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffff81418ae0-ffffffff81418e61: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff814928a0)
Location: fs/quota/dquot.c:1862
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffff814928a0-ffffffff81492c75: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff815265a0)
Location: fs/quota/dquot.c:1862
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffff815265a0-ffffffff8152690e: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8155ea70)
Location: fs/quota/dquot.c:1920
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffff8155ea70-ffffffff8155edde: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81595160)
Location: fs/quota/dquot.c:1874
Inline: False
Direct callers:
  - mm/shmem.c:shmem_inode_unacct_blocks
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffff81595160-ffffffff815954ce: __dquot_free_space (STB_GLOBAL)
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
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffff8000104318f0)
Location: fs/quota/dquot.c:1850
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffff8000104318f0-ffff800010431c4c: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c05fbda0)
Location: fs/quota/dquot.c:1850
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
c05fbda0-c05fc188: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c000000000545d00)
Location: fs/quota/dquot.c:1850
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
c000000000545d00-c000000000546120: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffe0002cc450)
Location: fs/quota/dquot.c:1850
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffe0002cc450-ffffffe0002cc70e: __dquot_free_space (STB_GLOBAL)
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
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81360790)
Location: fs/quota/dquot.c:1850
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffff81360790-ffffffff81360a32: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81351430)
Location: fs/quota/dquot.c:1850
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffff81351430-ffffffff813516d2: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135e260)
Location: fs/quota/dquot.c:1850
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffff8135e260-ffffffff8135e502: __dquot_free_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __dquot_free_space(struct inode *inode, qsize_t number, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81373f20)
Location: fs/quota/dquot.c:1850
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_release_space
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_free_quota
```
**Symbols:**

```
ffffffff81373f20-ffffffff813741c7: __dquot_free_space (STB_GLOBAL)
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
