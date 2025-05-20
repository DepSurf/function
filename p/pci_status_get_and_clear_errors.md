# Function: <code>pci_status_get_and_clear_errors</code>

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
int pci_status_get_and_clear_errors(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81624760)
Location: drivers/pci/pci.c:182
Inline: False
```
**Symbols:**

```
ffffffff81624760-ffffffff816247e0: pci_status_get_and_clear_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_status_get_and_clear_errors(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164a3b0)
Location: drivers/pci/pci.c:191
Inline: False
```
**Symbols:**

```
ffffffff8164a3b0-ffffffff8164a42b: pci_status_get_and_clear_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_status_get_and_clear_errors(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162cfa0)
Location: drivers/pci/pci.c:191
Inline: False
```
**Symbols:**

```
ffffffff8162cfa0-ffffffff8162d01b: pci_status_get_and_clear_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_status_get_and_clear_errors(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169c260)
Location: drivers/pci/pci.c:197
Inline: False
```
**Symbols:**

```
ffffffff8169c260-ffffffff8169c2db: pci_status_get_and_clear_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_status_get_and_clear_errors(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817bdc00)
Location: drivers/pci/pci.c:214
Inline: False
```
**Symbols:**

```
ffffffff817bdc00-ffffffff817bdc8a: pci_status_get_and_clear_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_status_get_and_clear_errors(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818d9e40)
Location: drivers/pci/pci.c:198
Inline: False
```
**Symbols:**

```
ffffffff818d9e40-ffffffff818d9eca: pci_status_get_and_clear_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_status_get_and_clear_errors(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191d190)
Location: drivers/pci/pci.c:213
Inline: False
```
**Symbols:**

```
ffffffff8191d190-ffffffff8191d21a: pci_status_get_and_clear_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_status_get_and_clear_errors(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819655c0)
Location: drivers/pci/pci.c:213
Inline: False
```
**Symbols:**

```
ffffffff819655c0-ffffffff8196564a: pci_status_get_and_clear_errors (STB_GLOBAL)
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
