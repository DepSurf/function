# Function: <code>__ecreate</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810674e2)
Location: arch/x86/kernel/cpu/sgx/encls.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067eb1)
Location: arch/x86/kernel/cpu/sgx/encls.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81069465)
Location: arch/x86/kernel/cpu/sgx/encls.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81072314)
Location: arch/x86/kernel/cpu/sgx/encls.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073b15)
Location: arch/x86/kernel/cpu/sgx/encls.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107fdd6)
Location: arch/x86/kernel/cpu/sgx/encls.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8108219d)
Location: arch/x86/kernel/cpu/sgx/encls.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109270b)
Location: arch/x86/kernel/cpu/sgx/encls.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094bcd)
Location: arch/x86/kernel/cpu/sgx/encls.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109563b)
Location: arch/x86/kernel/cpu/sgx/encls.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097af5)
Location: arch/x86/kernel/cpu/sgx/encls.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109cb7b)
Location: arch/x86/kernel/cpu/sgx/encls.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f065)
Location: arch/x86/kernel/cpu/sgx/encls.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
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
