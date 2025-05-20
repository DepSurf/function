# Function: <code>pci_mmconfig_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff816f70e0)
Location: arch/x86/pci/mmconfig-shared.c:116
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
```
**Symbols:**

```
ffffffff816f70e0-ffffffff816f7123: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8175be18)
Location: arch/x86/pci/mmconfig-shared.c:116
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff8175bd70-ffffffff8175bdb3: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81788388)
Location: arch/x86/pci/mmconfig-shared.c:116
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff817882e0-ffffffff81788323: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff817a7482)
Location: arch/x86/pci/mmconfig-shared.c:116
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff817a73e0-ffffffff817a7423: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8181e6e2)
Location: arch/x86/pci/mmconfig-shared.c:117
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff8181e640-ffffffff8181e683: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81868940)
Location: arch/x86/pci/mmconfig-shared.c:117
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff81868890-ffffffff818688d3: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff818889c0)
Location: arch/x86/pci/mmconfig-shared.c:117
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff81888910-ffffffff81888953: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff818d32ef)
Location: arch/x86/pci/mmconfig-shared.c:117
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff818d3240-ffffffff818d3283: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8190566f)
Location: arch/x86/pci/mmconfig-shared.c:118
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff819055c0-ffffffff81905603: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bb5c2c)
Location: arch/x86/pci/mmconfig-shared.c:118
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff81bb5b80-ffffffff81bb5bc3: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bcaddc)
Location: arch/x86/pci/mmconfig-shared.c:118
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff81bcad30-ffffffff81bcad73: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bbe71c)
Location: arch/x86/pci/mmconfig-shared.c:118
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff81bbe670-ffffffff81bbe6b3: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81c8e66b)
Location: arch/x86/pci/mmconfig-shared.c:118
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff81c8e5b0-ffffffff81c8e5f3: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81e3d70d)
Location: arch/x86/pci/mmconfig-shared.c:118
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff81e3d640-ffffffff81e3d697: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff82016b5d)
Location: arch/x86/pci/mmconfig-shared.c:119
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff82016a80-ffffffff82016ad7: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff82096f0d)
Location: arch/x86/pci/mmconfig-shared.c:119
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff82096e30-ffffffff82096e87: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8216e3b2)
Location: arch/x86/pci/mmconfig-shared.c:118
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff8216e2d0-ffffffff8216e327: pci_mmconfig_lookup (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff818a4a2f)
Location: arch/x86/pci/mmconfig-shared.c:118
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff818a4980-ffffffff818a49c3: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff818601ef)
Location: arch/x86/pci/mmconfig-shared.c:118
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff81860140-ffffffff81860183: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff818f608f)
Location: arch/x86/pci/mmconfig-shared.c:118
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff818f5fe0-ffffffff818f6023: pci_mmconfig_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_lookup(int segment, int bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8191717f)
Location: arch/x86/pci/mmconfig-shared.c:118
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
Direct callers:
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_write
  - arch/x86/pci/mmconfig_64.c:pci_mmcfg_read
  - arch/x86/pci/numachip.c:pci_mmcfg_write_numachip
  - arch/x86/pci/numachip.c:pci_mmcfg_read_numachip
```
**Symbols:**

```
ffffffff819170d0-ffffffff81917113: pci_mmconfig_lookup (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
