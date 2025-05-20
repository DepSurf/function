# Function: <code>vm_setup_vq</code>

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
In drivers/virtio/virtio_mmio.c (ffffffff814c0af3)
Location: drivers/virtio/virtio_mmio.c:361
Inline: True
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
In drivers/virtio/virtio_mmio.c (ffffffff815110f3)
Location: drivers/virtio/virtio_mmio.c:351
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8153d0b3)
Location: drivers/virtio/virtio_mmio.c:352
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81550d7c)
Location: drivers/virtio/virtio_mmio.c:352
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff815b459c)
Location: drivers/virtio/virtio_mmio.c:352
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff815ec97f)
Location: drivers/virtio/virtio_mmio.c:352
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8160757e)
Location: drivers/virtio/virtio_mmio.c:352
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8163b3b7)
Location: drivers/virtio/virtio_mmio.c:348
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8165d887)
Location: drivers/virtio/virtio_mmio.c:348
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vm_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:348
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff8170c730-ffffffff8170c993: vm_setup_vq (STB_LOCAL)
ffffffff8170cfcd-ffffffff8170cff6: vm_setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vm_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:348
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff81729550-ffffffff817297b3: vm_setup_vq (STB_LOCAL)
ffffffff81c0468e-ffffffff81c046b7: vm_setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vm_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:348
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff8170dcf0-ffffffff8170df5f: vm_setup_vq (STB_LOCAL)
ffffffff81bf6377-ffffffff81bf63a0: vm_setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vm_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:348
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff8178a570-ffffffff8178a7df: vm_setup_vq (STB_LOCAL)
ffffffff81cf4e71-ffffffff81cf4e9a: vm_setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vm_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_mmio.c (0)
Location: drivers/virtio/virtio_mmio.c:361
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff818c1d90-ffffffff818c2011: vm_setup_vq (STB_LOCAL)
ffffffff81ebcfdd-ffffffff81ebd006: vm_setup_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct virtqueue *vm_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81a11d80)
Location: drivers/virtio/virtio_mmio.c:361
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff81a11d80-ffffffff81a1203a: vm_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct virtqueue *vm_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81a5adc0)
Location: drivers/virtio/virtio_mmio.c:372
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff81a5adc0-ffffffff81a5b0b4: vm_setup_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct virtqueue *vm_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81aac200)
Location: drivers/virtio/virtio_mmio.c:372
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
```
**Symbols:**

```
ffffffff81aac200-ffffffff81aac524: vm_setup_vq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffff8000108264ec)
Location: drivers/virtio/virtio_mmio.c:348
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (c0944648)
Location: drivers/virtio/virtio_mmio.c:348
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (c0000000008d1cc0)
Location: drivers/virtio/virtio_mmio.c:348
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct virtqueue *vm_setup_vq(struct virtio_device *vdev, unsigned int index, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffe00051c666)
Location: drivers/virtio/virtio_mmio.c:348
Inline: False
```
**Symbols:**

```
ffffffe00051c666-ffffffe00051c9de: vm_setup_vq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81623727)
Location: drivers/virtio/virtio_mmio.c:348
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff81617d77)
Location: drivers/virtio/virtio_mmio.c:348
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff816516c7)
Location: drivers/virtio/virtio_mmio.c:348
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_mmio.c (ffffffff8166bd57)
Location: drivers/virtio/virtio_mmio.c:348
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
