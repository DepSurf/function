# Function: <code>virtqueue_disable_cb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff814bf690)
Location: drivers/virtio/virtio_ring.c:543
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/net/virtio_net.c:skb_recv_done
  - drivers/net/virtio_net.c:skb_xmit_done
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:virtnet_busy_poll
  - drivers/net/virtio_net.c:virtnet_busy_poll
```
**Symbols:**

```
ffffffff814bf690-ffffffff814bf6b3: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150f570)
Location: drivers/virtio/virtio_ring.c:729
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:virtnet_busy_poll
  - drivers/net/virtio_net.c:virtnet_busy_poll
  - drivers/net/virtio_net.c:skb_recv_done
  - drivers/net/virtio_net.c:skb_xmit_done
```
**Symbols:**

```
ffffffff8150f570-ffffffff8150f593: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153b710)
Location: drivers/virtio/virtio_ring.c:729
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff8153b710-ffffffff8153b739: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154f050)
Location: drivers/virtio/virtio_ring.c:772
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff8154f050-ffffffff8154f079: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b27f0)
Location: drivers/virtio/virtio_ring.c:771
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff815b27f0-ffffffff815b2819: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815eac20)
Location: drivers/virtio/virtio_ring.c:770
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff815eac20-ffffffff815eac49: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816050c0)
Location: drivers/virtio/virtio_ring.c:1913
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff816050c0-ffffffff8160510c: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816382c0)
Location: drivers/virtio/virtio_ring.c:1919
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff816382c0-ffffffff8163830c: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165a0b0)
Location: drivers/virtio/virtio_ring.c:1918
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff8165a0b0-ffffffff8165a0fc: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81709e40)
Location: drivers/virtio/virtio_ring.c:1918
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff81709e40-ffffffff81709e8c: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81727040)
Location: drivers/virtio/virtio_ring.c:1918
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff81727040-ffffffff8172708c: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b040)
Location: drivers/virtio/virtio_ring.c:1920
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff8170b040-ffffffff8170b08c: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817868b9)
Location: drivers/virtio/virtio_ring.c:2018
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff81cf4616-ffffffff81cf4655: virtqueue_disable_cb.cold (STB_LOCAL)
ffffffff81786880-ffffffff81786918: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818bd850)
Location: drivers/virtio/virtio_ring.c:2022
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff81ebc735-ffffffff81ebc774: virtqueue_disable_cb.cold (STB_LOCAL)
ffffffff818bd810-ffffffff818bd8b6: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0cb83)
Location: drivers/virtio/virtio_ring.c:2308
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff82093c92-ffffffff82093cd1: virtqueue_disable_cb.cold (STB_LOCAL)
ffffffff81a0cb40-ffffffff81a0cbf5: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2345
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/scsi/virtio_scsi.c:virtscsi_event_done
  - drivers/scsi/virtio_scsi.c:virtscsi_ctrl_done
  - drivers/scsi/virtio_scsi.c:virtscsi_req_done
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:refill_work
  - drivers/net/virtio_net.c:skb_recv_done
  - drivers/net/virtio_net.c:skb_xmit_done
  - drivers/net/virtio_net.c:skb_xmit_done
```
**Symbols:**

```
ffffffff8211495d-ffffffff821149b1: virtqueue_disable_cb.cold (STB_LOCAL)
ffffffff81a557c0-ffffffff81a5588b: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2439
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/scsi/virtio_scsi.c:virtscsi_event_done
  - drivers/scsi/virtio_scsi.c:virtscsi_ctrl_done
  - drivers/scsi/virtio_scsi.c:virtscsi_req_done
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:refill_work
  - drivers/net/virtio_net.c:skb_recv_done
  - drivers/net/virtio_net.c:skb_xmit_done
  - drivers/net/virtio_net.c:skb_xmit_done
```
**Symbols:**

```
ffffffff821f2574-ffffffff821f25c8: virtqueue_disable_cb.cold (STB_LOCAL)
ffffffff81aa6830-ffffffff81aa68fb: virtqueue_disable_cb (STB_GLOBAL)
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
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010822008)
Location: drivers/virtio/virtio_ring.c:1918
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffff800010822008-ffff800010822074: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c093fbd8)
Location: drivers/virtio/virtio_ring.c:1918
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
c093fbd8-c093fc3c: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cc790)
Location: drivers/virtio/virtio_ring.c:1918
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
c0000000008cc790-c0000000008cc7fc: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000518c0c)
Location: drivers/virtio/virtio_ring.c:1918
Inline: True
```
**Symbols:**

```
ffffffe000518c0c-ffffffe000518c66: virtqueue_disable_cb (STB_GLOBAL)
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
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161ff50)
Location: drivers/virtio/virtio_ring.c:1918
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff8161ff50-ffffffff8161ff9c: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816144e0)
Location: drivers/virtio/virtio_ring.c:1918
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff816144e0-ffffffff8161452c: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164def0)
Location: drivers/virtio/virtio_ring.c:1918
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/scsi/virtio_scsi.c:virtscsi_vq_done
```
**Symbols:**

```
ffffffff8164def0-ffffffff8164df3c: virtqueue_disable_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void virtqueue_disable_cb(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81668580)
Location: drivers/virtio/virtio_ring.c:1918
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
```
**Symbols:**

```
ffffffff81668580-ffffffff816685cc: virtqueue_disable_cb (STB_GLOBAL)
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
