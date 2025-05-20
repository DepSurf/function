# Function: <code>vp_setup_vq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff814c2bb8)
Location: drivers/virtio/virtio_pci_common.c:225
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8151312d)
Location: drivers/virtio/virtio_pci_common.c:225
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8153ecd0)
Location: drivers/virtio/virtio_pci_common.c:170
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff8153ecd0-ffffffff8153edda: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81552a50)
Location: drivers/virtio/virtio_pci_common.c:176
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff81552a50-ffffffff81552b5f: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff815b63b0)
Location: drivers/virtio/virtio_pci_common.c:176
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff815b63b0-ffffffff815b64c5: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff815ee750)
Location: drivers/virtio/virtio_pci_common.c:177
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff815ee750-ffffffff815ee865: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81608e50)
Location: drivers/virtio/virtio_pci_common.c:177
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff81608e50-ffffffff81608f65: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8163ccb0)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff8163ccb0-ffffffff8163cdc0: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8165f190)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff8165f190-ffffffff8165f2a0: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8170e280)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_intx
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff8170e280-ffffffff8170e390: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8172b050)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_intx
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff8172b050-ffffffff8172b160: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8170edd0)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff8170edd0-ffffffff8170eedd: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8178b700)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff8178b700-ffffffff8178b80d: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff818c3270)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff818c3270-ffffffff818c3388: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81a13850)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff81a13850-ffffffff81a13968: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81a5c8b0)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff81a5c8b0-ffffffff81a5c9c9: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81aae660)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff81aae660-ffffffff81aae7a8: vp_setup_vq (STB_LOCAL)
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
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffff800010828280)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffff800010828280-ffff8000108283e0: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (c0945e64)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
c0945e64-c0945f50: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (c0000000008d41a0)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
c0000000008d41a0-c0000000008d4308: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffe00051e5ac)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffe00051e5ac-ffffffe00051e68c: vp_setup_vq (STB_LOCAL)
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
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81625000)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff81625000-ffffffff81625110: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81619680)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff81619680-ffffffff81619790: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81652fd0)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff81652fd0-ffffffff816530e0: vp_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct virtqueue *vp_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx, u16 msix_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8166d660)
Location: drivers/virtio/virtio_pci_common.c:174
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff8166d660-ffffffff8166d770: vp_setup_vq (STB_LOCAL)
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
<code>bool ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>vdev, index, callback, name, msix_vec</code> ➡️ <code>vdev, index, callback, name, ctx, msix_vec</code>
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
