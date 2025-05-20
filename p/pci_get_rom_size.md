# Function: <code>pci_get_rom_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t pci_get_rom_size(struct pci_dev *pdev, void *rom, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff8143cfa0)
Location: drivers/pci/rom.c:70
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
```
**Symbols:**

```
ffffffff8143cfa0-ffffffff8143d036: pci_get_rom_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t pci_get_rom_size(struct pci_dev *pdev, void *rom, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff81488ef0)
Location: drivers/pci/rom.c:79
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
```
**Symbols:**

```
ffffffff81488ef0-ffffffff81488f8d: pci_get_rom_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t pci_get_rom_size(struct pci_dev *pdev, void *rom, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff814aa6c0)
Location: drivers/pci/rom.c:84
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
```
**Symbols:**

```
ffffffff814aa6c0-ffffffff814aa75d: pci_get_rom_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t pci_get_rom_size(struct pci_dev *pdev, void *rom, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff814b4a10)
Location: drivers/pci/rom.c:84
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
```
**Symbols:**

```
ffffffff814b4a10-ffffffff814b4aad: pci_get_rom_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t pci_get_rom_size(struct pci_dev *pdev, void *rom, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff814f4230)
Location: drivers/pci/rom.c:84
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
```
**Symbols:**

```
ffffffff814f4230-ffffffff814f42cd: pci_get_rom_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t pci_get_rom_size(struct pci_dev *pdev, void *rom, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffff815242f0)
Location: drivers/pci/rom.c:83
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
```
**Symbols:**

```
ffffffff815242f0-ffffffff8152438d: pci_get_rom_size (STB_GLOBAL)
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
In drivers/pci/rom.c (ffffffff8153a1aa)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
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
In drivers/pci/rom.c (ffffffff81569c2a)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
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
In drivers/pci/rom.c (ffffffff8158abfa)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
size_t pci_get_rom_size(struct pci_dev *pdev, void *rom, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (0)
Location: drivers/pci/rom.c:83
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
```
**Symbols:**

```
ffffffff816319c0-ffffffff81631a6d: pci_get_rom_size (STB_LOCAL)
ffffffff81631c71-ffffffff81631c89: pci_get_rom_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
size_t pci_get_rom_size(struct pci_dev *pdev, void *rom, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/rom.c (0)
Location: drivers/pci/rom.c:83
Inline: False
Direct callers:
  - drivers/pci/rom.c:pci_map_rom
```
**Symbols:**

```
ffffffff81656fd0-ffffffff8165707d: pci_get_rom_size (STB_LOCAL)
ffffffff81bf81c2-ffffffff81bf81da: pci_get_rom_size.cold (STB_LOCAL)
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
In drivers/pci/rom.c (ffffffff81639abe)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
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
In drivers/pci/rom.c (ffffffff816aa28b)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
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
In drivers/pci/rom.c (ffffffff817cd158)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
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
In drivers/pci/rom.c (ffffffff818ec5b8)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
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
In drivers/pci/rom.c (ffffffff8192fa98)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
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
In drivers/pci/rom.c (ffffffff81978418)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffff8000106ef828)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (c088a424)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (c00000000086c7b8)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/rom.c (ffffffe0004c3694)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
```
</details>
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
In drivers/pci/rom.c (ffffffff8157ea7a)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
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
In drivers/pci/rom.c (ffffffff8156d85a)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
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
In drivers/pci/rom.c (ffffffff8157e94a)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
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
In drivers/pci/rom.c (ffffffff81598dfa)
Location: drivers/pci/rom.c:83
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_map_rom
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
