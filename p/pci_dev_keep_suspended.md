# Function: <code>pci_dev_keep_suspended</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool pci_dev_keep_suspended(struct pci_dev *pci_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814371a0)
Location: drivers/pci/pci.c:2075
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
**Symbols:**

```
ffffffff814371a0-ffffffff8143724f: pci_dev_keep_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool pci_dev_keep_suspended(struct pci_dev *pci_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81482d40)
Location: drivers/pci/pci.c:2096
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
**Symbols:**

```
ffffffff81482d40-ffffffff81482df8: pci_dev_keep_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool pci_dev_keep_suspended(struct pci_dev *pci_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a42d0)
Location: drivers/pci/pci.c:2138
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
**Symbols:**

```
ffffffff814a42d0-ffffffff814a4388: pci_dev_keep_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool pci_dev_keep_suspended(struct pci_dev *pci_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ae370)
Location: drivers/pci/pci.c:2153
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
**Symbols:**

```
ffffffff814ae370-ffffffff814ae442: pci_dev_keep_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool pci_dev_keep_suspended(struct pci_dev *pci_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ed750)
Location: drivers/pci/pci.c:2163
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
**Symbols:**

```
ffffffff814ed750-ffffffff814ed81f: pci_dev_keep_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pci_dev_keep_suspended(struct pci_dev *pci_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151d3a0)
Location: drivers/pci/pci.c:2242
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
**Symbols:**

```
ffffffff8151d3a0-ffffffff8151d474: pci_dev_keep_suspended (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pci_dev_keep_suspended(struct pci_dev *pci_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81532aa0)
Location: drivers/pci/pci.c:2419
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
```
**Symbols:**

```
ffffffff81532aa0-ffffffff81532b74: pci_dev_keep_suspended (STB_GLOBAL)
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
