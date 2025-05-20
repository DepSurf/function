# Function: <code>print_iommu_info</code>

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
In drivers/iommu/amd_iommu_init.c (ffffffff81faa334)
Location: drivers/iommu/amd_iommu_init.c:1328
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff81fd6e15)
Location: drivers/iommu/amd_iommu_init.c:1533
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff82012cb5)
Location: drivers/iommu/amd_iommu_init.c:1645
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff820f658c)
Location: drivers/iommu/amd_iommu_init.c:1657
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff826ffcc2)
Location: drivers/iommu/amd_iommu_init.c:1802
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:1803
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
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
In drivers/iommu/amd_iommu_init.c (0)
Location: drivers/iommu/amd_iommu_init.c:1834
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
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
In drivers/iommu/amd_iommu_init.c (ffffffff828fccbb)
Location: drivers/iommu/amd_iommu_init.c:1821
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff82905c90)
Location: drivers/iommu/amd_iommu_init.c:1841
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_iommu_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179bf65)
Location: drivers/iommu/amd/init.c:1828
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff8179bf65-ffffffff8179c068: print_iommu_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void print_iommu_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81c0bd6c)
Location: drivers/iommu/amd/init.c:1942
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff81c0bd6c-ffffffff81c0be66: print_iommu_info (STB_LOCAL)
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
In drivers/iommu/amd/init.c (ffffffff83213917)
Location: drivers/iommu/amd/init.c:1895
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff832fcba0)
Location: drivers/iommu/amd/init.c:1909
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff834b5778)
Location: drivers/iommu/amd/init.c:1916
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff83ef15c1)
Location: drivers/iommu/amd/init.c:2122
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff837171d1)
Location: drivers/iommu/amd/init.c:2157
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff8394ac1e)
Location: drivers/iommu/amd/init.c:2159
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff828ed477)
Location: drivers/iommu/amd_iommu_init.c:1841
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff828e4904)
Location: drivers/iommu/amd_iommu_init.c:1841
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff82900fb3)
Location: drivers/iommu/amd_iommu_init.c:1841
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff82906cf2)
Location: drivers/iommu/amd_iommu_init.c:1841
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
