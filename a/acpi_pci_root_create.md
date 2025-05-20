# Function: <code>acpi_pci_root_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81486306)
Location: drivers/acpi/pci_root.c:821
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff81486306-ffffffff814864e3: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814d4ea8)
Location: drivers/acpi/pci_root.c:856
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff814d4ea8-ffffffff814d508e: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814f74fb)
Location: drivers/acpi/pci_root.c:866
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff814f74fb-ffffffff814f76e1: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81505ed0)
Location: drivers/acpi/pci_root.c:867
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff81505ed0-ffffffff815060c9: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81548030)
Location: drivers/acpi/pci_root.c:867
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff81548030-ffffffff8154822f: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff8157ddd0)
Location: drivers/acpi/pci_root.c:876
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff8157ddd0-ffffffff8157e025: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81595ab0)
Location: drivers/acpi/pci_root.c:885
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff81595ab0-ffffffff81595d05: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:874
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff815c71a3-ffffffff815c7217: acpi_pci_root_create.cold (STB_LOCAL)
ffffffff815c6990-ffffffff815c6be4: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:873
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff815e83c0-ffffffff815e8434: acpi_pci_root_create.cold (STB_LOCAL)
ffffffff815e7bc0-ffffffff815e7e14: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:881
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff81693d13-ffffffff81693d87: acpi_pci_root_create.cold (STB_LOCAL)
ffffffff81693550-ffffffff816937b0: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:877
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff81c01d4f-ffffffff81c01dc3: acpi_pci_root_create.cold (STB_LOCAL)
ffffffff816b1040-ffffffff816b12a0: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:865
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff81bf3852-ffffffff81bf38c6: acpi_pci_root_create.cold (STB_LOCAL)
ffffffff81693210-ffffffff81693470: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:867
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff81cf04aa-ffffffff81cf051e: acpi_pci_root_create.cold (STB_LOCAL)
ffffffff81708d60-ffffffff81708fc0: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:1050
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff81eb8330-ffffffff81eb83a4: acpi_pci_root_create.cold (STB_LOCAL)
ffffffff81837130-ffffffff818373a8: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff8196c340)
Location: drivers/acpi/pci_root.c:1001
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff8196c340-ffffffff8196c62d: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff819b28b0)
Location: drivers/acpi/pci_root.c:1001
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff819b28b0-ffffffff819b2bac: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff819fcdc0)
Location: drivers/acpi/pci_root.c:1001
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff819fcdc0-ffffffff819fd0c5: acpi_pci_root_create (STB_GLOBAL)
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
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffff800010775440)
Location: drivers/acpi/pci_root.c:873
Inline: False
Direct callers:
  - arch/arm64/kernel/pci.c:pci_acpi_scan_root
```
**Symbols:**

```
ffff800010775440-ffff800010775734: acpi_pci_root_create (STB_GLOBAL)
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
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:873
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff815d9679-ffffffff815d96ed: acpi_pci_root_create.cold (STB_LOCAL)
ffffffff815d8ea0-ffffffff815d90f4: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:873
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff815c3290-ffffffff815c3304: acpi_pci_root_create.cold (STB_LOCAL)
ffffffff815c2a90-ffffffff815c2ce4: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:873
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff815dc6a0-ffffffff815dc714: acpi_pci_root_create.cold (STB_LOCAL)
ffffffff815dbea0-ffffffff815dc0f4: acpi_pci_root_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct pci_bus *acpi_pci_root_create(struct acpi_pci_root *root, struct acpi_pci_root_ops *ops, struct acpi_pci_root_info *info, void *sysdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:873
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff815f6560-ffffffff815f65d4: acpi_pci_root_create.cold (STB_LOCAL)
ffffffff815f5d60-ffffffff815f5fb4: acpi_pci_root_create (STB_GLOBAL)
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
