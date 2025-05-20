# Function: <code>vring_create_virtqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150f820)
Location: drivers/virtio/virtio_ring.c:1011
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff8150f820-ffffffff8150fa30: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153b9d0)
Location: drivers/virtio/virtio_ring.c:1015
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff8153b9d0-ffffffff8153bbe0: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154f300)
Location: drivers/virtio/virtio_ring.c:1060
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff8154f300-ffffffff8154f518: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b2ac0)
Location: drivers/virtio/virtio_ring.c:1059
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff815b2ac0-ffffffff815b2cd8: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815eaf00)
Location: drivers/virtio/virtio_ring.c:1058
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff815eaf00-ffffffff815eb112: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81605de0)
Location: drivers/virtio/virtio_ring.c:2126
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff81605de0-ffffffff816062e5: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2132
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff8163ac92-ffffffff8163acab: vring_create_virtqueue.cold (STB_LOCAL)
ffffffff81637f60-ffffffff816381b0: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2131
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff8165d152-ffffffff8165d16b: vring_create_virtqueue.cold (STB_LOCAL)
ffffffff81659d50-ffffffff81659fa0: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170c210)
Location: drivers/virtio/virtio_ring.c:2134
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff8170c210-ffffffff8170c268: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81729060)
Location: drivers/virtio/virtio_ring.c:2134
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff81729060-ffffffff817290b8: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170cc40)
Location: drivers/virtio/virtio_ring.c:2138
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff8170cc40-ffffffff8170cc98: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81789000)
Location: drivers/virtio/virtio_ring.c:2258
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff81789000-ffffffff81789058: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818c0210)
Location: drivers/virtio/virtio_ring.c:2273
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff818c0210-ffffffff818c029a: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0eb30)
Location: drivers/virtio/virtio_ring.c:2536
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff81a0eb30-ffffffff81a0ec6b: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a57c90)
Location: drivers/virtio/virtio_ring.c:2569
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff81a57c90-ffffffff81a57d2b: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa9090)
Location: drivers/virtio/virtio_ring.c:2665
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff81aa9090-ffffffff81aa912b: vring_create_virtqueue (STB_GLOBAL)
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
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010824288)
Location: drivers/virtio/virtio_ring.c:2131
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffff800010824288-ffff8000108244f4: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0941550)
Location: drivers/virtio/virtio_ring.c:2131
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
c0941550-c09417c8: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cc1c0)
Location: drivers/virtio/virtio_ring.c:2131
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
c0000000008cc1c0-c0000000008cc564: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe00051a14c)
Location: drivers/virtio/virtio_ring.c:2131
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffe00051a14c-ffffffe00051a380: vring_create_virtqueue (STB_GLOBAL)
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
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2131
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff81622ff2-ffffffff8162300b: vring_create_virtqueue.cold (STB_LOCAL)
ffffffff8161fbf0-ffffffff8161fe40: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2131
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff81617642-ffffffff8161765b: vring_create_virtqueue.cold (STB_LOCAL)
ffffffff81614180-ffffffff816143d0: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2131
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff81650f92-ffffffff81650fab: vring_create_virtqueue.cold (STB_LOCAL)
ffffffff8164db90-ffffffff8164dde0: vring_create_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vring_create_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2131
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff8166b622-ffffffff8166b63b: vring_create_virtqueue.cold (STB_LOCAL)
ffffffff81668220-ffffffff81668470: vring_create_virtqueue (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool context</code>
</li>
<li>
<b>Param reordered. </b>
<code>index, num, vring_align, vdev, weak_barriers, may_reduce_num, notify, callback, name</code> ➡️ <code>index, num, vring_align, vdev, weak_barriers, may_reduce_num, context, notify, callback, name</code>
</li>
</ul>
</details>
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
