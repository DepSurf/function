# Function: <code>vfio_noiommu_ioctl</code>

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
long int vfio_noiommu_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817cfea0)
Location: drivers/vfio/vfio.c:187
Inline: False
```
**Symbols:**

```
ffffffff817cfea0-ffffffff817cfecc: vfio_noiommu_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int vfio_noiommu_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189a900)
Location: drivers/vfio/vfio.c:188
Inline: False
```
**Symbols:**

```
ffffffff8189a900-ffffffff8189a92c: vfio_noiommu_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int vfio_noiommu_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818a94b0)
Location: drivers/vfio/vfio.c:188
Inline: False
```
**Symbols:**

```
ffffffff818a94b0-ffffffff818a94dc: vfio_noiommu_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int vfio_noiommu_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188c880)
Location: drivers/vfio/vfio.c:178
Inline: False
```
**Symbols:**

```
ffffffff8188c880-ffffffff8188c8ac: vfio_noiommu_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int vfio_noiommu_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:251
Inline: False
```
**Symbols:**

```
ffffffff819204b0-ffffffff819204f0: vfio_noiommu_ioctl (STB_LOCAL)
ffffffff81d11641-ffffffff81d1165d: vfio_noiommu_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int vfio_noiommu_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (0)
Location: drivers/vfio/vfio.c:180
Inline: False
```
**Symbols:**

```
ffffffff81a764e0-ffffffff81a76534: vfio_noiommu_ioctl (STB_LOCAL)
ffffffff81edc39e-ffffffff81edc3ba: vfio_noiommu_ioctl.cold (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int vfio_noiommu_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aad800)
Location: drivers/vfio/vfio.c:187
Inline: False
```
**Symbols:**

```
c000000000aad800-c000000000aad858: vfio_noiommu_ioctl (STB_LOCAL)
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
long int vfio_noiommu_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81779f50)
Location: drivers/vfio/vfio.c:187
Inline: False
```
**Symbols:**

```
ffffffff81779f50-ffffffff81779f7c: vfio_noiommu_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int vfio_noiommu_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c4d20)
Location: drivers/vfio/vfio.c:187
Inline: False
```
**Symbols:**

```
ffffffff817c4d20-ffffffff817c4d4c: vfio_noiommu_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int vfio_noiommu_ioctl(void *iommu_data, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817defc0)
Location: drivers/vfio/vfio.c:187
Inline: False
```
**Symbols:**

```
ffffffff817defc0-ffffffff817defec: vfio_noiommu_ioctl (STB_LOCAL)
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
