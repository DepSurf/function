# Function: <code>vfio_group_get_from_iommu</code>

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
struct vfio_group *vfio_group_get_from_iommu(struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d0f60)
Location: drivers/vfio/vfio.c:483
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
```
**Symbols:**

```
ffffffff817d0f60-ffffffff817d0fde: vfio_group_get_from_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vfio_group *vfio_group_get_from_iommu(struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189be00)
Location: drivers/vfio/vfio.c:484
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
**Symbols:**

```
ffffffff8189be00-ffffffff8189bea7: vfio_group_get_from_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vfio_group *vfio_group_get_from_iommu(struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818aaa10)
Location: drivers/vfio/vfio.c:484
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
**Symbols:**

```
ffffffff818aaa10-ffffffff818aaab7: vfio_group_get_from_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vfio_group *vfio_group_get_from_iommu(struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188e0d0)
Location: drivers/vfio/vfio.c:474
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
```
**Symbols:**

```
ffffffff8188e0d0-ffffffff8188e177: vfio_group_get_from_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vfio_group *vfio_group_get_from_iommu(struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81921710)
Location: drivers/vfio/vfio.c:547
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_unregister_notifier
  - drivers/vfio/vfio.c:vfio_register_notifier
  - drivers/vfio/vfio.c:vfio_unpin_pages
  - drivers/vfio/vfio.c:vfio_pin_pages
  - drivers/vfio/vfio.c:vfio_group_get_external_user_from_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_dev
  - drivers/vfio/vfio.c:vfio_register_group_dev
```
**Symbols:**

```
ffffffff81921710-ffffffff819217b7: vfio_group_get_from_iommu (STB_LOCAL)
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
In drivers/vfio/vfio.c (ffffffff81a785d5)
Location: drivers/vfio/vfio.c:320
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_register_group_dev
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
struct vfio_group *vfio_group_get_from_iommu(struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aadea0)
Location: drivers/vfio/vfio.c:483
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
```
**Symbols:**

```
c000000000aadea0-c000000000aadfa4: vfio_group_get_from_iommu (STB_LOCAL)
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
struct vfio_group *vfio_group_get_from_iommu(struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177b010)
Location: drivers/vfio/vfio.c:483
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
```
**Symbols:**

```
ffffffff8177b010-ffffffff8177b08e: vfio_group_get_from_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vfio_group *vfio_group_get_from_iommu(struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c5de0)
Location: drivers/vfio/vfio.c:483
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
```
**Symbols:**

```
ffffffff817c5de0-ffffffff817c5e5e: vfio_group_get_from_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vfio_group *vfio_group_get_from_iommu(struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817e0080)
Location: drivers/vfio/vfio.c:483
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_group_get_from_dev
```
**Symbols:**

```
ffffffff817e0080-ffffffff817e00fe: vfio_group_get_from_iommu (STB_LOCAL)
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
