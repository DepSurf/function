# Function: <code>pci_reset_supported</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool pci_reset_supported(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a22d5)
Location: drivers/pci/pci.c:76
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/pci.c:pci_dev_reset_method_attr_is_visible
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_dev_reset_attr_is_visible
```
**Symbols:**

```
ffffffff816a1410-ffffffff816a1425: pci_reset_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool pci_reset_supported(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c4395)
Location: drivers/pci/pci.c:76
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/pci.c:pci_dev_reset_method_attr_is_visible
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_dev_reset_attr_is_visible
```
**Symbols:**

```
ffffffff817c3220-ffffffff817c323b: pci_reset_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool pci_reset_supported(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e12d5)
Location: drivers/pci/pci.c:80
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/pci.c:pci_dev_reset_method_attr_is_visible
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_dev_reset_attr_is_visible
```
**Symbols:**

```
ffffffff818dffd0-ffffffff818dffeb: pci_reset_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool pci_reset_supported(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81924715)
Location: drivers/pci/pci.c:95
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/pci.c:pci_dev_reset_method_attr_is_visible
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_dev_reset_attr_is_visible
```
**Symbols:**

```
ffffffff81923430-ffffffff8192344b: pci_reset_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool pci_reset_supported(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196cde5)
Location: drivers/pci/pci.c:95
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/pci/pci.c:pci_reset_function_locked
  - drivers/pci/pci.c:pci_reset_function
  - drivers/pci/pci.c:pci_dev_reset_method_attr_is_visible
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_dev_reset_attr_is_visible
```
**Symbols:**

```
ffffffff8196b9b0-ffffffff8196b9cb: pci_reset_supported (STB_GLOBAL)
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
