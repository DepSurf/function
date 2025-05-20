# Function: <code>vp_legacy_get_status</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
u8 vp_legacy_get_status(struct virtio_pci_legacy_device *ldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_legacy_dev.c (ffffffff818c1500)
Location: drivers/virtio/virtio_pci_legacy_dev.c:121
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
```
**Symbols:**

```
ffffffff818c1500-ffffffff818c151e: vp_legacy_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u8 vp_legacy_get_status(struct virtio_pci_legacy_device *ldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_legacy_dev.c (ffffffff81a11340)
Location: drivers/virtio/virtio_pci_legacy_dev.c:121
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
```
**Symbols:**

```
ffffffff81a11340-ffffffff81a1135e: vp_legacy_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u8 vp_legacy_get_status(struct virtio_pci_legacy_device *ldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_legacy_dev.c (ffffffff81a5a310)
Location: drivers/virtio/virtio_pci_legacy_dev.c:121
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
```
**Symbols:**

```
ffffffff81a5a310-ffffffff81a5a32e: vp_legacy_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u8 vp_legacy_get_status(struct virtio_pci_legacy_device *ldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_legacy_dev.c (ffffffff81aab750)
Location: drivers/virtio/virtio_pci_legacy_dev.c:121
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
```
**Symbols:**

```
ffffffff81aab750-ffffffff81aab76e: vp_legacy_get_status (STB_GLOBAL)
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
