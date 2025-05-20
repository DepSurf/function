# Function: <code>pci_p2pdma_enable_store</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pci_p2pdma_enable_store(const char *page, struct pci_dev **p2p_dev, bool *use_p2pdma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/p2pdma.c (0)
Location: drivers/pci/p2pdma.c:1055
Inline: False
```
**Symbols:**

```
ffffffff8208ff67-ffffffff8208ff7c: pci_p2pdma_enable_store.cold (STB_LOCAL)
ffffffff8191d200-ffffffff8191d31c: pci_p2pdma_enable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pci_p2pdma_enable_store(const char *page, struct pci_dev **p2p_dev, bool *use_p2pdma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/p2pdma.c (0)
Location: drivers/pci/p2pdma.c:1056
Inline: False
```
**Symbols:**

```
ffffffff821102ca-ffffffff821102df: pci_p2pdma_enable_store.cold (STB_LOCAL)
ffffffff819607c0-ffffffff819608dc: pci_p2pdma_enable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pci_p2pdma_enable_store(const char *page, struct pci_dev **p2p_dev, bool *use_p2pdma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/p2pdma.c (0)
Location: drivers/pci/p2pdma.c:1054
Inline: False
```
**Symbols:**

```
ffffffff821edff2-ffffffff821ee007: pci_p2pdma_enable_store.cold (STB_LOCAL)
ffffffff819a9ee0-ffffffff819a9ffc: pci_p2pdma_enable_store (STB_GLOBAL)
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
