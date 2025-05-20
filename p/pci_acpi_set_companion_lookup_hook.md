# Function: <code>pci_acpi_set_companion_lookup_hook</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_acpi_set_companion_lookup_hook(struct acpi_device * (*func)(struct pci_dev *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff816ba910)
Location: drivers/pci/pci-acpi.c:1202
Inline: False
```
**Symbols:**

```
ffffffff816ba910-ffffffff816ba968: pci_acpi_set_companion_lookup_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_acpi_set_companion_lookup_hook(struct acpi_device * (*func)(struct pci_dev *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff817df330)
Location: drivers/pci/pci-acpi.c:1215
Inline: False
```
**Symbols:**

```
ffffffff817df330-ffffffff817df38e: pci_acpi_set_companion_lookup_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_acpi_set_companion_lookup_hook(struct acpi_device * (*func)(struct pci_dev *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff819020b0)
Location: drivers/pci/pci-acpi.c:1233
Inline: False
```
**Symbols:**

```
ffffffff819020b0-ffffffff8190210e: pci_acpi_set_companion_lookup_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_acpi_set_companion_lookup_hook(struct acpi_device * (*func)(struct pci_dev *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81945740)
Location: drivers/pci/pci-acpi.c:1260
Inline: False
```
**Symbols:**

```
ffffffff81945740-ffffffff8194579e: pci_acpi_set_companion_lookup_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_acpi_set_companion_lookup_hook(struct acpi_device * (*func)(struct pci_dev *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff8198ea70)
Location: drivers/pci/pci-acpi.c:1260
Inline: False
```
**Symbols:**

```
ffffffff8198ea70-ffffffff8198eace: pci_acpi_set_companion_lookup_hook (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
