# Function: <code>netif_is_rxfh_configured</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (0)
Location: include/linux/netdevice.h:3938
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (0)
Location: include/linux/netdevice.h:4225
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (0)
Location: include/linux/netdevice.h:4179
Inline: True
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
In net/core/ethtool.c (0)
Location: include/linux/netdevice.h:4237
Inline: True
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
In net/core/ethtool.c (0)
Location: include/linux/netdevice.h:4271
Inline: True
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
In net/core/ethtool.c (ffffffff8189ab0f)
Location: include/linux/netdevice.h:4368
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
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
In net/core/ethtool.c (ffffffff818bd310)
Location: include/linux/netdevice.h:4610
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
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
In net/core/ethtool.c (ffffffff8190a4e9)
Location: include/linux/netdevice.h:4636
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
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
In net/core/ethtool.c (ffffffff8193cae9)
Location: include/linux/netdevice.h:4649
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a806a0)
Location: include/linux/netdevice.h:4842
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
```
```
In net/ethtool/channels.c (ffffffff81a8b307)
Location: include/linux/netdevice.h:4842
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a8a710)
Location: include/linux/netdevice.h:5043
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
```
```
In net/ethtool/channels.c (ffffffff81a9493b)
Location: include/linux/netdevice.h:5043
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a73c7e)
Location: include/linux/netdevice.h:5174
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
```
```
In net/ethtool/channels.c (ffffffff81a7e34a)
Location: include/linux/netdevice.h:5174
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81b2d7ee)
Location: include/linux/netdevice.h:5222
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
```
```
In net/ethtool/channels.c (ffffffff81b38480)
Location: include/linux/netdevice.h:5222
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81cb7a0f)
Location: include/linux/netdevice.h:5042
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
```
```
In net/ethtool/channels.c (ffffffff81cc41db)
Location: include/linux/netdevice.h:5042
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81e759fa)
Location: include/linux/netdevice.h:5086
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
```
```
In net/ethtool/channels.c (ffffffff81e835eb)
Location: include/linux/netdevice.h:5086
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
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
In net/ethtool/ioctl.c (ffffffff81ed1b5a)
Location: include/linux/netdevice.h:5130
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
```
```
In net/ethtool/channels.c (ffffffff81edfd52)
Location: include/linux/netdevice.h:5130
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
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
In net/ethtool/ioctl.c (ffffffff81f9567a)
Location: include/linux/netdevice.h:5211
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_set_channels
```
```
In net/ethtool/channels.c (ffffffff81fa3bf2)
Location: include/linux/netdevice.h:5211
Inline: True
Inline callers:
  - net/ethtool/channels.c:ethnl_set_channels
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffff800010bdb248)
Location: include/linux/netdevice.h:4649
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
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
In net/core/ethtool.c (c0cf6954)
Location: include/linux/netdevice.h:4649
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
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
In net/core/ethtool.c (c000000000cbc1d8)
Location: include/linux/netdevice.h:4649
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
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
In net/core/ethtool.c (ffffffe0007633a6)
Location: include/linux/netdevice.h:4649
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
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
In net/core/ethtool.c (ffffffff818dcab9)
Location: include/linux/netdevice.h:4649
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
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
In net/core/ethtool.c (ffffffff818968f9)
Location: include/linux/netdevice.h:4649
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
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
In net/core/ethtool.c (ffffffff8192dae9)
Location: include/linux/netdevice.h:4649
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
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
In net/core/ethtool.c (ffffffff8194f1b9)
Location: include/linux/netdevice.h:4649
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_channels
```
</details>
</li>
</ul>

## Differences
