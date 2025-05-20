# Function: <code>alloc_etherdev_mqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8173ff50)
Location: net/ethernet/eth.c:384
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8173ff50-ffffffff8173ff76: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817acc90)
Location: net/ethernet/eth.c:385
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff817acc90-ffffffff817accb6: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817dc2e0)
Location: net/ethernet/eth.c:388
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff817dc2e0-ffffffff817dc306: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817fb99e)
Location: net/ethernet/eth.c:388
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff817fb910-ffffffff817fb936: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8187934e)
Location: net/ethernet/eth.c:388
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff818792c0-ffffffff818792e6: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818cad48)
Location: net/ethernet/eth.c:388
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff818caca0-ffffffff818cacc6: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818f5e18)
Location: net/ethernet/eth.c:391
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff818f5d70-ffffffff818f5d96: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81955499)
Location: net/ethernet/eth.c:406
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff819553f0-ffffffff81955416: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8198b939)
Location: net/ethernet/eth.c:411
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8198b890-ffffffff8198b8b6: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81a63550)
Location: net/ethernet/eth.c:395
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/devres.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff81a63550-ffffffff81a63576: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81a6b6a0)
Location: net/ethernet/eth.c:395
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/devres.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff81a6b6a0-ffffffff81a6b6c6: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81a53dd0)
Location: net/ethernet/eth.c:396
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/devres.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff81a53dd0-ffffffff81a53df6: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81b0cae0)
Location: net/ethernet/eth.c:390
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/devres.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff81b0cae0-ffffffff81b0cb06: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81c934b0)
Location: net/ethernet/eth.c:391
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/devres.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff81c934b0-ffffffff81c934eb: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81e4e990)
Location: net/ethernet/eth.c:391
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_dev
  - net/devres.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff81e4e990-ffffffff81e4e9cb: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81eaa030)
Location: net/ethernet/eth.c:391
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/net_failover.c:net_failover_create
  - net/devres.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff81eaa030-ffffffff81eaa06b: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81f6cae0)
Location: net/ethernet/eth.c:391
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/net_failover.c:net_failover_create
  - net/devres.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff81f6cae0-ffffffff81f6cb1b: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffff800010c368d4)
Location: net/ethernet/eth.c:411
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffff800010c36800-ffff800010c36858: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (c0d49278)
Location: net/ethernet/eth.c:411
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
**Symbols:**

```
c0d491d0-c0d49210: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (c000000000d2ea24)
Location: net/ethernet/eth.c:411
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
c000000000d2e930-c000000000d2e980: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffe0007a8300)
Location: net/ethernet/eth.c:411
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffe0007a8248-ffffffe0007a8294: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8192b7a9)
Location: net/ethernet/eth.c:411
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8192b700-ffffffff8192b726: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818e5559)
Location: net/ethernet/eth.c:411
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
```
**Symbols:**

```
ffffffff818e54b0-ffffffff818e54d6: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8197c939)
Location: net/ethernet/eth.c:411
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8197c890-ffffffff8197c8b6: alloc_etherdev_mqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct net_device *alloc_etherdev_mqs(int sizeof_priv, unsigned int txqs, unsigned int rxqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8199ee89)
Location: net/ethernet/eth.c:411
Inline: True
Inline callers:
  - net/ethernet/eth.c:devm_alloc_etherdev_mqs
Direct callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8199ede0-ffffffff8199ee06: alloc_etherdev_mqs (STB_GLOBAL)
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
