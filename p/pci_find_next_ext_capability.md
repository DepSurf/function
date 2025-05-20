# Function: <code>pci_find_next_ext_capability</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81435380)
Location: drivers/pci/pci.c:288
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
```
**Symbols:**

```
ffffffff81435380-ffffffff81435445: pci_find_next_ext_capability.part.16 (STB_LOCAL)
ffffffff81435450-ffffffff8143546f: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81481833)
Location: drivers/pci/pci.c:309
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
```
**Symbols:**

```
ffffffff81480ce0-ffffffff81480da6: pci_find_next_ext_capability.part.16 (STB_LOCAL)
ffffffff81480db0-ffffffff81480dcf: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a2d03)
Location: drivers/pci/pci.c:309
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
```
**Symbols:**

```
ffffffff814a23a0-ffffffff814a2466: pci_find_next_ext_capability.part.19 (STB_LOCAL)
ffffffff814a2470-ffffffff814a248f: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff814aefec)
Location: drivers/pci/pci.c:311
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
```
**Symbols:**

```
ffffffff814ac140-ffffffff814ac1f8: pci_find_next_ext_capability.part.17 (STB_LOCAL)
ffffffff814ac200-ffffffff814ac21f: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ebec5)
Location: drivers/pci/pci.c:312
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
```
**Symbols:**

```
ffffffff814eb210-ffffffff814eb2c8: pci_find_next_ext_capability.part.17 (STB_LOCAL)
ffffffff814eb2d0-ffffffff814eb2ef: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151b9f5)
Location: drivers/pci/pci.c:324
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_std_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
```
**Symbols:**

```
ffffffff8151a7d0-ffffffff8151a88a: pci_find_next_ext_capability.part.19 (STB_LOCAL)
ffffffff8151a890-ffffffff8151a8af: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81531685)
Location: drivers/pci/pci.c:490
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
```
**Symbols:**

```
ffffffff81530530-ffffffff815305ea: pci_find_next_ext_capability.part.20 (STB_LOCAL)
ffffffff815305f0-ffffffff8153060f: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155fe55)
Location: drivers/pci/pci.c:490
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8155fd10-ffffffff8155fdca: pci_find_next_ext_capability.part.0 (STB_LOCAL)
ffffffff8155fdd0-ffffffff8155fdef: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81580f85)
Location: drivers/pci/pci.c:490
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81580e40-ffffffff81580efa: pci_find_next_ext_capability.part.0 (STB_LOCAL)
ffffffff81580f00-ffffffff81580f1f: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81626895)
Location: drivers/pci/pci.c:522
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_disable_acs_redir
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_has_feat
```
**Symbols:**

```
ffffffff81625e40-ffffffff81625efa: pci_find_next_ext_capability.part.0 (STB_LOCAL)
ffffffff81625f00-ffffffff81625f1f: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
u16 pci_find_next_ext_capability(struct pci_dev *dev, u16 start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164c415)
Location: drivers/pci/pci.c:530
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_has_feat
```
**Symbols:**

```
ffffffff8164bc60-ffffffff8164bd37: pci_find_next_ext_capability.part.0 (STB_LOCAL)
ffffffff8164bd40-ffffffff8164bd62: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
u16 pci_find_next_ext_capability(struct pci_dev *dev, u16 start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162eff5)
Location: drivers/pci/pci.c:530
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
```
**Symbols:**

```
ffffffff8162e830-ffffffff8162e902: pci_find_next_ext_capability.part.0 (STB_LOCAL)
ffffffff8162e910-ffffffff8162e932: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
u16 pci_find_next_ext_capability(struct pci_dev *dev, u16 start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169e925)
Location: drivers/pci/pci.c:540
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/pci.c:pci_get_dsn
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_get_dsn
```
**Symbols:**

```
ffffffff8169dc90-ffffffff8169dd62: pci_find_next_ext_capability.part.0 (STB_LOCAL)
ffffffff8169dd70-ffffffff8169dd92: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u16 pci_find_next_ext_capability(struct pci_dev *dev, u16 start, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817be080)
Location: drivers/pci/pci.c:557
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_find_vsec_capability
  - drivers/pci/pci.c:pci_get_dsn
```
**Symbols:**

```
ffffffff817be080-ffffffff817be160: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 pci_find_next_ext_capability(struct pci_dev *dev, u16 start, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818da350)
Location: drivers/pci/pci.c:541
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_find_vsec_capability
  - drivers/pci/pci.c:pci_get_dsn
```
**Symbols:**

```
ffffffff818da350-ffffffff818da430: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 pci_find_next_ext_capability(struct pci_dev *dev, u16 start, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191d690)
Location: drivers/pci/pci.c:556
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_find_vsec_capability
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/doe.c:pci_doe_init
```
**Symbols:**

```
ffffffff8191d690-ffffffff8191d770: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 pci_find_next_ext_capability(struct pci_dev *dev, u16 start, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81965ac0)
Location: drivers/pci/pci.c:556
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_init
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:_pci_add_cap_save_buffer
  - drivers/pci/pci.c:pci_restore_rebar_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_find_dvsec_capability
  - drivers/pci/pci.c:pci_find_vsec_capability
  - drivers/pci/pci.c:pci_get_dsn
  - drivers/pci/doe.c:pci_doe_init
```
**Symbols:**

```
ffffffff81965ac0-ffffffff81965ba0: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e3ea8)
Location: drivers/pci/pci.c:490
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffff8000106e3cb0-ffff8000106e3d88: pci_find_next_ext_capability.part.0 (STB_LOCAL)
ffff8000106e3d88-ffff8000106e3dec: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c087fd00)
Location: drivers/pci/pci.c:490
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
c087fb5c-c087fc44: pci_find_next_ext_capability.part.0 (STB_LOCAL)
c087fc44-c087fc74: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c00000000085e130)
Location: drivers/pci/pci.c:490
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - arch/powerpc/platforms/powernv/ocxl.c:find_dvsec_from_pos
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
c00000000085df50-c00000000085e08c: pci_find_next_ext_capability.part.0 (STB_LOCAL)
c00000000085e090-c00000000085e0b8: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bb2ba)
Location: drivers/pci/pci.c:490
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffe0004bb124-ffffffe0004bb1dc: pci_find_next_ext_capability.part.0 (STB_LOCAL)
ffffffe0004bb1dc-ffffffe0004bb224: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff815754a5)
Location: drivers/pci/pci.c:490
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81575360-ffffffff8157541a: pci_find_next_ext_capability.part.0 (STB_LOCAL)
ffffffff81575420-ffffffff8157543f: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81563c05)
Location: drivers/pci/pci.c:490
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81563ac0-ffffffff81563b7a: pci_find_next_ext_capability.part.0 (STB_LOCAL)
ffffffff81563b80-ffffffff81563b9f: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574cd5)
Location: drivers/pci/pci.c:490
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81574b90-ffffffff81574c4a: pci_find_next_ext_capability.part.0 (STB_LOCAL)
ffffffff81574c50-ffffffff81574c6f: pci_find_next_ext_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_find_next_ext_capability(struct pci_dev *dev, int start, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158f2a5)
Location: drivers/pci/pci.c:490
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_rebar_find_pos
  - drivers/pci/pci.c:pci_acs_flags_enabled
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_enable_acs
  - drivers/pci/pci.c:pci_configure_ari
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8158f160-ffffffff8158f21a: pci_find_next_ext_capability.part.0 (STB_LOCAL)
ffffffff8158f220-ffffffff8158f23f: pci_find_next_ext_capability (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int start</code> ➡️ <code>u16 start</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u16</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
