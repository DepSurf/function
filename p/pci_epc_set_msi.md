# Function: <code>pci_epc_set_msi</code>

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
int pci_epc_set_msi(struct pci_epc *epc, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff814d2270)
Location: drivers/pci/endpoint/pci-epc-core.c:206
Inline: True
```
**Symbols:**

```
ffffffff814d2270-ffffffff814d22fe: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815126a0)
Location: drivers/pci/endpoint/pci-epc-core.c:207
Inline: True
```
**Symbols:**

```
ffffffff815126a0-ffffffff81512734: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815472f0)
Location: drivers/pci/endpoint/pci-epc-core.c:198
Inline: False
```
**Symbols:**

```
ffffffff815472f0-ffffffff815473ad: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8155d9d0)
Location: drivers/pci/endpoint/pci-epc-core.c:198
Inline: False
```
**Symbols:**

```
ffffffff8155d9d0-ffffffff8155daa4: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8158de30)
Location: drivers/pci/endpoint/pci-epc-core.c:251
Inline: False
```
**Symbols:**

```
ffffffff8158de30-ffffffff8158df09: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815afa50)
Location: drivers/pci/endpoint/pci-epc-core.c:251
Inline: False
```
**Symbols:**

```
ffffffff815afa50-ffffffff815afb29: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81658c10)
Location: drivers/pci/endpoint/pci-epc-core.c:245
Inline: False
```
**Symbols:**

```
ffffffff81658c10-ffffffff81658cbe: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81678ff0)
Location: drivers/pci/endpoint/pci-epc-core.c:245
Inline: False
```
**Symbols:**

```
ffffffff81678ff0-ffffffff816790bb: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165b960)
Location: drivers/pci/endpoint/pci-epc-core.c:312
Inline: False
```
**Symbols:**

```
ffffffff8165b960-ffffffff8165ba2b: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816ce050)
Location: drivers/pci/endpoint/pci-epc-core.c:331
Inline: False
```
**Symbols:**

```
ffffffff816ce050-ffffffff816ce13c: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff817f6cd0)
Location: drivers/pci/endpoint/pci-epc-core.c:331
Inline: False
```
**Symbols:**

```
ffffffff817f6cd0-ffffffff817f6df7: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819227c0)
Location: drivers/pci/endpoint/pci-epc-core.c:331
Inline: False
```
**Symbols:**

```
ffffffff819227c0-ffffffff819228e7: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81966560)
Location: drivers/pci/endpoint/pci-epc-core.c:331
Inline: False
```
**Symbols:**

```
ffffffff81966560-ffffffff81966687: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 vfunc_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819afc70)
Location: drivers/pci/endpoint/pci-epc-core.c:330
Inline: False
```
**Symbols:**

```
ffffffff819afc70-ffffffff819afd97: pci_epc_set_msi (STB_GLOBAL)
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
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071bcf0)
Location: drivers/pci/endpoint/pci-epc-core.c:251
Inline: False
```
**Symbols:**

```
ffff80001071bcf0-ffff80001071be2c: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (c08a4c9c)
Location: drivers/pci/endpoint/pci-epc-core.c:251
Inline: False
```
**Symbols:**

```
c08a4c9c-c08a4d5c: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (c00000000088b680)
Location: drivers/pci/endpoint/pci-epc-core.c:251
Inline: False
```
**Symbols:**

```
c00000000088b680-c00000000088b7d4: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffe0004e277c)
Location: drivers/pci/endpoint/pci-epc-core.c:251
Inline: False
```
**Symbols:**

```
ffffffe0004e277c-ffffffe0004e2812: pci_epc_set_msi (STB_GLOBAL)
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
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a3210)
Location: drivers/pci/endpoint/pci-epc-core.c:251
Inline: False
```
**Symbols:**

```
ffffffff815a3210-ffffffff815a32e9: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815923b0)
Location: drivers/pci/endpoint/pci-epc-core.c:251
Inline: False
```
**Symbols:**

```
ffffffff815923b0-ffffffff81592489: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a37a0)
Location: drivers/pci/endpoint/pci-epc-core.c:251
Inline: False
```
**Symbols:**

```
ffffffff815a37a0-ffffffff815a3879: pci_epc_set_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_epc_set_msi(struct pci_epc *epc, u8 func_no, u8 interrupts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815bdba0)
Location: drivers/pci/endpoint/pci-epc-core.c:251
Inline: False
```
**Symbols:**

```
ffffffff815bdba0-ffffffff815bdc79: pci_epc_set_msi (STB_GLOBAL)
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
<code>epc, interrupts</code> ➡️ <code>epc, func_no, interrupts</code>
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
<code>epc, func_no, interrupts</code> ➡️ <code>epc, func_no, vfunc_no, interrupts</code>
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
