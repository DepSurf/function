# Function: <code>pcibios_fwaddrmap_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pcibios_fwaddrmap *pcibios_fwaddrmap_lookup(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff816f5f90)
Location: arch/x86/pci/i386.c:57
Inline: False
Direct callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
```
**Symbols:**

```
ffffffff816f5f90-ffffffff816f5fe7: pcibios_fwaddrmap_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pcibios_fwaddrmap *pcibios_fwaddrmap_lookup(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff8175ac50)
Location: arch/x86/pci/i386.c:57
Inline: False
Direct callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
```
**Symbols:**

```
ffffffff8175ac50-ffffffff8175aca4: pcibios_fwaddrmap_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pcibios_fwaddrmap *pcibios_fwaddrmap_lookup(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff817871b0)
Location: arch/x86/pci/i386.c:57
Inline: False
Direct callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
```
**Symbols:**

```
ffffffff817871b0-ffffffff81787204: pcibios_fwaddrmap_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pcibios_fwaddrmap *pcibios_fwaddrmap_lookup(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff817a63c0)
Location: arch/x86/pci/i386.c:57
Inline: False
Direct callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
```
**Symbols:**

```
ffffffff817a63c0-ffffffff817a6403: pcibios_fwaddrmap_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pcibios_fwaddrmap *pcibios_fwaddrmap_lookup(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff8181d640)
Location: arch/x86/pci/i386.c:58
Inline: False
Direct callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
```
**Symbols:**

```
ffffffff8181d640-ffffffff8181d6b0: pcibios_fwaddrmap_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pcibios_fwaddrmap *pcibios_fwaddrmap_lookup(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff81867810)
Location: arch/x86/pci/i386.c:58
Inline: False
Direct callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
```
**Symbols:**

```
ffffffff81867810-ffffffff8186787a: pcibios_fwaddrmap_lookup (STB_LOCAL)
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
In arch/x86/pci/i386.c (ffffffff81887c87)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
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
In arch/x86/pci/i386.c (ffffffff818d24f8)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
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
In arch/x86/pci/i386.c (ffffffff819048b5)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff81bb50b9)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
  - arch/x86/pci/i386.c:pcibios_save_fw_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff81bca319)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
  - arch/x86/pci/i386.c:pcibios_save_fw_addr
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
In arch/x86/pci/i386.c (ffffffff81bbd856)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
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
In arch/x86/pci/i386.c (ffffffff81c8d753)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
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
In arch/x86/pci/i386.c (ffffffff81e3c651)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
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
In arch/x86/pci/i386.c (ffffffff82015848)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
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
In arch/x86/pci/i386.c (ffffffff82095b82)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
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
In arch/x86/pci/i386.c (ffffffff8216d05c)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
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
In arch/x86/pci/i386.c (ffffffff818a3cd8)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
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
In arch/x86/pci/i386.c (ffffffff8185f455)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
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
In arch/x86/pci/i386.c (ffffffff818f52d5)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
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
In arch/x86/pci/i386.c (ffffffff81916375)
Location: arch/x86/pci/i386.c:58
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
  - arch/x86/pci/i386.c:pcibios_retrieve_fw_addr
```
</details>
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
</ul>
