# Function: <code>setup_vq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff814c16e0)
Location: drivers/virtio/virtio_pci_modern.c:315
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff814c31d0)
Location: drivers/virtio/virtio_pci_legacy.c:114
Inline: False
```
**Symbols:**

```
ffffffff814c16e0-ffffffff814c1b27: setup_vq (STB_LOCAL)
ffffffff814c31d0-ffffffff814c33af: setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff81511cb0)
Location: drivers/virtio/virtio_pci_modern.c:295
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81513710)
Location: drivers/virtio/virtio_pci_legacy.c:114
Inline: False
```
**Symbols:**

```
ffffffff81511cb0-ffffffff81511f9b: setup_vq (STB_LOCAL)
ffffffff81513710-ffffffff81513876: setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff8153e040)
Location: drivers/virtio/virtio_pci_modern.c:295
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff8153fb30)
Location: drivers/virtio/virtio_pci_legacy.c:114
Inline: False
```
**Symbols:**

```
ffffffff8153e040-ffffffff8153e32b: setup_vq (STB_LOCAL)
ffffffff8153fb30-ffffffff8153fc96: setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff81551d90)
Location: drivers/virtio/virtio_pci_modern.c:295
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81553900)
Location: drivers/virtio/virtio_pci_legacy.c:114
Inline: False
```
**Symbols:**

```
ffffffff81551d90-ffffffff81552064: setup_vq (STB_LOCAL)
ffffffff81553900-ffffffff81553a68: setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff815b5680)
Location: drivers/virtio/virtio_pci_modern.c:295
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815b7280)
Location: drivers/virtio/virtio_pci_legacy.c:114
Inline: False
```
**Symbols:**

```
ffffffff815b5680-ffffffff815b5954: setup_vq (STB_LOCAL)
ffffffff815b7280-ffffffff815b73e8: setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff815eda70)
Location: drivers/virtio/virtio_pci_modern.c:309
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff815ef780)
Location: drivers/virtio/virtio_pci_legacy.c:114
Inline: False
```
**Symbols:**

```
ffffffff815eda70-ffffffff815edd52: setup_vq (STB_LOCAL)
ffffffff815ef780-ffffffff815ef91c: setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff81608350)
Location: drivers/virtio/virtio_pci_modern.c:309
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81609ea0)
Location: drivers/virtio/virtio_pci_legacy.c:116
Inline: False
```
**Symbols:**

```
ffffffff81608350-ffffffff81608632: setup_vq (STB_LOCAL)
ffffffff81609ea0-ffffffff8160a03c: setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:306
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_legacy.c:113
Inline: False
```
**Symbols:**

```
ffffffff8163c100-ffffffff8163c3a8: setup_vq (STB_LOCAL)
ffffffff8163cb76-ffffffff8163cbd1: setup_vq.cold (STB_LOCAL)
ffffffff8163dc80-ffffffff8163ddf7: setup_vq (STB_LOCAL)
ffffffff8163e08f-ffffffff8163e0ba: setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:306
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_legacy.c:113
Inline: False
```
**Symbols:**

```
ffffffff8165e5b0-ffffffff8165e858: setup_vq (STB_LOCAL)
ffffffff8165f056-ffffffff8165f0b1: setup_vq.cold (STB_LOCAL)
ffffffff81660160-ffffffff816602d7: setup_vq (STB_LOCAL)
ffffffff8166056f-ffffffff8166059a: setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:307
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_legacy.c:113
Inline: False
```
**Symbols:**

```
ffffffff8170d750-ffffffff8170d9f8: setup_vq (STB_LOCAL)
ffffffff8170e134-ffffffff8170e18f: setup_vq.cold (STB_LOCAL)
ffffffff8170f350-ffffffff8170f4c7: setup_vq (STB_LOCAL)
ffffffff8170f761-ffffffff8170f78c: setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:307
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_legacy.c:113
Inline: False
```
**Symbols:**

```
ffffffff8172a660-ffffffff8172a908: setup_vq (STB_LOCAL)
ffffffff81c048e4-ffffffff81c0493f: setup_vq.cold (STB_LOCAL)
ffffffff8172c120-ffffffff8172c297: setup_vq (STB_LOCAL)
ffffffff81c04950-ffffffff81c0497b: setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:184
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_legacy.c:113
Inline: False
```
**Symbols:**

```
ffffffff8170e5b0-ffffffff8170e758: setup_vq (STB_LOCAL)
ffffffff81bf64b4-ffffffff81bf64dc: setup_vq.cold (STB_LOCAL)
ffffffff8170fe70-ffffffff8170ffe5: setup_vq (STB_LOCAL)
ffffffff81bf6539-ffffffff81bf6564: setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:184
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_legacy.c:113
Inline: False
```
**Symbols:**

```
ffffffff8178ae40-ffffffff8178afe8: setup_vq (STB_LOCAL)
ffffffff81cf4fe0-ffffffff81cf5008: setup_vq.cold (STB_LOCAL)
ffffffff8178c850-ffffffff8178c9c5: setup_vq (STB_LOCAL)
ffffffff81cf515e-ffffffff81cf5189: setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:184
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_legacy.c:110
Inline: False
```
**Symbols:**

```
ffffffff818c2800-ffffffff818c29b3: setup_vq (STB_LOCAL)
ffffffff81ebd13f-ffffffff81ebd168: setup_vq.cold (STB_LOCAL)
ffffffff818c4480-ffffffff818c45da: setup_vq (STB_LOCAL)
ffffffff81ebd2cb-ffffffff81ebd2f6: setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff81a12a70)
Location: drivers/virtio/virtio_pci_modern.c:291
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81a14bb0)
Location: drivers/virtio/virtio_pci_legacy.c:110
Inline: False
```
**Symbols:**

```
ffffffff81a12a70-ffffffff81a12be3: setup_vq (STB_LOCAL)
ffffffff81a14bb0-ffffffff81a14d3c: setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff81a5baf0)
Location: drivers/virtio/virtio_pci_modern.c:300
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81a5dc60)
Location: drivers/virtio/virtio_pci_legacy.c:110
Inline: False
```
**Symbols:**

```
ffffffff81a5baf0-ffffffff81a5bc5d: setup_vq (STB_LOCAL)
ffffffff81a5dc60-ffffffff81a5ddec: setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffff81aadca0)
Location: drivers/virtio/virtio_pci_modern.c:530
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffff81aafc50)
Location: drivers/virtio/virtio_pci_legacy.c:110
Inline: False
```
**Symbols:**

```
ffffffff81aadca0-ffffffff81aaded8: setup_vq (STB_LOCAL)
ffffffff81aafc50-ffffffff81aafddc: setup_vq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffff800010827628)
Location: drivers/virtio/virtio_pci_modern.c:306
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (ffff800010829308)
Location: drivers/virtio/virtio_pci_legacy.c:113
Inline: False
```
**Symbols:**

```
ffff800010827628-ffff8000108278f0: setup_vq (STB_LOCAL)
ffff800010829308-ffff8000108294b0: setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (c094542c)
Location: drivers/virtio/virtio_pci_modern.c:306
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (c0946d7c)
Location: drivers/virtio/virtio_pci_legacy.c:113
Inline: False
```
**Symbols:**

```
c094542c-c09456fc: setup_vq (STB_LOCAL)
c0946d7c-c0946ed0: setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (c0000000008d33a0)
Location: drivers/virtio/virtio_pci_modern.c:306
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (c0000000008d5910)
Location: drivers/virtio/virtio_pci_legacy.c:113
Inline: False
```
**Symbols:**

```
c0000000008d33a0-c0000000008d3744: setup_vq (STB_LOCAL)
c0000000008d5910-c0000000008d5afc: setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (ffffffe00051dc4a)
Location: drivers/virtio/virtio_pci_modern.c:306
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffe00051f536)
Location: drivers/virtio/virtio_pci_legacy.c:113
Inline: False
```
**Symbols:**

```
ffffffe00051dc4a-ffffffe00051dec6: setup_vq (STB_LOCAL)
ffffffe00051f536-ffffffe00051f6d4: setup_vq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:306
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_legacy.c:113
Inline: False
```
**Symbols:**

```
ffffffff81624450-ffffffff816246f8: setup_vq (STB_LOCAL)
ffffffff81624ec6-ffffffff81624f21: setup_vq.cold (STB_LOCAL)
ffffffff81625fd0-ffffffff81626147: setup_vq (STB_LOCAL)
ffffffff816263df-ffffffff8162640a: setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Transformation ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:306
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_legacy.c:113
Inline: False
```
**Symbols:**

```
ffffffff81618aa0-ffffffff81618d48: setup_vq (STB_LOCAL)
ffffffff81619546-ffffffff816195a1: setup_vq.cold (STB_LOCAL)
ffffffff8161a650-ffffffff8161a7c7: setup_vq (STB_LOCAL)
ffffffff8161aa5f-ffffffff8161aa8a: setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:306
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_legacy.c:113
Inline: False
```
**Symbols:**

```
ffffffff816523f0-ffffffff81652698: setup_vq (STB_LOCAL)
ffffffff81652e96-ffffffff81652ef1: setup_vq.cold (STB_LOCAL)
ffffffff81653fa0-ffffffff81654117: setup_vq (STB_LOCAL)
ffffffff816543af-ffffffff816543da: setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
struct virtqueue *setup_vq(struct virtio_pci_device *vp_dev, struct virtio_pci_vq_info *info, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:306
Inline: False
```
```
In drivers/virtio/virtio_pci_legacy.c (0)
Location: drivers/virtio/virtio_pci_legacy.c:113
Inline: False
```
**Symbols:**

```
ffffffff8166ca80-ffffffff8166cd28: setup_vq (STB_LOCAL)
ffffffff8166d526-ffffffff8166d581: setup_vq.cold (STB_LOCAL)
ffffffff8166e630-ffffffff8166e7a7: setup_vq (STB_LOCAL)
ffffffff8166ea3f-ffffffff8166ea6a: setup_vq.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>vp_dev, info, index, callback, name, msix_vec</code> ➡️ <code>vp_dev, info, index, callback, name, ctx, msix_vec</code>
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
