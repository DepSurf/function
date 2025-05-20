# Function: <code>dquot_state_types</code>

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
Location: include/linux/quota.h:488
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/quota.h:488
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
In fs/quota/dquot.c (ffffffff812a0fd8)
Location: include/linux/quota.h:503
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (0)
Location: include/linux/quota.h:503
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
In fs/quota/dquot.c (ffffffff812b6988)
Location: include/linux/quota.h:503
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (0)
Location: include/linux/quota.h:503
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
In fs/quota/dquot.c (ffffffff812c3c73)
Location: include/linux/quota.h:505
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (0)
Location: include/linux/quota.h:505
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
In fs/quota/dquot.c (ffffffff812e7ae3)
Location: include/linux/quota.h:508
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (0)
Location: include/linux/quota.h:508
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
In fs/quota/dquot.c (ffffffff81312b06)
Location: include/linux/quota.h:507
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff81387d57)
Location: include/linux/quota.h:507
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (ffffffff81329a96)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff813a08f5)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (ffffffff81351676)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff813cb030)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (ffffffff813699f6)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff813e4524)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (ffffffff813b16fa)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff81431973)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (ffffffff813c2cfa)
Location: include/linux/quota.h:502
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff8144a526)
Location: include/linux/quota.h:502
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (ffffffff813c9e99)
Location: include/linux/quota.h:502
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff8144fe9a)
Location: include/linux/quota.h:502
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (ffffffff8141a839)
Location: include/linux/quota.h:502
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff814a6b15)
Location: include/linux/quota.h:502
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (ffffffff81490a1a)
Location: include/linux/quota.h:502
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff8152b7de)
Location: include/linux/quota.h:502
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
In fs/quota/dquot.c (ffffffff815245ca)
Location: include/linux/quota.h:502
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff815ca80e)
Location: include/linux/quota.h:502
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
In fs/quota/dquot.c (ffffffff8155c9ea)
Location: include/linux/quota.h:502
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff816024f5)
Location: include/linux/quota.h:502
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
In mm/shmem.c (ffffffff813e656d)
Location: include/linux/quota.h:504
Inline: True
Inline callers:
  - mm/shmem.c:shmem_reconfigure
```
```
In fs/quota/dquot.c (ffffffff815931ac)
Location: include/linux/quota.h:504
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff8163b2eb)
Location: include/linux/quota.h:504
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
In fs/quota/dquot.c (ffff800010431cc0)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffff8000104bdb30)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (c05f9ce4)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (c068127c)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (c000000000542e84)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (c0000000005f3d98)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (ffffffe0002ce000)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffe000339662)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (ffffffff81361fd6)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff813dcb04)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (ffffffff81352c76)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff813cd584)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (ffffffff8135faa6)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff813d9fa4)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
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
In fs/quota/dquot.c (ffffffff81372576)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:dquot_alloc_inode
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
```
In fs/ext4/super.c (ffffffff813ef284)
Location: include/linux/quota.h:501
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:set_qf_name
```
</details>
</li>
</ul>

## Differences
