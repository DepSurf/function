# Function: <code>pcie_pme_handle_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8144bbcc)
Location: drivers/pci/pcie/pme.c:138
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff81497e6c)
Location: drivers/pci/pcie/pme.c:138
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff814b971c)
Location: drivers/pci/pcie/pme.c:137
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff814c3f97)
Location: drivers/pci/pcie/pme.c:131
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff815041e0)
Location: drivers/pci/pcie/pme.c:131
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8153514e)
Location: drivers/pci/pcie/pme.c:127
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8154c6fe)
Location: drivers/pci/pcie/pme.c:127
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8157c33d)
Location: drivers/pci/pcie/pme.c:129
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8159dd9d)
Location: drivers/pci/pcie/pme.c:129
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pcie_pme_handle_request(struct pci_dev *port, u16 req_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (0)
Location: drivers/pci/pcie/pme.c:129
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff8163d860-ffffffff8163da40: pcie_pme_handle_request (STB_LOCAL)
ffffffff8163dee1-ffffffff8163df23: pcie_pme_handle_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pcie_pme_handle_request(struct pci_dev *port, u16 req_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (0)
Location: drivers/pci/pcie/pme.c:129
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff81663ef0-ffffffff816640d0: pcie_pme_handle_request (STB_LOCAL)
ffffffff81bf9a1b-ffffffff81bf9a5d: pcie_pme_handle_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pcie_pme_handle_request(struct pci_dev *port, u16 req_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (0)
Location: drivers/pci/pcie/pme.c:129
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff81646360-ffffffff81646540: pcie_pme_handle_request (STB_LOCAL)
ffffffff81beb866-ffffffff81beb8a8: pcie_pme_handle_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pcie_pme_handle_request(struct pci_dev *port, u16 req_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (0)
Location: drivers/pci/pcie/pme.c:129
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff816b7bd0-ffffffff816b7db0: pcie_pme_handle_request (STB_LOCAL)
ffffffff81ce63bf-ffffffff81ce6401: pcie_pme_handle_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pcie_pme_handle_request(struct pci_dev *port, u16 req_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/pme.c (0)
Location: drivers/pci/pcie/pme.c:129
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff817dbfb0-ffffffff817dc179: pcie_pme_handle_request (STB_LOCAL)
ffffffff81eacf14-ffffffff81eacf4d: pcie_pme_handle_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcie_pme_handle_request(struct pci_dev *port, u16 req_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff818fde10)
Location: drivers/pci/pcie/pme.c:129
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff818fde10-ffffffff818fe046: pcie_pme_handle_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcie_pme_handle_request(struct pci_dev *port, u16 req_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff819412c0)
Location: drivers/pci/pcie/pme.c:129
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff819412c0-ffffffff819414f7: pcie_pme_handle_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcie_pme_handle_request(struct pci_dev *port, u16 req_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8198a520)
Location: drivers/pci/pcie/pme.c:130
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
**Symbols:**

```
ffffffff8198a520-ffffffff8198a757: pcie_pme_handle_request (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffff80001070625c)
Location: drivers/pci/pcie/pme.c:129
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (c089d1e8)
Location: drivers/pci/pcie/pme.c:129
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffe0004d3dcc)
Location: drivers/pci/pcie/pme.c:129
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8159159d)
Location: drivers/pci/pcie/pme.c:129
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff81580891)
Location: drivers/pci/pcie/pme.c:129
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff81591aed)
Location: drivers/pci/pcie/pme.c:129
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff815ac12e)
Location: drivers/pci/pcie/pme.c:129
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
