# Function: <code>ext4_superblock_csum</code>

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
In fs/ext4/super.c (ffffffff812b79f0)
Location: fs/ext4/super.c:124
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_superblock_csum_set
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812eb230)
Location: fs/ext4/super.c:153
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813010f2)
Location: fs/ext4/super.c:155
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81335fb4)
Location: fs/ext4/super.c:157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8135d091)
Location: fs/ext4/super.c:157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81386975)
Location: fs/ext4/super.c:157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8139f475)
Location: fs/ext4/super.c:180
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c91c3)
Location: fs/ext4/super.c:181
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e2571)
Location: fs/ext4/super.c:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
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
In fs/ext4/super.c (ffffffff8142e62a)
Location: fs/ext4/super.c:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814449d4)
Location: fs/ext4/super.c:265
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144a25e)
Location: fs/ext4/super.c:265
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814a0ba4)
Location: fs/ext4/super.c:262
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
__le32 ext4_superblock_csum(struct super_block *sb, struct ext4_super_block *es);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81527687)
Location: fs/ext4/super.c:281
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
Direct callers:
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_backup_sb
```
**Symbols:**

```
ffffffff81524a70-ffffffff81524af1: ext4_superblock_csum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
__le32 ext4_superblock_csum(struct super_block *sb, struct ext4_super_block *es);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c5767)
Location: fs/ext4/super.c:275
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
Direct callers:
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffffffff815c1f20-ffffffff815c1fa1: ext4_superblock_csum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
__le32 ext4_superblock_csum(struct super_block *sb, struct ext4_super_block *es);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fd389)
Location: fs/ext4/super.c:275
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
Direct callers:
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffffffff815f96a0-ffffffff815f9721: ext4_superblock_csum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
__le32 ext4_superblock_csum(struct super_block *sb, struct ext4_super_block *es);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81635eef)
Location: fs/ext4/super.c:283
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
Direct callers:
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/ioctl.c:ext4_update_backup_sb
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffffffff816322a0-ffffffff81632321: ext4_superblock_csum (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104bb96c)
Location: fs/ext4/super.c:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067f184)
Location: fs/ext4/super.c:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f19ac)
Location: fs/ext4/super.c:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000337d66)
Location: fs/ext4/super.c:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813dab51)
Location: fs/ext4/super.c:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813cb5d1)
Location: fs/ext4/super.c:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d7ff1)
Location: fs/ext4/super.c:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ed291)
Location: fs/ext4/super.c:176
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_superblock_csum_set
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
