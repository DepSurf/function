# Function: <code>iommu_sva_set_ops</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iommu_sva_set_ops(struct iommu_sva *handle, const struct iommu_sva_ops *sva_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b5be0)
Location: drivers/iommu/iommu.c:2450
Inline: False
```
**Symbols:**

```
ffffffff816b5be0-ffffffff816b5c06: iommu_sva_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_sva_set_ops(struct iommu_sva *handle, const struct iommu_sva_ops *sva_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d88e0)
Location: drivers/iommu/iommu.c:2528
Inline: False
```
**Symbols:**

```
ffffffff816d88e0-ffffffff816d8906: iommu_sva_set_ops (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int iommu_sva_set_ops(struct iommu_sva *handle, const struct iommu_sva_ops *sva_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c3fb0)
Location: drivers/iommu/iommu.c:2528
Inline: False
```
**Symbols:**

```
ffff8000108c3fb0-ffff8000108c3ff8: iommu_sva_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_sva_set_ops(struct iommu_sva *handle, const struct iommu_sva_ops *sva_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bb4a4)
Location: drivers/iommu/iommu.c:2528
Inline: False
```
**Symbols:**

```
c09bb4a4-c09bb4e4: iommu_sva_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_sva_set_ops(struct iommu_sva *handle, const struct iommu_sva_ops *sva_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c000000000969c10)
Location: drivers/iommu/iommu.c:2528
Inline: False
```
**Symbols:**

```
c000000000969c10-c000000000969c48: iommu_sva_set_ops (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int iommu_sva_set_ops(struct iommu_sva *handle, const struct iommu_sva_ops *sva_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169e330)
Location: drivers/iommu/iommu.c:2528
Inline: False
```
**Symbols:**

```
ffffffff8169e330-ffffffff8169e356: iommu_sva_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_sva_set_ops(struct iommu_sva *handle, const struct iommu_sva_ops *sva_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167bd20)
Location: drivers/iommu/iommu.c:2528
Inline: False
```
**Symbols:**

```
ffffffff8167bd20-ffffffff8167bd46: iommu_sva_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_sva_set_ops(struct iommu_sva *handle, const struct iommu_sva_ops *sva_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cc5a0)
Location: drivers/iommu/iommu.c:2528
Inline: False
```
**Symbols:**

```
ffffffff816cc5a0-ffffffff816cc5c6: iommu_sva_set_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_sva_set_ops(struct iommu_sva *handle, const struct iommu_sva_ops *sva_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e6a70)
Location: drivers/iommu/iommu.c:2528
Inline: False
```
**Symbols:**

```
ffffffff816e6a70-ffffffff816e6a96: iommu_sva_set_ops (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
