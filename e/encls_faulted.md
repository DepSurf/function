# Function: <code>encls_faulted</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810666ce)
Location: arch/x86/kernel/cpu/sgx/encls.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8106763f)
Location: arch/x86/kernel/cpu/sgx/encls.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068713)
Location: arch/x86/kernel/cpu/sgx/encls.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810697dc)
Location: arch/x86/kernel/cpu/sgx/encls.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107084a)
Location: arch/x86/kernel/cpu/sgx/encls.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810719f9)
Location: arch/x86/kernel/cpu/sgx/encls.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072c49)
Location: arch/x86/kernel/cpu/sgx/encls.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073bfc)
Location: arch/x86/kernel/cpu/sgx/encls.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107de24)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107fac6)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810810e9)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810823dc)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f356)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81091605)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810940d5)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094e3c)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092256)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094545)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81097060)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097d2c)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099676)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109ba25)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e5d0)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f29c)
Location: arch/x86/kernel/cpu/sgx/encls.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_ecreate
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
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
