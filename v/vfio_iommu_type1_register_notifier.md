# Function: <code>vfio_iommu_type1_register_notifier</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfio_iommu_type1_register_notifier(void *iommu_data, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d2a10)
Location: drivers/vfio/vfio_iommu_type1.c:2323
Inline: False
```
**Symbols:**

```
ffffffff817d2a10-ffffffff817d2a33: vfio_iommu_type1_register_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_iommu_type1_register_notifier(void *iommu_data, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189dc20)
Location: drivers/vfio/vfio_iommu_type1.c:2830
Inline: False
```
**Symbols:**

```
ffffffff8189dc20-ffffffff8189dc43: vfio_iommu_type1_register_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_iommu_type1_register_notifier(void *iommu_data, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ac8b0)
Location: drivers/vfio/vfio_iommu_type1.c:2886
Inline: False
```
**Symbols:**

```
ffffffff818ac8b0-ffffffff818ac8d3: vfio_iommu_type1_register_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_iommu_type1_register_notifier(void *iommu_data, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8188f9f0)
Location: drivers/vfio/vfio_iommu_type1.c:3111
Inline: False
```
**Symbols:**

```
ffffffff8188f9f0-ffffffff8188fa13: vfio_iommu_type1_register_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_iommu_type1_register_notifier(void *iommu_data, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819232f0)
Location: drivers/vfio/vfio_iommu_type1.c:3113
Inline: False
```
**Symbols:**

```
ffffffff819232f0-ffffffff81923313: vfio_iommu_type1_register_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_iommu_type1_register_notifier(void *iommu_data, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a78da0)
Location: drivers/vfio/vfio_iommu_type1.c:3105
Inline: False
```
**Symbols:**

```
ffffffff81a78da0-ffffffff81a78ddb: vfio_iommu_type1_register_notifier (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfio_iommu_type1_register_notifier(void *iommu_data, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177cac0)
Location: drivers/vfio/vfio_iommu_type1.c:2323
Inline: False
```
**Symbols:**

```
ffffffff8177cac0-ffffffff8177cae3: vfio_iommu_type1_register_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_iommu_type1_register_notifier(void *iommu_data, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c7890)
Location: drivers/vfio/vfio_iommu_type1.c:2323
Inline: False
```
**Symbols:**

```
ffffffff817c7890-ffffffff817c78b3: vfio_iommu_type1_register_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_iommu_type1_register_notifier(void *iommu_data, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e1b30)
Location: drivers/vfio/vfio_iommu_type1.c:2323
Inline: False
```
**Symbols:**

```
ffffffff817e1b30-ffffffff817e1b53: vfio_iommu_type1_register_notifier (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
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
