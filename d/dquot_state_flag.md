# Function: <code>dquot_state_flag</code>

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
In fs/quota/dquot.c (ffffffff81271a1a)
Location: include/linux/quota.h:477
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/quota/quota.c (0)
Location: include/linux/quota.h:477
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
In fs/quota/dquot.c (ffffffff8129ce9e)
Location: include/linux/quota.h:492
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_disable
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff812a2537)
Location: include/linux/quota.h:492
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
```
In fs/ext4/super.c (ffffffff812e0cc8)
Location: include/linux/quota.h:492
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (ffffffff812b247b)
Location: include/linux/quota.h:492
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_disable
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff812b7f05)
Location: include/linux/quota.h:492
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
```
In fs/ext4/super.c (ffffffff812f67f8)
Location: include/linux/quota.h:492
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (ffffffff812bfa57)
Location: include/linux/quota.h:494
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_idq
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff812c5250)
Location: include/linux/quota.h:494
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
```
In fs/ext4/super.c (ffffffff8132b118)
Location: include/linux/quota.h:494
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (ffffffff812e34f7)
Location: include/linux/quota.h:497
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff812e90f0)
Location: include/linux/quota.h:497
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
```
In fs/ext4/super.c (ffffffff8134f588)
Location: include/linux/quota.h:497
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (ffffffff81310b0c)
Location: include/linux/quota.h:496
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff81315ca0)
Location: include/linux/quota.h:496
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:kernel_quotactl
```
```
In fs/ext4/super.c (ffffffff8137d9f8)
Location: include/linux/quota.h:496
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (ffffffff8132787c)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff8132cc32)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:kernel_quotactl
```
```
In fs/ext4/super.c (ffffffff813961f8)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (ffffffff8134f3d2)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff81354ce7)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffffffff813c01a8)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (ffffffff813676e2)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff8136d057)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffffffff813d9478)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (ffffffff813af3b2)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff813b4e49)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (0)
Location: include/linux/quota.h:490
Inline: True
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
In fs/quota/dquot.c (ffffffff813c09a2)
Location: include/linux/quota.h:491
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff813c687c)
Location: include/linux/quota.h:491
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (0)
Location: include/linux/quota.h:491
Inline: True
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
In fs/quota/dquot.c (ffffffff813c76b2)
Location: include/linux/quota.h:491
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff813cd4fc)
Location: include/linux/quota.h:491
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (0)
Location: include/linux/quota.h:491
Inline: True
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
In fs/quota/dquot.c (ffffffff81417c2d)
Location: include/linux/quota.h:491
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff8141e7bc)
Location: include/linux/quota.h:491
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (0)
Location: include/linux/quota.h:491
Inline: True
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
In fs/quota/dquot.c (ffffffff8148f95d)
Location: include/linux/quota.h:491
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff814962df)
Location: include/linux/quota.h:491
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (0)
Location: include/linux/quota.h:491
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
In fs/quota/dquot.c (ffffffff8152345d)
Location: include/linux/quota.h:491
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff8152a23f)
Location: include/linux/quota.h:491
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (0)
Location: include/linux/quota.h:491
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
In fs/quota/dquot.c (ffffffff8155b8e8)
Location: include/linux/quota.h:491
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff81562868)
Location: include/linux/quota.h:491
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (0)
Location: include/linux/quota.h:491
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
In mm/shmem_quota.c (ffffffff81408f0c)
Location: include/linux/quota.h:493
Inline: True
Inline callers:
  - mm/shmem_quota.c:shmem_get_next_id
  - mm/shmem_quota.c:shmem_get_next_id
```
```
In fs/quota/dquot.c (ffffffff81592058)
Location: include/linux/quota.h:493
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff81598f58)
Location: include/linux/quota.h:493
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (0)
Location: include/linux/quota.h:493
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
In fs/quota/dquot.c (ffff80001042f66c)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffff800010436e48)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffff8000104acbc0)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (c05f79e4)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (c05feaf0)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (c0675294)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (c00000000054127c)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (c000000000548f28)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (c0000000005e4d84)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (ffffffe0002cb7b2)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffe0002d1270)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffffffe00032ff04)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (ffffffff8135fcc2)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff81365637)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffffffff813d1a58)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (ffffffff81350962)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff813562d7)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffffffff813c24d8)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (ffffffff8135d792)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff81363107)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffffffff813ceee8)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
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
In fs/quota/dquot.c (ffffffff813707d2)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff813767b7)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffffffff813e4218)
Location: include/linux/quota.h:490
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
```
</details>
</li>
</ul>

## Differences
