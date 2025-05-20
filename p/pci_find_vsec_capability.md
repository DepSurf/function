# Function: <code>pci_find_vsec_capability</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u16 pci_find_vsec_capability(struct pci_dev *dev, u16 vendor, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162e940)
Location: drivers/pci/pci.c:705
Inline: True
```
**Symbols:**

```
ffffffff8162e940-ffffffff8162e9e3: pci_find_vsec_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u16 pci_find_vsec_capability(struct pci_dev *dev, u16 vendor, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169dda0)
Location: drivers/pci/pci.c:715
Inline: True
```
**Symbols:**

```
ffffffff8169dda0-ffffffff8169de43: pci_find_vsec_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u16 pci_find_vsec_capability(struct pci_dev *dev, u16 vendor, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817be300)
Location: drivers/pci/pci.c:732
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff817be300-ffffffff817be3a3: pci_find_vsec_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 pci_find_vsec_capability(struct pci_dev *dev, u16 vendor, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818da610)
Location: drivers/pci/pci.c:716
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff818da610-ffffffff818da6b3: pci_find_vsec_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 pci_find_vsec_capability(struct pci_dev *dev, u16 vendor, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191d950)
Location: drivers/pci/pci.c:731
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8191d950-ffffffff8191d9f3: pci_find_vsec_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 pci_find_vsec_capability(struct pci_dev *dev, u16 vendor, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81965d80)
Location: drivers/pci/pci.c:731
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81965d80-ffffffff81965e23: pci_find_vsec_capability (STB_GLOBAL)
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
