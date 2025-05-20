# Function: <code>ksys_unlink</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002efa)
Location: include/linux/syscalls.h:1172
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff826cdaa0)
Location: include/linux/syscalls.h:1172
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff826ce2a4)
Location: include/linux/syscalls.h:1172
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff826ce61a)
Location: include/linux/syscalls.h:1172
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
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
In init/do_mounts.c (ffffffff81002f87)
Location: include/linux/syscalls.h:1195
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff82883ae3)
Location: include/linux/syscalls.h:1195
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff828842e7)
Location: include/linux/syscalls.h:1195
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8288465d)
Location: include/linux/syscalls.h:1195
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
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
In init/do_mounts.c (ffffffff810030b4)
Location: include/linux/syscalls.h:1282
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff8289ab10)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8289b338)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289b6ac)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
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
In init/do_mounts.c (ffffffff810030a4)
Location: include/linux/syscalls.h:1282
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff8289daf5)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8289e31d)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289e691)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81004279)
Location: include/linux/syscalls.h:1285
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff810042cc)
Location: include/linux/syscalls.h:1285
Inline: True
Direct callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8100436f)
Location: include/linux/syscalls.h:1285
Inline: True
```
```
In init/initramfs.c (ffffffff82cc539d)
Location: include/linux/syscalls.h:1285
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
**Symbols:**

```
ffffffff810042cc-ffffffff810042e4: ksys_unlink.isra.0 (STB_LOCAL)
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffff8000100856f8)
Location: include/linux/syscalls.h:1282
Inline: True
```
```
In init/do_mounts_initrd.c (ffff800011431c94)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffff8000114324bc)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffff800011432928)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
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
In init/do_mounts.c (c0303eb8)
Location: include/linux/syscalls.h:1282
Inline: True
```
```
In init/do_mounts_initrd.c (c1501cd0)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (c150251c)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (c150298c)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
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
In init/do_mounts.c (c000000000011360)
Location: include/linux/syscalls.h:1282
Inline: True
```
```
In init/do_mounts_initrd.c (c0000000013451d0)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (c000000001345ca8)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (c000000001346248)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
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
In init/do_mounts.c (ffffffe0000b4aa2)
Location: include/linux/syscalls.h:1282
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffe00000191e)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffe00000208c)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffe00000248e)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
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
In init/do_mounts.c (ffffffff810030a4)
Location: include/linux/syscalls.h:1282
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff8288baf5)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8288c31d)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8288c691)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
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
In init/do_mounts.c (ffffffff81001584)
Location: include/linux/syscalls.h:1282
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff82889a72)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8288a29a)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8288a60e)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
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
In init/do_mounts.c (ffffffff810030a4)
Location: include/linux/syscalls.h:1282
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff8289eaf5)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8289f31d)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289f691)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
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
In init/do_mounts.c (ffffffff810030f4)
Location: include/linux/syscalls.h:1282
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff8289eafa)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8289f322)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289f696)
Location: include/linux/syscalls.h:1282
Inline: True
Inline callers:
  - init/initramfs.c:clean_path
```
</details>
</li>
</ul>

## Differences
