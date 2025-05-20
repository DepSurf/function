# Function: <code>unregister_netdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81717990)
Location: net/core/dev.c:7287
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:xennet_remove
```
**Symbols:**

```
ffffffff81717990-ffffffff817179b4: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177f9b0)
Location: net/core/dev.c:7805
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:xennet_remove
```
**Symbols:**

```
ffffffff8177f9b0-ffffffff8177f9d4: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817acbe0)
Location: net/core/dev.c:7976
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff817acbe0-ffffffff817acc04: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cb360)
Location: net/core/dev.c:8170
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
```
**Symbols:**

```
ffffffff817cb360-ffffffff817cb384: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81844bf0)
Location: net/core/dev.c:8349
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
```
**Symbols:**

```
ffffffff81844bf0-ffffffff81844c14: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818982d0)
Location: net/core/dev.c:8599
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
```
**Symbols:**

```
ffffffff818982d0-ffffffff818982f4: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ba730)
Location: net/core/dev.c:9229
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
```
**Symbols:**

```
ffffffff818ba730-ffffffff818ba754: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fcbf0)
Location: net/core/dev.c:9334
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
```
**Symbols:**

```
ffffffff818fcbf0-ffffffff818fcc16: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192f200)
Location: net/core/dev.c:9678
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
```
**Symbols:**

```
ffffffff8192f200-ffffffff8192f226: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0e320)
Location: net/core/dev.c:10133
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - net/devres.c:devm_netdev_release
```
**Symbols:**

```
ffffffff81a0e320-ffffffff81a0e348: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a05e90)
Location: net/core/dev.c:10842
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - net/devres.c:devm_unregister_netdev
```
**Symbols:**

```
ffffffff81a05e90-ffffffff81a05eb8: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ec7c0)
Location: net/core/dev.c:11110
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - net/devres.c:devm_unregister_netdev
```
**Symbols:**

```
ffffffff819ec7c0-ffffffff819ec7e8: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9d6f0)
Location: net/core/dev.c:11117
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - net/devres.c:devm_unregister_netdev
```
**Symbols:**

```
ffffffff81a9d6f0-ffffffff81a9d718: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c16f40)
Location: net/core/dev.c:10900
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - net/devres.c:devm_unregister_netdev
  - net/mctp/device.c:mctp_unregister_netdev
```
**Symbols:**

```
ffffffff81c16f40-ffffffff81c16f6f: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dd1a50)
Location: net/core/dev.c:10904
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
  - net/devres.c:devm_unregister_netdev
  - net/mctp/device.c:mctp_unregister_netdev
```
**Symbols:**

```
ffffffff81dd1a50-ffffffff81dd1a7f: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e42630)
Location: net/core/dev.c:10921
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/net_failover.c:net_failover_create
  - net/devres.c:devm_unregister_netdev
  - net/mctp/device.c:mctp_unregister_netdev
```
**Symbols:**

```
ffffffff81e42630-ffffffff81e4265f: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81f01260)
Location: net/core/dev.c:11132
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/net_failover.c:net_failover_create
  - net/devres.c:devm_unregister_netdev
  - net/mctp/device.c:mctp_unregister_netdev
```
**Symbols:**

```
ffffffff81f01260-ffffffff81f0128f: unregister_netdev (STB_GLOBAL)
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
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcc040)
Location: net/core/dev.c:9678
Inline: False
Direct callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_remove
  - drivers/net/xen-netfront.c:xennet_remove
```
**Symbols:**

```
ffff800010bcc040-ffff800010bcc078: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cea0cc)
Location: net/core/dev.c:9678
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/ti/cpsw.c:cpsw_remove
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
```
**Symbols:**

```
c0cea0cc-c0cea0fc: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca8ab0)
Location: net/core/dev.c:9678
Inline: False
```
**Symbols:**

```
c000000000ca8ab0-c000000000ca8afc: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007598de)
Location: net/core/dev.c:9678
Inline: False
```
**Symbols:**

```
ffffffe0007598de-ffffffe00075991a: unregister_netdev (STB_GLOBAL)
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
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cf200)
Location: net/core/dev.c:9678
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
```
**Symbols:**

```
ffffffff818cf200-ffffffff818cf226: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81889320)
Location: net/core/dev.c:9678
Inline: False
```
**Symbols:**

```
ffffffff81889320-ffffffff81889346: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81920200)
Location: net/core/dev.c:9678
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
```
**Symbols:**

```
ffffffff81920200-ffffffff81920226: unregister_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unregister_netdev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81941f60)
Location: net/core/dev.c:9678
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_remove
```
**Symbols:**

```
ffffffff81941f60-ffffffff81941f86: unregister_netdev (STB_GLOBAL)
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
