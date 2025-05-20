# Function: <code>uv_bios_call</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
s64 uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff81098010)
Location: arch/x86/platform/uv/bios_uv.c:45
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
```
**Symbols:**

```
ffffffff81098010-ffffffff8109808b: uv_bios_call (STB_GLOBAL)
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
In arch/x86/platform/uv/bios_uv.c (ffffffff8109d9d9)
Location: arch/x86/platform/uv/bios_uv.c:48
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
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
In arch/x86/platform/uv/bios_uv.c (ffffffff8109903a)
Location: arch/x86/platform/uv/bios_uv.c:40
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs
  - arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count
  - arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
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
In arch/x86/platform/uv/bios_uv.c (ffffffff8109985a)
Location: arch/x86/platform/uv/bios_uv.c:40
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs
  - arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count
  - arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
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
In arch/x86/platform/uv/bios_uv.c (ffffffff810a987a)
Location: arch/x86/platform/uv/bios_uv.c:40
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs
  - arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count
  - arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
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
In arch/x86/platform/uv/bios_uv.c (ffffffff810bf179)
Location: arch/x86/platform/uv/bios_uv.c:40
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs
  - arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count
  - arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
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
In arch/x86/platform/uv/bios_uv.c (ffffffff810daeb9)
Location: arch/x86/platform/uv/bios_uv.c:40
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs
  - arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count
  - arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
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
In arch/x86/platform/uv/bios_uv.c (ffffffff810e6449)
Location: arch/x86/platform/uv/bios_uv.c:40
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs
  - arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count
  - arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
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
In arch/x86/platform/uv/bios_uv.c (ffffffff810ee7c9)
Location: arch/x86/platform/uv/bios_uv.c:40
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_pci_topology
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_geoinfo
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_ports
  - arch/x86/platform/uv/bios_uv.c:uv_bios_enum_objs
  - arch/x86/platform/uv/bios_uv.c:uv_bios_obj_count
  - arch/x86/platform/uv/bios_uv.c:uv_bios_install_heap
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_heapsize
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_master_nasid
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
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
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
s64 uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810994e0)
Location: arch/x86/platform/uv/bios_uv.c:45
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
```
**Symbols:**

```
ffffffff810994e0-ffffffff8109955b: uv_bios_call (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
