# Function: <code>pci_dev_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8143ada0)
Location: drivers/pci/search.c:370
Inline: False
```
**Symbols:**

```
ffffffff8143ada0-ffffffff8143ae0c: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81486cc0)
Location: drivers/pci/search.c:374
Inline: False
```
**Symbols:**

```
ffffffff81486cc0-ffffffff81486d2c: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814a8470)
Location: drivers/pci/search.c:374
Inline: False
```
**Symbols:**

```
ffffffff814a8470-ffffffff814a84dc: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814b23e0)
Location: drivers/pci/search.c:378
Inline: False
```
**Symbols:**

```
ffffffff814b23e0-ffffffff814b243d: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814f1ad0)
Location: drivers/pci/search.c:378
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff814f1ad0-ffffffff814f1b2d: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81521d60)
Location: drivers/pci/search.c:379
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff81521d60-ffffffff81521dbd: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81537b90)
Location: drivers/pci/search.c:379
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff81537b90-ffffffff81537bed: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/search.c (0)
Location: drivers/pci/search.c:375
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff81567717-ffffffff8156772a: pci_dev_present.cold (STB_LOCAL)
ffffffff81567530-ffffffff8156758c: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81588880)
Location: drivers/pci/search.c:374
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff81588880-ffffffff815888dd: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8162f3c0)
Location: drivers/pci/search.c:380
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff8162f3c0-ffffffff8162f423: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81654a50)
Location: drivers/pci/search.c:380
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff81654a50-ffffffff81654ab3: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816373d0)
Location: drivers/pci/search.c:377
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff816373d0-ffffffff8163744b: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816a7640)
Location: drivers/pci/search.c:377
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff816a7640-ffffffff816a76bb: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff817ca050)
Location: drivers/pci/search.c:377
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff817ca050-ffffffff817ca0e9: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff818e7af0)
Location: drivers/pci/search.c:377
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff818e7af0-ffffffff818e7b89: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8192b110)
Location: drivers/pci/search.c:377
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff8192b110-ffffffff8192b1a9: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81973990)
Location: drivers/pci/search.c:408
Inline: False
Direct callers:
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff81973990-ffffffff81973a29: pci_dev_present (STB_GLOBAL)
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
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffff8000106ece30)
Location: drivers/pci/search.c:374
Inline: False
```
**Symbols:**

```
ffff8000106ece30-ffff8000106eceb0: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c08880c8)
Location: drivers/pci/search.c:374
Inline: False
```
**Symbols:**

```
c08880c8-c0888170: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c000000000868d40)
Location: drivers/pci/search.c:374
Inline: False
```
**Symbols:**

```
c000000000868d40-c000000000868df8: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffe0004c1c50)
Location: drivers/pci/search.c:374
Inline: False
```
**Symbols:**

```
ffffffe0004c1c50-ffffffe0004c1cbc: pci_dev_present (STB_GLOBAL)
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
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c710)
Location: drivers/pci/search.c:374
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff8157c710-ffffffff8157c76d: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8156b4e0)
Location: drivers/pci/search.c:374
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff8156b4e0-ffffffff8156b53d: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c5d0)
Location: drivers/pci/search.c:374
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff8157c5d0-ffffffff8157c62d: pci_dev_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_dev_present(const struct pci_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81596a80)
Location: drivers/pci/search.c:374
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - arch/x86/pci/irq.c:intel_router_probe
```
**Symbols:**

```
ffffffff81596a80-ffffffff81596add: pci_dev_present (STB_GLOBAL)
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
