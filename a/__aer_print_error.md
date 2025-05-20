# Function: <code>__aer_print_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff8144957d)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:139
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff8149586d)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:139
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814b722d)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:139
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814c1b78)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:139
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff81501d88)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:139
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81533110)
Location: drivers/pci/pcie/aer.c:529
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:cper_print_aer
```
**Symbols:**

```
ffffffff81533110-ffffffff815331e9: __aer_print_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8154a8d0)
Location: drivers/pci/pcie/aer.c:717
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff8154a8d0-ffffffff8154aa40: __aer_print_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8157b725)
Location: drivers/pci/pcie/aer.c:717
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff8157b725-ffffffff8157b86f: __aer_print_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8159d18a)
Location: drivers/pci/pcie/aer.c:717
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff8159d18a-ffffffff8159d2d6: __aer_print_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8163cf78)
Location: drivers/pci/pcie/aer.c:650
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff8163cf78-ffffffff8163d13a: __aer_print_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81bf92d7)
Location: drivers/pci/pcie/aer.c:670
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff81bf92d7-ffffffff81bf9476: __aer_print_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81beb12c)
Location: drivers/pci/pcie/aer.c:670
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff81beb12c-ffffffff81beb2cb: __aer_print_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:672
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff816b65a0-ffffffff816b6627: __aer_print_error (STB_LOCAL)
ffffffff81ce600f-ffffffff81ce6095: __aer_print_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:677
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff817d9ff0-ffffffff817da168: __aer_print_error (STB_LOCAL)
ffffffff81eacafa-ffffffff81eacb7b: __aer_print_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff818fba00)
Location: drivers/pci/pcie/aer.c:682
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff818fba00-ffffffff818fbbf5: __aer_print_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8193f2d0)
Location: drivers/pci/pcie/aer.c:685
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff8193f2d0-ffffffff8193f4c5: __aer_print_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81988070)
Location: drivers/pci/pcie/aer.c:674
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:pci_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff81988070-ffffffff81988265: __aer_print_error (STB_LOCAL)
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
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffff800010705278)
Location: drivers/pci/pcie/aer.c:717
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffff800010705278-ffff800010705410: __aer_print_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (c089c73c)
Location: drivers/pci/pcie/aer.c:717
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffe0004d3502)
Location: drivers/pci/pcie/aer.c:717
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81590de1)
Location: drivers/pci/pcie/aer.c:717
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8157fb5a)
Location: drivers/pci/pcie/aer.c:717
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff8157fb5a-ffffffff8157fca6: __aer_print_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81590eda)
Location: drivers/pci/pcie/aer.c:717
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff81590eda-ffffffff81591026: __aer_print_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __aer_print_error(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff815ab38a)
Location: drivers/pci/pcie/aer.c:717
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff815ab38a-ffffffff815ab4d6: __aer_print_error (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
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
