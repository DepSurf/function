# Function: <code>pcie_capability_write_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8142e310)
Location: drivers/pci/access.c:712
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff8142e310-ffffffff8142e38d: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814798e0)
Location: drivers/pci/access.c:823
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff814798e0-ffffffff81479951: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149ad70)
Location: drivers/pci/access.c:835
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff8149ad70-ffffffff8149ade1: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a4b00)
Location: drivers/pci/access.c:845
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff814a4b00-ffffffff814a4b74: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e38e0)
Location: drivers/pci/access.c:845
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aer/aerdrv.c:aer_error_resume
  - drivers/pci/pcie/aer/aerdrv.c:aer_probe
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff814e38e0-ffffffff814e3954: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815132d0)
Location: drivers/pci/access.c:478
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aer.c:aer_error_resume
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_reenable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff815132d0-ffffffff81513365: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81528a30)
Location: drivers/pci/access.c:478
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81528a30-ffffffff81528aa7: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81557de0)
Location: drivers/pci/access.c:478
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81557de0-ffffffff81557e4e: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff815793f0)
Location: drivers/pci/access.c:469
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff815793f0-ffffffff8157945e: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8161e4c0)
Location: drivers/pci/access.c:465
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pci.c:pci_restore_pcie_state
  - drivers/pci/pci.c:pci_restore_pcie_state
  - drivers/pci/pci.c:pci_restore_pcie_state
  - drivers/pci/pci.c:pci_restore_pcie_state
  - drivers/pci/pci.c:pci_restore_pcie_state
  - drivers/pci/pci.c:pci_restore_pcie_state
  - drivers/pci/pci.c:pci_restore_pcie_state
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff8161e4c0-ffffffff8161e546: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81644ce0)
Location: drivers/pci/access.c:465
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pci.c:pcie_clear_device_status
  - drivers/pci/pci.c:pci_restore_pcie_state
  - drivers/pci/pci.c:pci_restore_pcie_state
  - drivers/pci/pci.c:pci_restore_pcie_state
  - drivers/pci/pci.c:pci_restore_pcie_state
  - drivers/pci/pci.c:pci_restore_pcie_state
  - drivers/pci/pci.c:pci_restore_pcie_state
  - drivers/pci/pci.c:pci_restore_pcie_state
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81644ce0-ffffffff81644d71: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81627980)
Location: drivers/pci/access.c:465
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pci.c:pcie_clear_device_status
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81627980-ffffffff81627a11: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81697280)
Location: drivers/pci/access.c:465
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pci.c:pcie_clear_device_status
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81697280-ffffffff81697311: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff817b8a30)
Location: drivers/pci/access.c:470
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pci.c:pcie_clear_device_status
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff817b8a30-ffffffff817b8ad7: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff818d34b0)
Location: drivers/pci/access.c:476
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pci.c:pcie_clear_device_status
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff818d34b0-ffffffff818d3557: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81916510)
Location: drivers/pci/access.c:476
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word_locked
  - drivers/pci/pci.c:pcie_clear_device_status
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81916510-ffffffff819165b7: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8195e540)
Location: drivers/pci/access.c:476
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word_locked
  - drivers/pci/pci.c:pcie_clear_device_status
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/pci/quirks.c:pcie_failed_link_retrain
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff8195e540-ffffffff8195e5e7: pcie_capability_write_word (STB_GLOBAL)
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
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffff8000106dbdc0)
Location: drivers/pci/access.c:469
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffff8000106dbdc0-ffff8000106dbe54: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c0877dfc)
Location: drivers/pci/access.c:469
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
```
**Symbols:**

```
c0877dfc-c0877e74: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (c000000000853140)
Location: drivers/pci/access.c:469
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
```
**Symbols:**

```
c000000000853140-c000000000853238: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffe0004b3f38)
Location: drivers/pci/access.c:469
Inline: False
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffe0004b3f38-ffffffe0004b3fb2: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d910)
Location: drivers/pci/access.c:469
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff8156d910-ffffffff8156d97e: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8155c080)
Location: drivers/pci/access.c:469
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff8155c080-ffffffff8155c0ee: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8156d140)
Location: drivers/pci/access.c:469
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff8156d140-ffffffff8156d1ae: pcie_capability_write_word (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pcie_capability_write_word(struct pci_dev *dev, int pos, u16 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81587c40)
Location: drivers/pci/access.c:469
Inline: True
Direct callers:
  - drivers/pci/access.c:pcie_capability_clear_and_set_word
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:pci_aer_clear_device_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
**Symbols:**

```
ffffffff81587c40-ffffffff81587cae: pcie_capability_write_word (STB_GLOBAL)
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
