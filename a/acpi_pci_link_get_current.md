# Function: <code>acpi_pci_link_get_current</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_pci_link_get_current(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff8148666e)
Location: drivers/acpi/pci_link.c:242
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_add
```
**Symbols:**

```
ffffffff8148666e-ffffffff8148675c: acpi_pci_link_get_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_pci_link_get_current(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff814d52c4)
Location: drivers/acpi/pci_link.c:243
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff814d52c4-ffffffff814d53b4: acpi_pci_link_get_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_pci_link_get_current(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff814f78f6)
Location: drivers/acpi/pci_link.c:244
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff814f78f6-ffffffff814f79e6: acpi_pci_link_get_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff815063b0)
Location: drivers/acpi/pci_link.c:244
Inline: True
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff815063b0-ffffffff815064ac: acpi_pci_link_get_current.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff815485b0)
Location: drivers/acpi/pci_link.c:244
Inline: True
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff815485b0-ffffffff81548746: acpi_pci_link_get_current.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:244
Inline: True
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff8157e740-ffffffff8157e8ac: acpi_pci_link_get_current.isra.5 (STB_LOCAL)
ffffffff8157f0f7-ffffffff8157f121: acpi_pci_link_get_current.isra.5.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:244
Inline: True
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff81596470-ffffffff815965dc: acpi_pci_link_get_current.isra.5 (STB_LOCAL)
ffffffff81596e17-ffffffff81596e41: acpi_pci_link_get_current.isra.5.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:231
Inline: True
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff815c7580-ffffffff815c76f3: acpi_pci_link_get_current.isra.0 (STB_LOCAL)
ffffffff815c7fa8-ffffffff815c7fd3: acpi_pci_link_get_current.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:231
Inline: True
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff815e87a0-ffffffff815e8913: acpi_pci_link_get_current.isra.0 (STB_LOCAL)
ffffffff815e91c8-ffffffff815e91f3: acpi_pci_link_get_current.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_get_current(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:229
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff816940c0-ffffffff81694226: acpi_pci_link_get_current (STB_LOCAL)
ffffffff81694b55-ffffffff81694b80: acpi_pci_link_get_current.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_get_current(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:229
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff816b15d0-ffffffff816b1739: acpi_pci_link_get_current (STB_LOCAL)
ffffffff81c01e35-ffffffff81c01e60: acpi_pci_link_get_current.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_pci_link_get_current(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81693780)
Location: drivers/acpi/pci_link.c:228
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff81693780-ffffffff816938d6: acpi_pci_link_get_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_pci_link_get_current(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81709390)
Location: drivers/acpi/pci_link.c:228
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff81709390-ffffffff817094e0: acpi_pci_link_get_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_pci_link_get_current(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81837760)
Location: drivers/acpi/pci_link.c:228
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff81837760-ffffffff818378c3: acpi_pci_link_get_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_pci_link_get_current(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff8196ca10)
Location: drivers/acpi/pci_link.c:228
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff8196ca10-ffffffff8196cb70: acpi_pci_link_get_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_pci_link_get_current(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff819b2fa0)
Location: drivers/acpi/pci_link.c:228
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff819b2fa0-ffffffff819b3100: acpi_pci_link_get_current (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_pci_link_get_current(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff819fd4c0)
Location: drivers/acpi/pci_link.c:228
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff819fd4c0-ffffffff819fd620: acpi_pci_link_get_current (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (ffff800010775b10)
Location: drivers/acpi/pci_link.c:231
Inline: True
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffff800010775b10-ffff800010775c10: acpi_pci_link_get_current.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:231
Inline: True
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff815d99c0-ffffffff815d9aa1: acpi_pci_link_get_current.isra.0 (STB_LOCAL)
ffffffff815da209-ffffffff815da234: acpi_pci_link_get_current.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:231
Inline: True
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff815c35e0-ffffffff815c36c1: acpi_pci_link_get_current.isra.0 (STB_LOCAL)
ffffffff815c3e29-ffffffff815c3e54: acpi_pci_link_get_current.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:231
Inline: True
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff815dca80-ffffffff815dcbf3: acpi_pci_link_get_current.isra.0 (STB_LOCAL)
ffffffff815dd4a8-ffffffff815dd4d3: acpi_pci_link_get_current.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:231
Inline: True
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
**Symbols:**

```
ffffffff815f6940-ffffffff815f6ab3: acpi_pci_link_get_current.isra.0 (STB_LOCAL)
ffffffff815f7368-ffffffff815f7393: acpi_pci_link_get_current.isra.0.cold (STB_LOCAL)
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
