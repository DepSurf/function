# Function: <code>iomem_get_mapping</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
struct address_space *iomem_get_mapping();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ae130)
Location: kernel/resource.c:1152
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_create_attr
  - drivers/pci/proc.c:proc_bus_pci_open
```
**Symbols:**

```
ffffffff810ae130-ffffffff810ae146: iomem_get_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct address_space *iomem_get_mapping();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bfcb0)
Location: kernel/resource.c:1152
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_open
```
**Symbols:**

```
ffffffff810bfcb0-ffffffff810bfcc6: iomem_get_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct address_space *iomem_get_mapping();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d7190)
Location: kernel/resource.c:1139
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_open
```
**Symbols:**

```
ffffffff810d7190-ffffffff810d71aa: iomem_get_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct address_space *iomem_get_mapping();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f6bc0)
Location: kernel/resource.c:1147
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_open
```
**Symbols:**

```
ffffffff810f6bc0-ffffffff810f6bda: iomem_get_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct address_space *iomem_get_mapping();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81102fd0)
Location: kernel/resource.c:1147
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_open
```
**Symbols:**

```
ffffffff81102fd0-ffffffff81102fea: iomem_get_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct address_space *iomem_get_mapping();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110c900)
Location: kernel/resource.c:1202
Inline: False
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_open
```
**Symbols:**

```
ffffffff8110c900-ffffffff8110c91a: iomem_get_mapping (STB_GLOBAL)
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
