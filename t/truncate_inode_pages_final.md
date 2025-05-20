# Function: <code>truncate_inode_pages_final</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8119f500)
Location: mm/truncate.c:403
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_evict_inode
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/debugfs/inode.c:debugfs_evict_inode
```
**Symbols:**

```
ffffffff8119f500-ffffffff8119f552: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811b5230)
Location: mm/truncate.c:414
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_evict_inode
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/debugfs/inode.c:debugfs_evict_inode
```
**Symbols:**

```
ffffffff811b5230-ffffffff811b5282: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811c5840)
Location: mm/truncate.c:443
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_evict_inode
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/debugfs/inode.c:debugfs_evict_inode
```
**Symbols:**

```
ffffffff811c5840-ffffffff811c5892: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811cdb50)
Location: mm/truncate.c:442
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_evict_inode
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/debugfs/inode.c:debugfs_evict_inode
  - security/inode.c:securityfs_evict_inode
  - security/apparmor/apparmorfs.c:aafs_evict_inode
```
**Symbols:**

```
ffffffff811cdb50-ffffffff811cdba3: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811e2f00)
Location: mm/truncate.c:495
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_evict_inode
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/debugfs/inode.c:debugfs_evict_inode
  - security/inode.c:securityfs_evict_inode
  - security/apparmor/apparmorfs.c:aafs_evict_inode
```
**Symbols:**

```
ffffffff811e2f00-ffffffff811e2f51: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81204560)
Location: mm/truncate.c:491
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_evict_inode
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/debugfs/inode.c:debugfs_evict_inode
  - security/inode.c:securityfs_evict_inode
  - security/apparmor/apparmorfs.c:aafs_evict_inode
```
**Symbols:**

```
ffffffff81204560-ffffffff812045b6: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81216f20)
Location: mm/truncate.c:488
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_evict_inode
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/debugfs/inode.c:debugfs_evict_inode
  - security/inode.c:securityfs_evict_inode
  - security/apparmor/apparmorfs.c:aafs_evict_inode
```
**Symbols:**

```
ffffffff81216f20-ffffffff81216f73: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81226880)
Location: mm/truncate.c:489
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
```
**Symbols:**

```
ffffffff81226880-ffffffff812268d5: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812346f0)
Location: mm/truncate.c:489
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
```
**Symbols:**

```
ffffffff812346f0-ffffffff81234745: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81261cb0)
Location: mm/truncate.c:489
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81261cb0-ffffffff81261d05: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126bfb0)
Location: mm/truncate.c:489
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff8126bfb0-ffffffff8126c005: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81270eb0)
Location: mm/truncate.c:437
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81270eb0-ffffffff81270f00: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812ade70)
Location: mm/truncate.c:438
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - block/bdev.c:bdev_evict_inode
```
**Symbols:**

```
ffffffff812ade70-ffffffff812adec3: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81308a60)
Location: mm/truncate.c:465
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - block/bdev.c:bdev_evict_inode
```
**Symbols:**

```
ffffffff81308a60-ffffffff81308ab2: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81372860)
Location: mm/truncate.c:461
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - block/bdev.c:bdev_evict_inode
```
**Symbols:**

```
ffffffff81372860-ffffffff813728b2: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813a49d0)
Location: mm/truncate.c:462
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - block/bdev.c:bdev_evict_inode
```
**Symbols:**

```
ffffffff813a49d0-ffffffff813a4a1f: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813ce530)
Location: mm/truncate.c:452
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
  - block/bdev.c:bdev_evict_inode
```
**Symbols:**

```
ffffffff813ce530-ffffffff813ce57f: truncate_inode_pages_final (STB_GLOBAL)
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
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffff8000102c4c70)
Location: mm/truncate.c:489
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
```
**Symbols:**

```
ffff8000102c4c70-ffff8000102c4d70: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c04ef534)
Location: mm/truncate.c:489
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
```
**Symbols:**

```
c04ef534-c04ef5bc: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c00000000037f3e0)
Location: mm/truncate.c:489
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
```
**Symbols:**

```
c00000000037f3e0-c00000000037f4c0: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffe0001e53e0)
Location: mm/truncate.c:489
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
```
**Symbols:**

```
ffffffe0001e53e0-ffffffe0001e5476: truncate_inode_pages_final (STB_GLOBAL)
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
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122cd40)
Location: mm/truncate.c:489
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
```
**Symbols:**

```
ffffffff8122cd40-ffffffff8122cd95: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8121fe20)
Location: mm/truncate.c:489
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
```
**Symbols:**

```
ffffffff8121fe20-ffffffff8121fe6f: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122aae0)
Location: mm/truncate.c:489
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
```
**Symbols:**

```
ffffffff8122aae0-ffffffff8122ab35: truncate_inode_pages_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void truncate_inode_pages_final(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81239ef0)
Location: mm/truncate.c:489
Inline: False
Direct callers:
  - fs/inode.c:evict
  - fs/block_dev.c:bdev_evict_inode
  - fs/proc/inode.c:proc_evict_inode
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/fat/inode.c:fat_evict_inode
  - fs/ecryptfs/super.c:ecryptfs_evict_inode
```
**Symbols:**

```
ffffffff81239ef0-ffffffff81239f3c: truncate_inode_pages_final (STB_GLOBAL)
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
