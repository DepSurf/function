# Function: <code>ethtool_validate_duplex</code>

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
In drivers/net/virtio_net.c (ffffffff81650b70)
Location: include/uapi/linux/ethtool.h:1491
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
In net/ethtool/ioctl.c (ffffffff81a840fa)
Location: include/uapi/linux/ethtool.h:1657
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
In net/ethtool/ioctl.c (ffffffff81a8dc2a)
Location: include/uapi/linux/ethtool.h:1746
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
In net/ethtool/ioctl.c (ffffffff81a76aea)
Location: include/uapi/linux/ethtool.h:1786
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
In net/ethtool/ioctl.c (ffffffff81b30cba)
Location: include/uapi/linux/ethtool.h:1788
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
In net/ethtool/ioctl.c (ffffffff81cbbbc7)
Location: include/uapi/linux/ethtool.h:1819
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
In net/ethtool/ioctl.c (ffffffff81e7a197)
Location: include/uapi/linux/ethtool.h:1870
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
In drivers/net/virtio_net.c (ffffffff81c4ca62)
Location: include/uapi/linux/ethtool.h:1916
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81ed6497)
Location: include/uapi/linux/ethtool.h:1916
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
In drivers/net/virtio_net.c (ffffffff81d022e2)
Location: include/uapi/linux/ethtool.h:1919
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81f9a017)
Location: include/uapi/linux/ethtool.h:1919
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
