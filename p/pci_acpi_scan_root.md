# Function: <code>pci_acpi_scan_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/acpi.c (ffffffff816f8dd0)
Location: arch/x86/pci/acpi.c:317
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff816f8dd0-ffffffff816f8f75: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/acpi.c (ffffffff8175dae0)
Location: arch/x86/pci/acpi.c:317
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8175dae0-ffffffff8175dc86: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/acpi.c (ffffffff8178a010)
Location: arch/x86/pci/acpi.c:327
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8178a010-ffffffff8178a1ba: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/acpi.c (ffffffff817a9140)
Location: arch/x86/pci/acpi.c:327
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff817a9140-ffffffff817a92f3: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/acpi.c (ffffffff818205f0)
Location: arch/x86/pci/acpi.c:328
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff818205f0-ffffffff818207a3: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:326
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8186aa4d-ffffffff8186aa67: pci_acpi_scan_root.cold.4 (STB_LOCAL)
ffffffff8186a840-ffffffff8186aa07: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:326
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8188ab18-ffffffff8188ab32: pci_acpi_scan_root.cold.3 (STB_LOCAL)
ffffffff8188a910-ffffffff8188aadd: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:326
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff818d5414-ffffffff818d546b: pci_acpi_scan_root.cold (STB_LOCAL)
ffffffff818d5150-ffffffff818d52ea: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:326
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81907794-ffffffff819077eb: pci_acpi_scan_root.cold (STB_LOCAL)
ffffffff819074d0-ffffffff8190766d: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:326
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81bb7eb2-ffffffff81bb7f09: pci_acpi_scan_root.cold (STB_LOCAL)
ffffffff81bb7bd0-ffffffff81bb7d96: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:326
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81c3469f-ffffffff81c346f6: pci_acpi_scan_root.cold (STB_LOCAL)
ffffffff81bcc920-ffffffff81bccae6: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:326
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81c26a7b-ffffffff81c26ad2: pci_acpi_scan_root.cold (STB_LOCAL)
ffffffff81bc0350-ffffffff81bc0516: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:326
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81d44903-ffffffff81d4496f: pci_acpi_scan_root.cold (STB_LOCAL)
ffffffff81c90310-ffffffff81c904e5: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:413
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81f11812-ffffffff81f1187e: pci_acpi_scan_root.cold (STB_LOCAL)
ffffffff81e3f430-ffffffff81e3f60b: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:411
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff820b72c5-ffffffff820b72da: pci_acpi_scan_root.cold (STB_LOCAL)
ffffffff820192c0-ffffffff820194e5: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:411
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff82138661-ffffffff82138676: pci_acpi_scan_root.cold (STB_LOCAL)
ffffffff82099940-ffffffff82099b65: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:414
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8221a5a7-ffffffff8221a5bc: pci_acpi_scan_root.cold (STB_LOCAL)
ffffffff82171040-ffffffff82171298: pci_acpi_scan_root (STB_GLOBAL)
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
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/pci.c (ffff8000100a7c98)
Location: arch/arm64/kernel/pci.c:162
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffff8000100a7c98-ffff8000100a7ec0: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:326
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff818a6b54-ffffffff818a6bab: pci_acpi_scan_root.cold (STB_LOCAL)
ffffffff818a6890-ffffffff818a6a2d: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:326
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81861674-ffffffff818616cb: pci_acpi_scan_root.cold (STB_LOCAL)
ffffffff818613c0-ffffffff8186154d: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:326
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff818f81b4-ffffffff818f820b: pci_acpi_scan_root.cold (STB_LOCAL)
ffffffff818f7ef0-ffffffff818f808d: pci_acpi_scan_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_acpi_scan_root(struct acpi_pci_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:326
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff819192b4-ffffffff8191930b: pci_acpi_scan_root.cold (STB_LOCAL)
ffffffff81918ff0-ffffffff8191918d: pci_acpi_scan_root (STB_GLOBAL)
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
