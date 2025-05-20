# Function: <code>iommu_group_for_each_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152a040)
Location: drivers/iommu/iommu.c:530
Inline: False
```
**Symbols:**

```
ffffffff8152a040-ffffffff8152a0b1: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157d6d0)
Location: drivers/iommu/iommu.c:521
Inline: False
```
**Symbols:**

```
ffffffff8157d6d0-ffffffff8157d741: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815a97f0)
Location: drivers/iommu/iommu.c:659
Inline: False
```
**Symbols:**

```
ffffffff815a97f0-ffffffff815a9861: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815bf430)
Location: drivers/iommu/iommu.c:703
Inline: False
```
**Symbols:**

```
ffffffff815bf430-ffffffff815bf4a1: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81625a30)
Location: drivers/iommu/iommu.c:705
Inline: False
```
**Symbols:**

```
ffffffff81625a30-ffffffff81625aa3: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81660a10)
Location: drivers/iommu/iommu.c:706
Inline: False
```
**Symbols:**

```
ffffffff81660a10-ffffffff81660a83: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167eef0)
Location: drivers/iommu/iommu.c:772
Inline: False
```
**Symbols:**

```
ffffffff8167eef0-ffffffff8167ef63: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b5d70)
Location: drivers/iommu/iommu.c:790
Inline: False
```
**Symbols:**

```
ffffffff816b5d70-ffffffff816b5de4: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d8a70)
Location: drivers/iommu/iommu.c:846
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff816d8a70-ffffffff816d8ae4: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178ecd0)
Location: drivers/iommu/iommu.c:948
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio_iommu_type1.c:vfio_release_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff8178ecd0-ffffffff8178ed44: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817baee0)
Location: drivers/iommu/iommu.c:969
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio_iommu_type1.c:vfio_release_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff817baee0-ffffffff817baf54: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179e9c0)
Location: drivers/iommu/iommu.c:998
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio_iommu_type1.c:vfio_release_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff8179e9c0-ffffffff8179ea34: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81827790)
Location: drivers/iommu/iommu.c:1013
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio_iommu_type1.c:vfio_release_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff81827790-ffffffff81827804: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81967230)
Location: drivers/iommu/iommu.c:1017
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff81967230-ffffffff819672ae: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad0e10)
Location: drivers/iommu/iommu.c:1138
Inline: False
```
**Symbols:**

```
ffffffff81ad0e10-ffffffff81ad0e8e: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1c2c0)
Location: drivers/iommu/iommu.c:1124
Inline: False
```
**Symbols:**

```
ffffffff81b1c2c0-ffffffff81b1c33e: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b72640)
Location: drivers/iommu/iommu.c:1268
Inline: False
```
**Symbols:**

```
ffffffff81b72640-ffffffff81b726be: iommu_group_for_each_dev (STB_GLOBAL)
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
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c4158)
Location: drivers/iommu/iommu.c:846
Inline: False
```
**Symbols:**

```
ffff8000108c4158-ffff8000108c4204: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bb6b0)
Location: drivers/iommu/iommu.c:846
Inline: False
```
**Symbols:**

```
c09bb6b0-c09bb724: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c000000000969df0)
Location: drivers/iommu/iommu.c:846
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh.c:eeh_iommu_group_to_pe
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
**Symbols:**

```
c000000000969df0-c000000000969f0c: iommu_group_for_each_dev (STB_GLOBAL)
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
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169e4c0)
Location: drivers/iommu/iommu.c:846
Inline: False
```
**Symbols:**

```
ffffffff8169e4c0-ffffffff8169e534: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167beb0)
Location: drivers/iommu/iommu.c:846
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff8167beb0-ffffffff8167bf24: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cc730)
Location: drivers/iommu/iommu.c:846
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff816cc730-ffffffff816cc7a4: iommu_group_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_group_for_each_dev(struct iommu_group *group, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e6c10)
Location: drivers/iommu/iommu.c:846
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_add_container_user
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff816e6c10-ffffffff816e6c84: iommu_group_for_each_dev (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
