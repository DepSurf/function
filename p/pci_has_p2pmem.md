# Function: <code>pci_has_p2pmem</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_has_p2pmem(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff8191d248)
Location: drivers/pci/p2pdma.c:731
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
```
**Symbols:**

```
ffffffff8208ff2a-ffffffff8208ff3e: pci_has_p2pmem.cold (STB_LOCAL)
ffffffff8191bba0-ffffffff8191bbfa: pci_has_p2pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_has_p2pmem(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff81960808)
Location: drivers/pci/p2pdma.c:733
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
```
**Symbols:**

```
ffffffff8211028d-ffffffff821102a1: pci_has_p2pmem.cold (STB_LOCAL)
ffffffff8195f1b0-ffffffff8195f20a: pci_has_p2pmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_has_p2pmem(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff819a9f28)
Location: drivers/pci/p2pdma.c:732
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
```
**Symbols:**

```
ffffffff821edfb5-ffffffff821edfc9: pci_has_p2pmem.cold (STB_LOCAL)
ffffffff819a8810-ffffffff819a886a: pci_has_p2pmem (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
