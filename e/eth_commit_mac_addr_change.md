# Function: <code>eth_commit_mac_addr_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8173fdf0)
Location: net/ethernet/eth.c:284
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:virtnet_set_mac_address
```
**Symbols:**

```
ffffffff8173fdf0-ffffffff8173fe0f: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817acb30)
Location: net/ethernet/eth.c:285
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:virtnet_set_mac_address
```
**Symbols:**

```
ffffffff817acb30-ffffffff817acb4f: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817dc120)
Location: net/ethernet/eth.c:286
Inline: True
```
**Symbols:**

```
ffffffff817dc120-ffffffff817dc13f: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817fb720)
Location: net/ethernet/eth.c:286
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffff817fb720-ffffffff817fb73f: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818790d0)
Location: net/ethernet/eth.c:286
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffff818790d0-ffffffff818790ef: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818caac0)
Location: net/ethernet/eth.c:286
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffff818caac0-ffffffff818caadf: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818f5b90)
Location: net/ethernet/eth.c:289
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffff818f5b90-ffffffff818f5baf: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81955250)
Location: net/ethernet/eth.c:303
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffff81955250-ffffffff8195526f: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8198b6f0)
Location: net/ethernet/eth.c:308
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffff8198b6f0-ffffffff8198b70f: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81a63aaf)
Location: net/ethernet/eth.c:308
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffff81a633f0-ffffffff81a6340f: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81a6bc0f)
Location: net/ethernet/eth.c:308
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffff81a6b540-ffffffff81a6b55f: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81a5439f)
Location: net/ethernet/eth.c:309
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffff81a53c60-ffffffff81a53c7f: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81b0d08f)
Location: net/ethernet/eth.c:303
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffff81b0c970-ffffffff81b0c98f: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81c93480)
Location: net/ethernet/eth.c:304
Inline: True
```
**Symbols:**

```
ffffffff81c93480-ffffffff81c934a7: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81e4e950)
Location: net/ethernet/eth.c:304
Inline: True
```
**Symbols:**

```
ffffffff81e4e950-ffffffff81e4e977: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81ea9ff0)
Location: net/ethernet/eth.c:304
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:virtnet_set_mac_address
```
**Symbols:**

```
ffffffff81ea9ff0-ffffffff81eaa017: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81f6caa0)
Location: net/ethernet/eth.c:304
Inline: True
Direct callers:
  - drivers/net/virtio_net.c:virtnet_set_mac_address
```
**Symbols:**

```
ffffffff81f6caa0-ffffffff81f6cac7: eth_commit_mac_addr_change (STB_GLOBAL)
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
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffff800010c365e8)
Location: net/ethernet/eth.c:308
Inline: False
Direct callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_set_mac_address
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffff800010c365e8-ffff800010c36624: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (c0d49018)
Location: net/ethernet/eth.c:308
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
c0d49018-c0d49044: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (c000000000d2e670)
Location: net/ethernet/eth.c:308
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
c000000000d2e670-c000000000d2e690: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffe0007a806a)
Location: net/ethernet/eth.c:308
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffe0007a7fc2-ffffffe0007a801c: eth_commit_mac_addr_change (STB_GLOBAL)
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
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8192b560)
Location: net/ethernet/eth.c:308
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffff8192b560-ffffffff8192b57f: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818e5310)
Location: net/ethernet/eth.c:308
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffff818e5310-ffffffff818e532f: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8197c6f0)
Location: net/ethernet/eth.c:308
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffff8197c6f0-ffffffff8197c70f: eth_commit_mac_addr_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void eth_commit_mac_addr_change(struct net_device *dev, void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8199ec40)
Location: net/ethernet/eth.c:308
Inline: False
Direct callers:
  - net/ethernet/eth.c:eth_mac_addr
```
**Symbols:**

```
ffffffff8199ec40-ffffffff8199ec5f: eth_commit_mac_addr_change (STB_GLOBAL)
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
