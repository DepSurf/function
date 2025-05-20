# Function: <code>pci_epc_multi_mem_init</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_epc_multi_mem_init(struct pci_epc *epc, struct pci_epc_mem_window *windows, unsigned int num_windows);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8165a120)
Location: drivers/pci/endpoint/pci-epc-mem.c:47
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_init
```
**Symbols:**

```
ffffffff8165a120-ffffffff8165a2bd: pci_epc_multi_mem_init.part.0 (STB_LOCAL)
ffffffff8165a2c0-ffffffff8165a332: pci_epc_multi_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_epc_multi_mem_init(struct pci_epc *epc, struct pci_epc_mem_window *windows, unsigned int num_windows);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8167a390)
Location: drivers/pci/endpoint/pci-epc-mem.c:47
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_init
```
**Symbols:**

```
ffffffff8167a390-ffffffff8167a52d: pci_epc_multi_mem_init.part.0 (STB_LOCAL)
ffffffff8167a530-ffffffff8167a5a2: pci_epc_multi_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_epc_multi_mem_init(struct pci_epc *epc, struct pci_epc_mem_window *windows, unsigned int num_windows);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8165ce90)
Location: drivers/pci/endpoint/pci-epc-mem.c:47
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_init
```
**Symbols:**

```
ffffffff8165ce90-ffffffff8165d024: pci_epc_multi_mem_init.part.0 (STB_LOCAL)
ffffffff8165d030-ffffffff8165d0a2: pci_epc_multi_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_epc_multi_mem_init(struct pci_epc *epc, struct pci_epc_mem_window *windows, unsigned int num_windows);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff816cfa70)
Location: drivers/pci/endpoint/pci-epc-mem.c:47
Inline: True
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_init
```
**Symbols:**

```
ffffffff816cf8d0-ffffffff816cfa68: pci_epc_multi_mem_init.part.0 (STB_LOCAL)
ffffffff81ceb293-ffffffff81ceb2af: pci_epc_multi_mem_init.part.0.cold (STB_LOCAL)
ffffffff816cfa70-ffffffff816cfae2: pci_epc_multi_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_epc_multi_mem_init(struct pci_epc *epc, struct pci_epc_mem_window *windows, unsigned int num_windows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: drivers/pci/endpoint/pci-epc-mem.c:47
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_init
```
**Symbols:**

```
ffffffff81eb26f9-ffffffff81eb2715: pci_epc_multi_mem_init.cold (STB_LOCAL)
ffffffff817f8750-ffffffff817f8931: pci_epc_multi_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pci_epc_multi_mem_init(struct pci_epc *epc, struct pci_epc_mem_window *windows, unsigned int num_windows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: drivers/pci/endpoint/pci-epc-mem.c:47
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_init
```
**Symbols:**

```
ffffffff820901e5-ffffffff82090201: pci_epc_multi_mem_init.cold (STB_LOCAL)
ffffffff81924500-ffffffff819246e1: pci_epc_multi_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pci_epc_multi_mem_init(struct pci_epc *epc, struct pci_epc_mem_window *windows, unsigned int num_windows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: drivers/pci/endpoint/pci-epc-mem.c:47
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_init
```
**Symbols:**

```
ffffffff82110583-ffffffff8211059f: pci_epc_multi_mem_init.cold (STB_LOCAL)
ffffffff819681b0-ffffffff8196838e: pci_epc_multi_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pci_epc_multi_mem_init(struct pci_epc *epc, struct pci_epc_mem_window *windows, unsigned int num_windows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: drivers/pci/endpoint/pci-epc-mem.c:47
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_init
```
**Symbols:**

```
ffffffff821ee2e2-ffffffff821ee2fe: pci_epc_multi_mem_init.cold (STB_LOCAL)
ffffffff819b18b0-ffffffff819b1abd: pci_epc_multi_mem_init (STB_GLOBAL)
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
