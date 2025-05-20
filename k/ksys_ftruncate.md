# Function: <code>ksys_ftruncate</code>

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
In init/initramfs.c (ffffffff826cedef)
Location: include/linux/syscalls.h:1250
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81084da5)
Location: include/linux/syscalls.h:1250
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
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
In init/initramfs.c (ffffffff82884e42)
Location: include/linux/syscalls.h:1273
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108ba75)
Location: include/linux/syscalls.h:1273
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
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
In init/initramfs.c (ffffffff8289be94)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f875)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
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
In init/initramfs.c (ffffffff8289ee80)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff810904d5)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
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
In init/initramfs.c (ffffffff82cc5604)
Location: include/linux/syscalls.h:1363
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff81039fa5)
Location: include/linux/syscalls.h:1363
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff8103a7b5)
Location: include/linux/syscalls.h:1322
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff8103c1b5)
Location: include/linux/syscalls.h:1335
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff81041cb5)
Location: include/linux/syscalls.h:1336
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff81049a55)
Location: include/linux/syscalls.h:1340
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff81054b75)
Location: include/linux/syscalls.h:1342
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff81055bd5)
Location: include/linux/syscalls.h:1238
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff8105ce25)
Location: include/linux/syscalls.h:1249
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_ftruncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_ftruncate64
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
In init/initramfs.c (ffff800011433128)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In arch/arm64/kernel/sys32.c (ffff80001009dd50)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_ftruncate64
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
In init/initramfs.c (c1503230)
Location: include/linux/syscalls.h:1360
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
In init/initramfs.c (c000000001346d40)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In arch/powerpc/kernel/sys_ppc32.c (c00000000003185c)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - arch/powerpc/kernel/sys_ppc32.c:compat_sys_ftruncate64
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
In init/initramfs.c (ffffffe000002b84)
Location: include/linux/syscalls.h:1360
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
In init/initramfs.c (ffffffff8288ce80)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f495)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
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
In init/initramfs.c (ffffffff8288adfd)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8107dfa5)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
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
In init/initramfs.c (ffffffff8289fe80)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f445)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
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
In init/initramfs.c (ffffffff8289fe85)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - init/initramfs.c:do_name
```
```
In arch/x86/ia32/sys_ia32.c (ffffffff81091825)
Location: include/linux/syscalls.h:1360
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_ftruncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_ftruncate64
```
</details>
</li>
</ul>

## Differences
