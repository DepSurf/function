# Function: <code>virtio_set_mem_acc_cb</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8345190c)
Location: include/linux/virtio_anchor.h:11
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476ffb)
Location: include/linux/virtio_anchor.h:11
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:sev_setup_arch
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
In arch/x86/xen/enlighten_pv.c (ffffffff83e6e5c5)
Location: include/linux/virtio_anchor.h:11
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83ea03cb)
Location: include/linux/virtio_anchor.h:11
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:sev_setup_arch
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
In arch/x86/xen/enlighten_pv.c (ffffffff8368f9b5)
Location: include/linux/virtio_anchor.h:11
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c454b)
Location: include/linux/virtio_anchor.h:11
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:sev_setup_arch
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
In arch/x86/xen/enlighten_pv.c (ffffffff838bf6a5)
Location: include/linux/virtio_anchor.h:11
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_pv_init_platform
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff838f472b)
Location: include/linux/virtio_anchor.h:11
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_setup_arch
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
