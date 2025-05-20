# Function: <code>pci_pri_init</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_pri_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816559e0)
Location: drivers/pci/ats.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_init_capabilities
```
**Symbols:**

```
ffffffff816559e0-ffffffff81655a52: pci_pri_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_pri_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81675f80)
Location: drivers/pci/ats.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_init_capabilities
```
**Symbols:**

```
ffffffff81675f80-ffffffff81675ff2: pci_pri_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_pri_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816584b0)
Location: drivers/pci/ats.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff816584b0-ffffffff81658522: pci_pri_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_pri_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816ca4f0)
Location: drivers/pci/ats.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff816ca4f0-ffffffff816ca562: pci_pri_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_pri_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff817f08e0)
Location: drivers/pci/ats.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff817f08e0-ffffffff817f0964: pci_pri_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_pri_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81918bf0)
Location: drivers/pci/ats.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81918bf0-ffffffff81918c74: pci_pri_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_pri_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8195c210)
Location: drivers/pci/ats.c:175
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8195c210-ffffffff8195c294: pci_pri_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_pri_init(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff819a5830)
Location: drivers/pci/ats.c:176
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff819a5830-ffffffff819a58b4: pci_pri_init (STB_GLOBAL)
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
