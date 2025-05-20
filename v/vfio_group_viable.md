# Function: <code>vfio_group_viable</code>

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
In drivers/vfio/vfio.c (ffffffff817d2420)
Location: drivers/vfio/vfio.c:1426
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189d1d5)
Location: drivers/vfio/vfio.c:1430
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818abe05)
Location: drivers/vfio/vfio.c:1431
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_add_container_user
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
In drivers/vfio/vfio.c (ffffffff8188ed85)
Location: drivers/vfio/vfio.c:1330
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_add_container_user
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
In drivers/vfio/vfio.c (ffffffff81922405)
Location: drivers/vfio/vfio.c:1416
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_group_add_container_user
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aaf844)
Location: drivers/vfio/vfio.c:1426
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_add_container_user
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
In drivers/vfio/vfio.c (ffffffff8177c4d0)
Location: drivers/vfio/vfio.c:1426
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_add_container_user
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
In drivers/vfio/vfio.c (ffffffff817c72a0)
Location: drivers/vfio/vfio.c:1426
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_add_container_user
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
In drivers/vfio/vfio.c (ffffffff817e1540)
Location: drivers/vfio/vfio.c:1426
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
</details>
</li>
</ul>

## Differences
