# Function: <code>pci_epc_set_msix</code>

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
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8155d7c0)
Location: drivers/pci/endpoint/pci-epc-core.c:258
Inline: False
```
**Symbols:**

```
ffffffff8155d7c0-ffffffff8155d857: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8158dbc0)
Location: drivers/pci/endpoint/pci-epc-core.c:311
Inline: False
```
**Symbols:**

```
ffffffff8158dbc0-ffffffff8158dc71: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815af7e0)
Location: drivers/pci/endpoint/pci-epc-core.c:311
Inline: False
```
**Symbols:**

```
ffffffff815af7e0-ffffffff815af891: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81658a50)
Location: drivers/pci/endpoint/pci-epc-core.c:305
Inline: False
```
**Symbols:**

```
ffffffff81658a50-ffffffff81658b0b: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81678e50)
Location: drivers/pci/endpoint/pci-epc-core.c:305
Inline: False
```
**Symbols:**

```
ffffffff81678e50-ffffffff81678f0b: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165b7c0)
Location: drivers/pci/endpoint/pci-epc-core.c:372
Inline: False
```
**Symbols:**

```
ffffffff8165b7c0-ffffffff8165b878: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816cdca0)
Location: drivers/pci/endpoint/pci-epc-core.c:399
Inline: False
```
**Symbols:**

```
ffffffff816cdca0-ffffffff816cdd8d: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff817f6890)
Location: drivers/pci/endpoint/pci-epc-core.c:399
Inline: False
```
**Symbols:**

```
ffffffff817f6890-ffffffff817f69c3: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81922340)
Location: drivers/pci/endpoint/pci-epc-core.c:399
Inline: False
```
**Symbols:**

```
ffffffff81922340-ffffffff81922473: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81965da0)
Location: drivers/pci/endpoint/pci-epc-core.c:399
Inline: False
```
**Symbols:**

```
ffffffff81965da0-ffffffff81965ed3: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u16 interrupts, enum pci_barno bir, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819af4b0)
Location: drivers/pci/endpoint/pci-epc-core.c:398
Inline: False
```
**Symbols:**

```
ffffffff819af4b0-ffffffff819af5e3: pci_epc_set_msix (STB_GLOBAL)
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
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071bbd8)
Location: drivers/pci/endpoint/pci-epc-core.c:311
Inline: False
```
**Symbols:**

```
ffff80001071bbd8-ffff80001071bcf0: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (c08a4aec)
Location: drivers/pci/endpoint/pci-epc-core.c:311
Inline: False
```
**Symbols:**

```
c08a4aec-c08a4b90: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (c00000000088bff0)
Location: drivers/pci/endpoint/pci-epc-core.c:311
Inline: True
```
**Symbols:**

```
c00000000088bff0-c00000000088c138: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffe0004e2c4c)
Location: drivers/pci/endpoint/pci-epc-core.c:311
Inline: True
```
**Symbols:**

```
ffffffe0004e2c4c-ffffffe0004e2cde: pci_epc_set_msix (STB_GLOBAL)
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
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a2fa0)
Location: drivers/pci/endpoint/pci-epc-core.c:311
Inline: False
```
**Symbols:**

```
ffffffff815a2fa0-ffffffff815a3051: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81592140)
Location: drivers/pci/endpoint/pci-epc-core.c:311
Inline: False
```
**Symbols:**

```
ffffffff81592140-ffffffff815921f1: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a3530)
Location: drivers/pci/endpoint/pci-epc-core.c:311
Inline: False
```
**Symbols:**

```
ffffffff815a3530-ffffffff815a35e1: pci_epc_set_msix (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_epc_set_msix(struct pci_epc *epc, u8 func_no, u16 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815bd930)
Location: drivers/pci/endpoint/pci-epc-core.c:311
Inline: False
```
**Symbols:**

```
ffffffff815bd930-ffffffff815bd9e1: pci_epc_set_msix (STB_GLOBAL)
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
<code>enum pci_barno bir</code>
</li>
<li>
<b>Param added. </b>
<code>u32 offset</code>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 vfunc_no</code>
</li>
<li>
<b>Param reordered. </b>
<code>epc, func_no, interrupts, bir, offset</code> ➡️ <code>epc, func_no, vfunc_no, interrupts, bir, offset</code>
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
