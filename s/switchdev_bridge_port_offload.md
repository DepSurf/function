# Function: <code>switchdev_bridge_port_offload</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int switchdev_bridge_port_offload(struct net_device *brport_dev, struct net_device *dev, const void *ctx, struct notifier_block *atomic_nb, struct notifier_block *blocking_nb, bool tx_fwd_offload, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (0)
Location: net/switchdev/switchdev.c:813
Inline: False
```
**Symbols:**

```
ffffffff81d42303-ffffffff81d42318: switchdev_bridge_port_offload.cold (STB_LOCAL)
ffffffff81c698b0-ffffffff81c69999: switchdev_bridge_port_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int switchdev_bridge_port_offload(struct net_device *brport_dev, struct net_device *dev, const void *ctx, struct notifier_block *atomic_nb, struct notifier_block *blocking_nb, bool tx_fwd_offload, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (0)
Location: net/switchdev/switchdev.c:818
Inline: False
```
**Symbols:**

```
ffffffff81f0ec72-ffffffff81f0ec87: switchdev_bridge_port_offload.cold (STB_LOCAL)
ffffffff81e0c9a0-ffffffff81e0caa1: switchdev_bridge_port_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int switchdev_bridge_port_offload(struct net_device *brport_dev, struct net_device *dev, const void *ctx, struct notifier_block *atomic_nb, struct notifier_block *blocking_nb, bool tx_fwd_offload, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (0)
Location: net/switchdev/switchdev.c:818
Inline: False
```
**Symbols:**

```
ffffffff820b5804-ffffffff820b5819: switchdev_bridge_port_offload.cold (STB_LOCAL)
ffffffff81fe2b40-ffffffff81fe2c41: switchdev_bridge_port_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int switchdev_bridge_port_offload(struct net_device *brport_dev, struct net_device *dev, const void *ctx, struct notifier_block *atomic_nb, struct notifier_block *blocking_nb, bool tx_fwd_offload, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (0)
Location: net/switchdev/switchdev.c:818
Inline: False
```
**Symbols:**

```
ffffffff82136d8d-ffffffff82136da2: switchdev_bridge_port_offload.cold (STB_LOCAL)
ffffffff8205ee60-ffffffff8205ef61: switchdev_bridge_port_offload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int switchdev_bridge_port_offload(struct net_device *brport_dev, struct net_device *dev, const void *ctx, struct notifier_block *atomic_nb, struct notifier_block *blocking_nb, bool tx_fwd_offload, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/switchdev/switchdev.c (0)
Location: net/switchdev/switchdev.c:891
Inline: False
```
**Symbols:**

```
ffffffff82218bda-ffffffff82218bef: switchdev_bridge_port_offload.cold (STB_LOCAL)
ffffffff82131ca0-ffffffff82131da1: switchdev_bridge_port_offload (STB_GLOBAL)
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
