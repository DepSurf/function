# Function: <code>iommu_default_passthrough</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d87b0)
Location: drivers/iommu/iommu.c:2271
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816d87b0-ffffffff816d87c5: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178cf20)
Location: drivers/iommu/iommu.c:2570
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_init_dma_ops
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff8178cf20-ffffffff8178cf35: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b8940)
Location: drivers/iommu/iommu.c:2793
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_init_dma_ops
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff817b8940-ffffffff817b8955: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179bbd0)
Location: drivers/iommu/iommu.c:2777
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff8179bbd0-ffffffff8179bbe5: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff83300993)
Location: drivers/iommu/iommu.c:2862
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_subsys_init
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff818247a0-ffffffff818247b5: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff834b9662)
Location: drivers/iommu/iommu.c:2639
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_subsys_init
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff81964650-ffffffff81964669: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff83ef68bb)
Location: drivers/iommu/iommu.c:2701
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_subsys_init
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/init.c:amd_iommu_snp_enable
  - drivers/iommu/amd/init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff81acd730-ffffffff81acd749: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8371c34f)
Location: drivers/iommu/iommu.c:2707
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_subsys_init
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/init.c:amd_iommu_snp_enable
  - drivers/iommu/amd/init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff81b1c1d0-ffffffff81b1c1e9: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8394fe3f)
Location: drivers/iommu/iommu.c:2983
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_subsys_init
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/init.c:amd_iommu_snp_enable
```
**Symbols:**

```
ffffffff81b72550-ffffffff81b72569: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c3de0)
Location: drivers/iommu/iommu.c:2271
Inline: True
```
**Symbols:**

```
ffff8000108c3de0-ffff8000108c3e08: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bb340)
Location: drivers/iommu/iommu.c:2271
Inline: True
```
**Symbols:**

```
c09bb340-c09bb370: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c0000000009699c0)
Location: drivers/iommu/iommu.c:2271
Inline: True
```
**Symbols:**

```
c0000000009699c0-c0000000009699e8: iommu_default_passthrough (STB_GLOBAL)
```
</details>
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
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169e200)
Location: drivers/iommu/iommu.c:2271
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8169e200-ffffffff8169e215: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167bbf0)
Location: drivers/iommu/iommu.c:2271
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8167bbf0-ffffffff8167bc05: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cc470)
Location: drivers/iommu/iommu.c:2271
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816cc470-ffffffff816cc485: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool iommu_default_passthrough();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e6940)
Location: drivers/iommu/iommu.c:2271
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_dma_ops
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816e6940-ffffffff816e6955: iommu_default_passthrough (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
