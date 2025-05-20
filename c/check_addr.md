# Function: <code>check_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_addr(char *name, struct device *hwdev, dma_addr_t bus, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-nommu.c (ffffffff81036d90)
Location: arch/x86/kernel/pci-nommu.c:15
Inline: False
Direct callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
  - arch/x86/kernel/pci-nommu.c:nommu_map_page
```
**Symbols:**

```
ffffffff81036d90-ffffffff81036dec: check_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_addr(char *name, struct device *hwdev, dma_addr_t bus, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-nommu.c (ffffffff81035f90)
Location: arch/x86/kernel/pci-nommu.c:15
Inline: False
Direct callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
  - arch/x86/kernel/pci-nommu.c:nommu_map_page
```
**Symbols:**

```
ffffffff81035f90-ffffffff81035fec: check_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_addr(char *name, struct device *hwdev, dma_addr_t bus, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-nommu.c (ffffffff81035cc0)
Location: arch/x86/kernel/pci-nommu.c:15
Inline: False
Direct callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
  - arch/x86/kernel/pci-nommu.c:nommu_map_page
```
**Symbols:**

```
ffffffff81035cc0-ffffffff81035d1c: check_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_addr(char *name, struct device *hwdev, dma_addr_t bus, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-nommu.c (ffffffff81033c90)
Location: arch/x86/kernel/pci-nommu.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
  - arch/x86/kernel/pci-nommu.c:nommu_map_page
```
**Symbols:**

```
ffffffff81033c90-ffffffff81033cde: check_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_addr(char *name, struct device *hwdev, dma_addr_t bus, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-nommu.c (ffffffff81035fd0)
Location: arch/x86/kernel/pci-nommu.c:18
Inline: False
Direct callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
  - arch/x86/kernel/pci-nommu.c:nommu_map_page
```
**Symbols:**

```
ffffffff81035fd0-ffffffff8103601e: check_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool check_addr(struct device *dev, dma_addr_t dma_addr, size_t size, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8110cfc0)
Location: kernel/dma/direct.c:33
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_page
```
**Symbols:**

```
ffffffff8110cfc0-ffffffff8110d03b: check_addr (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param added. </b>
<code>dma_addr_t dma_addr</code>
</li>
<li>
<b>Param added. </b>
<code>const char *caller</code>
</li>
<li>
<b>Param removed. </b>
<code>char *name</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *hwdev</code>
</li>
<li>
<b>Param removed. </b>
<code>dma_addr_t bus</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, hwdev, bus, size</code> ➡️ <code>dev, dma_addr, size, caller</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
</ul>
