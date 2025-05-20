# Function: <code>acpi_pci_link_free_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81486e41)
Location: drivers/acpi/pci_link.c:641
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff81486e41-ffffffff81486f01: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff814d5a9e)
Location: drivers/acpi/pci_link.c:691
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff814d5a9e-ffffffff814d5b5b: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff814f80d9)
Location: drivers/acpi/pci_link.c:684
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff814f80d9-ffffffff814f8196: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81506e00)
Location: drivers/acpi/pci_link.c:684
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff81506e00-ffffffff81506eda: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81549010)
Location: drivers/acpi/pci_link.c:684
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff81549010-ffffffff8154914e: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:684
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff8157f319-ffffffff8157f341: acpi_pci_link_free_irq.cold.12 (STB_LOCAL)
ffffffff8157ef00-ffffffff8157f012: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:684
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff81597039-ffffffff81597061: acpi_pci_link_free_irq.cold.13 (STB_LOCAL)
ffffffff81596c20-ffffffff81596d32: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:671
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff815c81f2-ffffffff815c821a: acpi_pci_link_free_irq.cold (STB_LOCAL)
ffffffff815c7d80-ffffffff815c7e92: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:671
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff815e9412-ffffffff815e943a: acpi_pci_link_free_irq.cold (STB_LOCAL)
ffffffff815e8fa0-ffffffff815e90b2: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:669
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff81694d93-ffffffff81694dbb: acpi_pci_link_free_irq.cold (STB_LOCAL)
ffffffff81694930-ffffffff81694a42: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:669
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff81c02085-ffffffff81c020ad: acpi_pci_link_free_irq.cold (STB_LOCAL)
ffffffff816b1e50-ffffffff816b1f64: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff816941d0)
Location: drivers/acpi/pci_link.c:659
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff816941d0-ffffffff81694309: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81709ea0)
Location: drivers/acpi/pci_link.c:659
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff81709ea0-ffffffff81709fd6: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81838350)
Location: drivers/acpi/pci_link.c:657
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff81838350-ffffffff81838448: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff8196d660)
Location: drivers/acpi/pci_link.c:657
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff8196d660-ffffffff8196d758: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff819b3ba0)
Location: drivers/acpi/pci_link.c:657
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff819b3ba0-ffffffff819b3c98: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff819fe110)
Location: drivers/acpi/pci_link.c:657
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff819fe110-ffffffff819fe208: acpi_pci_link_free_irq (STB_GLOBAL)
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
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffff800010776378)
Location: drivers/acpi/pci_link.c:671
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffff800010776378-ffff80001077647c: acpi_pci_link_free_irq (STB_GLOBAL)
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
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:671
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff815da44f-ffffffff815da477: acpi_pci_link_free_irq.cold (STB_LOCAL)
ffffffff815da040-ffffffff815da0fc: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:671
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff815c406f-ffffffff815c4097: acpi_pci_link_free_irq.cold (STB_LOCAL)
ffffffff815c3c60-ffffffff815c3d1c: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:671
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff815dd6f2-ffffffff815dd71a: acpi_pci_link_free_irq.cold (STB_LOCAL)
ffffffff815dd280-ffffffff815dd392: acpi_pci_link_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_free_irq(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:671
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff815f75b2-ffffffff815f75da: acpi_pci_link_free_irq.cold (STB_LOCAL)
ffffffff815f7140-ffffffff815f7252: acpi_pci_link_free_irq (STB_GLOBAL)
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
