# Function: <code>netdev_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81719c40)
Location: net/core/dev.c:7582
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
**Symbols:**

```
ffffffff81719c40-ffffffff81719cb4: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81782120)
Location: net/core/dev.c:8100
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
**Symbols:**

```
ffffffff81782120-ffffffff81782194: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817afa10)
Location: net/core/dev.c:8265
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff817afa10-ffffffff817afa84: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ce2c0)
Location: net/core/dev.c:8466
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff817ce2c0-ffffffff817ce332: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81847b40)
Location: net/core/dev.c:8649
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_choose_active_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff81847b40-ffffffff81847bb2: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81890910)
Location: net/core/dev.c:8900
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff81890910-ffffffff81890984: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b1c20)
Location: net/core/dev.c:9533
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_frame
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffffffff818b1c20-ffffffff818b1c94: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81906dc1)
Location: net/core/dev.c:9638
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffffffff81906dc1-ffffffff81906e35: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819394a6)
Location: net/core/dev.c:9989
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffffffff819394a6-ffffffff8193951a: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0e9a1)
Location: net/core/dev.c:10449
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffffffff81a0e9a1-ffffffff81a0ea15: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c30c95)
Location: net/core/dev.c:11158
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffffffff81c30c95-ffffffff81c30d09: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c22f9b)
Location: net/core/dev.c:11436
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffffffff81c22f9b-ffffffff81c2300f: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81d35a60)
Location: net/core/dev.c:11443
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffffffff81d35a60-ffffffff81d35ad4: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81f02096)
Location: net/core/dev.c:11225
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:netif_napi_add_weight
```
**Symbols:**

```
ffffffff81f02096-ffffffff81f02137: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc3700)
Location: net/core/dev.c:11229
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:netif_napi_add_weight
```
**Symbols:**

```
ffffffff81dc3700-ffffffff81dc3791: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e32ba0)
Location: net/core/dev.c:11246
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:netif_napi_add_weight
```
**Symbols:**

```
ffffffff81e32ba0-ffffffff81e32c31: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef0fd0)
Location: net/core/dev.c:11474
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:netif_napi_add_weight
```
**Symbols:**

```
ffffffff81ef0fd0-ffffffff81ef1061: netdev_printk (STB_GLOBAL)
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
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd8530)
Location: net/core/dev.c:9989
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffff800010bd8530-ffff800010bd85c4: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf2e70)
Location: net/core/dev.c:9989
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
c0cf2e70-c0cf2ee4: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb7f70)
Location: net/core/dev.c:9989
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
c000000000cb7f70-c000000000cb7ff8: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007612f2)
Location: net/core/dev.c:9989
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffffffe0007612f2-ffffffe000761350: netdev_printk (STB_GLOBAL)
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
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d9476)
Location: net/core/dev.c:9989
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffffffff818d9476-ffffffff818d94ea: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818932b6)
Location: net/core/dev.c:9989
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffffffff818932b6-ffffffff8189332a: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192a4a6)
Location: net/core/dev.c:9989
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffffffff8192a4a6-ffffffff8192a51a: netdev_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netdev_printk(const char *level, const struct net_device *dev, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8194bb9e)
Location: net/core/dev.c:9989
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_mp_reconstruct
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
  - net/core/dev.c:netif_napi_add
```
**Symbols:**

```
ffffffff8194bb9e-ffffffff8194bc12: netdev_printk (STB_GLOBAL)
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
