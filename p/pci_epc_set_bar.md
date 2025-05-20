# Function: <code>pci_epc_set_bar</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, enum pci_barno bar, dma_addr_t bar_phys, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff814d20d0)
Location: drivers/pci/endpoint/pci-epc-core.c:312
Inline: True
```
**Symbols:**

```
ffffffff814d20d0-ffffffff814d2163: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, enum pci_barno bar, dma_addr_t bar_phys, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81512500)
Location: drivers/pci/endpoint/pci-epc-core.c:313
Inline: True
```
**Symbols:**

```
ffffffff81512500-ffffffff8151259d: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815478c0)
Location: drivers/pci/endpoint/pci-epc-core.c:310
Inline: True
```
**Symbols:**

```
ffffffff815478c0-ffffffff8154798a: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8155e050)
Location: drivers/pci/endpoint/pci-epc-core.c:368
Inline: True
```
**Symbols:**

```
ffffffff8155e050-ffffffff8155e11a: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8158dc80)
Location: drivers/pci/endpoint/pci-epc-core.c:421
Inline: False
```
**Symbols:**

```
ffffffff8158dc80-ffffffff8158dd63: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815af8a0)
Location: drivers/pci/endpoint/pci-epc-core.c:421
Inline: False
```
**Symbols:**

```
ffffffff815af8a0-ffffffff815af983: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81658b10)
Location: drivers/pci/endpoint/pci-epc-core.c:410
Inline: False
```
**Symbols:**

```
ffffffff81658b10-ffffffff81658be5: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81678f10)
Location: drivers/pci/endpoint/pci-epc-core.c:410
Inline: False
```
**Symbols:**

```
ffffffff81678f10-ffffffff81678fe5: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165b880)
Location: drivers/pci/endpoint/pci-epc-core.c:477
Inline: False
```
**Symbols:**

```
ffffffff8165b880-ffffffff8165b955: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816cde70)
Location: drivers/pci/endpoint/pci-epc-core.c:522
Inline: False
```
**Symbols:**

```
ffffffff816cde70-ffffffff816cdf6f: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff817f6ac0)
Location: drivers/pci/endpoint/pci-epc-core.c:522
Inline: False
```
**Symbols:**

```
ffffffff817f6ac0-ffffffff817f6be9: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81922590)
Location: drivers/pci/endpoint/pci-epc-core.c:522
Inline: False
```
**Symbols:**

```
ffffffff81922590-ffffffff819226b9: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81965ff0)
Location: drivers/pci/endpoint/pci-epc-core.c:522
Inline: False
```
**Symbols:**

```
ffffffff81965ff0-ffffffff81966119: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, u8 vfunc_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819af700)
Location: drivers/pci/endpoint/pci-epc-core.c:521
Inline: False
```
**Symbols:**

```
ffffffff819af700-ffffffff819af829: pci_epc_set_bar (STB_GLOBAL)
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
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071be30)
Location: drivers/pci/endpoint/pci-epc-core.c:421
Inline: False
```
**Symbols:**

```
ffff80001071be30-ffff80001071bf70: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (c08a5520)
Location: drivers/pci/endpoint/pci-epc-core.c:421
Inline: True
```
**Symbols:**

```
c08a5520-c08a55e4: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (c00000000088b200)
Location: drivers/pci/endpoint/pci-epc-core.c:421
Inline: False
```
**Symbols:**

```
c00000000088b200-c00000000088b388: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffe0004e25e6)
Location: drivers/pci/endpoint/pci-epc-core.c:421
Inline: False
```
**Symbols:**

```
ffffffe0004e25e6-ffffffe0004e2696: pci_epc_set_bar (STB_GLOBAL)
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
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a3060)
Location: drivers/pci/endpoint/pci-epc-core.c:421
Inline: False
```
**Symbols:**

```
ffffffff815a3060-ffffffff815a3143: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81592200)
Location: drivers/pci/endpoint/pci-epc-core.c:421
Inline: False
```
**Symbols:**

```
ffffffff81592200-ffffffff815922e3: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a35f0)
Location: drivers/pci/endpoint/pci-epc-core.c:421
Inline: False
```
**Symbols:**

```
ffffffff815a35f0-ffffffff815a36d3: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_epc_set_bar(struct pci_epc *epc, u8 func_no, struct pci_epf_bar *epf_bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815bd9f0)
Location: drivers/pci/endpoint/pci-epc-core.c:421
Inline: False
```
**Symbols:**

```
ffffffff815bd9f0-ffffffff815bdad3: pci_epc_set_bar (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 func_no</code>
</li>
<li>
<b>Param added. </b>
<code>struct pci_epf_bar *epf_bar</code>
</li>
<li>
<b>Param removed. </b>
<code>enum pci_barno bar</code>
</li>
<li>
<b>Param removed. </b>
<code>dma_addr_t bar_phys</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>int flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 vfunc_no</code>
</li>
<li>
<b>Param reordered. </b>
<code>epc, func_no, epf_bar</code> ➡️ <code>epc, func_no, vfunc_no, epf_bar</code>
</li>
</ul>
</details>
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
