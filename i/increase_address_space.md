# Function: <code>increase_address_space</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8152ee51)
Location: drivers/iommu/amd_iommu.c:1128
Inline: True
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
In drivers/iommu/amd_iommu.c (ffffffff8158364f)
Location: drivers/iommu/amd_iommu.c:1224
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff815b095f)
Location: drivers/iommu/amd_iommu.c:1313
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff815c6890)
Location: drivers/iommu/amd_iommu.c:1372
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff8162d630)
Location: drivers/iommu/amd_iommu.c:1313
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff81668279)
Location: drivers/iommu/amd_iommu.c:1319
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff81686691)
Location: drivers/iommu/amd_iommu.c:1429
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff816bdd4a)
Location: drivers/iommu/amd_iommu.c:1438
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff816e0f37)
Location: drivers/iommu/amd_iommu.c:1464
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool increase_address_space(struct protection_domain *domain, long unsigned int address, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81798e50)
Location: drivers/iommu/amd/iommu.c:1406
Inline: False
```
**Symbols:**

```
ffffffff81798e50-ffffffff81798fbd: increase_address_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool increase_address_space(struct protection_domain *domain, long unsigned int address, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a76d0)
Location: drivers/iommu/amd/iommu.c:1496
Inline: False
```
**Symbols:**

```
ffffffff817a76d0-ffffffff817a7834: increase_address_space (STB_LOCAL)
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
In drivers/iommu/amd/io_pgtable.c (ffffffff8178bd3e)
Location: drivers/iommu/amd/io_pgtable.c:177
Inline: True
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
In drivers/iommu/amd/io_pgtable.c (ffffffff8181370f)
Location: drivers/iommu/amd/io_pgtable.c:177
Inline: True
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
In drivers/iommu/amd/io_pgtable.c (ffffffff81954827)
Location: drivers/iommu/amd/io_pgtable.c:151
Inline: True
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
In drivers/iommu/amd/io_pgtable.c (ffffffff81aba677)
Location: drivers/iommu/amd/io_pgtable.c:151
Inline: True
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
In drivers/iommu/amd/io_pgtable.c (ffffffff81b06c69)
Location: drivers/iommu/amd/io_pgtable.c:151
Inline: True
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
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5ac3f)
Location: drivers/iommu/amd/io_pgtable.c:151
Inline: True
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
In drivers/iommu/amd_iommu.c (ffffffff816a6987)
Location: drivers/iommu/amd_iommu.c:1464
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff81684377)
Location: drivers/iommu/amd_iommu.c:1464
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff816d4bf7)
Location: drivers/iommu/amd_iommu.c:1464
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
In drivers/iommu/amd_iommu.c (ffffffff816ef2f7)
Location: drivers/iommu/amd_iommu.c:1464
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
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
