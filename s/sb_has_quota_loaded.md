# Function: <code>sb_has_quota_loaded</code>

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
In fs/quota/dquot.c (ffffffff81270a58)
Location: include/linux/quotaops.h:141
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:__dquot_transfer
```
```
In fs/quota/quota.c (ffffffff81276294)
Location: include/linux/quotaops.h:141
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
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
In fs/quota/dquot.c (ffffffff8129ce92)
Location: include/linux/quotaops.h:144
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff812a252a)
Location: include/linux/quotaops.h:144
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
```
In fs/ext4/super.c (ffffffff812e0cc8)
Location: include/linux/quotaops.h:144
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
In fs/quota/dquot.c (ffffffff812b2465)
Location: include/linux/quotaops.h:144
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff812b7ef1)
Location: include/linux/quotaops.h:144
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
```
In fs/ext4/super.c (ffffffff812f67f8)
Location: include/linux/quotaops.h:144
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
In fs/quota/dquot.c (ffffffff812bfa45)
Location: include/linux/quotaops.h:145
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff812c523c)
Location: include/linux/quotaops.h:145
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
```
In fs/ext4/super.c (ffffffff8132b118)
Location: include/linux/quotaops.h:145
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
In fs/quota/dquot.c (ffffffff812e34e5)
Location: include/linux/quotaops.h:141
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff812e90dc)
Location: include/linux/quotaops.h:141
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
```
In fs/ext4/super.c (ffffffff8134f588)
Location: include/linux/quotaops.h:141
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
In fs/quota/dquot.c (ffffffff81310b05)
Location: include/linux/quotaops.h:144
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff81315c99)
Location: include/linux/quotaops.h:144
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
```
In fs/ext4/super.c (ffffffff8137d9f8)
Location: include/linux/quotaops.h:144
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
In fs/quota/dquot.c (ffffffff81327875)
Location: include/linux/quotaops.h:144
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff8132cc2b)
Location: include/linux/quotaops.h:144
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
```
In fs/ext4/super.c (ffffffff813961f8)
Location: include/linux/quotaops.h:144
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
In fs/quota/dquot.c (ffffffff8134f3cc)
Location: include/linux/quotaops.h:144
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff81354ce0)
Location: include/linux/quotaops.h:144
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffffffff813c01a8)
Location: include/linux/quotaops.h:144
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
In fs/quota/dquot.c (ffffffff813676dc)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff8136d050)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffffffff813d9478)
Location: include/linux/quotaops.h:154
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
In fs/quota/dquot.c (ffffffff813af3ac)
Location: include/linux/quotaops.h:156
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff813b4e42)
Location: include/linux/quotaops.h:156
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/dquot.c (ffffffff813c099c)
Location: include/linux/quotaops.h:153
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff813c6875)
Location: include/linux/quotaops.h:153
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/dquot.c (ffffffff813c76ac)
Location: include/linux/quotaops.h:153
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff813cd4f5)
Location: include/linux/quotaops.h:153
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/dquot.c (ffffffff81417c22)
Location: include/linux/quotaops.h:153
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff8141e7b5)
Location: include/linux/quotaops.h:153
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
Location: include/linux/quotaops.h:153
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff814962df)
Location: include/linux/quotaops.h:153
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
Location: include/linux/quotaops.h:155
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff8152a23f)
Location: include/linux/quotaops.h:155
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
Location: include/linux/quotaops.h:155
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff81562868)
Location: include/linux/quotaops.h:155
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
Location: include/linux/quotaops.h:155
Inline: True
Inline callers:
  - mm/shmem_quota.c:shmem_get_next_id
```
```
In fs/quota/dquot.c (ffffffff81592058)
Location: include/linux/quotaops.h:155
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff81598f58)
Location: include/linux/quotaops.h:155
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/dquot.c (ffff80001042f668)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffff800010436e44)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffff8000104acbc0)
Location: include/linux/quotaops.h:154
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
In fs/quota/dquot.c (c05f79e0)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (c05feaec)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (c0675294)
Location: include/linux/quotaops.h:154
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
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (c000000000548f24)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (c0000000005e4d84)
Location: include/linux/quotaops.h:154
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
In fs/quota/dquot.c (ffffffe0002cb7ae)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffe0002d126c)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffffffe00032ff04)
Location: include/linux/quotaops.h:154
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
In fs/quota/dquot.c (ffffffff8135fcbc)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff81365630)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffffffff813d1a58)
Location: include/linux/quotaops.h:154
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
In fs/quota/dquot.c (ffffffff8135095c)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff813562d0)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffffffff813c24d8)
Location: include/linux/quotaops.h:154
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
In fs/quota/dquot.c (ffffffff8135d78c)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff81363100)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffffffff813ceee8)
Location: include/linux/quotaops.h:154
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
In fs/quota/dquot.c (ffffffff813707cc)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff813767b0)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
```
In fs/ext4/super.c (ffffffff813e4218)
Location: include/linux/quotaops.h:154
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_next_id
```
</details>
</li>
</ul>

## Differences
