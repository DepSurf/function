# Function: <code>acpi_pci_irq_find_prt_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff81486f9f)
Location: drivers/acpi/pci_irq.c:221
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff81486f9f-ffffffff81487254: acpi_pci_irq_find_prt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff814d5bca)
Location: drivers/acpi/pci_irq.c:219
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff814d5bca-ffffffff814d5ea4: acpi_pci_irq_find_prt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff814f8222)
Location: drivers/acpi/pci_irq.c:219
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff814f8222-ffffffff814f84fc: acpi_pci_irq_find_prt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff81506f80)
Location: drivers/acpi/pci_irq.c:219
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff81506f80-ffffffff8150725d: acpi_pci_irq_find_prt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff815491f0)
Location: drivers/acpi/pci_irq.c:219
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff815491f0-ffffffff8154952b: acpi_pci_irq_find_prt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:219
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff8157f350-ffffffff8157f65e: acpi_pci_irq_find_prt_entry (STB_LOCAL)
ffffffff8157fcaa-ffffffff8157fcd9: acpi_pci_irq_find_prt_entry.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:219
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff81597070-ffffffff8159737e: acpi_pci_irq_find_prt_entry (STB_LOCAL)
ffffffff81597a3a-ffffffff81597a69: acpi_pci_irq_find_prt_entry.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:206
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff815c8220-ffffffff815c8528: acpi_pci_irq_find_prt_entry (STB_LOCAL)
ffffffff815c8afa-ffffffff815c8b2f: acpi_pci_irq_find_prt_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:206
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff815e9440-ffffffff815e9748: acpi_pci_irq_find_prt_entry (STB_LOCAL)
ffffffff815e9d1a-ffffffff815e9d4f: acpi_pci_irq_find_prt_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff81695040)
Location: drivers/acpi/pci_irq.c:206
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff81695040-ffffffff8169513a: acpi_pci_irq_find_prt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff816b2290)
Location: drivers/acpi/pci_irq.c:206
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff816b2290-ffffffff816b238a: acpi_pci_irq_find_prt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff81694600)
Location: drivers/acpi/pci_irq.c:199
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff81694600-ffffffff816946fa: acpi_pci_irq_find_prt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff8170a310)
Location: drivers/acpi/pci_irq.c:199
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff8170a310-ffffffff8170a40a: acpi_pci_irq_find_prt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff81838660)
Location: drivers/acpi/pci_irq.c:199
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff81838660-ffffffff81838887: acpi_pci_irq_find_prt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff8196d9f0)
Location: drivers/acpi/pci_irq.c:199
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff8196d9f0-ffffffff8196dc17: acpi_pci_irq_find_prt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff819b3f20)
Location: drivers/acpi/pci_irq.c:199
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff819b3f20-ffffffff819b4147: acpi_pci_irq_find_prt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff819fe640)
Location: drivers/acpi/pci_irq.c:199
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff819fe640-ffffffff819fe750: acpi_pci_irq_find_prt_entry (STB_LOCAL)
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
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffff800010776588)
Location: drivers/acpi/pci_irq.c:206
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffff800010776588-ffff80001077686c: acpi_pci_irq_find_prt_entry (STB_LOCAL)
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
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:206
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff815da480-ffffffff815da717: acpi_pci_irq_find_prt_entry (STB_LOCAL)
ffffffff815dab4a-ffffffff815dab7f: acpi_pci_irq_find_prt_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:206
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff815c40a0-ffffffff815c4337: acpi_pci_irq_find_prt_entry (STB_LOCAL)
ffffffff815c476a-ffffffff815c479f: acpi_pci_irq_find_prt_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:206
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff815dd720-ffffffff815dda28: acpi_pci_irq_find_prt_entry (STB_LOCAL)
ffffffff815ddffa-ffffffff815de02f: acpi_pci_irq_find_prt_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_find_prt_entry(struct pci_dev *dev, int pin, struct acpi_prt_entry **entry_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:206
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
  - drivers/acpi/pci_irq.c:acpi_pci_irq_lookup
```
**Symbols:**

```
ffffffff815f75e0-ffffffff815f78e8: acpi_pci_irq_find_prt_entry (STB_LOCAL)
ffffffff815f7eba-ffffffff815f7eef: acpi_pci_irq_find_prt_entry.cold (STB_LOCAL)
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
