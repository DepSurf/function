# Function: <code>virtqueue_kick_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff814bf750)
Location: drivers/virtio/virtio_ring.c:353
Inline: True
Direct callers:
  - drivers/block/virtio_blk.c:virtio_queue_rq
```
**Symbols:**

```
ffffffff814bf750-ffffffff814bf799: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150fa30)
Location: drivers/virtio/virtio_ring.c:523
Inline: True
Direct callers:
  - drivers/block/virtio_blk.c:virtio_queue_rq
```
**Symbols:**

```
ffffffff8150fa30-ffffffff8150fa75: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153bef0)
Location: drivers/virtio/virtio_ring.c:523
Inline: True
```
**Symbols:**

```
ffffffff8153bef0-ffffffff8153bf35: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154f730)
Location: drivers/virtio/virtio_ring.c:552
Inline: True
```
**Symbols:**

```
ffffffff8154f730-ffffffff8154f771: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b3040)
Location: drivers/virtio/virtio_ring.c:551
Inline: True
```
**Symbols:**

```
ffffffff815b3040-ffffffff815b308f: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815eb120)
Location: drivers/virtio/virtio_ring.c:550
Inline: True
```
**Symbols:**

```
ffffffff815eb120-ffffffff815eb16f: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81604fb0)
Location: drivers/virtio/virtio_ring.c:1820
Inline: False
```
**Symbols:**

```
ffffffff81604fb0-ffffffff81605065: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816381b0)
Location: drivers/virtio/virtio_ring.c:1825
Inline: False
```
**Symbols:**

```
ffffffff816381b0-ffffffff81638265: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81659fa0)
Location: drivers/virtio/virtio_ring.c:1824
Inline: False
```
**Symbols:**

```
ffffffff81659fa0-ffffffff8165a055: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81709d80)
Location: drivers/virtio/virtio_ring.c:1824
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff81709d80-ffffffff81709e35: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81726f80)
Location: drivers/virtio/virtio_ring.c:1824
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff81726f80-ffffffff81727035: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170aca0)
Location: drivers/virtio/virtio_ring.c:1826
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_kick
```
**Symbols:**

```
ffffffff8170aca0-ffffffff8170ad55: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1924
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_kick
```
**Symbols:**

```
ffffffff81cf45a7-ffffffff81cf4616: virtqueue_kick_prepare.cold (STB_LOCAL)
ffffffff81786720-ffffffff81786874: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1928
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_kick
```
**Symbols:**

```
ffffffff81ebc992-ffffffff81ebca01: virtqueue_kick_prepare.cold (STB_LOCAL)
ffffffff818bdfe0-ffffffff818be160: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2214
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_kick
```
**Symbols:**

```
ffffffff82093e10-ffffffff82093e7f: virtqueue_kick_prepare.cold (STB_LOCAL)
ffffffff81a0d020-ffffffff81a0d1a9: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2251
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_kick
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/block/virtio_blk.c:virtio_commit_rqs
  - drivers/scsi/virtio_scsi.c:virtscsi_commit_rqs
  - drivers/scsi/virtio_scsi.c:virtscsi_add_cmd
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
```
**Symbols:**

```
ffffffff82114af0-ffffffff82114b5f: virtqueue_kick_prepare.cold (STB_LOCAL)
ffffffff81a55ca0-ffffffff81a55e20: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
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
  - drivers/virtio/virtio_ring.c:virtqueue_kick
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/block/virtio_blk.c:virtio_commit_rqs
  - drivers/scsi/virtio_scsi.c:virtscsi_commit_rqs
  - drivers/scsi/virtio_scsi.c:virtscsi_add_cmd
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
```
**Symbols:**

```
ffffffff821f271c-ffffffff821f278b: virtqueue_kick_prepare.cold (STB_LOCAL)
ffffffff81aa6dc0-ffffffff81aa6f40: virtqueue_kick_prepare (STB_GLOBAL)
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
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010822110)
Location: drivers/virtio/virtio_ring.c:1824
Inline: False
```
**Symbols:**

```
ffff800010822110-ffff800010822254: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c093fa58)
Location: drivers/virtio/virtio_ring.c:1824
Inline: False
```
**Symbols:**

```
c093fa58-c093fb78: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cc5f0)
Location: drivers/virtio/virtio_ring.c:1824
Inline: False
```
**Symbols:**

```
c0000000008cc5f0-c0000000008cc6dc: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000518ab4)
Location: drivers/virtio/virtio_ring.c:1824
Inline: False
```
**Symbols:**

```
ffffffe000518ab4-ffffffe000518bbc: virtqueue_kick_prepare (STB_GLOBAL)
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
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161fe40)
Location: drivers/virtio/virtio_ring.c:1824
Inline: False
```
**Symbols:**

```
ffffffff8161fe40-ffffffff8161fef5: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816143d0)
Location: drivers/virtio/virtio_ring.c:1824
Inline: False
```
**Symbols:**

```
ffffffff816143d0-ffffffff81614485: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164dde0)
Location: drivers/virtio/virtio_ring.c:1824
Inline: False
Direct callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_commit_rqs
  - drivers/scsi/virtio_scsi.c:virtscsi_add_cmd
```
**Symbols:**

```
ffffffff8164dde0-ffffffff8164de95: virtqueue_kick_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool virtqueue_kick_prepare(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81668470)
Location: drivers/virtio/virtio_ring.c:1824
Inline: False
```
**Symbols:**

```
ffffffff81668470-ffffffff81668525: virtqueue_kick_prepare (STB_GLOBAL)
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
