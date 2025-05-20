# Function: <code>pci_request_region_exclusive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_request_region_exclusive(struct pci_dev *pdev, int bar, const char *res_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81434970)
Location: drivers/pci/pci.c:2902
Inline: False
```
**Symbols:**

```
ffffffff81434970-ffffffff81434985: pci_request_region_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_request_region_exclusive(struct pci_dev *pdev, int bar, const char *res_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814802e0)
Location: drivers/pci/pci.c:3080
Inline: False
```
**Symbols:**

```
ffffffff814802e0-ffffffff814802f5: pci_request_region_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_request_region_exclusive(struct pci_dev *pdev, int bar, const char *res_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a1930)
Location: drivers/pci/pci.c:3118
Inline: False
```
**Symbols:**

```
ffffffff814a1930-ffffffff814a1945: pci_request_region_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_request_region_exclusive(struct pci_dev *pdev, int bar, const char *res_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ab4b0)
Location: drivers/pci/pci.c:3135
Inline: False
```
**Symbols:**

```
ffffffff814ab4b0-ffffffff814ab4c5: pci_request_region_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_request_region_exclusive(struct pci_dev *pdev, int bar, const char *res_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ea6d0)
Location: drivers/pci/pci.c:3245
Inline: False
```
**Symbols:**

```
ffffffff814ea6d0-ffffffff814ea6e5: pci_request_region_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_request_region_exclusive(struct pci_dev *pdev, int bar, const char *res_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151ad90)
Location: drivers/pci/pci.c:3391
Inline: False
```
**Symbols:**

```
ffffffff8151ad90-ffffffff8151ada5: pci_request_region_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_request_region_exclusive(struct pci_dev *pdev, int bar, const char *res_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81530b00)
Location: drivers/pci/pci.c:3656
Inline: False
```
**Symbols:**

```
ffffffff81530b00-ffffffff81530b15: pci_request_region_exclusive (STB_GLOBAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
