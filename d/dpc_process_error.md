# Function: <code>dpc_process_error</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dpc_process_error(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:196
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8163e751-ffffffff8163e8be: dpc_process_error.cold (STB_LOCAL)
ffffffff8163e3b0-ffffffff8163e42c: dpc_process_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dpc_process_error(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:199
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff81bf9d59-ffffffff81bf9ec6: dpc_process_error.cold (STB_LOCAL)
ffffffff81664ad0-ffffffff81664b4c: dpc_process_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dpc_process_error(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:263
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff81bebbb6-ffffffff81bebd1d: dpc_process_error.cold (STB_LOCAL)
ffffffff81647080-ffffffff816470fc: dpc_process_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dpc_process_error(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:263
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff81ce6794-ffffffff81ce68f8: dpc_process_error.cold (STB_LOCAL)
ffffffff816b8930-ffffffff816b89ab: dpc_process_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dpc_process_error(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/dpc.c (0)
Location: drivers/pci/pcie/dpc.c:263
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/edr.c:edr_handle_event
```
**Symbols:**

```
ffffffff81ead327-ffffffff81ead4b4: dpc_process_error.cold (STB_LOCAL)
ffffffff817dcdf0-ffffffff817dce8d: dpc_process_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dpc_process_error(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff818ff140)
Location: drivers/pci/pcie/dpc.c:263
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/edr.c:edr_handle_event
```
**Symbols:**

```
ffffffff818ff140-ffffffff818ff361: dpc_process_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dpc_process_error(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff819426d0)
Location: drivers/pci/pcie/dpc.c:262
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/edr.c:edr_handle_event
```
**Symbols:**

```
ffffffff819426d0-ffffffff819428e0: dpc_process_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dpc_process_error(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/dpc.c (ffffffff8198b960)
Location: drivers/pci/pcie/dpc.c:266
Inline: False
Direct callers:
  - drivers/pci/pcie/dpc.c:dpc_handler
  - drivers/pci/pcie/edr.c:edr_handle_event
```
**Symbols:**

```
ffffffff8198b960-ffffffff8198bbac: dpc_process_error (STB_GLOBAL)
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
