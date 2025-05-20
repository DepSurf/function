# Function: <code>pci_epf_bind</code>

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
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff814d28b0)
Location: drivers/pci/endpoint/pci-epf-core.c:79
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff814d28b0-ffffffff814d292c: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81512c50)
Location: drivers/pci/endpoint/pci-epf-core.c:79
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff81512c50-ffffffff81512cd0: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81548040)
Location: drivers/pci/endpoint/pci-epf-core.c:70
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff81548040-ffffffff815480c0: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8155e910)
Location: drivers/pci/endpoint/pci-epf-core.c:70
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff8155e910-ffffffff8155e990: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8158ed70)
Location: drivers/pci/endpoint/pci-epf-core.c:70
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff8158ed70-ffffffff8158edf2: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815b0990)
Location: drivers/pci/endpoint/pci-epf-core.c:70
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff815b0990-ffffffff815b0a12: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81659780)
Location: drivers/pci/endpoint/pci-epf-core.c:52
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff81659780-ffffffff81659822: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81679b70)
Location: drivers/pci/endpoint/pci-epf-core.c:52
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff81679b70-ffffffff81679c12: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff8165c6b0)
Location: drivers/pci/endpoint/pci-epf-core.c:84
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
```
**Symbols:**

```
ffffffff8165c6b0-ffffffff8165c752: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:91
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
```
**Symbols:**

```
ffffffff81ceb1dc-ffffffff81ceb260: pci_epf_bind.cold (STB_LOCAL)
ffffffff816cf280-ffffffff816cf496: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (0)
Location: drivers/pci/endpoint/pci-epf-core.c:91
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
```
**Symbols:**

```
ffffffff81eb264a-ffffffff81eb269d: pci_epf_bind.cold (STB_LOCAL)
ffffffff817f7f60-ffffffff817f817e: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81923af0)
Location: drivers/pci/endpoint/pci-epf-core.c:91
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
```
**Symbols:**

```
ffffffff81923af0-ffffffff81923d4a: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff81967700)
Location: drivers/pci/endpoint/pci-epf-core.c:59
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
```
**Symbols:**

```
ffffffff81967700-ffffffff8196795a: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819b0e30)
Location: drivers/pci/endpoint/pci-epf-core.c:59
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_primary_epc_epf_link
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_secondary_epc_epf_link
```
**Symbols:**

```
ffffffff819b0e30-ffffffff819b108a: pci_epf_bind (STB_GLOBAL)
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
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffff80001071ca60)
Location: drivers/pci/endpoint/pci-epf-core.c:70
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffff80001071ca60-ffff80001071cae8: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (c08a5c94)
Location: drivers/pci/endpoint/pci-epf-core.c:70
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
c08a5c94-c08a5d2c: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (c00000000088d070)
Location: drivers/pci/endpoint/pci-epf-core.c:70
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
c00000000088d070-c00000000088d130: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffe0004e35c0)
Location: drivers/pci/endpoint/pci-epf-core.c:70
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffe0004e35c0-ffffffe0004e362a: pci_epf_bind (STB_GLOBAL)
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
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815a4150)
Location: drivers/pci/endpoint/pci-epf-core.c:70
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff815a4150-ffffffff815a41d2: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815932f0)
Location: drivers/pci/endpoint/pci-epf-core.c:70
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff815932f0-ffffffff81593372: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815a46e0)
Location: drivers/pci/endpoint/pci-epf-core.c:70
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff815a46e0-ffffffff815a4762: pci_epf_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pci_epf_bind(struct pci_epf *epf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff815beae0)
Location: drivers/pci/endpoint/pci-epf-core.c:70
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
```
**Symbols:**

```
ffffffff815beae0-ffffffff815beb62: pci_epf_bind (STB_GLOBAL)
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
