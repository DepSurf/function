# Function: <code>__uv_bios_call</code>

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
s64 __uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff81097ec0)
Location: arch/x86/platform/uv/bios_uv.c:21
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_call_irqsave
  - arch/x86/platform/uv/bios_uv.c:uv_bios_call
```
**Symbols:**

```
ffffffff81097ec0-ffffffff81098005: __uv_bios_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff8109d5f0)
Location: arch/x86/platform/uv/bios_uv.c:21
Inline: True
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_set_legacy_vga_target
  - arch/x86/platform/uv/bios_uv.c:uv_bios_freq_base
```
**Symbols:**

```
ffffffff8109d5f0-ffffffff8109d73e: __uv_bios_call.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
s64 __uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff81098f10)
Location: arch/x86/platform/uv/bios_uv.c:23
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff81098f10-ffffffff81099011: __uv_bios_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
s64 __uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff81099750)
Location: arch/x86/platform/uv/bios_uv.c:23
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff81099750-ffffffff81099840: __uv_bios_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
s64 __uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810a9770)
Location: arch/x86/platform/uv/bios_uv.c:23
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff810a9770-ffffffff810a9860: __uv_bios_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
s64 __uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810bf030)
Location: arch/x86/platform/uv/bios_uv.c:23
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff810bf030-ffffffff810bf152: __uv_bios_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
s64 __uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810dad60)
Location: arch/x86/platform/uv/bios_uv.c:23
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff810dad60-ffffffff810dae82: __uv_bios_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
s64 __uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (0)
Location: arch/x86/platform/uv/bios_uv.c:23
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff810e62f0-ffffffff810e641f: __uv_bios_call (STB_LOCAL)
ffffffff820d3c3d-ffffffff820d3c59: __uv_bios_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
s64 __uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (0)
Location: arch/x86/platform/uv/bios_uv.c:23
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff810ee6e0-ffffffff810ee79e: __uv_bios_call (STB_LOCAL)
ffffffff821aeaab-ffffffff821aeac7: __uv_bios_call.cold (STB_LOCAL)
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
s64 __uv_bios_call(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff81099380)
Location: arch/x86/platform/uv/bios_uv.c:21
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_call_irqsave
  - arch/x86/platform/uv/bios_uv.c:uv_bios_call
```
**Symbols:**

```
ffffffff81099380-ffffffff810994e0: __uv_bios_call (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
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
