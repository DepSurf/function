# Function: <code>ethtool_virtdev_set_link_ksettings</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ethtool_virtdev_set_link_ksettings(struct net_device *dev, const struct ethtool_link_ksettings *cmd, u32 *dev_speed, u8 *dev_duplex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a840d0)
Location: net/ethtool/ioctl.c:606
Inline: False
```
**Symbols:**

```
ffffffff81a840d0-ffffffff81a84130: ethtool_virtdev_set_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethtool_virtdev_set_link_ksettings(struct net_device *dev, const struct ethtool_link_ksettings *cmd, u32 *dev_speed, u8 *dev_duplex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a8dc00)
Location: net/ethtool/ioctl.c:610
Inline: False
```
**Symbols:**

```
ffffffff81a8dc00-ffffffff81a8dc60: ethtool_virtdev_set_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethtool_virtdev_set_link_ksettings(struct net_device *dev, const struct ethtool_link_ksettings *cmd, u32 *dev_speed, u8 *dev_duplex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a76ac0)
Location: net/ethtool/ioctl.c:610
Inline: False
```
**Symbols:**

```
ffffffff81a76ac0-ffffffff81a76b20: ethtool_virtdev_set_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ethtool_virtdev_set_link_ksettings(struct net_device *dev, const struct ethtool_link_ksettings *cmd, u32 *dev_speed, u8 *dev_duplex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81b30c90)
Location: net/ethtool/ioctl.c:612
Inline: False
```
**Symbols:**

```
ffffffff81b30c90-ffffffff81b30cf0: ethtool_virtdev_set_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethtool_virtdev_set_link_ksettings(struct net_device *dev, const struct ethtool_link_ksettings *cmd, u32 *dev_speed, u8 *dev_duplex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81cbbba0)
Location: net/ethtool/ioctl.c:636
Inline: False
```
**Symbols:**

```
ffffffff81cbbba0-ffffffff81cbbc19: ethtool_virtdev_set_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethtool_virtdev_set_link_ksettings(struct net_device *dev, const struct ethtool_link_ksettings *cmd, u32 *dev_speed, u8 *dev_duplex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81e7a170)
Location: net/ethtool/ioctl.c:617
Inline: False
```
**Symbols:**

```
ffffffff81e7a170-ffffffff81e7a1e9: ethtool_virtdev_set_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethtool_virtdev_set_link_ksettings(struct net_device *dev, const struct ethtool_link_ksettings *cmd, u32 *dev_speed, u8 *dev_duplex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81ed6470)
Location: net/ethtool/ioctl.c:618
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_set_link_ksettings
```
**Symbols:**

```
ffffffff81ed6470-ffffffff81ed64e9: ethtool_virtdev_set_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethtool_virtdev_set_link_ksettings(struct net_device *dev, const struct ethtool_link_ksettings *cmd, u32 *dev_speed, u8 *dev_duplex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81f99ff0)
Location: net/ethtool/ioctl.c:621
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_set_link_ksettings
```
**Symbols:**

```
ffffffff81f99ff0-ffffffff81f9a069: ethtool_virtdev_set_link_ksettings (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
