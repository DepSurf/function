# Function: <code>for_each_device_domain</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int for_each_device_domain(int (*fn)(struct device_domain_info *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816901c0)
Location: drivers/iommu/intel-iommu.c:388
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:get_alias_pasid_table
```
**Symbols:**

```
ffffffff816901c0-ffffffff8169025d: for_each_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int for_each_device_domain(int (*fn)(struct device_domain_info *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c8360)
Location: drivers/iommu/intel-iommu.c:382
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:get_alias_pasid_table
```
**Symbols:**

```
ffffffff816c8360-ffffffff816c83fd: for_each_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int for_each_device_domain(int (*fn)(struct device_domain_info *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eb310)
Location: drivers/iommu/intel-iommu.c:390
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:get_alias_pasid_table
```
**Symbols:**

```
ffffffff816eb310-ffffffff816eb3ad: for_each_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int for_each_device_domain(int (*fn)(struct device_domain_info *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a3b10)
Location: drivers/iommu/intel/iommu.c:394
Inline: False
Direct callers:
  - drivers/iommu/intel/pasid.c:get_alias_pasid_table
```
**Symbols:**

```
ffffffff817a3b10-ffffffff817a3bad: for_each_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int for_each_device_domain(int (*fn)(struct device_domain_info *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b0a50)
Location: drivers/iommu/intel/iommu.c:387
Inline: False
Direct callers:
  - drivers/iommu/intel/pasid.c:get_alias_pasid_table
```
**Symbols:**

```
ffffffff817b0a50-ffffffff817b0aed: for_each_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int for_each_device_domain(int (*fn)(struct device_domain_info *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817934e0)
Location: drivers/iommu/intel/iommu.c:396
Inline: False
Direct callers:
  - drivers/iommu/intel/pasid.c:get_alias_pasid_table
```
**Symbols:**

```
ffffffff817934e0-ffffffff8179357d: for_each_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int for_each_device_domain(int (*fn)(struct device_domain_info *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181b300)
Location: drivers/iommu/intel/iommu.c:378
Inline: False
Direct callers:
  - drivers/iommu/intel/pasid.c:get_alias_pasid_table
```
**Symbols:**

```
ffffffff8181b300-ffffffff8181b39d: for_each_device_domain (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int for_each_device_domain(int (*fn)(struct device_domain_info *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b0c40)
Location: drivers/iommu/intel-iommu.c:390
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:get_alias_pasid_table
```
**Symbols:**

```
ffffffff816b0c40-ffffffff816b0cdd: for_each_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int for_each_device_domain(int (*fn)(struct device_domain_info *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168e740)
Location: drivers/iommu/intel-iommu.c:390
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:get_alias_pasid_table
```
**Symbols:**

```
ffffffff8168e740-ffffffff8168e7dd: for_each_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int for_each_device_domain(int (*fn)(struct device_domain_info *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816defd0)
Location: drivers/iommu/intel-iommu.c:390
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:get_alias_pasid_table
```
**Symbols:**

```
ffffffff816defd0-ffffffff816df06d: for_each_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int for_each_device_domain(int (*fn)(struct device_domain_info *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f95e0)
Location: drivers/iommu/intel-iommu.c:390
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:get_alias_pasid_table
```
**Symbols:**

```
ffffffff816f95e0-ffffffff816f967d: for_each_device_domain (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
