# Function: <code>acpi_pci_link_allocate</code>

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
In drivers/acpi/pci_link.c (ffffffff81486c88)
Location: drivers/acpi/pci_link.c:507
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
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
In drivers/acpi/pci_link.c (ffffffff814d58cc)
Location: drivers/acpi/pci_link.c:558
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
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
In drivers/acpi/pci_link.c (ffffffff814f7efe)
Location: drivers/acpi/pci_link.c:547
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
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
In drivers/acpi/pci_link.c (ffffffff81506b8c)
Location: drivers/acpi/pci_link.c:547
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
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
In drivers/acpi/pci_link.c (ffffffff81548d3c)
Location: drivers/acpi/pci_link.c:547
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff8157ed3e)
Location: drivers/acpi/pci_link.c:547
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81596a5e)
Location: drivers/acpi/pci_link.c:547
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff815c7b6e)
Location: drivers/acpi/pci_link.c:534
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff815e8d8e)
Location: drivers/acpi/pci_link.c:534
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_allocate(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:532
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff81694510-ffffffff8169462d: acpi_pci_link_allocate (STB_LOCAL)
ffffffff81694bee-ffffffff81694c8f: acpi_pci_link_allocate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_allocate(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:532
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff816b1a30-ffffffff816b1b4d: acpi_pci_link_allocate (STB_LOCAL)
ffffffff81c01ed4-ffffffff81c01f7e: acpi_pci_link_allocate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_pci_link_allocate(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81693c10)
Location: drivers/acpi/pci_link.c:528
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff81693c10-ffffffff81693dcf: acpi_pci_link_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_pci_link_allocate(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81709a40)
Location: drivers/acpi/pci_link.c:528
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff81709a40-ffffffff81709c9e: acpi_pci_link_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_pci_link_allocate(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81837e60)
Location: drivers/acpi/pci_link.c:528
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff81837e60-ffffffff8183817b: acpi_pci_link_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_pci_link_allocate(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff8196d140)
Location: drivers/acpi/pci_link.c:528
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff8196d140-ffffffff8196d45b: acpi_pci_link_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_pci_link_allocate(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff819b36d0)
Location: drivers/acpi/pci_link.c:528
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff819b36d0-ffffffff819b39a0: acpi_pci_link_allocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_pci_link_allocate(struct acpi_pci_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff819fdc40)
Location: drivers/acpi/pci_link.c:528
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff819fdc40-ffffffff819fdf10: acpi_pci_link_allocate (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffff800010776104)
Location: drivers/acpi/pci_link.c:534
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff815d9e8e)
Location: drivers/acpi/pci_link.c:534
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff815c3aae)
Location: drivers/acpi/pci_link.c:534
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff815dd06e)
Location: drivers/acpi/pci_link.c:534
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff815f6f2e)
Location: drivers/acpi/pci_link.c:534
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
