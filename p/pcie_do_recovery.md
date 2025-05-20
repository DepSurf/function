# Function: <code>pcie_do_recovery</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcie_do_recovery(struct pci_dev *dev, enum pci_channel_state state, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81548410)
Location: drivers/pci/pcie/err.c:186
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff81548410-ffffffff815486ce: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pcie_do_recovery(struct pci_dev *dev, enum pci_channel_state state, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:186
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff81578734-ffffffff81578798: pcie_do_recovery.cold (STB_LOCAL)
ffffffff815784d0-ffffffff81578734: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pcie_do_recovery(struct pci_dev *dev, enum pci_channel_state state, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:186
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff81599ec5-ffffffff81599f29: pcie_do_recovery.cold (STB_LOCAL)
ffffffff81599c50-ffffffff81599ec5: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t pcie_do_recovery(struct pci_dev *dev, enum pci_channel_state state, pci_ers_result_t (*reset_link)(struct pci_dev *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:149
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff81639635-ffffffff81639649: pcie_do_recovery.cold (STB_LOCAL)
ffffffff81639410-ffffffff8163960a: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t pcie_do_recovery(struct pci_dev *dev, pci_channel_state_t state, pci_ers_result_t (*reset_subordinates)(struct pci_dev *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:172
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff81bf8f62-ffffffff81bf8f8d: pcie_do_recovery.cold (STB_LOCAL)
ffffffff8165ff30-ffffffff8166022a: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t pcie_do_recovery(struct pci_dev *dev, pci_channel_state_t state, pci_ers_result_t (*reset_subordinates)(struct pci_dev *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:172
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff81bead96-ffffffff81beadc1: pcie_do_recovery.cold (STB_LOCAL)
ffffffff81642420-ffffffff81642714: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t pcie_do_recovery(struct pci_dev *dev, pci_channel_state_t state, pci_ers_result_t (*reset_subordinates)(struct pci_dev *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:172
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff81ce5c8e-ffffffff81ce5cb7: pcie_do_recovery.cold (STB_LOCAL)
ffffffff816b3100-ffffffff816b3414: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t pcie_do_recovery(struct pci_dev *dev, pci_channel_state_t state, pci_ers_result_t (*reset_subordinates)(struct pci_dev *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:180
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/edr.c:edr_handle_event
```
**Symbols:**

```
ffffffff81eaceeb-ffffffff81eacf14: pcie_do_recovery.cold (STB_LOCAL)
ffffffff817dbad0-ffffffff817dbdee: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t pcie_do_recovery(struct pci_dev *dev, pci_channel_state_t state, pci_ers_result_t (*reset_subordinates)(struct pci_dev *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:184
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/edr.c:edr_handle_event
```
**Symbols:**

```
ffffffff8208f633-ffffffff8208f648: pcie_do_recovery.cold (STB_LOCAL)
ffffffff818fd8d0-ffffffff818fdc0e: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t pcie_do_recovery(struct pci_dev *dev, pci_channel_state_t state, pci_ers_result_t (*reset_subordinates)(struct pci_dev *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:184
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/edr.c:edr_handle_event
```
**Symbols:**

```
ffffffff8210f994-ffffffff8210f9a9: pcie_do_recovery.cold (STB_LOCAL)
ffffffff81940d80-ffffffff819410b7: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t pcie_do_recovery(struct pci_dev *dev, pci_channel_state_t state, pci_ers_result_t (*reset_subordinates)(struct pci_dev *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:184
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/edr.c:edr_handle_event
```
**Symbols:**

```
ffffffff821ed6bc-ffffffff821ed6d1: pcie_do_recovery.cold (STB_LOCAL)
ffffffff81989fe0-ffffffff8198a317: pcie_do_recovery (STB_GLOBAL)
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
void pcie_do_recovery(struct pci_dev *dev, enum pci_channel_state state, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffff800010701500)
Location: drivers/pci/pcie/err.c:186
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffff800010701500-ffff8000107017fc: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcie_do_recovery(struct pci_dev *dev, enum pci_channel_state state, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (c0899148)
Location: drivers/pci/pcie/err.c:186
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
c0899148-c0899430: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcie_do_recovery(struct pci_dev *dev, enum pci_channel_state state, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffe0004d019a)
Location: drivers/pci/pcie/err.c:186
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffe0004d019a-ffffffe0004d042a: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void pcie_do_recovery(struct pci_dev *dev, enum pci_channel_state state, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:186
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8158dd55-ffffffff8158ddb9: pcie_do_recovery.cold (STB_LOCAL)
ffffffff8158dae0-ffffffff8158dd55: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pcie_do_recovery(struct pci_dev *dev, enum pci_channel_state state, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:186
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8157c895-ffffffff8157c8f9: pcie_do_recovery.cold (STB_LOCAL)
ffffffff8157c620-ffffffff8157c895: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pcie_do_recovery(struct pci_dev *dev, enum pci_channel_state state, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:186
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8158dc15-ffffffff8158dc79: pcie_do_recovery.cold (STB_LOCAL)
ffffffff8158d9a0-ffffffff8158dc15: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pcie_do_recovery(struct pci_dev *dev, enum pci_channel_state state, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:186
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/aer.c:aer_recover_work_func
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff815a80c5-ffffffff815a8129: pcie_do_recovery.cold (STB_LOCAL)
ffffffff815a7e50-ffffffff815a80c5: pcie_do_recovery (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pci_ers_result_t (*reset_link)(struct pci_dev *)</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 service</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>pci_ers_result_t</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pci_ers_result_t (*reset_subordinates)(struct pci_dev *)</code>
</li>
<li>
<b>Param removed. </b>
<code>pci_ers_result_t (*reset_link)(struct pci_dev *)</code>
</li>
<li>
<b>Param type changed. </b>
<code>enum pci_channel_state state</code> ➡️ <code>pci_channel_state_t state</code>
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
