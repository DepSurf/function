# Function: <code>ksys_lchown</code>

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
In init/initramfs.c (ffffffff826ce70e)
Location: include/linux/syscalls.h:1241
Inline: True
Inline callers:
  - init/initramfs.c:do_symlink
```
```
In kernel/uid16.c (ffffffff8112ce93)
Location: include/linux/syscalls.h:1241
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
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
In init/initramfs.c (ffffffff82884751)
Location: include/linux/syscalls.h:1264
Inline: True
Inline callers:
  - init/initramfs.c:do_symlink
```
```
In kernel/uid16.c (ffffffff81138783)
Location: include/linux/syscalls.h:1264
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
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
In init/initramfs.c (ffffffff8289b7a0)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - init/initramfs.c:do_symlink
```
```
In kernel/uid16.c (ffffffff811439a7)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
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
In init/initramfs.c (ffffffff8289e785)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - init/initramfs.c:do_symlink
```
```
In kernel/uid16.c (ffffffff8114f487)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
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
In init/initramfs.c (ffffffff82cc5429)
Location: include/linux/syscalls.h:1354
Inline: True
Inline callers:
  - init/initramfs.c:do_symlink
```
```
In kernel/uid16.c (ffffffff8115fdc7)
Location: include/linux/syscalls.h:1354
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
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
In kernel/uid16.c (ffffffff8115bd37)
Location: include/linux/syscalls.h:1313
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
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
In kernel/uid16.c (ffffffff8115cf57)
Location: include/linux/syscalls.h:1326
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
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
In kernel/uid16.c (ffffffff81182257)
Location: include/linux/syscalls.h:1327
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811b8a31)
Location: include/linux/syscalls.h:1331
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811f9e41)
Location: include/linux/syscalls.h:1333
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8120f201)
Location: include/linux/syscalls.h:1229
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff812269a1)
Location: include/linux/syscalls.h:1240
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
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
In init/initramfs.c (ffff800011432a34)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - init/initramfs.c:do_symlink
```
```
In kernel/uid16.c (ffff8000101bdc04)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - kernel/uid16.c:__arm64_sys_lchown16
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
In init/initramfs.c (c1502ab8)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - init/initramfs.c:do_symlink
```
```
In kernel/uid16.c (c0405d24)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - kernel/uid16.c:__se_sys_lchown16
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
In init/initramfs.c (c000000001346398)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - init/initramfs.c:do_symlink
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
In init/initramfs.c (ffffffe00000254e)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - init/initramfs.c:do_symlink
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
In init/initramfs.c (ffffffff8288c785)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - init/initramfs.c:do_symlink
```
```
In kernel/uid16.c (ffffffff81147aa7)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
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
In init/initramfs.c (ffffffff8288a702)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - init/initramfs.c:do_symlink
```
```
In kernel/uid16.c (ffffffff8113ad57)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
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
In init/initramfs.c (ffffffff8289f785)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - init/initramfs.c:do_symlink
```
```
In kernel/uid16.c (ffffffff81145957)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
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
In init/initramfs.c (ffffffff8289f78a)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - init/initramfs.c:do_symlink
```
```
In kernel/uid16.c (ffffffff81152567)
Location: include/linux/syscalls.h:1351
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_lchown16
  - kernel/uid16.c:__x64_sys_lchown16
```
</details>
</li>
</ul>

## Differences
