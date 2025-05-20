# Function: <code>dpc_process_rp_pio_error</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pcie-dpc.c (ffffffff8150482a)
Location: drivers/pci/pcie/pcie-dpc.c:238
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
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
In drivers/pci/pcie/dpc.c (ffffffff8153561b)
Location: drivers/pci/pcie/dpc.c:124
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct dpc_dev *dpc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff8154ca90)
Location: drivers/pci/pcie/dpc.c:149
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8154ca90-ffffffff8154cce3: dpc_process_rp_pio_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct dpc_dev *dpc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff8157ccf8)
Location: drivers/pci/pcie/dpc.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8157ccf8-ffffffff8157cf21: dpc_process_rp_pio_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct dpc_dev *dpc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff8159e758)
Location: drivers/pci/pcie/dpc.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8159e758-ffffffff8159e981: dpc_process_rp_pio_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff8163e518)
Location: drivers/pci/pcie/dpc.c:120
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff8163e518-ffffffff8163e739: dpc_process_rp_pio_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81bf9b20)
Location: drivers/pci/pcie/dpc.c:123
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff81bf9b20-ffffffff81bf9d41: dpc_process_rp_pio_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81beb919)
Location: drivers/pci/pcie/dpc.c:187
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff81beb919-ffffffff81bebb3a: dpc_process_rp_pio_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81ce64b0)
Location: drivers/pci/pcie/dpc.c:187
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff81ce64b0-ffffffff81ce6703: dpc_process_rp_pio_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81ead059)
Location: drivers/pci/pcie/dpc.c:187
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff81ead059-ffffffff81ead2fa: dpc_process_rp_pio_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff818fea60)
Location: drivers/pci/pcie/dpc.c:187
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff818fea60-ffffffff818fed4c: dpc_process_rp_pio_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81941e70)
Location: drivers/pci/pcie/dpc.c:186
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff81941e70-ffffffff8194215c: dpc_process_rp_pio_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff8198b100)
Location: drivers/pci/pcie/dpc.c:190
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff8198b100-ffffffff8198b3ec: dpc_process_rp_pio_error (STB_LOCAL)
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
void dpc_process_rp_pio_error(struct dpc_dev *dpc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffff800010706c94)
Location: drivers/pci/pcie/dpc.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffff800010706c94-ffff800010706f00: dpc_process_rp_pio_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct dpc_dev *dpc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (c089dbb4)
Location: drivers/pci/pcie/dpc.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
c089dbb4-c089de3c: dpc_process_rp_pio_error (STB_LOCAL)
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
void dpc_process_rp_pio_error(struct dpc_dev *dpc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffe0004d4866)
Location: drivers/pci/pcie/dpc.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffe0004d4866-ffffffe0004d4ade: dpc_process_rp_pio_error (STB_LOCAL)
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
void dpc_process_rp_pio_error(struct dpc_dev *dpc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81591f68)
Location: drivers/pci/pcie/dpc.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff81591f68-ffffffff81592191: dpc_process_rp_pio_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct dpc_dev *dpc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff815810f8)
Location: drivers/pci/pcie/dpc.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff815810f8-ffffffff81581321: dpc_process_rp_pio_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct dpc_dev *dpc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff815924a8)
Location: drivers/pci/pcie/dpc.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff815924a8-ffffffff815926d1: dpc_process_rp_pio_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dpc_process_rp_pio_error(struct dpc_dev *dpc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff815ac928)
Location: drivers/pci/pcie/dpc.c:150
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff815ac928-ffffffff815acb51: dpc_process_rp_pio_error (STB_LOCAL)
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
<code>struct pci_dev *pdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dpc_dev *dpc</code>
</li>
</ul>
</details>
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
