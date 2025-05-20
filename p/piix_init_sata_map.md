# Function: <code>piix_init_sata_map</code>

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
In drivers/ata/ata_piix.c (ffffffff815e34b3)
Location: drivers/ata/ata_piix.c:1370
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
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
In drivers/ata/ata_piix.c (ffffffff8163d1c9)
Location: drivers/ata/ata_piix.c:1370
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
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
In drivers/ata/ata_piix.c (ffffffff8166e249)
Location: drivers/ata/ata_piix.c:1370
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
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
In drivers/ata/ata_piix.c (ffffffff8168279f)
Location: drivers/ata/ata_piix.c:1370
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
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
In drivers/ata/ata_piix.c (ffffffff816ebfcf)
Location: drivers/ata/ata_piix.c:1371
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
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
In drivers/ata/ata_piix.c (ffffffff81728956)
Location: drivers/ata/ata_piix.c:1371
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
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
In drivers/ata/ata_piix.c (ffffffff8174b144)
Location: drivers/ata/ata_piix.c:1371
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
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
In drivers/ata/ata_piix.c (ffffffff81786ed0)
Location: drivers/ata/ata_piix.c:1354
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
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
In drivers/ata/ata_piix.c (ffffffff817aab10)
Location: drivers/ata/ata_piix.c:1354
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
const int *piix_init_sata_map(struct pci_dev *pdev, struct ata_port_info *pinfo, const struct piix_map_db *map_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/ata_piix.c (0)
Location: drivers/ata/ata_piix.c:1352
Inline: False
Direct callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81870530-ffffffff818706ea: piix_init_sata_map (STB_LOCAL)
ffffffff81870e6d-ffffffff81870eca: piix_init_sata_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
const int *piix_init_sata_map(struct pci_dev *pdev, struct ata_port_info *pinfo, const struct piix_map_db *map_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/ata_piix.c (0)
Location: drivers/ata/ata_piix.c:1352
Inline: False
Direct callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff8187f200-ffffffff8187f3a8: piix_init_sata_map (STB_LOCAL)
ffffffff81c18366-ffffffff81c183c3: piix_init_sata_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
const int *piix_init_sata_map(struct pci_dev *pdev, struct ata_port_info *pinfo, const struct piix_map_db *map_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/ata_piix.c (0)
Location: drivers/ata/ata_piix.c:1352
Inline: False
Direct callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81861a70-ffffffff81861c16: piix_init_sata_map (STB_LOCAL)
ffffffff81c0a15b-ffffffff81c0a1b8: piix_init_sata_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
const int *piix_init_sata_map(struct pci_dev *pdev, struct ata_port_info *pinfo, const struct piix_map_db *map_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/ata_piix.c (0)
Location: drivers/ata/ata_piix.c:1352
Inline: False
Direct callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff818f09b0-ffffffff818f0b56: piix_init_sata_map (STB_LOCAL)
ffffffff81d0ed6c-ffffffff81d0edc9: piix_init_sata_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const int *piix_init_sata_map(struct pci_dev *pdev, struct ata_port_info *pinfo, const struct piix_map_db *map_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/ata_piix.c (0)
Location: drivers/ata/ata_piix.c:1356
Inline: False
Direct callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81a42d10-ffffffff81a42ecb: piix_init_sata_map (STB_LOCAL)
ffffffff81ed9c7b-ffffffff81ed9ce7: piix_init_sata_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const int *piix_init_sata_map(struct pci_dev *pdev, struct ata_port_info *pinfo, const struct piix_map_db *map_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/ata_piix.c (ffffffff81bc9200)
Location: drivers/ata/ata_piix.c:1356
Inline: False
Direct callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81bc9200-ffffffff81bc941f: piix_init_sata_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const int *piix_init_sata_map(struct pci_dev *pdev, struct ata_port_info *pinfo, const struct piix_map_db *map_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/ata_piix.c (ffffffff81c20d90)
Location: drivers/ata/ata_piix.c:1356
Inline: False
Direct callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81c20d90-ffffffff81c20fc1: piix_init_sata_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const int *piix_init_sata_map(struct pci_dev *pdev, struct ata_port_info *pinfo, const struct piix_map_db *map_db);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/ata_piix.c (ffffffff81c75f50)
Location: drivers/ata/ata_piix.c:1356
Inline: False
Direct callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
**Symbols:**

```
ffffffff81c75f50-ffffffff81c76181: piix_init_sata_map (STB_LOCAL)
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
In drivers/ata/ata_piix.c (ffffffff8176f630)
Location: drivers/ata/ata_piix.c:1354
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
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
In drivers/ata/ata_piix.c (ffffffff8174f480)
Location: drivers/ata/ata_piix.c:1354
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
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
In drivers/ata/ata_piix.c (ffffffff8179f990)
Location: drivers/ata/ata_piix.c:1354
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
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
In drivers/ata/ata_piix.c (ffffffff817b9810)
Location: drivers/ata/ata_piix.c:1354
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
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
