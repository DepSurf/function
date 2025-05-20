# Function: <code>ksys_truncate</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81084d55)
Location: include/linux/syscalls.h:1280
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108ba25)
Location: include/linux/syscalls.h:1303
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108f825)
Location: include/linux/syscalls.h:1390
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
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
In arch/x86/ia32/sys_ia32.c (ffffffff81090485)
Location: include/linux/syscalls.h:1390
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff81039f45)
Location: include/linux/syscalls.h:1393
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff8103a755)
Location: include/linux/syscalls.h:1329
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff8103c155)
Location: include/linux/syscalls.h:1342
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff81041c55)
Location: include/linux/syscalls.h:1343
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff810499f5)
Location: include/linux/syscalls.h:1347
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff81054af5)
Location: include/linux/syscalls.h:1349
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff81055b55)
Location: include/linux/syscalls.h:1245
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
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
In arch/x86/kernel/sys_ia32.c (ffffffff8105cda5)
Location: include/linux/syscalls.h:1256
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_truncate64
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_truncate64
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
In arch/arm64/kernel/sys32.c (ffff80001009dd18)
Location: include/linux/syscalls.h:1390
Inline: True
Inline callers:
  - arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_truncate64
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/sys_ppc32.c (c0000000000317cc)
Location: include/linux/syscalls.h:1390
Inline: True
Inline callers:
  - arch/powerpc/kernel/sys_ppc32.c:compat_sys_truncate64
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108f445)
Location: include/linux/syscalls.h:1390
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
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
In arch/x86/ia32/sys_ia32.c (ffffffff8107df55)
Location: include/linux/syscalls.h:1390
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
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
In arch/x86/ia32/sys_ia32.c (ffffffff8108f3f5)
Location: include/linux/syscalls.h:1390
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
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
In arch/x86/ia32/sys_ia32.c (ffffffff810917d5)
Location: include/linux/syscalls.h:1390
Inline: True
Inline callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_truncate64
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_truncate64
```
</details>
</li>
</ul>

## Differences
