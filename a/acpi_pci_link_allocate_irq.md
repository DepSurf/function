# Function: <code>acpi_pci_link_allocate_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81486bfd)
Location: drivers/acpi/pci_link.c:586
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff81486bfd-ffffffff81486e41: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff814d5846)
Location: drivers/acpi/pci_link.c:636
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff814d5846-ffffffff814d5a9e: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff814f7e78)
Location: drivers/acpi/pci_link.c:629
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff814f7e78-ffffffff814f80d9: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81506b20)
Location: drivers/acpi/pci_link.c:629
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff81506b20-ffffffff81506dff: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81548cd0)
Location: drivers/acpi/pci_link.c:629
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff81548cd0-ffffffff81549005: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:629
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff8157f23a-ffffffff8157f319: acpi_pci_link_allocate_irq.cold.11 (STB_LOCAL)
ffffffff8157ecd0-ffffffff8157ef00: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:629
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff81596f5a-ffffffff81597039: acpi_pci_link_allocate_irq.cold.12 (STB_LOCAL)
ffffffff815969f0-ffffffff81596c20: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:616
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff815c8104-ffffffff815c81f2: acpi_pci_link_allocate_irq.cold (STB_LOCAL)
ffffffff815c7b00-ffffffff815c7d75: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:616
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff815e9324-ffffffff815e9412: acpi_pci_link_allocate_irq.cold (STB_LOCAL)
ffffffff815e8d20-ffffffff815e8f95: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:614
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff81694d54-ffffffff81694d93: acpi_pci_link_allocate_irq.cold (STB_LOCAL)
ffffffff816947c0-ffffffff81694921: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:614
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff81c02046-ffffffff81c02085: acpi_pci_link_allocate_irq.cold (STB_LOCAL)
ffffffff816b1ce0-ffffffff816b1e45: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81694010)
Location: drivers/acpi/pci_link.c:606
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff81694010-ffffffff816941c2: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81709cf0)
Location: drivers/acpi/pci_link.c:606
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff81709cf0-ffffffff81709e9f: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff818381e0)
Location: drivers/acpi/pci_link.c:606
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff818381e0-ffffffff8183834d: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff8196d4e0)
Location: drivers/acpi/pci_link.c:606
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff8196d4e0-ffffffff8196d64b: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff819b3a20)
Location: drivers/acpi/pci_link.c:606
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff819b3a20-ffffffff819b3b8b: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff819fdf90)
Location: drivers/acpi/pci_link.c:606
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff819fdf90-ffffffff819fe0fb: acpi_pci_link_allocate_irq (STB_GLOBAL)
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
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffff800010776090)
Location: drivers/acpi/pci_link.c:616
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffff800010776090-ffff800010776374: acpi_pci_link_allocate_irq (STB_GLOBAL)
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
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:616
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff815da364-ffffffff815da44f: acpi_pci_link_allocate_irq.cold (STB_LOCAL)
ffffffff815d9e20-ffffffff815da03b: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:616
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff815c3f84-ffffffff815c406f: acpi_pci_link_allocate_irq.cold (STB_LOCAL)
ffffffff815c3a40-ffffffff815c3c5b: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:616
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff815dd604-ffffffff815dd6f2: acpi_pci_link_allocate_irq.cold (STB_LOCAL)
ffffffff815dd000-ffffffff815dd275: acpi_pci_link_allocate_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_allocate_irq(acpi_handle handle, int index, int *triggering, int *polarity, char **name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:616
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff815f74c4-ffffffff815f75b2: acpi_pci_link_allocate_irq.cold (STB_LOCAL)
ffffffff815f6ec0-ffffffff815f7135: acpi_pci_link_allocate_irq (STB_GLOBAL)
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
