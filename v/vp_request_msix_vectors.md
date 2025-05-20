# Function: <code>vp_request_msix_vectors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vp_request_msix_vectors(struct virtio_device *vdev, int nvectors, bool per_vq_vectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff814c2660)
Location: drivers/virtio/virtio_pci_common.c:140
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs
```
**Symbols:**

```
ffffffff814c2660-ffffffff814c2865: vp_request_msix_vectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vp_request_msix_vectors(struct virtio_device *vdev, int nvectors, bool per_vq_vectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81512be0)
Location: drivers/virtio/virtio_pci_common.c:140
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_try_to_find_vqs
```
**Symbols:**

```
ffffffff81512be0-ffffffff81512ddf: vp_request_msix_vectors (STB_LOCAL)
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
In drivers/virtio/virtio_pci_common.c (ffffffff8153f37b)
Location: drivers/virtio/virtio_pci_common.c:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
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
In drivers/virtio/virtio_pci_common.c (ffffffff81553102)
Location: drivers/virtio/virtio_pci_common.c:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
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
In drivers/virtio/virtio_pci_common.c (ffffffff815b6a82)
Location: drivers/virtio/virtio_pci_common.c:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
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
In drivers/virtio/virtio_pci_common.c (ffffffff815eeefd)
Location: drivers/virtio/virtio_pci_common.c:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
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
In drivers/virtio/virtio_pci_common.c (ffffffff816095fd)
Location: drivers/virtio/virtio_pci_common.c:105
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
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
In drivers/virtio/virtio_pci_common.c (ffffffff8163d483)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
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
In drivers/virtio/virtio_pci_common.c (ffffffff8165f963)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vp_request_msix_vectors(struct virtio_device *vdev, int nvectors, bool per_vq_vectors, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8170e6e0)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff8170e6e0-ffffffff8170e932: vp_request_msix_vectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vp_request_msix_vectors(struct virtio_device *vdev, int nvectors, bool per_vq_vectors, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8172b4b0)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff8172b4b0-ffffffff8172b702: vp_request_msix_vectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vp_request_msix_vectors(struct virtio_device *vdev, int nvectors, bool per_vq_vectors, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8170f240)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff8170f240-ffffffff8170f492: vp_request_msix_vectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vp_request_msix_vectors(struct virtio_device *vdev, int nvectors, bool per_vq_vectors, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8178bb80)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff8178bb80-ffffffff8178bdd2: vp_request_msix_vectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vp_request_msix_vectors(struct virtio_device *vdev, int nvectors, bool per_vq_vectors, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff818c3770)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff818c3770-ffffffff818c39ca: vp_request_msix_vectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vp_request_msix_vectors(struct virtio_device *vdev, int nvectors, bool per_vq_vectors, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81a13dd0)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff81a13dd0-ffffffff81a1402f: vp_request_msix_vectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vp_request_msix_vectors(struct virtio_device *vdev, int nvectors, bool per_vq_vectors, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81a5ce20)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff81a5ce20-ffffffff81a5d07f: vp_request_msix_vectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vp_request_msix_vectors(struct virtio_device *vdev, int nvectors, bool per_vq_vectors, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81aaedc0)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
**Symbols:**

```
ffffffff81aaedc0-ffffffff81aaf01f: vp_request_msix_vectors (STB_LOCAL)
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
In drivers/virtio/virtio_pci_common.c (ffff800010828888)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
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
In drivers/virtio/virtio_pci_common.c (c0946548)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
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
In drivers/virtio/virtio_pci_common.c (c0000000008d4dc8)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffe00051ec92)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
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
In drivers/virtio/virtio_pci_common.c (ffffffff816257d3)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
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
In drivers/virtio/virtio_pci_common.c (ffffffff81619e53)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
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
In drivers/virtio/virtio_pci_common.c (ffffffff816537a3)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
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
In drivers/virtio/virtio_pci_common.c (ffffffff8166de33)
Location: drivers/virtio/virtio_pci_common.c:102
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs_msix
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
