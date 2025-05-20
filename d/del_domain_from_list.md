# Function: <code>del_domain_from_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void del_domain_from_list(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152d670)
Location: drivers/iommu/amd_iommu.c:1608
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:protection_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff8152d670-ffffffff8152d6c4: del_domain_from_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void del_domain_from_list(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815811e0)
Location: drivers/iommu/amd_iommu.c:1503
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:protection_domain_free
  - drivers/iommu/amd_iommu.c:dma_ops_domain_free
```
**Symbols:**

```
ffffffff815811e0-ffffffff81581234: del_domain_from_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void del_domain_from_list(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815addd0)
Location: drivers/iommu/amd_iommu.c:1593
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:protection_domain_free
  - drivers/iommu/amd_iommu.c:dma_ops_domain_free
```
**Symbols:**

```
ffffffff815addd0-ffffffff815ade24: del_domain_from_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void del_domain_from_list(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c3a50)
Location: drivers/iommu/amd_iommu.c:1652
Inline: False
```
**Symbols:**

```
ffffffff815c3a50-ffffffff815c3aa4: del_domain_from_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void del_domain_from_list(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162a750)
Location: drivers/iommu/amd_iommu.c:1594
Inline: False
```
**Symbols:**

```
ffffffff8162a750-ffffffff8162a7a4: del_domain_from_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void del_domain_from_list(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81665400)
Location: drivers/iommu/amd_iommu.c:1600
Inline: False
```
**Symbols:**

```
ffffffff81665400-ffffffff81665454: del_domain_from_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void del_domain_from_list(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81683ce0)
Location: drivers/iommu/amd_iommu.c:1742
Inline: False
```
**Symbols:**

```
ffffffff81683ce0-ffffffff81683d34: del_domain_from_list (STB_LOCAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
