# Function: <code>do_detach</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8152ffba)
Location: drivers/iommu/amd_iommu.c:1913
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__detach_device
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
In drivers/iommu/amd_iommu.c (ffffffff81583c4a)
Location: drivers/iommu/amd_iommu.c:1793
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__detach_device
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
In drivers/iommu/amd_iommu.c (ffffffff815b0f5a)
Location: drivers/iommu/amd_iommu.c:1886
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__detach_device
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
In drivers/iommu/amd_iommu.c (ffffffff815c64ba)
Location: drivers/iommu/amd_iommu.c:2133
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__detach_device
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
In drivers/iommu/amd_iommu.c (ffffffff8162cf8a)
Location: drivers/iommu/amd_iommu.c:1904
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__detach_device
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
In drivers/iommu/amd_iommu.c (ffffffff81668b61)
Location: drivers/iommu/amd_iommu.c:1915
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__detach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816868e0)
Location: drivers/iommu/amd_iommu.c:1996
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:detach_device
```
**Symbols:**

```
ffffffff816868e0-ffffffff81686999: do_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816be140)
Location: drivers/iommu/amd_iommu.c:1995
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:detach_device
```
**Symbols:**

```
ffffffff816be140-ffffffff816be1f5: do_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e1400)
Location: drivers/iommu/amd_iommu.c:2056
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:detach_device
```
**Symbols:**

```
ffffffff816e1400-ffffffff816e14d7: do_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81796af0)
Location: drivers/iommu/amd/iommu.c:1917
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:detach_device
```
**Symbols:**

```
ffffffff81796af0-ffffffff81796c02: do_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a5210)
Location: drivers/iommu/amd/iommu.c:2008
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:detach_device
```
**Symbols:**

```
ffffffff817a5210-ffffffff817a5322: do_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817898c0)
Location: drivers/iommu/amd/iommu.c:1498
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:detach_device
```
**Symbols:**

```
ffffffff817898c0-ffffffff817899d2: do_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81810af0)
Location: drivers/iommu/amd/iommu.c:1547
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:detach_device
```
**Symbols:**

```
ffffffff81810af0-ffffffff81810bfd: do_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff819511e0)
Location: drivers/iommu/amd/iommu.c:1569
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:detach_device
```
**Symbols:**

```
ffffffff819511e0-ffffffff8195133c: do_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1671
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:detach_device
```
**Symbols:**

```
ffffffff81ab6360-ffffffff81ab64df: do_detach (STB_LOCAL)
ffffffff82096f31-ffffffff82096f4c: do_detach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1696
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:detach_device
```
**Symbols:**

```
ffffffff81b02510-ffffffff81b026d3: do_detach (STB_LOCAL)
ffffffff82117e17-ffffffff82117e32: do_detach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1838
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
```
**Symbols:**

```
ffffffff81b56880-ffffffff81b569c4: do_detach (STB_LOCAL)
ffffffff821f5ae0-ffffffff821f5afb: do_detach.cold (STB_LOCAL)
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
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a6e50)
Location: drivers/iommu/amd_iommu.c:2056
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:detach_device
```
**Symbols:**

```
ffffffff816a6e50-ffffffff816a6f27: do_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684840)
Location: drivers/iommu/amd_iommu.c:2056
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:detach_device
```
**Symbols:**

```
ffffffff81684840-ffffffff81684917: do_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d50c0)
Location: drivers/iommu/amd_iommu.c:2056
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:detach_device
```
**Symbols:**

```
ffffffff816d50c0-ffffffff816d5197: do_detach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_detach(struct iommu_dev_data *dev_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ef7c0)
Location: drivers/iommu/amd_iommu.c:2056
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:detach_device
```
**Symbols:**

```
ffffffff816ef7c0-ffffffff816ef897: do_detach (STB_LOCAL)
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
