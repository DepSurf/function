# Function: <code>vp_modern_probe</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vp_modern_probe(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (0)
Location: drivers/virtio/virtio_pci_modern_dev.c:207
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffff81bf634c-ffffffff81bf635d: vp_modern_probe.cold (STB_LOCAL)
ffffffff8170d290-ffffffff8170d849: vp_modern_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vp_modern_probe(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (0)
Location: drivers/virtio/virtio_pci_modern_dev.c:207
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffff81cf4e46-ffffffff81cf4e57: vp_modern_probe.cold (STB_LOCAL)
ffffffff81789840-ffffffff8178a0aa: vp_modern_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vp_modern_probe(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (0)
Location: drivers/virtio/virtio_pci_modern_dev.c:214
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffff81ebcf8f-ffffffff81ebcfaf: vp_modern_probe.cold (STB_LOCAL)
ffffffff818c0ba0-ffffffff818c144e: vp_modern_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vp_modern_probe(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a10920)
Location: drivers/virtio/virtio_pci_modern_dev.c:215
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffff81a10920-ffffffff81a11235: vp_modern_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vp_modern_probe(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81a59970)
Location: drivers/virtio/virtio_pci_modern_dev.c:215
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffff81a59970-ffffffff81a5a203: vp_modern_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vp_modern_probe(struct virtio_pci_modern_device *mdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_modern_dev.c (ffffffff81aaadb0)
Location: drivers/virtio/virtio_pci_modern_dev.c:223
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe
```
**Symbols:**

```
ffffffff81aaadb0-ffffffff81aab646: vp_modern_probe (STB_GLOBAL)
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
