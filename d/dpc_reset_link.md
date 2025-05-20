# Function: <code>dpc_reset_link</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81535a70)
Location: drivers/pci/pcie/dpc.c:75
Inline: False
```
**Symbols:**

```
ffffffff81535a70-ffffffff81535bdd: dpc_reset_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff8154d0f0)
Location: drivers/pci/pcie/dpc.c:119
Inline: False
```
**Symbols:**

```
ffffffff8154d0f0-ffffffff8154d1fd: dpc_reset_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:120
Inline: False
```
**Symbols:**

```
ffffffff8157cb50-ffffffff8157cc3f: dpc_reset_link (STB_LOCAL)
ffffffff8157d0d7-ffffffff8157d0f4: dpc_reset_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:120
Inline: False
```
**Symbols:**

```
ffffffff8159e5b0-ffffffff8159e69f: dpc_reset_link (STB_LOCAL)
ffffffff8159eb37-ffffffff8159eb54: dpc_reset_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:92
Inline: False
```
**Symbols:**

```
ffffffff8163e4fa-ffffffff8163e518: dpc_reset_link.cold (STB_LOCAL)
ffffffff8163e090-ffffffff8163e167: dpc_reset_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:92
Inline: False
```
**Symbols:**

```
ffffffff81bf9ace-ffffffff81bf9b20: dpc_reset_link.cold (STB_LOCAL)
ffffffff81664630-ffffffff81664711: dpc_reset_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:144
Inline: False
```
**Symbols:**

```
ffffffff81bebb52-ffffffff81bebbb6: dpc_reset_link.cold (STB_LOCAL)
ffffffff81646d20-ffffffff81646e36: dpc_reset_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:144
Inline: False
```
**Symbols:**

```
ffffffff81ce6730-ffffffff81ce6794: dpc_reset_link.cold (STB_LOCAL)
ffffffff816b85d0-ffffffff816b86e6: dpc_reset_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:144
Inline: False
```
**Symbols:**

```
ffffffff81eacffe-ffffffff81ead059: dpc_reset_link.cold (STB_LOCAL)
ffffffff817dc780-ffffffff817dc8c4: dpc_reset_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff818fe8c0)
Location: drivers/pci/pcie/dpc.c:144
Inline: False
```
**Symbols:**

```
ffffffff818fe8c0-ffffffff818fea4e: dpc_reset_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff81941cd0)
Location: drivers/pci/pcie/dpc.c:144
Inline: False
```
**Symbols:**

```
ffffffff81941cd0-ffffffff81941e59: dpc_reset_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff8198af60)
Location: drivers/pci/pcie/dpc.c:148
Inline: False
```
**Symbols:**

```
ffffffff8198af60-ffffffff8198b0e9: dpc_reset_link (STB_GLOBAL)
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
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffff800010706a60)
Location: drivers/pci/pcie/dpc.c:120
Inline: False
```
**Symbols:**

```
ffff800010706a60-ffff800010706ba4: dpc_reset_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (c089d568)
Location: drivers/pci/pcie/dpc.c:120
Inline: False
```
**Symbols:**

```
c089d568-c089d698: dpc_reset_link (STB_LOCAL)
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
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffe0004d4690)
Location: drivers/pci/pcie/dpc.c:120
Inline: False
```
**Symbols:**

```
ffffffe0004d4690-ffffffe0004d478a: dpc_reset_link (STB_LOCAL)
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
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:120
Inline: False
```
**Symbols:**

```
ffffffff81591dc0-ffffffff81591eaf: dpc_reset_link (STB_LOCAL)
ffffffff81592347-ffffffff81592364: dpc_reset_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:120
Inline: False
```
**Symbols:**

```
ffffffff81580f50-ffffffff8158103f: dpc_reset_link (STB_LOCAL)
ffffffff815814d7-ffffffff815814f4: dpc_reset_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:120
Inline: False
```
**Symbols:**

```
ffffffff81592300-ffffffff815923ef: dpc_reset_link (STB_LOCAL)
ffffffff81592887-ffffffff815928a4: dpc_reset_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
pci_ers_result_t dpc_reset_link(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:120
Inline: False
```
**Symbols:**

```
ffffffff815ac780-ffffffff815ac86f: dpc_reset_link (STB_LOCAL)
ffffffff815acd07-ffffffff815acd24: dpc_reset_link.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
