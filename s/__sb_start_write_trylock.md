# Function: <code>__sb_start_write_trylock</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81165d86)
Location: include/linux/fs.h:1597
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff8132acac)
Location: include/linux/fs.h:1597
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff813433d8)
Location: include/linux/fs.h:1597
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/file.c (ffffffff813fb01b)
Location: include/linux/fs.h:1597
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff8143eee2)
Location: include/linux/fs.h:1597
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
In kernel/acct.c (ffffffff81166ab6)
Location: include/linux/fs.h:1766
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff8133095f)
Location: include/linux/fs.h:1766
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff813496c8)
Location: include/linux/fs.h:1766
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/file.c (ffffffff814014eb)
Location: include/linux/fs.h:1766
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff81444d22)
Location: include/linux/fs.h:1766
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
In kernel/acct.c (ffffffff8118c276)
Location: include/linux/fs.h:1816
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff8137e0df)
Location: include/linux/fs.h:1816
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81397418)
Location: include/linux/fs.h:1816
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/file.c (ffffffff81453a6b)
Location: include/linux/fs.h:1816
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff81498bb2)
Location: include/linux/fs.h:1816
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
In kernel/acct.c (ffffffff811bb687)
Location: include/linux/fs.h:1702
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff813fdd0f)
Location: include/linux/fs.h:1702
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814195d7)
Location: include/linux/fs.h:1702
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/file.c (ffffffff814d0f3c)
Location: include/linux/fs.h:1702
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff81523a73)
Location: include/linux/fs.h:1702
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
In kernel/acct.c (ffffffff811fd4a7)
Location: include/linux/fs.h:1817
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff8148792f)
Location: include/linux/fs.h:1817
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814a5017)
Location: include/linux/fs.h:1817
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/file.c (ffffffff8156997c)
Location: include/linux/fs.h:1817
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff815c0c5a)
Location: include/linux/fs.h:1817
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
In kernel/acct.c (ffffffff81212634)
Location: include/linux/fs.h:1497
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff814bc790)
Location: include/linux/fs.h:1497
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814da297)
Location: include/linux/fs.h:1497
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/file.c (ffffffff815a176c)
Location: include/linux/fs.h:1497
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff815f83da)
Location: include/linux/fs.h:1497
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
In kernel/acct.c (ffffffff81229cb4)
Location: include/linux/fs.h:1644
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/pipe.c (ffffffff814eecd7)
Location: include/linux/fs.h:1644
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff8150c886)
Location: include/linux/fs.h:1644
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/ext4/file.c (ffffffff815da51c)
Location: include/linux/fs.h:1644
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/super.c (ffffffff81630f8a)
Location: include/linux/fs.h:1644
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
