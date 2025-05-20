# Function: <code>ksys_open</code>

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
In init/main.c (ffffffff826cd3b5)
Location: include/linux/syscalls.h:1270
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1270
Inline: True
```
```
In init/do_mounts_md.c (ffffffff826ce311)
Location: include/linux/syscalls.h:1270
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff826ced9c)
Location: include/linux/syscalls.h:1270
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In fs/open.c (ffffffff812970f5)
Location: include/linux/syscalls.h:1270
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
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
In init/main.c (ffffffff82883391)
Location: include/linux/syscalls.h:1293
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1293
Inline: True
```
```
In init/do_mounts_md.c (ffffffff82884354)
Location: include/linux/syscalls.h:1293
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff82884def)
Location: include/linux/syscalls.h:1293
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In fs/open.c (ffffffff812abda5)
Location: include/linux/syscalls.h:1293
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
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
In init/main.c (ffffffff8289a3de)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1380
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289b3a5)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289be40)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In fs/open.c (ffffffff812c85b5)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
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
In init/main.c (ffffffff8289d3c3)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1380
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289e38a)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289ee2c)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In fs/open.c (ffffffff812d9fc5)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
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
In init/main.c (ffffffff81003a55)
Location: include/linux/syscalls.h:1383
Inline: True
Inline callers:
  - init/main.c:console_on_rootfs
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1383
Inline: True
```
```
In init/do_mounts_md.c (ffffffff82cc48ab)
Location: include/linux/syscalls.h:1383
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff82cc55b0)
Location: include/linux/syscalls.h:1383
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In fs/open.c (ffffffff8130fc5f)
Location: include/linux/syscalls.h:1383
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
  - fs/open.c:__ia32_sys_open
  - fs/open.c:__x64_sys_open
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
In init/main.c (ffff8000114313b0)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1380
Inline: True
```
```
In init/do_mounts_md.c (ffff800011432520)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffff8000114330f8)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In fs/open.c (ffff80001037f2e8)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - fs/open.c:__arm64_sys_creat
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
In init/main.c (c1501418)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1380
Inline: True
```
```
In init/do_mounts_md.c (c150258c)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (c15031e4)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In fs/open.c (c0569b38)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - fs/open.c:__se_sys_creat
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
In init/main.c (c0000000013446a4)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1380
Inline: True
```
```
In init/do_mounts_md.c (c000000001345d38)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (c000000001346cc8)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In fs/open.c (c000000000475250)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - fs/open.c:__se_sys_creat
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
In init/main.c (ffffffe000001128)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1380
Inline: True
```
```
In init/do_mounts_md.c (ffffffe000002112)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffe000002b40)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In fs/open.c (ffffffe000254e32)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - fs/open.c:__se_sys_creat
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
In init/main.c (ffffffff8288b3c3)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1380
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8288c38a)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8288ce2c)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In fs/open.c (ffffffff812d25a5)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
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
In init/main.c (ffffffff82889340)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1380
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8288a307)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8288ada9)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In fs/open.c (ffffffff812c3225)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
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
In init/main.c (ffffffff8289e3c3)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1380
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289f38a)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289fe2c)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In fs/open.c (ffffffff812d03b5)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
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
In init/main.c (ffffffff8289e3c8)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
```
```
In init/do_mounts_initrd.c (0)
Location: include/linux/syscalls.h:1380
Inline: True
```
```
In init/do_mounts_md.c (ffffffff8289f38f)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_setup_drive
```
```
In init/initramfs.c (ffffffff8289fe31)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In fs/open.c (ffffffff812e11e5)
Location: include/linux/syscalls.h:1380
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_creat
  - fs/open.c:__x64_sys_creat
```
</details>
</li>
</ul>

## Differences
