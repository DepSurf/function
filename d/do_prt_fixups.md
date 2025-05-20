# Function: <code>do_prt_fixups</code>

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
In drivers/acpi/pci_irq.c (ffffffff814870fe)
Location: drivers/acpi/pci_irq.c:124
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
In drivers/acpi/pci_irq.c (ffffffff814d5d2d)
Location: drivers/acpi/pci_irq.c:125
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
In drivers/acpi/pci_irq.c (ffffffff814f8385)
Location: drivers/acpi/pci_irq.c:125
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
In drivers/acpi/pci_irq.c (ffffffff815070d7)
Location: drivers/acpi/pci_irq.c:125
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
In drivers/acpi/pci_irq.c (ffffffff81549324)
Location: drivers/acpi/pci_irq.c:125
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
In drivers/acpi/pci_irq.c (ffffffff8157f49c)
Location: drivers/acpi/pci_irq.c:125
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
In drivers/acpi/pci_irq.c (ffffffff815971bc)
Location: drivers/acpi/pci_irq.c:125
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
In drivers/acpi/pci_irq.c (ffffffff815c8378)
Location: drivers/acpi/pci_irq.c:112
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
In drivers/acpi/pci_irq.c (ffffffff815e9598)
Location: drivers/acpi/pci_irq.c:112
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void do_prt_fixups(struct acpi_prt_entry *entry, struct acpi_pci_routing_table *prt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:112
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
**Symbols:**

```
ffffffff81694dc0-ffffffff81694ea7: do_prt_fixups (STB_LOCAL)
ffffffff8169572a-ffffffff81695762: do_prt_fixups.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void do_prt_fixups(struct acpi_prt_entry *entry, struct acpi_pci_routing_table *prt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:112
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
**Symbols:**

```
ffffffff816b2010-ffffffff816b20f7: do_prt_fixups (STB_LOCAL)
ffffffff81c020ad-ffffffff81c020e5: do_prt_fixups.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void do_prt_fixups(struct acpi_prt_entry *entry, struct acpi_pci_routing_table *prt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:108
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
**Symbols:**

```
ffffffff816943b0-ffffffff81694497: do_prt_fixups (STB_LOCAL)
ffffffff81bf38da-ffffffff81bf390f: do_prt_fixups.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void do_prt_fixups(struct acpi_prt_entry *entry, struct acpi_pci_routing_table *prt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:108
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
**Symbols:**

```
ffffffff8170a0b0-ffffffff8170a1a2: do_prt_fixups (STB_LOCAL)
ffffffff81cf0532-ffffffff81cf0564: do_prt_fixups.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void do_prt_fixups(struct acpi_prt_entry *entry, struct acpi_pci_routing_table *prt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:108
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
**Symbols:**

```
ffffffff81838550-ffffffff81838656: do_prt_fixups (STB_LOCAL)
ffffffff81eb83b8-ffffffff81eb83e9: do_prt_fixups.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_prt_fixups(struct acpi_prt_entry *entry, struct acpi_pci_routing_table *prt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff8196d8a0)
Location: drivers/acpi/pci_irq.c:108
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
**Symbols:**

```
ffffffff8196d8a0-ffffffff8196d9d2: do_prt_fixups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_prt_fixups(struct acpi_prt_entry *entry, struct acpi_pci_routing_table *prt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff819b3dd0)
Location: drivers/acpi/pci_irq.c:108
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_find_prt_entry
```
**Symbols:**

```
ffffffff819b3dd0-ffffffff819b3f02: do_prt_fixups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_prt_fixups(struct acpi_prt_entry *entry, struct acpi_pci_routing_table *prt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff819fe340)
Location: drivers/acpi/pci_irq.c:108
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
**Symbols:**

```
ffffffff819fe340-ffffffff819fe472: do_prt_fixups (STB_LOCAL)
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
In drivers/acpi/pci_irq.c (ffff8000107766b8)
Location: drivers/acpi/pci_irq.c:112
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
In drivers/acpi/pci_irq.c (ffffffff815da5d8)
Location: drivers/acpi/pci_irq.c:112
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
In drivers/acpi/pci_irq.c (ffffffff815c41f8)
Location: drivers/acpi/pci_irq.c:112
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
In drivers/acpi/pci_irq.c (ffffffff815dd878)
Location: drivers/acpi/pci_irq.c:112
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
In drivers/acpi/pci_irq.c (ffffffff815f7738)
Location: drivers/acpi/pci_irq.c:112
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
