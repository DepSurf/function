# Function: <code>ethtool_validate_speed</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81650b61)
Location: include/uapi/linux/ethtool.h:1481
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_settings
```
</details>
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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a840e6)
Location: include/uapi/linux/ethtool.h:1647
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_virtdev_set_link_ksettings
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
In net/ethtool/ioctl.c (ffffffff81a8dc16)
Location: include/uapi/linux/ethtool.h:1736
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_virtdev_set_link_ksettings
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
In net/ethtool/ioctl.c (ffffffff81a76ad6)
Location: include/uapi/linux/ethtool.h:1776
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_virtdev_set_link_ksettings
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
In net/ethtool/ioctl.c (ffffffff81b30ca6)
Location: include/uapi/linux/ethtool.h:1778
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_virtdev_set_link_ksettings
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
In net/ethtool/ioctl.c (ffffffff81cbbbb6)
Location: include/uapi/linux/ethtool.h:1809
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_virtdev_set_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81e7a186)
Location: include/uapi/linux/ethtool.h:1860
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_virtdev_set_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81c4ca21)
Location: include/uapi/linux/ethtool.h:1906
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81ed6486)
Location: include/uapi/linux/ethtool.h:1906
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_virtdev_set_link_ksettings
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81d022a1)
Location: include/uapi/linux/ethtool.h:1909
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81f9a006)
Location: include/uapi/linux/ethtool.h:1909
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_virtdev_set_link_ksettings
```
</details>
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
