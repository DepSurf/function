# Function: <code>pcibios_save_fw_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff816f633a)
Location: arch/x86/pci/i386.c:71
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff8175b037)
Location: arch/x86/pci/i386.c:71
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff81787588)
Location: arch/x86/pci/i386.c:71
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff817a6760)
Location: arch/x86/pci/i386.c:71
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff8181d9f0)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff81867c43)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff81887c79)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff818d24e0)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff8190489d)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcibios_save_fw_addr(struct pci_dev *dev, int idx, resource_size_t fw_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff81bb4aa0)
Location: arch/x86/pci/i386.c:72
Inline: False
Direct callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff81bb4aa0-ffffffff81bb4b90: pcibios_save_fw_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcibios_save_fw_addr(struct pci_dev *dev, int idx, resource_size_t fw_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff81bc9d00)
Location: arch/x86/pci/i386.c:72
Inline: False
Direct callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
**Symbols:**

```
ffffffff81bc9d00-ffffffff81bc9df0: pcibios_save_fw_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff81bbd74d)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff81c8d663)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff81e3c543)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff820156d3)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff82095a20)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff8216cefd)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff818a3cc0)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff8185f43d)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff818f52bd)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff8191635d)
Location: arch/x86/pci/i386.c:72
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
