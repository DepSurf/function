# Function: <code>vp_find_vqs_msix</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8153f310)
Location: drivers/virtio/virtio_pci_common.c:268
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff8153f310-ffffffff8153f75c: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81553090)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff81553090-ffffffff815534e3: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff815b6a10)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff815b6a10-ffffffff815b6e68: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff815eee90)
Location: drivers/virtio/virtio_pci_common.c:280
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff815eee90-ffffffff815ef360: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81609590)
Location: drivers/virtio/virtio_pci_common.c:280
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff81609590-ffffffff81609a63: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8163d410)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff8163d410-ffffffff8163d841: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8165f8f0)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff8165f8f0-ffffffff8165fd30: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8170ec20)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff8170ec20-ffffffff8170eedb: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8172b9f0)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff8172b9f0-ffffffff8172bcab: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8170f780)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff8170f780-ffffffff8170fa34: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff8178c0e0-ffffffff8178c3c7: vp_find_vqs_msix (STB_LOCAL)
ffffffff81cf508f-ffffffff81cf5118: vp_find_vqs_msix.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.c:278
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff818c3cf0-ffffffff818c3ff8: vp_find_vqs_msix (STB_LOCAL)
ffffffff81ebd219-ffffffff81ebd287: vp_find_vqs_msix.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.c:284
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff81a143a0-ffffffff81a146a8: vp_find_vqs_msix (STB_LOCAL)
ffffffff82094530-ffffffff8209459e: vp_find_vqs_msix.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.c:284
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff81a5d3f0-ffffffff81a5d701: vp_find_vqs_msix (STB_LOCAL)
ffffffff82115290-ffffffff821152fe: vp_find_vqs_msix.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (0)
Location: drivers/virtio/virtio_pci_common.c:287
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff81aaf3a0-ffffffff81aaf6b1: vp_find_vqs_msix (STB_LOCAL)
ffffffff821f2eeb-ffffffff821f2f59: vp_find_vqs_msix.cold (STB_LOCAL)
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
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffff800010828820)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffff800010828820-ffff800010828c14: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (c09464e4)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
c09464e4-c0946908: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (c0000000008d4d20)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
c0000000008d4d20-c0000000008d5254: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffe00051ec32)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffe00051ec32-ffffffe00051efe6: vp_find_vqs_msix (STB_LOCAL)
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
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81625760)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff81625760-ffffffff81625ba0: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81619de0)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff81619de0-ffffffff8161a220: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81653730)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff81653730-ffffffff81653b70: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vp_find_vqs_msix(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, bool per_vq_vectors, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8166ddc0)
Location: drivers/virtio/virtio_pci_common.c:279
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff8166ddc0-ffffffff8166e200: vp_find_vqs_msix (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
