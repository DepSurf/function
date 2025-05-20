# Function: <code>vp_modern_get_features</code>

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
u64 vp_modern_get_features(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff8170cd60)
Location: drivers/virtio/virtio_pci_modern_dev.c:371
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
**Symbols:**

```
ffffffff8170cd60-ffffffff8170cdae: vp_modern_get_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 vp_modern_get_features(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81789120)
Location: drivers/virtio/virtio_pci_modern_dev.c:371
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
**Symbols:**

```
ffffffff81789120-ffffffff8178916e: vp_modern_get_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 vp_modern_get_features(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff818c06f0)
Location: drivers/virtio/virtio_pci_modern_dev.c:377
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
**Symbols:**

```
ffffffff818c06f0-ffffffff818c0746: vp_modern_get_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 vp_modern_get_features(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a10290)
Location: drivers/virtio/virtio_pci_modern_dev.c:378
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
**Symbols:**

```
ffffffff81a10290-ffffffff81a102e6: vp_modern_get_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 vp_modern_get_features(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a592e0)
Location: drivers/virtio/virtio_pci_modern_dev.c:387
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
**Symbols:**

```
ffffffff81a592e0-ffffffff81a59336: vp_modern_get_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 vp_modern_get_features(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81aaa6c0)
Location: drivers/virtio/virtio_pci_modern_dev.c:396
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
**Symbols:**

```
ffffffff81aaa6c0-ffffffff81aaa716: vp_modern_get_features (STB_GLOBAL)
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
