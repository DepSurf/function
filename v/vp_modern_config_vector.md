# Function: <code>vp_modern_config_vector</code>

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
u16 vp_modern_config_vector(struct virtio_pci_modern_device *mdev, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff8170cee0)
Location: drivers/virtio/virtio_pci_modern_dev.c:472
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
```
**Symbols:**

```
ffffffff8170cee0-ffffffff8170cf0c: vp_modern_config_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u16 vp_modern_config_vector(struct virtio_pci_modern_device *mdev, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81789300)
Location: drivers/virtio/virtio_pci_modern_dev.c:493
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
```
**Symbols:**

```
ffffffff81789300-ffffffff8178932c: vp_modern_config_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u16 vp_modern_config_vector(struct virtio_pci_modern_device *mdev, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff818c0920)
Location: drivers/virtio/virtio_pci_modern_dev.c:504
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
```
**Symbols:**

```
ffffffff818c0920-ffffffff818c0953: vp_modern_config_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 vp_modern_config_vector(struct virtio_pci_modern_device *mdev, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a10590)
Location: drivers/virtio/virtio_pci_modern_dev.c:543
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
```
**Symbols:**

```
ffffffff81a10590-ffffffff81a105c3: vp_modern_config_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 vp_modern_config_vector(struct virtio_pci_modern_device *mdev, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a595e0)
Location: drivers/virtio/virtio_pci_modern_dev.c:552
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
```
**Symbols:**

```
ffffffff81a595e0-ffffffff81a59613: vp_modern_config_vector (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 vp_modern_config_vector(struct virtio_pci_modern_device *mdev, u16 vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81aaa9c0)
Location: drivers/virtio/virtio_pci_modern_dev.c:561
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
```
**Symbols:**

```
ffffffff81aaa9c0-ffffffff81aaa9f3: vp_modern_config_vector (STB_GLOBAL)
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
