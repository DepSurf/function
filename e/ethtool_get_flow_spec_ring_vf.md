# Function: <code>ethtool_get_flow_spec_ring_vf</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81908c1e)
Location: include/uapi/linux/ethtool.h:912
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
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
In net/core/ethtool.c (ffffffff8193b364)
Location: include/uapi/linux/ethtool.h:934
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
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
In net/ethtool/ioctl.c (ffffffff81a8222f)
Location: include/uapi/linux/ethtool.h:949
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
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
In net/ethtool/ioctl.c (ffffffff81a8bd07)
Location: include/uapi/linux/ethtool.h:1021
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
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
In net/ethtool/ioctl.c (ffffffff81a74ed1)
Location: include/uapi/linux/ethtool.h:1035
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
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
In net/ethtool/ioctl.c (0)
Location: include/uapi/linux/ethtool.h:1037
Inline: True
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
In net/ethtool/ioctl.c (0)
Location: include/uapi/linux/ethtool.h:1067
Inline: True
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
In net/ethtool/ioctl.c (0)
Location: include/uapi/linux/ethtool.h:1110
Inline: True
```
```
In net/ethtool/common.c (ffffffff81e7c63e)
Location: include/uapi/linux/ethtool.h:1110
Inline: True
Inline callers:
  - net/ethtool/common.c:ethtool_get_max_rxnfc_channel
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
In net/ethtool/ioctl.c (0)
Location: include/uapi/linux/ethtool.h:1153
Inline: True
```
```
In net/ethtool/common.c (0)
Location: include/uapi/linux/ethtool.h:1153
Inline: True
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
In net/ethtool/ioctl.c (0)
Location: include/uapi/linux/ethtool.h:1153
Inline: True
```
```
In net/ethtool/common.c (0)
Location: include/uapi/linux/ethtool.h:1153
Inline: True
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
In net/core/ethtool.c (ffff800010bd9560)
Location: include/uapi/linux/ethtool.h:934
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
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
In net/core/ethtool.c (c0cf3c44)
Location: include/uapi/linux/ethtool.h:934
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
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
In net/core/ethtool.c (c000000000cba81c)
Location: include/uapi/linux/ethtool.h:934
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
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
In net/core/ethtool.c (ffffffe000762968)
Location: include/uapi/linux/ethtool.h:934
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
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
In net/core/ethtool.c (ffffffff818db334)
Location: include/uapi/linux/ethtool.h:934
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
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
In net/core/ethtool.c (ffffffff81895174)
Location: include/uapi/linux/ethtool.h:934
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
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
In net/core/ethtool.c (ffffffff8192c364)
Location: include/uapi/linux/ethtool.h:934
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
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
In net/core/ethtool.c (ffffffff8194da34)
Location: include/uapi/linux/ethtool.h:934
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
</details>
</li>
</ul>

## Differences
