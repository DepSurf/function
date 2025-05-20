# Function: <code>simple_positive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812336d0)
Location: include/linux/dcache.h:509
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:dcache_readdir
```
```
In fs/debugfs/inode.c (ffffffff8131d77c)
Location: include/linux/dcache.h:509
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8131f1b0)
Location: include/linux/dcache.h:509
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (ffffffff8133ff14)
Location: include/linux/dcache.h:509
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125be92)
Location: include/linux/dcache.h:483
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
```
```
In fs/debugfs/inode.c (ffffffff81352216)
Location: include/linux/dcache.h:483
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81354bc5)
Location: include/linux/dcache.h:483
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (ffffffff81375596)
Location: include/linux/dcache.h:483
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8126f442)
Location: include/linux/dcache.h:483
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
```
```
In fs/debugfs/inode.c (ffffffff813684c6)
Location: include/linux/dcache.h:483
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8136ae85)
Location: include/linux/dcache.h:483
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (ffffffff8138bec6)
Location: include/linux/dcache.h:483
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
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
In fs/libfs.c (ffffffff8127cc02)
Location: include/linux/dcache.h:489
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
```
```
In fs/configfs/inode.c (ffffffff812de296)
Location: include/linux/dcache.h:489
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/debugfs/inode.c (ffffffff8137cb2a)
Location: include/linux/dcache.h:489
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8137f4c3)
Location: include/linux/dcache.h:489
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In security/inode.c (ffffffff813a1c3e)
Location: include/linux/dcache.h:489
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff813d9118)
Location: include/linux/dcache.h:489
Inline: True
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
In fs/libfs.c (ffffffff8129f6a2)
Location: include/linux/dcache.h:490
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
```
```
In fs/configfs/inode.c (ffffffff81302bd6)
Location: include/linux/dcache.h:490
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/debugfs/inode.c (ffffffff813a1a46)
Location: include/linux/dcache.h:490
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff813a4513)
Location: include/linux/dcache.h:490
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
```
```
In security/inode.c (ffffffff813c7a3e)
Location: include/linux/dcache.h:490
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff813ff188)
Location: include/linux/dcache.h:490
Inline: True
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
In fs/libfs.c (ffffffff812c72b2)
Location: include/linux/dcache.h:491
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
```
```
In fs/configfs/inode.c (ffffffff81330b26)
Location: include/linux/dcache.h:491
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/debugfs/inode.c (ffffffff813d0d75)
Location: include/linux/dcache.h:491
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff813d38c3)
Location: include/linux/dcache.h:491
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (ffffffff813f7067)
Location: include/linux/dcache.h:491
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff81430118)
Location: include/linux/dcache.h:491
Inline: True
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
In fs/libfs.c (ffffffff812dc002)
Location: include/linux/dcache.h:488
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
```
```
In fs/configfs/inode.c (ffffffff81347f16)
Location: include/linux/dcache.h:488
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/debugfs/inode.c (ffffffff813eb4e5)
Location: include/linux/dcache.h:488
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff813edf53)
Location: include/linux/dcache.h:488
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (ffffffff81412b17)
Location: include/linux/dcache.h:488
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff8144cc68)
Location: include/linux/dcache.h:488
Inline: True
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
In fs/libfs.c (ffffffff812fa6a1)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
```
```
In fs/configfs/inode.c (ffffffff81370397)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/debugfs/inode.c (ffffffff81417565)
Location: include/linux/dcache.h:486
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8141a208)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (ffffffff8144050b)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffff8147a43b)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffffffff8130c7b1)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff81388887)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/debugfs/inode.c (ffffffff81431425)
Location: include/linux/dcache.h:486
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81434078)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (ffffffff81459ddb)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffff8149413b)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffffffff81346232)
Location: include/linux/dcache.h:493
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:find_next_child
  - fs/libfs.c:find_next_child
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff813d35c7)
Location: include/linux/dcache.h:493
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In security/inode.c (ffffffff814ad05b)
Location: include/linux/dcache.h:493
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffff814eb59b)
Location: include/linux/dcache.h:493
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffffffff81352722)
Location: include/linux/dcache.h:494
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:find_next_child
  - fs/libfs.c:find_next_child
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff813e5307)
Location: include/linux/dcache.h:494
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In security/inode.c (ffffffff814ca5ab)
Location: include/linux/dcache.h:494
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffff8150897b)
Location: include/linux/dcache.h:494
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffffffff81359442)
Location: include/linux/dcache.h:497
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff813ebf17)
Location: include/linux/dcache.h:497
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In security/inode.c (ffffffff814d0bdb)
Location: include/linux/dcache.h:497
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffff8150f4eb)
Location: include/linux/dcache.h:497
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffffffff813a78e2)
Location: include/linux/dcache.h:497
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff8143dcb7)
Location: include/linux/dcache.h:497
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In security/inode.c (ffffffff8152990b)
Location: include/linux/dcache.h:497
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffff8156d04b)
Location: include/linux/dcache.h:497
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffffffff8142a5b2)
Location: include/linux/dcache.h:487
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff814b95a6)
Location: include/linux/dcache.h:487
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In security/inode.c (ffffffff815bf12a)
Location: include/linux/dcache.h:487
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffff8160963a)
Location: include/linux/dcache.h:487
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffffffff814b7872)
Location: include/linux/dcache.h:487
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff81550d26)
Location: include/linux/dcache.h:487
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In security/inode.c (ffffffff8166b51a)
Location: include/linux/dcache.h:487
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffff816bb13a)
Location: include/linux/dcache.h:487
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffffffff814ec6c2)
Location: include/linux/dcache.h:487
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff81588a06)
Location: include/linux/dcache.h:487
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In security/inode.c (ffffffff816a3c7a)
Location: include/linux/dcache.h:487
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffff816f382a)
Location: include/linux/dcache.h:487
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffffffff815205fe)
Location: include/linux/dcache.h:494
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:offset_iterate_dir
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff815c15d6)
Location: include/linux/dcache.h:494
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In security/inode.c (ffffffff816e06da)
Location: include/linux/dcache.h:494
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffff817305ba)
Location: include/linux/dcache.h:494
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffff8000103c0f8c)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffff800010458b64)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/debugfs/inode.c (ffff800010516158)
Location: include/linux/dcache.h:486
Inline: True
```
```
In fs/tracefs/inode.c (ffff800010519b8c)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (ffff80001054612c)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffff80001058978c)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (c059c818)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (c061a8e0)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/debugfs/inode.c (c06d0ecc)
Location: include/linux/dcache.h:486
Inline: True
```
```
In fs/tracefs/inode.c (c06d4218)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (c06fbefc)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (c073a9a4)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (c0000000004c0558)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (c000000000573610)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/debugfs/inode.c (c00000000065ec58)
Location: include/linux/dcache.h:486
Inline: True
```
```
In fs/tracefs/inode.c (c0000000006632fc)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (c00000000069cb54)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (c0000000006fa7d4)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffffffe000281352)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffe0002e9b36)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/debugfs/inode.c (ffffffe00037f8c2)
Location: include/linux/dcache.h:486
Inline: True
```
```
In fs/tracefs/inode.c (ffffffe000382e28)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (ffffffe0003a1c34)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffe0003d867c)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffffffff81304d91)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff81380e67)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/debugfs/inode.c (ffffffff81429a05)
Location: include/linux/dcache.h:486
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8142c658)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (ffffffff814523bb)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffff8148c71b)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffffffff812f59b1)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff813718f7)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/debugfs/inode.c (ffffffff8141a485)
Location: include/linux/dcache.h:486
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8141d0d8)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (ffffffff81442e0b)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffff8147d13b)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffffffff81302b81)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff8137e937)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/debugfs/inode.c (ffffffff81425ba5)
Location: include/linux/dcache.h:486
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff814287f8)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (ffffffff8144e45b)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffff814887bb)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
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
In fs/libfs.c (ffffffff81312ce2)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/libfs.c:simple_empty
  - fs/libfs.c:scan_positives
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff81392447)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
```
In fs/debugfs/inode.c (ffffffff8143ca65)
Location: include/linux/dcache.h:486
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8143f6b8)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_remove_recursive
```
```
In security/inode.c (ffffffff8146582b)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/inode.c:securityfs_remove
```
```
In security/apparmor/apparmorfs.c (ffffffff814a02fb)
Location: include/linux/dcache.h:486
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aafs_remove
```
</details>
</li>
</ul>

## Differences
