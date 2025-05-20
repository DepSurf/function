# Function: <code>ksys_close</code>

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
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1262
Inline: True
```
```
In init/do_mounts_md.c (ffffffff826ce343)
Location: include/linux/syscalls.h:1262
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff826ceac1)
Location: include/linux/syscalls.h:1262
Inline: True
Inline callers:
  - init/initramfs.c:do_copy
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
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1285
Inline: True
```
```
In init/do_mounts_md.c (ffffffff82884386)
Location: include/linux/syscalls.h:1285
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff82884b04)
Location: include/linux/syscalls.h:1285
Inline: True
Inline callers:
  - init/initramfs.c:do_copy
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
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1372
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289b3d7)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289bb55)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/initramfs.c:do_copy
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
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1372
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289e3bc)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289eb3a)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/initramfs.c:do_copy
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
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1375
Inline: False
```
```
In init/do_mounts_md.c (ffffffff81004352)
Location: include/linux/syscalls.h:1375
Inline: True
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff82cc52a2)
Location: include/linux/syscalls.h:1375
Inline: True
Inline callers:
  - init/initramfs.c:do_copy
```
**Symbols:**

```
ffffffff81004352-ffffffff8100436f: ksys_close.isra.0 (STB_LOCAL)
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
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1372
Inline: True
```
```
In init/do_mounts_md.c (ffff800011432548)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffff800011432df0)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/initramfs.c:do_copy
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
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1372
Inline: True
```
```
In init/do_mounts_md.c (c15025b8)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (c1502efc)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/initramfs.c:do_copy
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
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1372
Inline: True
```
```
In init/do_mounts_md.c (c000000001345d74)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (c000000001346898)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/initramfs.c:do_copy
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
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1372
Inline: True
```
```
In init/do_mounts_md.c (ffffffe000002148)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffe0000028d4)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/initramfs.c:do_copy
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
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1372
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8288c3bc)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8288cb3a)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/initramfs.c:do_copy
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
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1372
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8288a339)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8288aab7)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/initramfs.c:do_copy
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
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1372
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289f3bc)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289fb3a)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/initramfs.c:do_copy
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
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1372
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289f3c1)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289fb3f)
Location: include/linux/syscalls.h:1372
Inline: True
Inline callers:
  - init/initramfs.c:do_copy
```
</details>
</li>
</ul>

## Differences
