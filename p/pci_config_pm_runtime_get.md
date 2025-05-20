# Function: <code>pci_config_pm_runtime_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814372c0)
Location: drivers/pci/pci.c:2127
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffff814372c0-ffffffff81437315: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81482e80)
Location: drivers/pci/pci.c:2148
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff81482e80-ffffffff81482ed8: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a4410)
Location: drivers/pci/pci.c:2190
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff814a4410-ffffffff814a4468: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ae4d0)
Location: drivers/pci/pci.c:2207
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff814ae4d0-ffffffff814ae528: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ed8a0)
Location: drivers/pci/pci.c:2216
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff814ed8a0-ffffffff814ed8f8: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151d500)
Location: drivers/pci/pci.c:2295
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff8151d500-ffffffff8151d558: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81532c00)
Location: drivers/pci/pci.c:2472
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff81532c00-ffffffff81532c58: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81562350)
Location: drivers/pci/pci.c:2565
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff81562350-ffffffff815623a8: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815834f0)
Location: drivers/pci/pci.c:2561
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff815834f0-ffffffff81583548: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162a0b0)
Location: drivers/pci/pci.c:2631
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff8162a0b0-ffffffff8162a108: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81650510)
Location: drivers/pci/pci.c:2798
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff81650510-ffffffff81650568: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816330c0)
Location: drivers/pci/pci.c:2828
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff816330c0-ffffffff81633118: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a3230)
Location: drivers/pci/pci.c:2870
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff816a3230-ffffffff816a3288: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c5430)
Location: drivers/pci/pci.c:2945
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff817c5430-ffffffff817c549c: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e24f0)
Location: drivers/pci/pci.c:2895
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource5_resize_show
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_show
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_show
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_show
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_show
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_show
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff818e24f0-ffffffff818e255c: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81925930)
Location: drivers/pci/pci.c:2933
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource5_resize_show
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_show
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_show
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_show
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_show
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_show
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff81925930-ffffffff8192599c: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196e0b0)
Location: drivers/pci/pci.c:3046
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource5_resize_show
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_show
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_show
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_show
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_show
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_show
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/vpd.c:vpd_write
  - drivers/pci/vpd.c:vpd_read
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff8196e0b0-ffffffff8196e11c: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e7460)
Location: drivers/pci/pci.c:2561
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffff8000106e7460-ffff8000106e74f4: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0882598)
Location: drivers/pci/pci.c:2561
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
c0882598-c0882608: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000861bc0)
Location: drivers/pci/pci.c:2561
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
c000000000861bc0-c000000000861c78: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bdbfc)
Location: drivers/pci/pci.c:2561
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffe0004bdbfc-ffffffe0004bdc68: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81577a10)
Location: drivers/pci/pci.c:2561
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff81577a10-ffffffff81577a68: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81566150)
Location: drivers/pci/pci.c:2561
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff81566150-ffffffff815661a8: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81577240)
Location: drivers/pci/pci.c:2561
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff81577240-ffffffff81577298: pci_config_pm_runtime_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_config_pm_runtime_get(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81591700)
Location: drivers/pci/pci.c:2561
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff81591700-ffffffff81591758: pci_config_pm_runtime_get (STB_GLOBAL)
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
