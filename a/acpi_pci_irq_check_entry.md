# Function: <code>acpi_pci_irq_check_entry</code>

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
In drivers/acpi/pci_irq.c (ffffffff8148705f)
Location: drivers/acpi/pci_irq.c:155
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
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
In drivers/acpi/pci_irq.c (ffffffff814d5c92)
Location: drivers/acpi/pci_irq.c:153
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
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
In drivers/acpi/pci_irq.c (ffffffff814f82ea)
Location: drivers/acpi/pci_irq.c:153
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
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
In drivers/acpi/pci_irq.c (ffffffff81507054)
Location: drivers/acpi/pci_irq.c:153
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
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
In drivers/acpi/pci_irq.c (ffffffff815492a1)
Location: drivers/acpi/pci_irq.c:153
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
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
In drivers/acpi/pci_irq.c (ffffffff8157f401)
Location: drivers/acpi/pci_irq.c:153
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
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
In drivers/acpi/pci_irq.c (ffffffff81597121)
Location: drivers/acpi/pci_irq.c:153
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
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
In drivers/acpi/pci_irq.c (ffffffff815c82d3)
Location: drivers/acpi/pci_irq.c:140
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
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
In drivers/acpi/pci_irq.c (ffffffff815e94f3)
Location: drivers/acpi/pci_irq.c:140
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_pci_irq_check_entry(acpi_handle handle, struct pci_dev *dev, int pin, struct acpi_pci_routing_table *prt, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff81694eb0)
Location: drivers/acpi/pci_irq.c:140
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
**Symbols:**

```
ffffffff81694eb0-ffffffff81695033: acpi_pci_irq_check_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_pci_irq_check_entry(acpi_handle handle, struct pci_dev *dev, int pin, struct acpi_pci_routing_table *prt, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff816b2100)
Location: drivers/acpi/pci_irq.c:140
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
**Symbols:**

```
ffffffff816b2100-ffffffff816b2283: acpi_pci_irq_check_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_pci_irq_check_entry(acpi_handle handle, struct pci_dev *dev, int pin, struct acpi_pci_routing_table *prt, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff816944a0)
Location: drivers/acpi/pci_irq.c:136
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
**Symbols:**

```
ffffffff816944a0-ffffffff816945f4: acpi_pci_irq_check_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_pci_irq_check_entry(acpi_handle handle, struct pci_dev *dev, int pin, struct acpi_pci_routing_table *prt, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff8170a1b0)
Location: drivers/acpi/pci_irq.c:136
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
**Symbols:**

```
ffffffff8170a1b0-ffffffff8170a301: acpi_pci_irq_check_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff8183870d)
Location: drivers/acpi/pci_irq.c:136
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff8196da9d)
Location: drivers/acpi/pci_irq.c:136
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff819b3fcd)
Location: drivers/acpi/pci_irq.c:136
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_pci_irq_check_entry(acpi_handle handle, struct pci_dev *dev, int pin, struct acpi_pci_routing_table *prt, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff819fe490)
Location: drivers/acpi/pci_irq.c:136
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
**Symbols:**

```
ffffffff819fe490-ffffffff819fe62a: acpi_pci_irq_check_entry (STB_LOCAL)
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
In drivers/acpi/pci_irq.c (ffff80001077662c)
Location: drivers/acpi/pci_irq.c:140
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
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
In drivers/acpi/pci_irq.c (ffffffff815da533)
Location: drivers/acpi/pci_irq.c:140
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
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
In drivers/acpi/pci_irq.c (ffffffff815c4153)
Location: drivers/acpi/pci_irq.c:140
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
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
In drivers/acpi/pci_irq.c (ffffffff815dd7d3)
Location: drivers/acpi/pci_irq.c:140
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
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
In drivers/acpi/pci_irq.c (ffffffff815f7693)
Location: drivers/acpi/pci_irq.c:140
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
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
</ul>
