# Function: <code>iommu_sva_bind_device</code>

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
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b6160)
Location: drivers/iommu/iommu.c:2384
Inline: False
```
**Symbols:**

```
ffffffff816b6160-ffffffff816b6240: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d8e60)
Location: drivers/iommu/iommu.c:2462
Inline: False
```
**Symbols:**

```
ffffffff816d8e60-ffffffff816d8f40: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178d450)
Location: drivers/iommu/iommu.c:2765
Inline: False
```
**Symbols:**

```
ffffffff8178d450-ffffffff8178d533: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b8f60)
Location: drivers/iommu/iommu.c:2988
Inline: False
```
**Symbols:**

```
ffffffff817b8f60-ffffffff817b9043: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179c170)
Location: drivers/iommu/iommu.c:2967
Inline: False
```
**Symbols:**

```
ffffffff8179c170-ffffffff8179c253: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81824e60)
Location: drivers/iommu/iommu.c:3052
Inline: False
```
**Symbols:**

```
ffffffff81824e60-ffffffff81824f43: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81965b80)
Location: drivers/iommu/iommu.c:2784
Inline: False
```
**Symbols:**

```
ffffffff81965b80-ffffffff81965c6d: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sva.c (ffffffff81adbc80)
Location: drivers/iommu/iommu-sva.c:90
Inline: True
```
**Symbols:**

```
ffffffff81adbc80-ffffffff81adbdd4: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sva.c (ffffffff81b29e40)
Location: drivers/iommu/iommu-sva.c:63
Inline: True
```
**Symbols:**

```
ffffffff81b29e40-ffffffff81b2a041: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sva.c (ffffffff81b80ef0)
Location: drivers/iommu/iommu-sva.c:70
Inline: False
```
**Symbols:**

```
ffffffff81b80ef0-ffffffff81b8121f: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c4610)
Location: drivers/iommu/iommu.c:2462
Inline: False
```
**Symbols:**

```
ffff8000108c4610-ffff8000108c4710: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bbad4)
Location: drivers/iommu/iommu.c:2462
Inline: False
```
**Symbols:**

```
c09bbad4-c09bbba0: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096a3b0)
Location: drivers/iommu/iommu.c:2462
Inline: False
```
**Symbols:**

```
c00000000096a3b0-c00000000096a538: iommu_sva_bind_device (STB_GLOBAL)
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
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169e8b0)
Location: drivers/iommu/iommu.c:2462
Inline: False
```
**Symbols:**

```
ffffffff8169e8b0-ffffffff8169e990: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167c2a0)
Location: drivers/iommu/iommu.c:2462
Inline: False
```
**Symbols:**

```
ffffffff8167c2a0-ffffffff8167c380: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ccb20)
Location: drivers/iommu/iommu.c:2462
Inline: False
```
**Symbols:**

```
ffffffff816ccb20-ffffffff816ccc00: iommu_sva_bind_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct iommu_sva *iommu_sva_bind_device(struct device *dev, struct mm_struct *mm, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e7000)
Location: drivers/iommu/iommu.c:2462
Inline: False
```
**Symbols:**

```
ffffffff816e7000-ffffffff816e70e0: iommu_sva_bind_device (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void *drvdata</code>
</li>
</ul>
</details>
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
