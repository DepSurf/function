# Function: <code>ksys_chown</code>

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
In init/initramfs.c (ffffffff826cee41)
Location: include/linux/syscalls.h:1235
Inline: True
Inline callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
```
In kernel/uid16.c (ffffffff8112ce03)
Location: include/linux/syscalls.h:1235
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In init/initramfs.c (ffffffff82884e94)
Location: include/linux/syscalls.h:1258
Inline: True
Inline callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
```
In kernel/uid16.c (ffffffff811386f3)
Location: include/linux/syscalls.h:1258
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In init/initramfs.c (ffffffff8289bee6)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
```
In kernel/uid16.c (ffffffff81143911)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In init/initramfs.c (ffffffff8289eed6)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
```
In kernel/uid16.c (ffffffff8114f3f1)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In init/initramfs.c (ffffffff82cc565a)
Location: include/linux/syscalls.h:1348
Inline: True
Inline callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
```
In kernel/uid16.c (ffffffff8115fd81)
Location: include/linux/syscalls.h:1348
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In kernel/uid16.c (ffffffff8115bcf1)
Location: include/linux/syscalls.h:1307
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In kernel/uid16.c (ffffffff8115cf11)
Location: include/linux/syscalls.h:1320
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In kernel/uid16.c (ffffffff81182211)
Location: include/linux/syscalls.h:1321
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In kernel/uid16.c (ffffffff811b89db)
Location: include/linux/syscalls.h:1325
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In kernel/uid16.c (ffffffff811f9ddb)
Location: include/linux/syscalls.h:1327
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In kernel/uid16.c (ffffffff8120f19b)
Location: include/linux/syscalls.h:1223
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In kernel/uid16.c (ffffffff8122693b)
Location: include/linux/syscalls.h:1234
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In init/initramfs.c (ffff800011433164)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
```
In kernel/uid16.c (ffff8000101bdbac)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - kernel/uid16.c:__arm64_sys_chown16
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
In init/initramfs.c (c1503274)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
```
In kernel/uid16.c (c0405cc0)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - kernel/uid16.c:__se_sys_chown16
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
In init/initramfs.c (c000000001346d94)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
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
In init/initramfs.c (ffffffe000002bc4)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - init/initramfs.c:do_name
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
In init/initramfs.c (ffffffff8288ced6)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
```
In kernel/uid16.c (ffffffff81147a11)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In init/initramfs.c (ffffffff8288ae53)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
```
In kernel/uid16.c (ffffffff8113acc1)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In init/initramfs.c (ffffffff8289fed6)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
```
In kernel/uid16.c (ffffffff811458c1)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
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
In init/initramfs.c (ffffffff8289fedb)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - init/initramfs.c:do_name
  - init/initramfs.c:do_name
```
```
In kernel/uid16.c (ffffffff811524d1)
Location: include/linux/syscalls.h:1345
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_chown16
  - kernel/uid16.c:__x64_sys_chown16
```
</details>
</li>
</ul>

## Differences
