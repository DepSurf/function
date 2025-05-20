# Function: <code>vfio_dev_viable</code>

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
int vfio_dev_viable(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d15f0)
Location: drivers/vfio/vfio.c:657
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
**Symbols:**

```
ffffffff817d15f0-ffffffff817d16b2: vfio_dev_viable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_dev_viable(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189c560)
Location: drivers/vfio/vfio.c:660
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
**Symbols:**

```
ffffffff8189c560-ffffffff8189c622: vfio_dev_viable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_dev_viable(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818ab170)
Location: drivers/vfio/vfio.c:661
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
**Symbols:**

```
ffffffff818ab170-ffffffff818ab232: vfio_dev_viable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_dev_viable(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188dbe0)
Location: drivers/vfio/vfio.c:600
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
**Symbols:**

```
ffffffff8188dbe0-ffffffff8188dcab: vfio_dev_viable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_dev_viable(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81921220)
Location: drivers/vfio/vfio.c:673
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
**Symbols:**

```
ffffffff81921220-ffffffff819212ee: vfio_dev_viable (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfio_dev_viable(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000ab0770)
Location: drivers/vfio/vfio.c:657
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
**Symbols:**

```
c000000000ab0770-c000000000ab08a0: vfio_dev_viable (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfio_dev_viable(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177b6a0)
Location: drivers/vfio/vfio.c:657
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
**Symbols:**

```
ffffffff8177b6a0-ffffffff8177b762: vfio_dev_viable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_dev_viable(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c6470)
Location: drivers/vfio/vfio.c:657
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
**Symbols:**

```
ffffffff817c6470-ffffffff817c6532: vfio_dev_viable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_dev_viable(struct device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817e0710)
Location: drivers/vfio/vfio.c:657
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
**Symbols:**

```
ffffffff817e0710-ffffffff817e07d2: vfio_dev_viable (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
