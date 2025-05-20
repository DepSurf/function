# Function: <code>pci_config_pm_runtime_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81437320)
Location: drivers/pci/pci.c:2149
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_write
```
**Symbols:**

```
ffffffff81437320-ffffffff81437353: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81482ee0)
Location: drivers/pci/pci.c:2170
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff81482ee0-ffffffff81482f13: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a4470)
Location: drivers/pci/pci.c:2212
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff814a4470-ffffffff814a44a3: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ae530)
Location: drivers/pci/pci.c:2229
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff814ae530-ffffffff814ae563: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ed900)
Location: drivers/pci/pci.c:2238
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff814ed900-ffffffff814ed933: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151d560)
Location: drivers/pci/pci.c:2317
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
ffffffff8151d560-ffffffff8151d593: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81532c60)
Location: drivers/pci/pci.c:2494
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff81532c60-ffffffff81532c93: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815623b0)
Location: drivers/pci/pci.c:2587
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff815623b0-ffffffff815623e6: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81583550)
Location: drivers/pci/pci.c:2583
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff81583550-ffffffff81583586: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162a110)
Location: drivers/pci/pci.c:2653
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
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
ffffffff8162a110-ffffffff8162a148: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81650570)
Location: drivers/pci/pci.c:2820
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
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
ffffffff81650570-ffffffff816505a8: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81633120)
Location: drivers/pci/pci.c:2850
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
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
ffffffff81633120-ffffffff81633158: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a3290)
Location: drivers/pci/pci.c:2892
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
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
ffffffff816a3290-ffffffff816a32c8: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c54a0)
Location: drivers/pci/pci.c:2967
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
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
ffffffff817c54a0-ffffffff817c54e1: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e2570)
Location: drivers/pci/pci.c:2917
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource5_resize_show
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_show
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_show
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_show
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_show
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_show
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
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
ffffffff818e2570-ffffffff818e25b1: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819259b0)
Location: drivers/pci/pci.c:2955
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource5_resize_show
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_show
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_show
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_show
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_show
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_show
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
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
ffffffff819259b0-ffffffff819259f1: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196e130)
Location: drivers/pci/pci.c:3068
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource5_resize_show
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_show
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_show
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_show
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_show
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_show
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
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
ffffffff8196e130-ffffffff8196e171: pci_config_pm_runtime_put (STB_GLOBAL)
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
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e74f8)
Location: drivers/pci/pci.c:2583
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffff8000106e74f8-ffff8000106e753c: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0882608)
Location: drivers/pci/pci.c:2583
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
c0882608-c0882648: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000861c80)
Location: drivers/pci/pci.c:2583
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
**Symbols:**

```
c000000000861c80-c000000000861ce0: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bdc68)
Location: drivers/pci/pci.c:2583
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffe0004bdc68-ffffffe0004bdcae: pci_config_pm_runtime_put (STB_GLOBAL)
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
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81577a70)
Location: drivers/pci/pci.c:2583
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff81577a70-ffffffff81577aa6: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815661b0)
Location: drivers/pci/pci.c:2583
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff815661b0-ffffffff815661e6: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815772a0)
Location: drivers/pci/pci.c:2583
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff815772a0-ffffffff815772d6: pci_config_pm_runtime_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_config_pm_runtime_put(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81591760)
Location: drivers/pci/pci.c:2583
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/pci-sysfs.c:pci_read_config
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:get_latch_status
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_raw_indicator_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status
```
**Symbols:**

```
ffffffff81591760-ffffffff81591796: pci_config_pm_runtime_put (STB_GLOBAL)
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
