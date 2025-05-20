# Function: <code>early_pci_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff816fa9e0)
Location: arch/x86/pci/early.c:53
Inline: True
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff816fa9e0-ffffffff816fa9fd: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8175f945)
Location: arch/x86/pci/early.c:53
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff8175f860-ffffffff8175f87d: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8178be85)
Location: arch/x86/pci/early.c:53
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff8178bda0-ffffffff8178bdbd: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff817aae45)
Location: arch/x86/pci/early.c:53
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff817aad60-ffffffff817aad7d: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81822335)
Location: arch/x86/pci/early.c:54
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff81822250-ffffffff8182226d: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8186c545)
Location: arch/x86/pci/early.c:54
Inline: True
Inline callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff8186c520-ffffffff8186c53d: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8188c6f0)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff8188c6f0-ffffffff8188c70d: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818d7040)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff818d7040-ffffffff818d705d: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff819093c0)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff819093c0-ffffffff819093dd: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bb9cb0)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff81bb9cb0-ffffffff81bb9ccd: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bce5b0)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff81bce5b0-ffffffff81bce5cd: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81bc1f60)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff81bc1f60-ffffffff81bc1f7d: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81c92570)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff81c92570-ffffffff81c9258d: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81e41c70)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff81e41c70-ffffffff81e41c91: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8201c370)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff8201c370-ffffffff8201c391: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8209ca10)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff8209ca10-ffffffff8209ca31: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff821741f0)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:early_reserve_memory
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
```
**Symbols:**

```
ffffffff821741f0-ffffffff82174211: early_pci_allowed (STB_GLOBAL)
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
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818a8780)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff818a8780-ffffffff818a879d: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81863190)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff81863190-ffffffff818631ad: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff818f9de0)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff818f9de0-ffffffff818f9dfd: early_pci_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int early_pci_allowed();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8191af40)
Location: arch/x86/pci/early.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/early-quirks.c:early_quirks
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base
  - arch/x86/kernel/vsmp_64.c:vsmp_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - arch/x86/pci/amd_bus.c:amd_postcore_init
  - arch/x86/pci/amd_bus.c:early_root_info_init
```
**Symbols:**

```
ffffffff8191af40-ffffffff8191af5d: early_pci_allowed (STB_GLOBAL)
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
