# Function: <code>sb_has_quota_suspended</code>

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
In fs/quota/dquot.c (ffffffff81271a33)
Location: include/linux/quotaops.h:129
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/quota/quota.c (0)
Location: include/linux/quotaops.h:129
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
Location: include/linux/quotaops.h:132
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff812a2537)
Location: include/linux/quotaops.h:132
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
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
Location: include/linux/quotaops.h:132
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff812b7f05)
Location: include/linux/quotaops.h:132
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
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
Location: include/linux/quotaops.h:133
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff812c5250)
Location: include/linux/quotaops.h:133
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
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
Location: include/linux/quotaops.h:129
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_resume
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_get_next_id
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_initialize_needed
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_writeback_dquots
```
```
In fs/quota/quota.c (ffffffff812e90f0)
Location: include/linux/quotaops.h:129
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
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
In fs/quota/dquot.c (ffffffff81310b17)
Location: include/linux/quotaops.h:132
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff81315cab)
Location: include/linux/quotaops.h:132
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
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
In fs/quota/dquot.c (ffffffff81327887)
Location: include/linux/quotaops.h:132
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff8132cc3d)
Location: include/linux/quotaops.h:132
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
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
In fs/quota/dquot.c (ffffffff8134f3db)
Location: include/linux/quotaops.h:132
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff81354cf7)
Location: include/linux/quotaops.h:132
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/dquot.c (ffffffff813676eb)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff8136d067)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/dquot.c (ffffffff813af3bb)
Location: include/linux/quotaops.h:144
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff813b4e59)
Location: include/linux/quotaops.h:144
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
In fs/quota/dquot.c (ffffffff813c09ab)
Location: include/linux/quotaops.h:141
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff813c688c)
Location: include/linux/quotaops.h:141
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
In fs/quota/dquot.c (ffffffff813c76bb)
Location: include/linux/quotaops.h:141
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff813cd50b)
Location: include/linux/quotaops.h:141
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
In fs/quota/dquot.c (ffffffff81cc7cdb)
Location: include/linux/quotaops.h:141
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff8141e7cb)
Location: include/linux/quotaops.h:141
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
In fs/quota/dquot.c (ffffffff81e7a8e1)
Location: include/linux/quotaops.h:141
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff814962ee)
Location: include/linux/quotaops.h:141
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
In fs/quota/dquot.c (ffffffff8206b7f5)
Location: include/linux/quotaops.h:143
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff8152a24e)
Location: include/linux/quotaops.h:143
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
In fs/quota/dquot.c (ffffffff820eb701)
Location: include/linux/quotaops.h:143
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff81562876)
Location: include/linux/quotaops.h:143
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
In mm/shmem_quota.c (ffffffff821bfcb8)
Location: include/linux/quotaops.h:143
Inline: True
Inline callers:
  - mm/shmem_quota.c:shmem_get_next_id
```
```
In fs/quota/dquot.c (ffffffff821c892b)
Location: include/linux/quotaops.h:143
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff81598f66)
Location: include/linux/quotaops.h:143
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
In fs/quota/dquot.c (ffff80001042f680)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffff800010436e60)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/dquot.c (c05f79f0)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (c05feafc)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/dquot.c (c0000000005412a4)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (c000000000548f40)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/dquot.c (ffffffe0002cb7c2)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffe0002d1280)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/dquot.c (ffffffff8135fccb)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff81365647)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/dquot.c (ffffffff8135096b)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff813562e7)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/dquot.c (ffffffff8135d79b)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff81363117)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
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
In fs/quota/dquot.c (ffffffff813707db)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqinfo
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_resume
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
In fs/quota/quota.c (ffffffff813767c7)
Location: include/linux/quotaops.h:142
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
```
</details>
</li>
</ul>

## Differences
