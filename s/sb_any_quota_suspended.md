# Function: <code>sb_any_quota_suspended</code>

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
In fs/quota/dquot.c (0)
Location: include/linux/quotaops.h:135
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/quotaops.h:135
Inline: True
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
In fs/quota/dquot.c (ffffffff812a0fd6)
Location: include/linux/quotaops.h:138
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (0)
Location: include/linux/quotaops.h:138
Inline: True
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
In fs/quota/dquot.c (ffffffff812b6986)
Location: include/linux/quotaops.h:138
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (0)
Location: include/linux/quotaops.h:138
Inline: True
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
In fs/quota/dquot.c (ffffffff812c3c71)
Location: include/linux/quotaops.h:139
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (0)
Location: include/linux/quotaops.h:139
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
In fs/quota/dquot.c (ffffffff812e7ae1)
Location: include/linux/quotaops.h:135
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (0)
Location: include/linux/quotaops.h:135
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
In fs/quota/dquot.c (ffffffff81313832)
Location: include/linux/quotaops.h:138
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff81387d57)
Location: include/linux/quotaops.h:138
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (ffffffff8132a7c2)
Location: include/linux/quotaops.h:138
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff813a08f5)
Location: include/linux/quotaops.h:138
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (ffffffff81352392)
Location: include/linux/quotaops.h:138
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff813cb030)
Location: include/linux/quotaops.h:138
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (ffffffff8136a712)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff813e4524)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (ffffffff813b2996)
Location: include/linux/quotaops.h:150
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff81431973)
Location: include/linux/quotaops.h:150
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (ffffffff813c3f86)
Location: include/linux/quotaops.h:147
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff8144a526)
Location: include/linux/quotaops.h:147
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (ffffffff813cac76)
Location: include/linux/quotaops.h:147
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff8144fe9a)
Location: include/linux/quotaops.h:147
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (ffffffff8141ba26)
Location: include/linux/quotaops.h:147
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff814a6b15)
Location: include/linux/quotaops.h:147
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (ffffffff814942b6)
Location: include/linux/quotaops.h:147
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff8152b7de)
Location: include/linux/quotaops.h:147
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
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
In fs/quota/dquot.c (ffffffff81527f87)
Location: include/linux/quotaops.h:149
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff815ca80e)
Location: include/linux/quotaops.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
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
In fs/quota/dquot.c (ffffffff81560497)
Location: include/linux/quotaops.h:149
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff816024f5)
Location: include/linux/quotaops.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
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
In fs/quota/dquot.c (ffffffff81596b87)
Location: include/linux/quotaops.h:149
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff8163b2eb)
Location: include/linux/quotaops.h:149
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
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
In fs/quota/dquot.c (ffff8000104334c0)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffff8000104bdb30)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (c05fcd4c)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (c068127c)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (c000000000547148)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (c0000000005f3d98)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (ffffffe0002cef12)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffe000339662)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (ffffffff81362cf2)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff813dcb04)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (ffffffff81353992)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff813cd584)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (ffffffff813607c2)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff813d9fa4)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
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
In fs/quota/dquot.c (ffffffff813749e2)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff813ef284)
Location: include/linux/quotaops.h:148
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
```
</details>
</li>
</ul>

## Differences
