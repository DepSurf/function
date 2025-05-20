# Function: <code>vfio_group_get_device</code>

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
struct vfio_device *vfio_group_get_device(struct vfio_group *group, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d1510)
Location: drivers/vfio/vfio.c:595
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_dev_viable
```
**Symbols:**

```
ffffffff817d1510-ffffffff817d159a: vfio_group_get_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vfio_device *vfio_group_get_device(struct vfio_group *group, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189c400)
Location: drivers/vfio/vfio.c:598
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_dev_viable
```
**Symbols:**

```
ffffffff8189c400-ffffffff8189c4d6: vfio_group_get_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vfio_device *vfio_group_get_device(struct vfio_group *group, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818ab010)
Location: drivers/vfio/vfio.c:598
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_dev_viable
```
**Symbols:**

```
ffffffff818ab010-ffffffff818ab0e6: vfio_group_get_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vfio_device *vfio_group_get_device(struct vfio_group *group, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188db30)
Location: drivers/vfio/vfio.c:538
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_dev_viable
```
**Symbols:**

```
ffffffff8188db30-ffffffff8188dbd4: vfio_group_get_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vfio_device *vfio_group_get_device(struct vfio_group *group, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81921170)
Location: drivers/vfio/vfio.c:611
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_dev_viable
```
**Symbols:**

```
ffffffff81921170-ffffffff81921214: vfio_group_get_device (STB_LOCAL)
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
In drivers/vfio/vfio.c (ffffffff81a783d0)
Location: drivers/vfio/vfio.c:462
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_register_dev
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
struct vfio_device *vfio_group_get_device(struct vfio_group *group, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aae030)
Location: drivers/vfio/vfio.c:595
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_dev_viable
```
**Symbols:**

```
c000000000aae030-c000000000aae12c: vfio_group_get_device (STB_LOCAL)
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
struct vfio_device *vfio_group_get_device(struct vfio_group *group, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177b5c0)
Location: drivers/vfio/vfio.c:595
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_dev_viable
```
**Symbols:**

```
ffffffff8177b5c0-ffffffff8177b64a: vfio_group_get_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vfio_device *vfio_group_get_device(struct vfio_group *group, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c6390)
Location: drivers/vfio/vfio.c:595
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_dev_viable
```
**Symbols:**

```
ffffffff817c6390-ffffffff817c641a: vfio_group_get_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vfio_device *vfio_group_get_device(struct vfio_group *group, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817e0630)
Location: drivers/vfio/vfio.c:595
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_dev_viable
```
**Symbols:**

```
ffffffff817e0630-ffffffff817e06ba: vfio_group_get_device (STB_LOCAL)
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
