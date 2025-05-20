# Function: <code>pci_epc_add_epf</code>

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
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff814d2610)
Location: drivers/pci/endpoint/pci-epc-core.c:370
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff814d2610-ffffffff814d2713: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81511fb0)
Location: drivers/pci/endpoint/pci-epc-core.c:371
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff81511fb0-ffffffff815120f0: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81547180)
Location: drivers/pci/endpoint/pci-epc-core.c:377
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff81547180-ffffffff81547221: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8155d860)
Location: drivers/pci/endpoint/pci-epc-core.c:435
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff8155d860-ffffffff8155d901: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8158db10)
Location: drivers/pci/endpoint/pci-epc-core.c:488
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff8158db10-ffffffff8158dbb6: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815af730)
Location: drivers/pci/endpoint/pci-epc-core.c:488
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff815af730-ffffffff815af7d6: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: drivers/pci/endpoint/pci-epc-core.c:475
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff816596f1-ffffffff81659705: pci_epc_add_epf.cold (STB_LOCAL)
ffffffff81658cc0-ffffffff81658d9d: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: drivers/pci/endpoint/pci-epc-core.c:475
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff81bfdd4d-ffffffff81bfdd61: pci_epc_add_epf.cold (STB_LOCAL)
ffffffff816790c0-ffffffff8167919d: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf, enum pci_epc_interface_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: drivers/pci/endpoint/pci-epc-core.c:544
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
```
**Symbols:**

```
ffffffff81befc79-ffffffff81befc8d: pci_epc_add_epf.cold (STB_LOCAL)
ffffffff8165ba30-ffffffff8165bb5b: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf, enum pci_epc_interface_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: drivers/pci/endpoint/pci-epc-core.c:600
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
```
**Symbols:**

```
ffffffff81ceb11e-ffffffff81ceb132: pci_epc_add_epf.cold (STB_LOCAL)
ffffffff816ce140-ffffffff816ce278: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf, enum pci_epc_interface_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: drivers/pci/endpoint/pci-epc-core.c:600
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
```
**Symbols:**

```
ffffffff81eb259f-ffffffff81eb25b8: pci_epc_add_epf.cold (STB_LOCAL)
ffffffff817f6e00-ffffffff817f6f48: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf, enum pci_epc_interface_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819231b0)
Location: drivers/pci/endpoint/pci-epc-core.c:600
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
```
**Symbols:**

```
ffffffff819231b0-ffffffff8192330e: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf, enum pci_epc_interface_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81966e90)
Location: drivers/pci/endpoint/pci-epc-core.c:600
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
```
**Symbols:**

```
ffffffff81966e90-ffffffff81966fee: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf, enum pci_epc_interface_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819b05c0)
Location: drivers/pci/endpoint/pci-epc-core.c:599
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
```
**Symbols:**

```
ffffffff819b05c0-ffffffff819b071e: pci_epc_add_epf (STB_GLOBAL)
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
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071b308)
Location: drivers/pci/endpoint/pci-epc-core.c:488
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffff80001071b308-ffff80001071b410: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (c08a4a58)
Location: drivers/pci/endpoint/pci-epc-core.c:488
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
c08a4a58-c08a4aec: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (c00000000088b110)
Location: drivers/pci/endpoint/pci-epc-core.c:488
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
c00000000088b110-c00000000088b1fc: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffe0004e2554)
Location: drivers/pci/endpoint/pci-epc-core.c:488
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffe0004e2554-ffffffe0004e25e6: pci_epc_add_epf (STB_GLOBAL)
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
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a2ef0)
Location: drivers/pci/endpoint/pci-epc-core.c:488
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff815a2ef0-ffffffff815a2f96: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81592090)
Location: drivers/pci/endpoint/pci-epc-core.c:488
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff81592090-ffffffff81592136: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a3480)
Location: drivers/pci/endpoint/pci-epc-core.c:488
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff815a3480-ffffffff815a3526: pci_epc_add_epf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_epc_add_epf(struct pci_epc *epc, struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815bd880)
Location: drivers/pci/endpoint/pci-epc-core.c:488
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff815bd880-ffffffff815bd926: pci_epc_add_epf (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum pci_epc_interface_type type</code>
</li>
</ul>
</details>
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
