# Function: <code>domain_id_free</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8152e015)
Location: drivers/iommu/amd_iommu.c:1634
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:protection_domain_free
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
In drivers/iommu/amd_iommu.c (ffffffff81581b65)
Location: drivers/iommu/amd_iommu.c:1529
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:protection_domain_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void domain_id_free(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815ade30)
Location: drivers/iommu/amd_iommu.c:1619
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:protection_domain_free
  - drivers/iommu/amd_iommu.c:dma_ops_domain_free
```
**Symbols:**

```
ffffffff815ade30-ffffffff815ade71: domain_id_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void domain_id_free(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c3ab0)
Location: drivers/iommu/amd_iommu.c:1678
Inline: False
```
**Symbols:**

```
ffffffff815c3ab0-ffffffff815c3af1: domain_id_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void domain_id_free(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162a7b0)
Location: drivers/iommu/amd_iommu.c:1620
Inline: False
```
**Symbols:**

```
ffffffff8162a7b0-ffffffff8162a7f1: domain_id_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void domain_id_free(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816687b0)
Location: drivers/iommu/amd_iommu.c:1625
Inline: False
```
**Symbols:**

```
ffffffff816687b0-ffffffff816687ef: domain_id_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void domain_id_free(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816870e0)
Location: drivers/iommu/amd_iommu.c:1767
Inline: False
```
**Symbols:**

```
ffffffff816870e0-ffffffff8168711f: domain_id_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void domain_id_free(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816be890)
Location: drivers/iommu/amd_iommu.c:1757
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:protection_domain_free
```
**Symbols:**

```
ffffffff816be890-ffffffff816be8cf: domain_id_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void domain_id_free(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e1c60)
Location: drivers/iommu/amd_iommu.c:1817
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:protection_domain_free
```
**Symbols:**

```
ffffffff816e1c60-ffffffff816e1c9f: domain_id_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81799dab)
Location: drivers/iommu/amd/iommu.c:1759
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a84db)
Location: drivers/iommu/amd/iommu.c:1850
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_free
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
In drivers/iommu/amd/iommu.c (ffffffff81789192)
Location: drivers/iommu/amd/iommu.c:1343
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_free
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
In drivers/iommu/amd/iommu.c (ffffffff8181108e)
Location: drivers/iommu/amd/iommu.c:1392
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
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
In drivers/iommu/amd/iommu.c (ffffffff8195143a)
Location: drivers/iommu/amd/iommu.c:1414
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void domain_id_free(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab1b80)
Location: drivers/iommu/amd/iommu.c:1496
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
**Symbols:**

```
ffffffff81ab1b80-ffffffff81ab1bc8: domain_id_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void domain_id_free(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81afdbf0)
Location: drivers/iommu/amd/iommu.c:1516
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
**Symbols:**

```
ffffffff81afdbf0-ffffffff81afdc38: domain_id_free (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff81b514bf)
Location: drivers/iommu/amd/iommu.c:1621
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_free
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
<summary>In <code>aws</code>: ✅</summary>

```c
void domain_id_free(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a76b0)
Location: drivers/iommu/amd_iommu.c:1817
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:protection_domain_free
```
**Symbols:**

```
ffffffff816a76b0-ffffffff816a76ef: domain_id_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void domain_id_free(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816850a0)
Location: drivers/iommu/amd_iommu.c:1817
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:protection_domain_free
```
**Symbols:**

```
ffffffff816850a0-ffffffff816850df: domain_id_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void domain_id_free(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d5920)
Location: drivers/iommu/amd_iommu.c:1817
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:protection_domain_free
```
**Symbols:**

```
ffffffff816d5920-ffffffff816d595f: domain_id_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void domain_id_free(int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ec4e0)
Location: drivers/iommu/amd_iommu.c:1817
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:protection_domain_free
```
**Symbols:**

```
ffffffff816ec4e0-ffffffff816ec51d: domain_id_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
