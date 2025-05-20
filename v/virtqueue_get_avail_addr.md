# Function: <code>virtqueue_get_avail_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150f040)
Location: drivers/virtio/virtio_ring.c:1175
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8150f040-ffffffff8150f062: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153b1a0)
Location: drivers/virtio/virtio_ring.c:1179
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8153b1a0-ffffffff8153b1c2: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154ea80)
Location: drivers/virtio/virtio_ring.c:1226
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8154ea80-ffffffff8154eaa2: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b2230)
Location: drivers/virtio/virtio_ring.c:1225
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff815b2230-ffffffff815b2251: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815ea690)
Location: drivers/virtio/virtio_ring.c:1224
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff815ea690-ffffffff815ea6b1: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81604b40)
Location: drivers/virtio/virtio_ring.c:2289
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81604b40-ffffffff81604b72: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81637470)
Location: drivers/virtio/virtio_ring.c:2295
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81637470-ffffffff816374a4: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816591d0)
Location: drivers/virtio/virtio_ring.c:2294
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff816591d0-ffffffff81659204: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81709b40)
Location: drivers/virtio/virtio_ring.c:2297
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81709b40-ffffffff81709b74: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81726ab0)
Location: drivers/virtio/virtio_ring.c:2297
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81726ab0-ffffffff81726ae4: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170a720)
Location: drivers/virtio/virtio_ring.c:2307
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8170a720-ffffffff8170a754: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8178644c)
Location: drivers/virtio/virtio_ring.c:2430
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81cf44fa-ffffffff81cf4524: virtqueue_get_avail_addr.cold (STB_LOCAL)
ffffffff81786410-ffffffff8178646e: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818bd16c)
Location: drivers/virtio/virtio_ring.c:2467
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81ebc58d-ffffffff81ebc5b7: virtqueue_get_avail_addr.cold (STB_LOCAL)
ffffffff818bd130-ffffffff818bd19e: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0bf9c)
Location: drivers/virtio/virtio_ring.c:2831
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff82093aa4-ffffffff82093ace: virtqueue_get_avail_addr.cold (STB_LOCAL)
ffffffff81a0bf60-ffffffff81a0bfce: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(const struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a54ebc)
Location: drivers/virtio/virtio_ring.c:2913
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff821147e0-ffffffff8211480a: virtqueue_get_avail_addr.cold (STB_LOCAL)
ffffffff81a54e80-ffffffff81a54eee: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(const struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa5f7c)
Location: drivers/virtio/virtio_ring.c:3074
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff821f23c6-ffffffff821f23f0: virtqueue_get_avail_addr.cold (STB_LOCAL)
ffffffff81aa5f40-ffffffff81aa5fae: virtqueue_get_avail_addr (STB_GLOBAL)
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
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010821ab0)
Location: drivers/virtio/virtio_ring.c:2294
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffff800010821ab0-ffff800010821b08: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c093f4f4)
Location: drivers/virtio/virtio_ring.c:2294
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
c093f4f4-c093f53c: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cb520)
Location: drivers/virtio/virtio_ring.c:2294
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
c0000000008cb520-c0000000008cb568: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000518646)
Location: drivers/virtio/virtio_ring.c:2294
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffe000518646-ffffffe00051868a: virtqueue_get_avail_addr (STB_GLOBAL)
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
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161f070)
Location: drivers/virtio/virtio_ring.c:2294
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8161f070-ffffffff8161f0a4: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81613750)
Location: drivers/virtio/virtio_ring.c:2294
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81613750-ffffffff81613784: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164d010)
Location: drivers/virtio/virtio_ring.c:2294
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8164d010-ffffffff8164d044: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_avail_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816676a0)
Location: drivers/virtio/virtio_ring.c:2294
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff816676a0-ffffffff816676d4: virtqueue_get_avail_addr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct virtqueue *_vq</code> ➡️ <code>const struct virtqueue *_vq</code>
</li>
</ul>
</details>
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
