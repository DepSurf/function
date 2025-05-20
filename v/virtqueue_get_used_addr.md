# Function: <code>virtqueue_get_used_addr</code>

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
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150f070)
Location: drivers/virtio/virtio_ring.c:1186
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8150f070-ffffffff8150f092: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153b1d0)
Location: drivers/virtio/virtio_ring.c:1190
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8153b1d0-ffffffff8153b1f2: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154eab0)
Location: drivers/virtio/virtio_ring.c:1237
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8154eab0-ffffffff8154ead2: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b2260)
Location: drivers/virtio/virtio_ring.c:1236
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff815b2260-ffffffff815b2281: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815ea6c0)
Location: drivers/virtio/virtio_ring.c:1235
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff815ea6c0-ffffffff815ea6e1: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81604b80)
Location: drivers/virtio/virtio_ring.c:2303
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81604b80-ffffffff81604bb2: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816374b0)
Location: drivers/virtio/virtio_ring.c:2309
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff816374b0-ffffffff816374e4: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81659210)
Location: drivers/virtio/virtio_ring.c:2308
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81659210-ffffffff81659244: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81709b80)
Location: drivers/virtio/virtio_ring.c:2311
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81709b80-ffffffff81709bb4: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81726af0)
Location: drivers/virtio/virtio_ring.c:2311
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81726af0-ffffffff81726b24: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170a760)
Location: drivers/virtio/virtio_ring.c:2321
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8170a760-ffffffff8170a794: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817864ac)
Location: drivers/virtio/virtio_ring.c:2444
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81cf4524-ffffffff81cf454e: virtqueue_get_used_addr.cold (STB_LOCAL)
ffffffff81786470-ffffffff817864ce: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818bd1dc)
Location: drivers/virtio/virtio_ring.c:2481
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81ebc5b7-ffffffff81ebc5e1: virtqueue_get_used_addr.cold (STB_LOCAL)
ffffffff818bd1a0-ffffffff818bd20e: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0c01c)
Location: drivers/virtio/virtio_ring.c:2845
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff82093ace-ffffffff82093af8: virtqueue_get_used_addr.cold (STB_LOCAL)
ffffffff81a0bfe0-ffffffff81a0c04e: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(const struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a54f3c)
Location: drivers/virtio/virtio_ring.c:2927
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff8211480a-ffffffff82114834: virtqueue_get_used_addr.cold (STB_LOCAL)
ffffffff81a54f00-ffffffff81a54f6e: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(const struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa5ffc)
Location: drivers/virtio/virtio_ring.c:3088
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_active_vq
```
**Symbols:**

```
ffffffff821f23f0-ffffffff821f241a: virtqueue_get_used_addr.cold (STB_LOCAL)
ffffffff81aa5fc0-ffffffff81aa602e: virtqueue_get_used_addr (STB_GLOBAL)
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
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010821b08)
Location: drivers/virtio/virtio_ring.c:2308
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffff800010821b08-ffff800010821b64: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c093f53c)
Location: drivers/virtio/virtio_ring.c:2308
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
c093f53c-c093f584: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cb570)
Location: drivers/virtio/virtio_ring.c:2308
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
c0000000008cb570-c0000000008cb5b8: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe00051868a)
Location: drivers/virtio/virtio_ring.c:2308
Inline: True
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffe00051868a-ffffffe0005186ce: virtqueue_get_used_addr (STB_GLOBAL)
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
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161f0b0)
Location: drivers/virtio/virtio_ring.c:2308
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8161f0b0-ffffffff8161f0e4: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81613790)
Location: drivers/virtio/virtio_ring.c:2308
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff81613790-ffffffff816137c4: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164d050)
Location: drivers/virtio/virtio_ring.c:2308
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff8164d050-ffffffff8164d084: virtqueue_get_used_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t virtqueue_get_used_addr(struct virtqueue *_vq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816676e0)
Location: drivers/virtio/virtio_ring.c:2308
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
**Symbols:**

```
ffffffff816676e0-ffffffff81667714: virtqueue_get_used_addr (STB_GLOBAL)
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
