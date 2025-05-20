# Function: <code>pci_find_saved_ext_cap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81436ab0)
Location: drivers/pci/pci.c:956
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_restore_vc_state
```
**Symbols:**

```
ffffffff81436ab0-ffffffff81436adf: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81482640)
Location: drivers/pci/pci.c:977
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
```
**Symbols:**

```
ffffffff81482640-ffffffff8148266f: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a3bd0)
Location: drivers/pci/pci.c:1002
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
```
**Symbols:**

```
ffffffff814a3bd0-ffffffff814a3bff: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814adc00)
Location: drivers/pci/pci.c:998
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
```
**Symbols:**

```
ffffffff814adc00-ffffffff814adc2b: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ecfe0)
Location: drivers/pci/pci.c:1001
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
```
**Symbols:**

```
ffffffff814ecfe0-ffffffff814ed00b: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151cc00)
Location: drivers/pci/pci.c:1013
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
```
**Symbols:**

```
ffffffff8151cc00-ffffffff8151cc2d: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81532300)
Location: drivers/pci/pci.c:1184
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff81532300-ffffffff8153232d: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81560c99)
Location: drivers/pci/pci.c:1213
Inline: True
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff815619d0-ffffffff815619fd: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81581ea7)
Location: drivers/pci/pci.c:1209
Inline: True
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff81582b70-ffffffff81582b9d: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81628c2f)
Location: drivers/pci/pci.c:1274
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_save_state
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff81629710-ffffffff8162973d: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164ee52)
Location: drivers/pci/pci.c:1408
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_save_state
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
```
**Symbols:**

```
ffffffff8164fae0-ffffffff8164fb0d: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81631922)
Location: drivers/pci/pci.c:1438
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_save_state
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
```
**Symbols:**

```
ffffffff81632690-ffffffff816326bd: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a11ca)
Location: drivers/pci/pci.c:1448
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_save_state
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
```
**Symbols:**

```
ffffffff81ce4835-ffffffff81ce4851: pci_find_saved_ext_cap.cold (STB_LOCAL)
ffffffff816a1d80-ffffffff816a1dd9: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c3142)
Location: drivers/pci/pci.c:1509
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_save_state
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/aspm.c:pci_restore_aspm_l1ss_state
  - drivers/pci/pcie/aspm.c:pci_save_aspm_l1ss_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
```
**Symbols:**

```
ffffffff81eab29a-ffffffff81eab2b6: pci_find_saved_ext_cap.cold (STB_LOCAL)
ffffffff817c3dd0-ffffffff817c3e41: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dfef7)
Location: drivers/pci/pci.c:1487
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_save_state
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
```
**Symbols:**

```
ffffffff8208f17a-ffffffff8208f196: pci_find_saved_ext_cap.cold (STB_LOCAL)
ffffffff818e0cc0-ffffffff818e0d31: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81923357)
Location: drivers/pci/pci.c:1525
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_save_state
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
```
**Symbols:**

```
ffffffff8210f4e0-ffffffff8210f4fc: pci_find_saved_ext_cap.cold (STB_LOCAL)
ffffffff81924100-ffffffff81924171: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196b8d7)
Location: drivers/pci/pci.c:1623
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_save_state
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/aer.c:pci_restore_aer_state
  - drivers/pci/pcie/aer.c:pci_save_aer_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
```
**Symbols:**

```
ffffffff821ed167-ffffffff821ed183: pci_find_saved_ext_cap.cold (STB_LOCAL)
ffffffff8196c7d0-ffffffff8196c841: pci_find_saved_ext_cap (STB_GLOBAL)
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
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e511c)
Location: drivers/pci/pci.c:1209
Inline: True
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffff8000106e6828-ffff8000106e6878: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0880d6c)
Location: drivers/pci/pci.c:1209
Inline: True
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
c0881b18-c0881b64: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085f888)
Location: drivers/pci/pci.c:1209
Inline: True
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
```
**Symbols:**

```
c000000000860c70-c000000000860cc4: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bc35e)
Location: drivers/pci/pci.c:1209
Inline: True
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffe0004bd1dc-ffffffe0004bd220: pci_find_saved_ext_cap (STB_GLOBAL)
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
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815763c7)
Location: drivers/pci/pci.c:1209
Inline: True
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff81577090-ffffffff815770bd: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564b27)
Location: drivers/pci/pci.c:1209
Inline: True
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff815657f0-ffffffff8156581d: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575bf7)
Location: drivers/pci/pci.c:1209
Inline: True
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff815768c0-ffffffff815768ed: pci_find_saved_ext_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct pci_cap_saved_state *pci_find_saved_ext_cap(struct pci_dev *dev, u16 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815901c7)
Location: drivers/pci/pci.c:1209
Inline: True
Direct callers:
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
**Symbols:**

```
ffffffff81590da0-ffffffff81590dcd: pci_find_saved_ext_cap (STB_GLOBAL)
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
