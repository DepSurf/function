# Function: <code>protection_domain_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void protection_domain_free(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152dfe0)
Location: drivers/iommu/amd_iommu.c:2814
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff8152dfe0-ffffffff8152e03d: protection_domain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void protection_domain_free(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81581b30)
Location: drivers/iommu/amd_iommu.c:2800
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81581b30-ffffffff81581b8d: protection_domain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void protection_domain_free(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815ae4c0)
Location: drivers/iommu/amd_iommu.c:2893
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff815ae4c0-ffffffff815ae4f6: protection_domain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c6653)
Location: drivers/iommu/amd_iommu.c:3039
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff815c4a80-ffffffff815c4ab9: protection_domain_free.part.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162d123)
Location: drivers/iommu/amd_iommu.c:2821
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff8162b8e0-ffffffff8162b919: protection_domain_free.part.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81668d03)
Location: drivers/iommu/amd_iommu.c:2832
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816687f0-ffffffff81668829: protection_domain_free.part.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8168720d)
Location: drivers/iommu/amd_iommu.c:2896
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81687120-ffffffff81687159: protection_domain_free.part.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void protection_domain_free(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816be8d0)
Location: drivers/iommu/amd_iommu.c:2877
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816be8d0-ffffffff816be90d: protection_domain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void protection_domain_free(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e1ca0)
Location: drivers/iommu/amd_iommu.c:2911
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816e1ca0-ffffffff816e1cdd: protection_domain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void protection_domain_free(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81799d30)
Location: drivers/iommu/amd/iommu.c:2311
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81799d30-ffffffff81799dd7: protection_domain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void protection_domain_free(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a8460)
Location: drivers/iommu/amd/iommu.c:2403
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff817a8460-ffffffff817a8507: protection_domain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void protection_domain_free(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81789150)
Location: drivers/iommu/amd/iommu.c:1832
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81789150-ffffffff817891ba: protection_domain_free (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff81810fd0)
Location: drivers/iommu/amd/iommu.c:1871
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
In drivers/iommu/amd/iommu.c (ffffffff81951370)
Location: drivers/iommu/amd/iommu.c:1887
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
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
In drivers/iommu/amd/iommu.c (ffffffff81ab6520)
Location: drivers/iommu/amd/iommu.c:1992
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
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
In drivers/iommu/amd/iommu.c (ffffffff81b02724)
Location: drivers/iommu/amd/iommu.c:2017
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void protection_domain_free(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b51420)
Location: drivers/iommu/amd/iommu.c:2065
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
**Symbols:**

```
ffffffff81b51420-ffffffff81b5155d: protection_domain_free (STB_LOCAL)
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
void protection_domain_free(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a76f0)
Location: drivers/iommu/amd_iommu.c:2911
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816a76f0-ffffffff816a772d: protection_domain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void protection_domain_free(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816850e0)
Location: drivers/iommu/amd_iommu.c:2911
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816850e0-ffffffff8168511d: protection_domain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void protection_domain_free(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d5960)
Location: drivers/iommu/amd_iommu.c:2911
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816d5960-ffffffff816d599d: protection_domain_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void protection_domain_free(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ec900)
Location: drivers/iommu/amd_iommu.c:2911
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816ec900-ffffffff816ec93d: protection_domain_free (STB_LOCAL)
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
