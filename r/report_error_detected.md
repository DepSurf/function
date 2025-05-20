# Function: <code>report_error_detected</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff8144a5b0)
Location: drivers/pci/pcie/aer/aerdrv_core.c:235
Inline: False
```
**Symbols:**

```
ffffffff8144a5b0-ffffffff8144a696: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81496870)
Location: drivers/pci/pcie/aer/aerdrv_core.c:235
Inline: False
```
**Symbols:**

```
ffffffff81496870-ffffffff81496957: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b8210)
Location: drivers/pci/pcie/aer/aerdrv_core.c:237
Inline: False
```
**Symbols:**

```
ffffffff814b8210-ffffffff814b82f7: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814c2a80)
Location: drivers/pci/pcie/aer/aerdrv_core.c:237
Inline: False
```
**Symbols:**

```
ffffffff814c2a80-ffffffff814c2b6f: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81502cc0)
Location: drivers/pci/pcie/aer/aerdrv_core.c:237
Inline: False
```
**Symbols:**

```
ffffffff81502cc0-ffffffff81502db2: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81530d60)
Location: drivers/pci/pcie/err.c:52
Inline: False
```
**Symbols:**

```
ffffffff81530d60-ffffffff81530e4d: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, enum pci_channel_state state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff815482f0)
Location: drivers/pci/pcie/err.c:46
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:report_normal_detected
  - drivers/pci/pcie/err.c:report_frozen_detected
```
**Symbols:**

```
ffffffff815482f0-ffffffff815483ca: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, enum pci_channel_state state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81578370)
Location: drivers/pci/pcie/err.c:46
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:report_normal_detected
  - drivers/pci/pcie/err.c:report_frozen_detected
```
**Symbols:**

```
ffffffff81578370-ffffffff81578488: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, enum pci_channel_state state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81599af0)
Location: drivers/pci/pcie/err.c:46
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:report_normal_detected
  - drivers/pci/pcie/err.c:report_frozen_detected
```
**Symbols:**

```
ffffffff81599af0-ffffffff81599c08: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int report_error_detected(struct pci_dev *dev, enum pci_channel_state state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:48
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:report_normal_detected
  - drivers/pci/pcie/err.c:report_frozen_detected
```
**Symbols:**

```
ffffffff816391a0-ffffffff81639289: report_error_detected (STB_LOCAL)
ffffffff8163960a-ffffffff81639635: report_error_detected.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int report_error_detected(struct pci_dev *dev, pci_channel_state_t state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:48
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff8165fcc0-ffffffff8165fda9: report_error_detected (STB_LOCAL)
ffffffff81bf8f37-ffffffff81bf8f62: report_error_detected.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int report_error_detected(struct pci_dev *dev, pci_channel_state_t state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:48
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff816421b0-ffffffff81642299: report_error_detected (STB_LOCAL)
ffffffff81bead6b-ffffffff81bead96: report_error_detected.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int report_error_detected(struct pci_dev *dev, pci_channel_state_t state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:48
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff816b2e90-ffffffff816b2f7f: report_error_detected (STB_LOCAL)
ffffffff81ce5c63-ffffffff81ce5c8e: report_error_detected.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int report_error_detected(struct pci_dev *dev, pci_channel_state_t state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/err.c (0)
Location: drivers/pci/pcie/err.c:48
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff817db830-ffffffff817db929: report_error_detected (STB_LOCAL)
ffffffff81eacec1-ffffffff81eaceeb: report_error_detected.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, pci_channel_state_t state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff818fd480)
Location: drivers/pci/pcie/err.c:48
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff818fd480-ffffffff818fd634: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, pci_channel_state_t state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81940910)
Location: drivers/pci/pcie/err.c:48
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff81940910-ffffffff81940acb: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, pci_channel_state_t state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81989b70)
Location: drivers/pci/pcie/err.c:48
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff81989b70-ffffffff81989d2b: report_error_detected (STB_LOCAL)
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
int report_error_detected(struct pci_dev *dev, enum pci_channel_state state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffff800010701368)
Location: drivers/pci/pcie/err.c:46
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:report_normal_detected
  - drivers/pci/pcie/err.c:report_frozen_detected
```
**Symbols:**

```
ffff800010701368-ffff800010701490: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, enum pci_channel_state state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (c0899014)
Location: drivers/pci/pcie/err.c:46
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:report_normal_detected
  - drivers/pci/pcie/err.c:report_frozen_detected
```
**Symbols:**

```
c0899014-c0899100: report_error_detected (STB_LOCAL)
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
int report_error_detected(struct pci_dev *dev, enum pci_channel_state state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffe0004d0056)
Location: drivers/pci/pcie/err.c:46
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:report_normal_detected
  - drivers/pci/pcie/err.c:report_frozen_detected
```
**Symbols:**

```
ffffffe0004d0056-ffffffe0004d0132: report_error_detected (STB_LOCAL)
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
int report_error_detected(struct pci_dev *dev, enum pci_channel_state state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8158d980)
Location: drivers/pci/pcie/err.c:46
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:report_normal_detected
  - drivers/pci/pcie/err.c:report_frozen_detected
```
**Symbols:**

```
ffffffff8158d980-ffffffff8158da98: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, enum pci_channel_state state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8157c4c0)
Location: drivers/pci/pcie/err.c:46
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:report_normal_detected
  - drivers/pci/pcie/err.c:report_frozen_detected
```
**Symbols:**

```
ffffffff8157c4c0-ffffffff8157c5d8: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, enum pci_channel_state state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff8158d840)
Location: drivers/pci/pcie/err.c:46
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:report_normal_detected
  - drivers/pci/pcie/err.c:report_frozen_detected
```
**Symbols:**

```
ffffffff8158d840-ffffffff8158d958: report_error_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int report_error_detected(struct pci_dev *dev, enum pci_channel_state state, enum pci_ers_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff815a7cf0)
Location: drivers/pci/pcie/err.c:46
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:report_normal_detected
  - drivers/pci/pcie/err.c:report_frozen_detected
```
**Symbols:**

```
ffffffff815a7cf0-ffffffff815a7e08: report_error_detected (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum pci_channel_state state</code>
</li>
<li>
<b>Param added. </b>
<code>enum pci_ers_result *result</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
</ul>
</details>
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
