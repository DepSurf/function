# Function: <code>pci_epc_raise_irq</code>

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
int pci_epc_raise_irq(struct pci_epc *epc, enum pci_epc_irq_type type, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff814d1e60)
Location: drivers/pci/endpoint/pci-epc-core.c:149
Inline: True
```
**Symbols:**

```
ffffffff814d1e60-ffffffff814d1ee5: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, enum pci_epc_irq_type type, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81512270)
Location: drivers/pci/endpoint/pci-epc-core.c:150
Inline: True
```
**Symbols:**

```
ffffffff81512270-ffffffff815122fb: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u8 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81547590)
Location: drivers/pci/endpoint/pci-epc-core.c:139
Inline: True
```
**Symbols:**

```
ffffffff81547590-ffffffff8154762c: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8155dc90)
Location: drivers/pci/endpoint/pci-epc-core.c:139
Inline: True
```
**Symbols:**

```
ffffffff8155dc90-ffffffff8155dd2c: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8158e1f0)
Location: drivers/pci/endpoint/pci-epc-core.c:192
Inline: True
```
**Symbols:**

```
ffffffff8158e1f0-ffffffff8158e2a8: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815afe10)
Location: drivers/pci/endpoint/pci-epc-core.c:192
Inline: True
```
**Symbols:**

```
ffffffff815afe10-ffffffff815afec8: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81658fa0)
Location: drivers/pci/endpoint/pci-epc-core.c:188
Inline: True
```
**Symbols:**

```
ffffffff81658fa0-ffffffff81659049: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816793a0)
Location: drivers/pci/endpoint/pci-epc-core.c:188
Inline: True
```
**Symbols:**

```
ffffffff816793a0-ffffffff81679449: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165bd60)
Location: drivers/pci/endpoint/pci-epc-core.c:214
Inline: True
```
**Symbols:**

```
ffffffff8165bd60-ffffffff8165be02: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816cdb00)
Location: drivers/pci/endpoint/pci-epc-core.c:220
Inline: False
```
**Symbols:**

```
ffffffff816cdb00-ffffffff816cdbcf: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff817f64f0)
Location: drivers/pci/endpoint/pci-epc-core.c:220
Inline: False
```
**Symbols:**

```
ffffffff817f64f0-ffffffff817f65d1: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81921f60)
Location: drivers/pci/endpoint/pci-epc-core.c:220
Inline: False
```
**Symbols:**

```
ffffffff81921f60-ffffffff81922041: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819659c0)
Location: drivers/pci/endpoint/pci-epc-core.c:220
Inline: False
```
**Symbols:**

```
ffffffff819659c0-ffffffff81965aa1: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, u8 vfunc_no, unsigned int type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819af0d0)
Location: drivers/pci/endpoint/pci-epc-core.c:219
Inline: False
```
**Symbols:**

```
ffffffff819af0d0-ffffffff819af1b1: pci_epc_raise_irq (STB_GLOBAL)
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
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071b7a8)
Location: drivers/pci/endpoint/pci-epc-core.c:192
Inline: True
```
**Symbols:**

```
ffff80001071b7a8-ffff80001071b8c4: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (c08a518c)
Location: drivers/pci/endpoint/pci-epc-core.c:192
Inline: True
```
**Symbols:**

```
c08a518c-c08a522c: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (c00000000088bca0)
Location: drivers/pci/endpoint/pci-epc-core.c:192
Inline: True
```
**Symbols:**

```
c00000000088bca0-c00000000088bdf8: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffe0004e2ab4)
Location: drivers/pci/endpoint/pci-epc-core.c:192
Inline: True
```
**Symbols:**

```
ffffffe0004e2ab4-ffffffe0004e2b3e: pci_epc_raise_irq (STB_GLOBAL)
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
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a35d0)
Location: drivers/pci/endpoint/pci-epc-core.c:192
Inline: True
```
**Symbols:**

```
ffffffff815a35d0-ffffffff815a3688: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81592770)
Location: drivers/pci/endpoint/pci-epc-core.c:192
Inline: True
```
**Symbols:**

```
ffffffff81592770-ffffffff81592828: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a3b60)
Location: drivers/pci/endpoint/pci-epc-core.c:192
Inline: True
```
**Symbols:**

```
ffffffff815a3b60-ffffffff815a3c18: pci_epc_raise_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_raise_irq(struct pci_epc *epc, u8 func_no, enum pci_epc_irq_type type, u16 interrupt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815bdf60)
Location: drivers/pci/endpoint/pci-epc-core.c:192
Inline: True
```
**Symbols:**

```
ffffffff815bdf60-ffffffff815be018: pci_epc_raise_irq (STB_GLOBAL)
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
<b>Param reordered. </b>
<code>epc, type, interrupt_num</code> ➡️ <code>epc, func_no, type, interrupt_num</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 interrupt_num</code> ➡️ <code>u16 interrupt_num</code>
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
<code>epc, func_no, type, interrupt_num</code> ➡️ <code>epc, func_no, vfunc_no, type, interrupt_num</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum pci_epc_irq_type type</code> ➡️ <code>unsigned int type</code>
</li>
</ul>
</details>
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
