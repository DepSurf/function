# Function: <code>pci_epc_get_next_free_bar</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
enum pci_barno pci_epc_get_next_free_bar(const struct pci_epc_features *epc_features, enum pci_barno bar);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165c565)
Location: drivers/pci/endpoint/pci-epc-core.c:108
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
**Symbols:**

```
ffffffff8165c4a0-ffffffff8165c51f: pci_epc_get_next_free_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum pci_barno pci_epc_get_next_free_bar(const struct pci_epc_features *epc_features, enum pci_barno bar);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816ceba5)
Location: drivers/pci/endpoint/pci-epc-core.c:108
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
**Symbols:**

```
ffffffff81ceb15f-ffffffff81ceb191: pci_epc_get_next_free_bar.cold (STB_LOCAL)
ffffffff816cead0-ffffffff816ceb56: pci_epc_get_next_free_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum pci_barno pci_epc_get_next_free_bar(const struct pci_epc_features *epc_features, enum pci_barno bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: drivers/pci/endpoint/pci-epc-core.c:108
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
**Symbols:**

```
ffffffff81eb25cd-ffffffff81eb25ff: pci_epc_get_next_free_bar.cold (STB_LOCAL)
ffffffff817f7720-ffffffff817f77ce: pci_epc_get_next_free_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum pci_barno pci_epc_get_next_free_bar(const struct pci_epc_features *epc_features, enum pci_barno bar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (0)
Location: drivers/pci/endpoint/pci-epc-core.c:108
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
**Symbols:**

```
ffffffff82090131-ffffffff82090163: pci_epc_get_next_free_bar.cold (STB_LOCAL)
ffffffff81923320-ffffffff819233ce: pci_epc_get_next_free_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum pci_barno pci_epc_get_next_free_bar(const struct pci_epc_features *epc_features, enum pci_barno bar);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819670f5)
Location: drivers/pci/endpoint/pci-epc-core.c:108
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
**Symbols:**

```
ffffffff821104d8-ffffffff82110501: pci_epc_get_next_free_bar.cold (STB_LOCAL)
ffffffff81967000-ffffffff81967091: pci_epc_get_next_free_bar (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum pci_barno pci_epc_get_next_free_bar(const struct pci_epc_features *epc_features, enum pci_barno bar);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819b0825)
Location: drivers/pci/endpoint/pci-epc-core.c:107
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
**Symbols:**

```
ffffffff821ee200-ffffffff821ee229: pci_epc_get_next_free_bar.cold (STB_LOCAL)
ffffffff819b0730-ffffffff819b07c1: pci_epc_get_next_free_bar (STB_GLOBAL)
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
