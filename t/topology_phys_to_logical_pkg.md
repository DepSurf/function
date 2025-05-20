# Function: <code>topology_phys_to_logical_pkg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81050e30)
Location: arch/x86/kernel/smpboot.c:299
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff81050e30-ffffffff81050e56: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81050fe0)
Location: arch/x86/kernel/smpboot.c:303
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff81050fe0-ffffffff81051006: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810538a0)
Location: arch/x86/kernel/smpboot.c:318
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
```
**Symbols:**

```
ffffffff810538a0-ffffffff810538c6: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053200)
Location: arch/x86/kernel/smpboot.c:321
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:snbep_qpi_enable_event
```
**Symbols:**

```
ffffffff81053200-ffffffff81053226: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81056fe0)
Location: arch/x86/kernel/smpboot.c:276
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff81056fe0-ffffffff8105704a: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81059e50)
Location: arch/x86/kernel/smpboot.c:296
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff81059e50-ffffffff81059eba: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105fad0)
Location: arch/x86/kernel/smpboot.c:296
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff8105fad0-ffffffff8105fb3a: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81062f10)
Location: arch/x86/kernel/smpboot.c:289
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff81062f10-ffffffff81062f7a: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810635c0)
Location: arch/x86/kernel/smpboot.c:289
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff810635c0-ffffffff8106362a: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81069780)
Location: arch/x86/kernel/smpboot.c:302
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff81069780-ffffffff810697ea: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106b390)
Location: arch/x86/kernel/smpboot.c:297
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff8106b390-ffffffff8106b3fa: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106be10)
Location: arch/x86/kernel/smpboot.c:296
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff8106be10-ffffffff8106be84: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81076970)
Location: arch/x86/kernel/smpboot.c:295
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff81076970-ffffffff81076a0f: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81085800)
Location: arch/x86/kernel/smpboot.c:291
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff81085800-ffffffff810858be: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81099710)
Location: arch/x86/kernel/smpboot.c:289
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff81099710-ffffffff810997e0: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109c9c0)
Location: arch/x86/kernel/smpboot.c:343
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff8109c9c0-ffffffff8109ca90: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a3ef0)
Location: arch/x86/kernel/smpboot.c:345
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:discover_upi_topology
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff810a3ef0-ffffffff810a3fce: topology_phys_to_logical_pkg (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810630b0)
Location: arch/x86/kernel/smpboot.c:289
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff810630b0-ffffffff8106311a: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810533c0)
Location: arch/x86/kernel/smpboot.c:289
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff810533c0-ffffffff8105342a: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063560)
Location: arch/x86/kernel/smpboot.c:289
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff81063560-ffffffff810635ca: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int topology_phys_to_logical_pkg(unsigned int phys_pkg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064b20)
Location: arch/x86/kernel/smpboot.c:289
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_init_box
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/kernel/smpboot.c:topology_update_package_map
```
**Symbols:**

```
ffffffff81064b20-ffffffff81064b8a: topology_phys_to_logical_pkg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
