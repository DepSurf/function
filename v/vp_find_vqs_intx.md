# Function: <code>vp_find_vqs_intx</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8153f7c4)
Location: drivers/virtio/virtio_pci_common.c:339
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
In drivers/virtio/virtio_pci_common.c (ffffffff81553563)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
In drivers/virtio/virtio_pci_common.c (ffffffff815b6ee3)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
In drivers/virtio/virtio_pci_common.c (ffffffff815ef3d7)
Location: drivers/virtio/virtio_pci_common.c:354
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
In drivers/virtio/virtio_pci_common.c (ffffffff81609ae7)
Location: drivers/virtio/virtio_pci_common.c:354
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
In drivers/virtio/virtio_pci_common.c (ffffffff8163d8c1)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
In drivers/virtio/virtio_pci_common.c (ffffffff8165fda1)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vp_find_vqs_intx(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8170eee0)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff8170eee0-ffffffff8170f012: vp_find_vqs_intx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vp_find_vqs_intx(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8172bcb0)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
**Symbols:**

```
ffffffff8172bcb0-ffffffff8172bde2: vp_find_vqs_intx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8170fab1)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff8178c441)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff818c408f)
Location: drivers/virtio/virtio_pci_common.c:352
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81a14761)
Location: drivers/virtio/virtio_pci_common.c:358
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81a5d7c1)
Location: drivers/virtio/virtio_pci_common.c:358
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81aaf771)
Location: drivers/virtio/virtio_pci_common.c:361
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
In drivers/virtio/virtio_pci_common.c (ffff800010828cc4)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
In drivers/virtio/virtio_pci_common.c (c0946994)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
In drivers/virtio/virtio_pci_common.c (c0000000008d5348)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
In drivers/virtio/virtio_pci_common.c (ffffffe00051f072)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
In drivers/virtio/virtio_pci_common.c (ffffffff81625c11)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
In drivers/virtio/virtio_pci_common.c (ffffffff8161a291)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
In drivers/virtio/virtio_pci_common.c (ffffffff81653be1)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
In drivers/virtio/virtio_pci_common.c (ffffffff8166e271)
Location: drivers/virtio/virtio_pci_common.c:353
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_find_vqs
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
</ul>
