# Function: <code>pci_epc_destroy</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff814d1d00)
Location: drivers/pci/endpoint/pci-epc-core.c:444
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff814d1d00-ffffffff814d1d2c: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815120f0)
Location: drivers/pci/endpoint/pci-epc-core.c:450
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff815120f0-ffffffff8151211c: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815473b0)
Location: drivers/pci/endpoint/pci-epc-core.c:449
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff815473b0-ffffffff815473dc: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8155dab0)
Location: drivers/pci/endpoint/pci-epc-core.c:507
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff8155dab0-ffffffff8155dadc: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8158df90)
Location: drivers/pci/endpoint/pci-epc-core.c:561
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff8158df90-ffffffff8158dfbe: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815afbb0)
Location: drivers/pci/endpoint/pci-epc-core.c:561
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff815afbb0-ffffffff815afbde: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816596ce)
Location: drivers/pci/endpoint/pci-epc-core.c:573
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff81658e00-ffffffff81658e30: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81679ace)
Location: drivers/pci/endpoint/pci-epc-core.c:573
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff81679200-ffffffff81679230: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165c52e)
Location: drivers/pci/endpoint/pci-epc-core.c:667
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff8165bbc0-ffffffff8165bbf0: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816ceb6e)
Location: drivers/pci/endpoint/pci-epc-core.c:723
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff816ce2e0-ffffffff816ce310: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff817f77fd)
Location: drivers/pci/endpoint/pci-epc-core.c:723
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff817f6ff0-ffffffff817f7025: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8192341d)
Location: drivers/pci/endpoint/pci-epc-core.c:723
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff819229c0-ffffffff819229ed: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819670bd)
Location: drivers/pci/endpoint/pci-epc-core.c:793
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff819666a0-ffffffff819666cd: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819b07ed)
Location: drivers/pci/endpoint/pci-epc-core.c:792
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff819afdb0-ffffffff819afddd: pci_epc_destroy (STB_GLOBAL)
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
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071af38)
Location: drivers/pci/endpoint/pci-epc-core.c:561
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffff80001071af38-ffff80001071af74: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (c08a4dc8)
Location: drivers/pci/endpoint/pci-epc-core.c:561
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
c08a4dc8-c08a4dfc: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (c00000000088b8a0)
Location: drivers/pci/endpoint/pci-epc-core.c:561
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
c00000000088b8a0-c00000000088b8fc: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffe0004e288a)
Location: drivers/pci/endpoint/pci-epc-core.c:561
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffe0004e288a-ffffffe0004e28ca: pci_epc_destroy (STB_GLOBAL)
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
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a3370)
Location: drivers/pci/endpoint/pci-epc-core.c:561
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff815a3370-ffffffff815a339e: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81592510)
Location: drivers/pci/endpoint/pci-epc-core.c:561
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff81592510-ffffffff8159253e: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a3900)
Location: drivers/pci/endpoint/pci-epc-core.c:561
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff815a3900-ffffffff815a392e: pci_epc_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_epc_destroy(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815bdd00)
Location: drivers/pci/endpoint/pci-epc-core.c:561
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
```
**Symbols:**

```
ffffffff815bdd00-ffffffff815bdd2e: pci_epc_destroy (STB_GLOBAL)
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
