# Function: <code>file_permission</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810be5b7)
Location: include/linux/fs.h:3008
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/mincore.c (ffffffff812a6816)
Location: include/linux/fs.h:3008
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/madvise.c (ffffffff812c7c90)
Location: include/linux/fs.h:3008
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
```
```
In mm/memcontrol.c (ffffffff8130b014)
Location: include/linux/fs.h:3008
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff81320682)
Location: include/linux/fs.h:3008
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/verity/enable.c (ffffffff813af3ee)
Location: include/linux/fs.h:3008
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/sys.c (ffffffff810d0323)
Location: include/linux/fs.h:2991
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/mincore.c (ffffffff812e7cec)
Location: include/linux/fs.h:2991
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/madvise.c (ffffffff8130ca50)
Location: include/linux/fs.h:2991
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
```
```
In mm/memcontrol.c (ffffffff81355894)
Location: include/linux/fs.h:2991
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8136d1b2)
Location: include/linux/fs.h:2991
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/verity/enable.c (ffffffff813fef9e)
Location: include/linux/fs.h:2991
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/sys.c (ffffffff810e9265)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/mincore.c (ffffffff81348f5e)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/madvise.c (ffffffff81375679)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
```
```
In mm/memcontrol.c (ffffffff813ce251)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff813ebde0)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/verity/enable.c (ffffffff81472b30)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/sys.c (ffffffff8110a10d)
Location: include/linux/fs.h:2911
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/mincore.c (ffffffff813c12fd)
Location: include/linux/fs.h:2911
Inline: True
Inline callers:
  - mm/mincore.c:do_mincore
```
```
In mm/madvise.c (ffffffff813f358c)
Location: include/linux/fs.h:2911
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff81453777)
Location: include/linux/fs.h:2911
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8147427c)
Location: include/linux/fs.h:2911
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/verity/enable.c (ffffffff81504876)
Location: include/linux/fs.h:2911
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/sys.c (ffffffff811163f1)
Location: include/linux/fs.h:2525
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/mincore.c (ffffffff813f6064)
Location: include/linux/fs.h:2525
Inline: True
Inline callers:
  - mm/mincore.c:do_mincore
```
```
In mm/madvise.c (ffffffff81426fef)
Location: include/linux/fs.h:2525
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff81489592)
Location: include/linux/fs.h:2525
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff814a8c39)
Location: include/linux/fs.h:2525
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/verity/enable.c (ffffffff8153bfb1)
Location: include/linux/fs.h:2525
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/sys.c (ffffffff8111fde1)
Location: include/linux/fs.h:2760
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In mm/mincore.c (ffffffff81421d14)
Location: include/linux/fs.h:2760
Inline: True
Inline callers:
  - mm/mincore.c:do_mincore
```
```
In mm/madvise.c (ffffffff814602d4)
Location: include/linux/fs.h:2760
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff814b89f1)
Location: include/linux/fs.h:2760
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff814d9c99)
Location: include/linux/fs.h:2760
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
```
```
In fs/verity/enable.c (ffffffff81571291)
Location: include/linux/fs.h:2760
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
