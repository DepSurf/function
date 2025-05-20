# Function: <code>sb_has_quota_limits_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8127138e)
Location: include/linux/quotaops.h:123
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
In fs/quota/dquot.c (ffffffff8129d198)
Location: include/linux/quotaops.h:126
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_disable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:check_bdq
```
```
In fs/ext4/super.c (0)
Location: include/linux/quotaops.h:126
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
In fs/quota/dquot.c (ffffffff812b2ae1)
Location: include/linux/quotaops.h:126
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_disable
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:check_bdq
```
```
In fs/ext4/super.c (0)
Location: include/linux/quotaops.h:126
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
In fs/quota/dquot.c (ffffffff812c2640)
Location: include/linux/quotaops.h:127
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_idq
```
```
In fs/ext4/super.c (0)
Location: include/linux/quotaops.h:127
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
In fs/quota/dquot.c (ffffffff812e6500)
Location: include/linux/quotaops.h:123
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (0)
Location: include/linux/quotaops.h:123
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
In fs/quota/dquot.c (ffffffff81314380)
Location: include/linux/quotaops.h:126
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff813834c9)
Location: include/linux/quotaops.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff8132b310)
Location: include/linux/quotaops.h:126
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff8139bee9)
Location: include/linux/quotaops.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff8134f1c3)
Location: include/linux/quotaops.h:126
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff813c4a37)
Location: include/linux/quotaops.h:126
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff813674d3)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff813dddb7)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff813af1a3)
Location: include/linux/quotaops.h:138
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff8142771b)
Location: include/linux/quotaops.h:138
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff813c0793)
Location: include/linux/quotaops.h:135
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff8143f51d)
Location: include/linux/quotaops.h:135
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff813c74a3)
Location: include/linux/quotaops.h:135
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff8144a584)
Location: include/linux/quotaops.h:135
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff814179d0)
Location: include/linux/quotaops.h:135
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff8149e04a)
Location: include/linux/quotaops.h:135
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff8148f5f5)
Location: include/linux/quotaops.h:135
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff8152264a)
Location: include/linux/quotaops.h:135
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff815230b5)
Location: include/linux/quotaops.h:137
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff815bf46a)
Location: include/linux/quotaops.h:137
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff8155b655)
Location: include/linux/quotaops.h:137
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff815f662a)
Location: include/linux/quotaops.h:137
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff81591dc5)
Location: include/linux/quotaops.h:137
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff8162ef2a)
Location: include/linux/quotaops.h:137
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffff80001042f148)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffff8000104b83f8)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (c05f8584)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (c0675a10)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (c000000000541150)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (c0000000005e56fc)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffe0002cb57a)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffe0003316ac)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff8135fab3)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff813d6397)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff81350753)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff813c6e17)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff8135d583)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff813d3827)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
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
In fs/quota/dquot.c (ffffffff81370cf3)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_get_state
  - fs/quota/dquot.c:dquot_enable
  - fs/quota/dquot.c:info_idq_free
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
```
```
In fs/ext4/super.c (ffffffff813e4827)
Location: include/linux/quotaops.h:136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_statfs
```
</details>
</li>
</ul>

## Differences
