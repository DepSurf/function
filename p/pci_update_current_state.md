# Function: <code>pci_update_current_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81436470)
Location: drivers/pci/pci.c:688
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci-driver.c:pci_restore_standard_config
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
```
**Symbols:**

```
ffffffff81436470-ffffffff814364e9: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81481fb0)
Location: drivers/pci/pci.c:709
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff81481fb0-ffffffff81482038: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a3520)
Location: drivers/pci/pci.c:741
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff814a3520-ffffffff814a35cc: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ad500)
Location: drivers/pci/pci.c:736
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff814ad500-ffffffff814ad5b3: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ec8d0)
Location: drivers/pci/pci.c:737
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff814ec8d0-ffffffff814ec989: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151c4b0)
Location: drivers/pci/pci.c:749
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff8151c4b0-ffffffff8151c569: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81531da0)
Location: drivers/pci/pci.c:920
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff81531da0-ffffffff81531e58: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81561420)
Location: drivers/pci/pci.c:931
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff81561420-ffffffff815614d8: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815825e0)
Location: drivers/pci/pci.c:931
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff815825e0-ffffffff8158268e: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81628f20)
Location: drivers/pci/pci.c:984
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff81628f20-ffffffff81628fd6: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164f170)
Location: drivers/pci/pci.c:1124
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff8164f170-ffffffff8164f226: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81631c40)
Location: drivers/pci/pci.c:1154
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff81631c40-ffffffff81631cf6: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a1560)
Location: drivers/pci/pci.c:1164
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff816a1560-ffffffff816a1616: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c3461)
Location: drivers/pci/pci.c:1099
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci.c:pci_refresh_power_state
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff817c3310-ffffffff817c33b9: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e0261)
Location: drivers/pci/pci.c:1083
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci.c:pci_refresh_power_state
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff818e00f0-ffffffff818e0199: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819236c1)
Location: drivers/pci/pci.c:1097
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci.c:pci_refresh_power_state
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff81923550-ffffffff819235f9: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196bce1)
Location: drivers/pci/pci.c:1160
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci.c:pci_refresh_power_state
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:__pci_set_power_state
  - drivers/pci/pci.c:__pci_set_power_state
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_thaw_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff8196bb70-ffffffff8196bc19: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e6170)
Location: drivers/pci/pci.c:931
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffff8000106e6170-ffff8000106e623c: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c08814b4)
Location: drivers/pci/pci.c:931
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
c08814b4-c0881584: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0000000008602c0)
Location: drivers/pci/pci.c:931
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
c0000000008602c0-c0000000008603cc: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bcc9a)
Location: drivers/pci/pci.c:931
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
```
**Symbols:**

```
ffffffe0004bcc9a-ffffffe0004bcd24: pci_update_current_state (STB_GLOBAL)
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
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576b00)
Location: drivers/pci/pci.c:931
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff81576b00-ffffffff81576bae: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81565260)
Location: drivers/pci/pci.c:931
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff81565260-ffffffff8156530e: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576330)
Location: drivers/pci/pci.c:931
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff81576330-ffffffff815763de: pci_update_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pci_update_current_state(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81590810)
Location: drivers/pci/pci.c:931
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_platform_power_transition
  - drivers/pci/pci.c:pci_refresh_power_state
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff81590810-ffffffff815908be: pci_update_current_state (STB_GLOBAL)
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
