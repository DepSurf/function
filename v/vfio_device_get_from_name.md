# Function: <code>vfio_device_get_from_name</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d22d6)
Location: drivers/vfio/vfio.c:875
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vfio_device *vfio_device_get_from_name(struct vfio_group *group, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189cbd0)
Location: drivers/vfio/vfio.c:878
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
```
**Symbols:**

```
ffffffff8189cbd0-ffffffff8189ccdb: vfio_device_get_from_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vfio_device *vfio_device_get_from_name(struct vfio_group *group, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818ab800)
Location: drivers/vfio/vfio.c:879
Inline: False
Direct callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
```
**Symbols:**

```
ffffffff818ab800-ffffffff818ab90b: vfio_device_get_from_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188d8af)
Location: drivers/vfio/vfio.c:824
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81920ef9)
Location: drivers/vfio/vfio.c:910
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
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
In drivers/vfio/vfio.c (ffffffff81a779bc)
Location: drivers/vfio/vfio.c:630
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aaf5b4)
Location: drivers/vfio/vfio.c:875
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
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
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177c386)
Location: drivers/vfio/vfio.c:875
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c7156)
Location: drivers/vfio/vfio.c:875
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817e13f6)
Location: drivers/vfio/vfio.c:875
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
