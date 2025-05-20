# Function: <code>ethtool_cmd_speed_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff815e991b)
Location: include/uapi/linux/ethtool.h:113
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_gset
```
```
In drivers/net/tun.c (ffffffff815edb66)
Location: include/uapi/linux/ethtool.h:113
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8164806b)
Location: include/uapi/linux/ethtool.h:119
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_gset
```
```
In drivers/net/tun.c (ffffffff8164c936)
Location: include/uapi/linux/ethtool.h:119
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_settings
```
```
In drivers/net/virtio_net.c (ffffffff8165074f)
Location: include/uapi/linux/ethtool.h:119
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_get_settings
  - drivers/net/virtio_net.c:virtnet_set_settings
```
```
In net/core/ethtool.c (ffffffff81788c04)
Location: include/uapi/linux/ethtool.h:119
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8167918b)
Location: include/uapi/linux/ethtool.h:119
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_gset
```
```
In drivers/net/tun.c (ffffffff8167e666)
Location: include/uapi/linux/ethtool.h:119
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_settings
```
```
In net/core/ethtool.c (ffffffff817b64b4)
Location: include/uapi/linux/ethtool.h:119
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817d5116)
Location: include/uapi/linux/ethtool.h:119
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8184f68b)
Location: include/uapi/linux/ethtool.h:120
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81899ccc)
Location: include/uapi/linux/ethtool.h:120
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818bc7f3)
Location: include/uapi/linux/ethtool.h:116
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8190914b)
Location: include/uapi/linux/ethtool.h:116
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8193b88b)
Location: include/uapi/linux/ethtool.h:116
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
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
In net/ethtool/ioctl.c (ffffffff81a817eb)
Location: include/uapi/linux/ethtool.h:116
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
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
In net/ethtool/ioctl.c (ffffffff81a8b3db)
Location: include/uapi/linux/ethtool.h:116
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
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
In net/ethtool/ioctl.c (ffffffff81a74896)
Location: include/uapi/linux/ethtool.h:125
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
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
In net/ethtool/ioctl.c (ffffffff81b2eae6)
Location: include/uapi/linux/ethtool.h:125
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
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
In net/ethtool/ioctl.c (ffffffff81cb9939)
Location: include/uapi/linux/ethtool.h:125
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
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
In net/ethtool/ioctl.c (ffffffff81e77680)
Location: include/uapi/linux/ethtool.h:125
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81ed3810)
Location: include/uapi/linux/ethtool.h:125
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81f97120)
Location: include/uapi/linux/ethtool.h:125
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_settings
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/mii.c (ffff8000109cef1c)
Location: include/uapi/linux/ethtool.h:116
Inline: True
Inline callers:
  - drivers/net/mii.c:mii_ethtool_gset
  - drivers/net/mii.c:mii_ethtool_gset
  - drivers/net/mii.c:mii_ethtool_gset
  - drivers/net/mii.c:mii_ethtool_gset
```
```
In net/core/ethtool.c (ffff800010bda5f8)
Location: include/uapi/linux/ethtool.h:116
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c0cf4978)
Location: include/uapi/linux/ethtool.h:116
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c000000000cb9f68)
Location: include/uapi/linux/ethtool.h:116
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffe000761db6)
Location: include/uapi/linux/ethtool.h:116
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818db85b)
Location: include/uapi/linux/ethtool.h:116
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8189569b)
Location: include/uapi/linux/ethtool.h:116
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
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
In net/core/ethtool.c (ffffffff8192c88b)
Location: include/uapi/linux/ethtool.h:116
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
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
In net/core/ethtool.c (ffffffff8194df5b)
Location: include/uapi/linux/ethtool.h:116
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_settings
```
</details>
</li>
</ul>

## Differences
