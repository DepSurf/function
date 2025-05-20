# Function: <code>ksys_mknod</code>

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
In init/do_mounts.c (ffffffff81002f1a)
Location: include/linux/syscalls.h:1203
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff826cdab9)
Location: include/linux/syscalls.h:1203
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff826ce2c2)
Location: include/linux/syscalls.h:1203
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff826cef16)
Location: include/linux/syscalls.h:1203
Inline: True
Inline callers:
  - init/initramfs.c:do_name
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
In init/do_mounts.c (ffffffff81002fa7)
Location: include/linux/syscalls.h:1226
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff82883afc)
Location: include/linux/syscalls.h:1226
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff82884305)
Location: include/linux/syscalls.h:1226
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff82884f69)
Location: include/linux/syscalls.h:1226
Inline: True
Inline callers:
  - init/initramfs.c:do_name
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
In init/do_mounts.c (ffffffff810030d4)
Location: include/linux/syscalls.h:1313
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff8289ab29)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8289b356)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289bfbb)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/initramfs.c:do_name
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
In init/do_mounts.c (ffffffff810030c4)
Location: include/linux/syscalls.h:1313
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff8289db0e)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8289e33b)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289efab)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/initramfs.c:do_name
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
In init/do_mounts.c (ffffffff81004299)
Location: include/linux/syscalls.h:1316
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff82cc40d1)
Location: include/linux/syscalls.h:1316
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8100438d)
Location: include/linux/syscalls.h:1316
Inline: True
```
```
In init/initramfs.c (ffffffff82cc572f)
Location: include/linux/syscalls.h:1316
Inline: True
Inline callers:
  - init/initramfs.c:do_name
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
In init/do_mounts.c (ffff800010085724)
Location: include/linux/syscalls.h:1313
Inline: True
```
```
In init/do_mounts_initrd.c (ffff800011431cb0)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffff8000114324d0)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffff800011433210)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/initramfs.c:do_name
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
In init/do_mounts.c (c0303ed8)
Location: include/linux/syscalls.h:1313
Inline: True
```
```
In init/do_mounts_initrd.c (c1501ce8)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (c150253c)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (c1503338)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/initramfs.c:do_name
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
In init/do_mounts.c (c000000000011388)
Location: include/linux/syscalls.h:1313
Inline: True
```
```
In init/do_mounts_initrd.c (c0000000013451f4)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (c000000001345cd4)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (c000000001346e68)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/initramfs.c:do_name
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
In init/do_mounts.c (ffffffe0000b4acc)
Location: include/linux/syscalls.h:1313
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffe00000193c)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffe0000020aa)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffe000002c76)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/initramfs.c:do_name
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
In init/do_mounts.c (ffffffff810030c4)
Location: include/linux/syscalls.h:1313
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff8288bb0e)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8288c33b)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8288cfab)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/initramfs.c:do_name
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
In init/do_mounts.c (ffffffff810015a4)
Location: include/linux/syscalls.h:1313
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff82889a8b)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8288a2b8)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8288af28)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/initramfs.c:do_name
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
In init/do_mounts.c (ffffffff810030c4)
Location: include/linux/syscalls.h:1313
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff8289eb0e)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8289f33b)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289ffab)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/initramfs.c:do_name
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
In init/do_mounts.c (ffffffff81003114)
Location: include/linux/syscalls.h:1313
Inline: True
```
```
In init/do_mounts_initrd.c (ffffffff8289eb13)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8289f340)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289ffb0)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
</details>
</li>
</ul>

## Differences
