# Function: <code>clear_buffer_write_io_error</code>

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
In fs/buffer.c (ffffffff81244b26)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff812b8151)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff812f1a67)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff8126d09c)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff812e6e55)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff8131f2f9)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff81280313)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff812fc9d3)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff8133537b)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff8128dbf3)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff8133163c)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff8134a0ff)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff812b07e1)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff81355aed)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff8136e752)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff812d85d2)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff81383eb4)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff8139cda3)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff812edaa6)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff8139c97d)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff813b5b13)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff8130f276)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff813c6bd5)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff813e01ff)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff813221d3)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff813dff95)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff813fa23f)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff81359806)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff8142c847)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff81447808)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff81367599)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff81445561)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff8146418b)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff8136dfce)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff8144aeb8)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
```
```
In fs/jbd2/journal.c (ffffffff8146983b)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff813bccce)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff8149edc8)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
```
```
In fs/jbd2/journal.c (ffffffff814bfcdb)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff8144308c)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/ioctl.c (ffffffff814ed539)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/super.c (ffffffff81525573)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
```
```
In fs/jbd2/journal.c (ffffffff8154a497)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff814d234b)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/ioctl.c (ffffffff81587346)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/super.c (ffffffff815c2bcc)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
```
```
In fs/jbd2/journal.c (ffffffff815e9dc0)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff81508c0c)
Location: include/linux/buffer_head.h:135
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/ioctl.c (ffffffff815bda06)
Location: include/linux/buffer_head.h:135
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/super.c (ffffffff815fa32c)
Location: include/linux/buffer_head.h:135
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
```
```
In fs/jbd2/journal.c (ffffffff81621bad)
Location: include/linux/buffer_head.h:135
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff8153daa2)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/ioctl.c (ffffffff815f67c6)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_update_primary_sb
```
```
In fs/ext4/super.c (ffffffff81632f2c)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:update_super_work
```
```
In fs/jbd2/journal.c (ffffffff8165a0d8)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffff8000103daf50)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffff8000104b8fc8)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffff8000104d7084)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (c05b42ec)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (c067c668)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (c0699204)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (c0000000004e01e0)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (c0000000005ee158)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (c000000000611c58)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffe000293918)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffe0003358e0)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffe00034d000)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff8131a7b3)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff813d8575)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff813f281f)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff8130b353)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff813c8ff5)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff813e329f)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff81318283)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff813d5a05)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff813efb9f)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
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
In fs/buffer.c (ffffffff81329ea3)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:submit_bh_wbc
```
```
In fs/ext4/super.c (ffffffff813eac85)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:ext4_commit_super
```
```
In fs/jbd2/journal.c (ffffffff814055c3)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
```
</details>
</li>
</ul>

## Differences
