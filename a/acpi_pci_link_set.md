# Function: <code>acpi_pci_link_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff8148675c)
Location: drivers/acpi/pci_link.c:290
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff8148675c-ffffffff81486973: acpi_pci_link_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff814d55f9)
Location: drivers/acpi/pci_link.c:291
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff814d55f9-ffffffff814d5809: acpi_pci_link_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff814f7c2b)
Location: drivers/acpi/pci_link.c:292
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff814f7c2b-ffffffff814f7e3b: acpi_pci_link_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81506880)
Location: drivers/acpi/pci_link.c:292
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff81506880-ffffffff81506ac7: acpi_pci_link_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff815489e0)
Location: drivers/acpi/pci_link.c:292
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff815489e0-ffffffff81548c77: acpi_pci_link_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:292
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff8157ea40-ffffffff8157ec73: acpi_pci_link_set (STB_LOCAL)
ffffffff8157f1e4-ffffffff8157f23a: acpi_pci_link_set.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:292
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff81596770-ffffffff8159699d: acpi_pci_link_set (STB_LOCAL)
ffffffff81596f04-ffffffff81596f5a: acpi_pci_link_set.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:279
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff815c7880-ffffffff815c7aa5: acpi_pci_link_set (STB_LOCAL)
ffffffff815c8096-ffffffff815c8104: acpi_pci_link_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:279
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff815e8aa0-ffffffff815e8cc5: acpi_pci_link_set (STB_LOCAL)
ffffffff815e92b6-ffffffff815e9324: acpi_pci_link_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:277
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
```
**Symbols:**

```
ffffffff816942f0-ffffffff81694510: acpi_pci_link_set (STB_LOCAL)
ffffffff81694b80-ffffffff81694bee: acpi_pci_link_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:277
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
```
**Symbols:**

```
ffffffff816b1800-ffffffff816b1a23: acpi_pci_link_set (STB_LOCAL)
ffffffff81c01e60-ffffffff81c01ed4: acpi_pci_link_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff816939a0)
Location: drivers/acpi/pci_link.c:277
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
```
**Symbols:**

```
ffffffff816939a0-ffffffff81693c0e: acpi_pci_link_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff817097d0)
Location: drivers/acpi/pci_link.c:277
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
```
**Symbols:**

```
ffffffff817097d0-ffffffff81709a3e: acpi_pci_link_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff81837be0)
Location: drivers/acpi/pci_link.c:277
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
```
**Symbols:**

```
ffffffff81837be0-ffffffff81837e57: acpi_pci_link_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff8196ceb0)
Location: drivers/acpi/pci_link.c:277
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
```
**Symbols:**

```
ffffffff8196ceb0-ffffffff8196d124: acpi_pci_link_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff819b3440)
Location: drivers/acpi/pci_link.c:277
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
```
**Symbols:**

```
ffffffff819b3440-ffffffff819b36b4: acpi_pci_link_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffffffff819fd990)
Location: drivers/acpi/pci_link.c:277
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
```
**Symbols:**

```
ffffffff819fd990-ffffffff819fdc29: acpi_pci_link_set (STB_LOCAL)
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
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_link.c (ffff800010775e00)
Location: drivers/acpi/pci_link.c:279
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffff800010775e00-ffff800010776028: acpi_pci_link_set (STB_LOCAL)
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
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:279
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff815d9bf0-ffffffff815d9dc7: acpi_pci_link_set (STB_LOCAL)
ffffffff815da2f6-ffffffff815da364: acpi_pci_link_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:279
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff815c3810-ffffffff815c39e2: acpi_pci_link_set (STB_LOCAL)
ffffffff815c3f16-ffffffff815c3f84: acpi_pci_link_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:279
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff815dcd80-ffffffff815dcfa5: acpi_pci_link_set (STB_LOCAL)
ffffffff815dd596-ffffffff815dd604: acpi_pci_link_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_pci_link_set(struct acpi_pci_link *link, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_link.c (0)
Location: drivers/acpi/pci_link.c:279
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:irqrouter_resume
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
```
**Symbols:**

```
ffffffff815f6c40-ffffffff815f6e65: acpi_pci_link_set (STB_LOCAL)
ffffffff815f7456-ffffffff815f74c4: acpi_pci_link_set.cold (STB_LOCAL)
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
