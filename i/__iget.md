# Function: <code>__iget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812272e2)
Location: fs/inode.c:380
Inline: True
Inline callers:
  - fs/inode.c:find_inode
  - fs/inode.c:find_inode_fast
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffffffff81228bd0-ffffffff81228be2: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81250aa6)
Location: fs/inode.c:388
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffffffff812512d0-ffffffff812512e2: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81263b46)
Location: fs/inode.c:390
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffffffff812643d0-ffffffff812643e2: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8127147f)
Location: fs/inode.c:388
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffffffff81271d80-ffffffff81271d92: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81293da1)
Location: fs/inode.c:388
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffffffff812946a0-ffffffff812946b2: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ba3b4)
Location: fs/inode.c:394
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffffffff812ba7b0-ffffffff812ba7c2: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cf700)
Location: fs/inode.c:394
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffffffff812cfaf0-ffffffff812cfb02: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ec651)
Location: fs/inode.c:407
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffffffff812eca40-ffffffff812eca52: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fe1a1)
Location: fs/inode.c:411
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffffffff812fe590-ffffffff812fe5a2: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813374e1)
Location: fs/inode.c:412
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:add_dquot_ref
```
**Symbols:**

```
ffffffff81336810-ffffffff81336822: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81342e21)
Location: fs/inode.c:413
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:add_dquot_ref
```
**Symbols:**

```
ffffffff81342170-ffffffff81342182: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813490d1)
Location: fs/inode.c:413
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
```
**Symbols:**

```
ffffffff81348570-ffffffff81348582: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81396e1b)
Location: fs/inode.c:417
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - block/bdev.c:iterate_bdevs
```
**Symbols:**

```
ffffffff81396240-ffffffff81396252: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81418afb)
Location: fs/inode.c:441
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_prepare_wbs_switch
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - block/bdev.c:sync_bdevs
```
**Symbols:**

```
ffffffff81418ea0-ffffffff81418eb8: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a441b)
Location: fs/inode.c:440
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_prepare_wbs_switch
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - block/bdev.c:sync_bdevs
```
**Symbols:**

```
ffffffff814a47b0-ffffffff814a47c8: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d9592)
Location: fs/inode.c:440
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_prepare_wbs_switch
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - block/bdev.c:sync_bdevs
```
**Symbols:**

```
ffffffff814d9940-ffffffff814d9958: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8150bd42)
Location: fs/inode.c:441
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_prepare_wbs_switch
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - block/bdev.c:sync_bdevs
```
**Symbols:**

```
ffffffff8150c0f0-ffffffff8150c108: __iget (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103aea08)
Location: fs/inode.c:411
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffff8000103af340-ffff8000103af38c: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058e888)
Location: fs/inode.c:411
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_fast
  - fs/inode.c:find_inode
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
c058f180-c058f1b4: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a9ee0)
Location: fs/inode.c:411
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
c0000000004aade0-c0000000004aae00: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe0002737f2)
Location: fs/inode.c:411
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffffffe000273e22-ffffffe000273e4c: __iget (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f6781)
Location: fs/inode.c:411
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffffffff812f6b70-ffffffff812f6b82: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e73a1)
Location: fs/inode.c:411
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffffffff812e7790-ffffffff812e77a2: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4591)
Location: fs/inode.c:411
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffffffff812f4980-ffffffff812f4992: __iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __iget(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813054e1)
Location: fs/inode.c:411
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:igrab
  - fs/inode.c:inode_lru_isolate
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:iterate_bdevs
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/crypto/keyring.c:do_remove_key
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/quota/dquot.c:vfs_load_quota_inode
```
**Symbols:**

```
ffffffff81305b20-ffffffff81305b32: __iget (STB_GLOBAL)
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
