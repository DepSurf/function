# Function: <code>__einit</code>

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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810670b8)
Location: arch/x86/kernel/cpu/sgx/encls.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067626)
Location: arch/x86/kernel/cpu/sgx/encls.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810694ef)
Location: arch/x86/kernel/cpu/sgx/encls.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810719e0)
Location: arch/x86/kernel/cpu/sgx/encls.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073b9f)
Location: arch/x86/kernel/cpu/sgx/encls.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107faa4)
Location: arch/x86/kernel/cpu/sgx/encls.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8108226b)
Location: arch/x86/kernel/cpu/sgx/encls.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81091b94)
Location: arch/x86/kernel/cpu/sgx/encls.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094cab)
Location: arch/x86/kernel/cpu/sgx/encls.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094a9e)
Location: arch/x86/kernel/cpu/sgx/encls.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097b7b)
Location: arch/x86/kernel/cpu/sgx/encls.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109bf7e)
Location: arch/x86/kernel/cpu/sgx/encls.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f0eb)
Location: arch/x86/kernel/cpu/sgx/encls.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:__sgx_virt_einit
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
