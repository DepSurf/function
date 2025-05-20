# Function: <code>vp_legacy_probe</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vp_legacy_probe(struct virtio_pci_legacy_device *ldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_legacy_dev.c (0)
Location: drivers/virtio/virtio_pci_legacy_dev.c:16
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff81ebcfaf-ffffffff81ebcfc3: vp_legacy_probe.cold (STB_LOCAL)
ffffffff818c16c0-ffffffff818c17c0: vp_legacy_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vp_legacy_probe(struct virtio_pci_legacy_device *ldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_legacy_dev.c (ffffffff81a11570)
Location: drivers/virtio/virtio_pci_legacy_dev.c:16
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff81a11570-ffffffff81a11680: vp_legacy_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vp_legacy_probe(struct virtio_pci_legacy_device *ldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_legacy_dev.c (ffffffff81a5a540)
Location: drivers/virtio/virtio_pci_legacy_dev.c:16
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff81a5a540-ffffffff81a5a650: vp_legacy_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vp_legacy_probe(struct virtio_pci_legacy_device *ldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_legacy_dev.c (ffffffff81aab980)
Location: drivers/virtio/virtio_pci_legacy_dev.c:16
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe
```
**Symbols:**

```
ffffffff81aab980-ffffffff81aaba90: vp_legacy_probe (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
