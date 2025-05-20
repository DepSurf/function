# Function: <code>vp_modern_set_features</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vp_modern_set_features(struct virtio_pci_modern_device *mdev, u64 features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff8170cd00)
Location: drivers/virtio/virtio_pci_modern_dev.c:391
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
**Symbols:**

```
ffffffff8170cd00-ffffffff8170cd55: vp_modern_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vp_modern_set_features(struct virtio_pci_modern_device *mdev, u64 features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff817890c0)
Location: drivers/virtio/virtio_pci_modern_dev.c:412
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
**Symbols:**

```
ffffffff817890c0-ffffffff81789115: vp_modern_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vp_modern_set_features(struct virtio_pci_modern_device *mdev, u64 features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff818c0690)
Location: drivers/virtio/virtio_pci_modern_dev.c:418
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
**Symbols:**

```
ffffffff818c0690-ffffffff818c06ed: vp_modern_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vp_modern_set_features(struct virtio_pci_modern_device *mdev, u64 features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a10220)
Location: drivers/virtio/virtio_pci_modern_dev.c:419
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
**Symbols:**

```
ffffffff81a10220-ffffffff81a1027d: vp_modern_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vp_modern_set_features(struct virtio_pci_modern_device *mdev, u64 features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a59270)
Location: drivers/virtio/virtio_pci_modern_dev.c:428
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
**Symbols:**

```
ffffffff81a59270-ffffffff81a592cc: vp_modern_set_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vp_modern_set_features(struct virtio_pci_modern_device *mdev, u64 features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81aaa650)
Location: drivers/virtio/virtio_pci_modern_dev.c:437
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
**Symbols:**

```
ffffffff81aaa650-ffffffff81aaa6ac: vp_modern_set_features (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
