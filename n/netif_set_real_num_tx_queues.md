# Function: <code>netif_set_real_num_tx_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81715a20)
Location: net/core/dev.c:2160
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_set_channels
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81715a20-ffffffff81715bc2: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177da50)
Location: net/core/dev.c:2181
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_set_channels
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8177da50-ffffffff8177dbf5: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ab270)
Location: net/core/dev.c:2313
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff817ab270-ffffffff817ab41f: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c98e0)
Location: net/core/dev.c:2347
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff817c98e0-ffffffff817c9a87: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81843ac0)
Location: net/core/dev.c:2367
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81843ac0-ffffffff81843c99: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2411
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81898ea1-ffffffff81898ee6: netif_set_real_num_tx_queues.cold.147 (STB_LOCAL)
ffffffff8188ddc0-ffffffff8188df74: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2646
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff818bb4d0-ffffffff818bb518: netif_set_real_num_tx_queues.cold.168 (STB_LOCAL)
ffffffff818b3550-ffffffff818b3705: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2656
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff819071dd-ffffffff81907229: netif_set_real_num_tx_queues.cold (STB_LOCAL)
ffffffff818fc420-ffffffff818fc5d5: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2574
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff819398af-ffffffff819398fb: netif_set_real_num_tx_queues.cold (STB_LOCAL)
ffffffff8192ea00-ffffffff8192ebb5: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2934
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff81a0ef6c-ffffffff81a0efb8: netif_set_real_num_tx_queues.cold (STB_LOCAL)
ffffffff81a054f0-ffffffff81a056ce: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2959
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff81c3127c-ffffffff81c312c8: netif_set_real_num_tx_queues.cold (STB_LOCAL)
ffffffff81a06ac0-ffffffff81a06c9e: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3027
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff81c234cd-ffffffff81c23516: netif_set_real_num_tx_queues.cold (STB_LOCAL)
ffffffff819ecb00-ffffffff819eccd4: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2902
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:netif_set_real_num_queues
  - net/core/dev.c:netif_set_real_num_queues
```
**Symbols:**

```
ffffffff81d361f8-ffffffff81d36256: netif_set_real_num_tx_queues.cold (STB_LOCAL)
ffffffff81a9db40-ffffffff81a9dd58: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2879
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:netif_set_real_num_queues
  - net/core/dev.c:netif_set_real_num_queues
```
**Symbols:**

```
ffffffff81f02a3e-ffffffff81f02a9e: netif_set_real_num_tx_queues.cold (STB_LOCAL)
ffffffff81c16f70-ffffffff81c17172: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2864
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - net/core/dev.c:netif_set_real_num_queues
  - net/core/dev.c:netif_set_real_num_queues
```
**Symbols:**

```
ffffffff820ab5ad-ffffffff820ab5c2: netif_set_real_num_tx_queues.cold (STB_LOCAL)
ffffffff81dc7f20-ffffffff81dc815f: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2892
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_set_channels
  - net/core/dev.c:netif_set_real_num_queues
  - net/core/dev.c:netif_set_real_num_queues
```
**Symbols:**

```
ffffffff8212cbd2-ffffffff8212cbe7: netif_set_real_num_tx_queues.cold (STB_LOCAL)
ffffffff81e36d20-ffffffff81e36f6c: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2895
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_set_channels
  - net/core/dev.c:netif_set_real_num_queues
  - net/core/dev.c:netif_set_real_num_queues
```
**Symbols:**

```
ffffffff8220e910-ffffffff8220e925: netif_set_real_num_tx_queues.cold (STB_LOCAL)
ffffffff81ef4d70-ffffffff81ef4f98: netif_set_real_num_tx_queues (STB_GLOBAL)
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
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcea28)
Location: net/core/dev.c:2574
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffff800010bcea28-ffff800010bcec74: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce9794)
Location: net/core/dev.c:2574
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_set_channels_common
```
**Symbols:**

```
c0ce9794-c0ce9990: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca7ef0)
Location: net/core/dev.c:2574
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
```
**Symbols:**

```
c000000000ca7ef0-c000000000ca81a4: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007591a4)
Location: net/core/dev.c:2574
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
```
**Symbols:**

```
ffffffe0007591a4-ffffffe000759362: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2574
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff818d987f-ffffffff818d98cb: netif_set_real_num_tx_queues.cold (STB_LOCAL)
ffffffff818cea00-ffffffff818cebb5: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2574
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
```
**Symbols:**

```
ffffffff818936bf-ffffffff8189370b: netif_set_real_num_tx_queues.cold (STB_LOCAL)
ffffffff81888b20-ffffffff81888cd5: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2574
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff8192a8af-ffffffff8192a8fb: netif_set_real_num_tx_queues.cold (STB_LOCAL)
ffffffff8191fa00-ffffffff8191fbb5: netif_set_real_num_tx_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int netif_set_real_num_tx_queues(struct net_device *dev, unsigned int txq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2574
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff8194bff9-ffffffff8194c045: netif_set_real_num_tx_queues.cold (STB_LOCAL)
ffffffff81941760-ffffffff81941915: netif_set_real_num_tx_queues (STB_GLOBAL)
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
