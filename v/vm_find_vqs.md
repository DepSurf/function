# Function: <code>vm_find_vqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const char **names);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff814c0a80)
Location: drivers/virtio/virtio_mmio.c:482
Inline: True
```
**Symbols:**

```
ffffffff814c0a80-ffffffff814c0e7b: vm_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81511090)
Location: drivers/virtio/virtio_mmio.c:445
Inline: True
```
**Symbols:**

```
ffffffff81511090-ffffffff81511454: vm_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8153d050)
Location: drivers/virtio/virtio_mmio.c:446
Inline: True
```
**Symbols:**

```
ffffffff8153d050-ffffffff8153d414: vm_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81550ce0)
Location: drivers/virtio/virtio_mmio.c:446
Inline: True
```
**Symbols:**

```
ffffffff81550ce0-ffffffff8155109a: vm_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff815b4500)
Location: drivers/virtio/virtio_mmio.c:446
Inline: True
```
**Symbols:**

```
ffffffff815b4500-ffffffff815b48ba: vm_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff815ec8e0)
Location: drivers/virtio/virtio_mmio.c:446
Inline: True
```
**Symbols:**

```
ffffffff815ec8e0-ffffffff815ecc43: vm_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff816074d0)
Location: drivers/virtio/virtio_mmio.c:462
Inline: True
```
**Symbols:**

```
ffffffff816074d0-ffffffff81607867: vm_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:458
Inline: True
```
**Symbols:**

```
ffffffff8163b2f0-ffffffff8163b655: vm_find_vqs (STB_LOCAL)
ffffffff8163b9e7-ffffffff8163ba3a: vm_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:458
Inline: True
```
**Symbols:**

```
ffffffff8165d7c0-ffffffff8165db25: vm_find_vqs (STB_LOCAL)
ffffffff8165dea4-ffffffff8165dee4: vm_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8170ce60)
Location: drivers/virtio/virtio_mmio.c:458
Inline: False
```
**Symbols:**

```
ffffffff8170ce60-ffffffff8170cfb3: vm_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81729c80)
Location: drivers/virtio/virtio_mmio.c:458
Inline: False
```
**Symbols:**

```
ffffffff81729c80-ffffffff81729dd3: vm_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8170df60)
Location: drivers/virtio/virtio_mmio.c:458
Inline: False
```
**Symbols:**

```
ffffffff8170df60-ffffffff8170e06c: vm_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:458
Inline: False
```
**Symbols:**

```
ffffffff8178a970-ffffffff8178aaa6: vm_find_vqs (STB_LOCAL)
ffffffff81cf4e9a-ffffffff81cf4ecc: vm_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:471
Inline: False
```
**Symbols:**

```
ffffffff818c22a0-ffffffff818c240c: vm_find_vqs (STB_LOCAL)
ffffffff81ebd006-ffffffff81ebd037: vm_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:473
Inline: False
```
**Symbols:**

```
ffffffff81a121e0-ffffffff81a1234c: vm_find_vqs (STB_LOCAL)
ffffffff82094464-ffffffff82094495: vm_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:490
Inline: False
```
**Symbols:**

```
ffffffff81a5b220-ffffffff81a5b387: vm_find_vqs (STB_LOCAL)
ffffffff821151c4-ffffffff821151f5: vm_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:490
Inline: False
```
**Symbols:**

```
ffffffff81aac690-ffffffff81aac7f7: vm_find_vqs (STB_LOCAL)
ffffffff821f2e06-ffffffff821f2e37: vm_find_vqs.cold (STB_LOCAL)
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
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffff800010826418)
Location: drivers/virtio/virtio_mmio.c:458
Inline: True
```
**Symbols:**

```
ffff800010826418-ffff800010826894: vm_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (c0944554)
Location: drivers/virtio/virtio_mmio.c:458
Inline: True
```
**Symbols:**

```
c0944554-c0944908: vm_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (c0000000008d1b80)
Location: drivers/virtio/virtio_mmio.c:458
Inline: True
```
**Symbols:**

```
c0000000008d1b80-c0000000008d2144: vm_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffe00051ce52)
Location: drivers/virtio/virtio_mmio.c:458
Inline: True
```
**Symbols:**

```
ffffffe00051ce52-ffffffe00051cf60: vm_find_vqs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:458
Inline: True
```
**Symbols:**

```
ffffffff81623660-ffffffff816239c5: vm_find_vqs (STB_LOCAL)
ffffffff81623d44-ffffffff81623d84: vm_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:458
Inline: True
```
**Symbols:**

```
ffffffff81617cb0-ffffffff81618015: vm_find_vqs (STB_LOCAL)
ffffffff81618394-ffffffff816183d4: vm_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:458
Inline: True
```
**Symbols:**

```
ffffffff81651600-ffffffff81651965: vm_find_vqs (STB_LOCAL)
ffffffff81651ce4-ffffffff81651d24: vm_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vm_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:458
Inline: True
```
**Symbols:**

```
ffffffff8166bc90-ffffffff8166bff5: vm_find_vqs (STB_LOCAL)
ffffffff8166c374-ffffffff8166c3b4: vm_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const char **names</code> ➡️ <code>const const char * *names</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const bool *ctx</code>
</li>
<li>
<b>Param added. </b>
<code>struct irq_affinity *desc</code>
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
