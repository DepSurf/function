# Function: <code>pci_enable_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8143da70)
Location: drivers/pci/setup-res.c:352
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:pci_enable_sriov
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff8143da70-ffffffff8143dbe2: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81489870)
Location: drivers/pci/setup-res.c:358
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:pci_enable_sriov
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff81489870-ffffffff814899e2: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814ab060)
Location: drivers/pci/setup-res.c:386
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:pci_enable_sriov
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff814ab060-ffffffff814ab1d2: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814b5360)
Location: drivers/pci/setup-res.c:386
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:pci_enable_sriov
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff814b5360-ffffffff814b54d3: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814f4d60)
Location: drivers/pci/setup-res.c:458
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:pci_enable_sriov
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff814f4d60-ffffffff814f4ed3: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81524e10)
Location: drivers/pci/setup-res.c:455
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff81524e10-ffffffff81524f68: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8153ac90)
Location: drivers/pci/setup-res.c:455
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff8153ac90-ffffffff8153ade8: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:455
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff8156a7f7-ffffffff8156a87e: pci_enable_resources.cold (STB_LOCAL)
ffffffff8156a410-ffffffff8156a4f2: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:455
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff8158b7c7-ffffffff8158b84e: pci_enable_resources.cold (STB_LOCAL)
ffffffff8158b3e0-ffffffff8158b4c2: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:456
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff81632862-ffffffff816328e3: pci_enable_resources.cold (STB_LOCAL)
ffffffff81632410-ffffffff816324fe: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:463
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff81bf853e-ffffffff81bf85bf: pci_enable_resources.cold (STB_LOCAL)
ffffffff81657a30-ffffffff81657b1e: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:463
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff81bea37f-ffffffff81bea400: pci_enable_resources.cold (STB_LOCAL)
ffffffff8163a300-ffffffff8163a3ee: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:463
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff81ce51e8-ffffffff81ce525a: pci_enable_resources.cold (STB_LOCAL)
ffffffff816aab10-ffffffff816aac06: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:467
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff81eabc7e-ffffffff81eabcef: pci_enable_resources.cold (STB_LOCAL)
ffffffff817cda70-ffffffff817cdb73: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff818ed330)
Location: drivers/pci/setup-res.c:478
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff818ed330-ffffffff818ed496: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81930820)
Location: drivers/pci/setup-res.c:478
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff81930820-ffffffff8193099a: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81979220)
Location: drivers/pci/setup-res.c:483
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff81979220-ffffffff819793cb: pci_enable_resources (STB_GLOBAL)
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
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffff8000106f03f8)
Location: drivers/pci/setup-res.c:455
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffff8000106f03f8-ffff8000106f055c: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (c088af34)
Location: drivers/pci/setup-res.c:455
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
c088af34-c088b0a4: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (c00000000086d9f0)
Location: drivers/pci/setup-res.c:455
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_enable_device
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
c00000000086d9f0-c00000000086dba4: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffe0004c3fec)
Location: drivers/pci/setup-res.c:455
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffe0004c3fec-ffffffe0004c410a: pci_enable_resources (STB_GLOBAL)
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
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:455
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff8157f647-ffffffff8157f6ce: pci_enable_resources.cold (STB_LOCAL)
ffffffff8157f260-ffffffff8157f342: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:455
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff8156e427-ffffffff8156e4ae: pci_enable_resources.cold (STB_LOCAL)
ffffffff8156e040-ffffffff8156e122: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:455
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff8157f517-ffffffff8157f59e: pci_enable_resources.cold (STB_LOCAL)
ffffffff8157f130-ffffffff8157f212: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_enable_resources(struct pci_dev *dev, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:455
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcibios_enable_device
  - drivers/pci/iov.c:sriov_enable
  - arch/x86/pci/common.c:pcibios_enable_device
```
**Symbols:**

```
ffffffff815999c7-ffffffff81599a4e: pci_enable_resources.cold (STB_LOCAL)
ffffffff815995e0-ffffffff815996c2: pci_enable_resources (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
