# Function: <code>register_netdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171ecf0)
Location: net/core/dev.c:6800
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8171ecf0-ffffffff8171ed16: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81787610)
Location: net/core/dev.c:7309
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81787610-ffffffff81787636: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b4bd0)
Location: net/core/dev.c:7479
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff817b4bd0-ffffffff817b4bf6: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d3770)
Location: net/core/dev.c:7666
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff817d3770-ffffffff817d3796: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184dc40)
Location: net/core/dev.c:7845
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8184dc40-ffffffff8184dc66: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81898aa0)
Location: net/core/dev.c:8111
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff81898aa0-ffffffff81898ad1: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818baf00)
Location: net/core/dev.c:8741
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff818baf00-ffffffff818baf31: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81906870)
Location: net/core/dev.c:8846
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff81906870-ffffffff819068a6: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81938f60)
Location: net/core/dev.c:9184
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff81938f60-ffffffff81938f96: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0e110)
Location: net/core/dev.c:9640
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/xen-netfront.c:xennet_connect
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff81a0e110-ffffffff81a0e148: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0ef20)
Location: net/core/dev.c:10264
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/xen-netfront.c:xennet_connect
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff81a0ef20-ffffffff81a0ef58: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f5c60)
Location: net/core/dev.c:10428
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/xen-netfront.c:xennet_connect
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff819f5c60-ffffffff819f5c98: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa7660)
Location: net/core/dev.c:10435
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/xen-netfront.c:xennet_connect
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff81aa7660-ffffffff81aa7698: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1f580)
Location: net/core/dev.c:10172
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/xen-netfront.c:xennet_connect
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff81c1f580-ffffffff81c1f5ba: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dd1a00)
Location: net/core/dev.c:10161
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/xen-netfront.c:xennet_connect
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff81dd1a00-ffffffff81dd1a3a: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e425e0)
Location: net/core/dev.c:10173
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/net_failover.c:net_failover_create
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff81e425e0-ffffffff81e4261a: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81f01210)
Location: net/core/dev.c:10365
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/net_failover.c:net_failover_create
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff81f01210-ffffffff81f0124a: register_netdev (STB_GLOBAL)
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
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd7848)
Location: net/core/dev.c:9184
Inline: False
Direct callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffff800010bd7848-ffff800010bd7890: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf2908)
Location: net/core/dev.c:9184
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
```
**Symbols:**

```
c0cf2908-c0cf294c: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb7830)
Location: net/core/dev.c:9184
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_net_init
```
**Symbols:**

```
c000000000cb7830-c000000000cb7898: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000760e38)
Location: net/core/dev.c:9184
Inline: False
```
**Symbols:**

```
ffffffe000760e38-ffffffe000760e7c: register_netdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d8f30)
Location: net/core/dev.c:9184
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff818d8f30-ffffffff818d8f66: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81892d70)
Location: net/core/dev.c:9184
Inline: False
```
**Symbols:**

```
ffffffff81892d70-ffffffff81892da6: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81929f60)
Location: net/core/dev.c:9184
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff81929f60-ffffffff81929f96: register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8194b630)
Location: net/core/dev.c:9184
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff8194b630-ffffffff8194b666: register_netdev (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
