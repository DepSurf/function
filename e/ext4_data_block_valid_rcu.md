# Function: <code>ext4_data_block_valid_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff8138f2a0)
Location: fs/ext4/block_validity.c:155
Inline: True
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff8138f2a0-ffffffff8138f31a: ext4_data_block_valid_rcu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff813dac35)
Location: fs/ext4/block_validity.c:152
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_inode_block_valid
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (ffff800010461ae8)
Location: fs/ext4/block_validity.c:155
Inline: True
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffff800010461ae8-ffff800010461bac: ext4_data_block_valid_rcu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_data_block_valid_rcu(struct ext4_sb_info *sbi, struct ext4_system_blocks *system_blks, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (c0621d74)
Location: fs/ext4/block_validity.c:155
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
c0621d74-c0621e54: ext4_data_block_valid_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_data_block_valid_rcu(struct ext4_sb_info *sbi, struct ext4_system_blocks *system_blks, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (c00000000057df50)
Location: fs/ext4/block_validity.c:155
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
c00000000057df50-c00000000057dffc: ext4_data_block_valid_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_data_block_valid_rcu(struct ext4_sb_info *sbi, struct ext4_system_blocks *system_blks, ext4_fsblk_t start_blk, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffe0002f0858)
Location: fs/ext4/block_validity.c:155
Inline: False
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffe0002f0858-ffffffe0002f08f0: ext4_data_block_valid_rcu (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81387880)
Location: fs/ext4/block_validity.c:155
Inline: True
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff81387880-ffffffff813878fa: ext4_data_block_valid_rcu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81378310)
Location: fs/ext4/block_validity.c:155
Inline: True
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff81378310-ffffffff8137838a: ext4_data_block_valid_rcu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81385350)
Location: fs/ext4/block_validity.c:155
Inline: True
Direct callers:
  - fs/ext4/block_validity.c:ext4_check_blockref
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff81385350-ffffffff813853ca: ext4_data_block_valid_rcu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81398ed0)
Location: fs/ext4/block_validity.c:155
Inline: True
Direct callers:
  - fs/ext4/block_validity.c:ext4_data_block_valid
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
**Symbols:**

```
ffffffff81398ed0-ffffffff81398f4a: ext4_data_block_valid_rcu.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
