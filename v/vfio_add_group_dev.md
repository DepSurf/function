# Function: <code>vfio_add_group_dev</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfio_add_group_dev(struct device *dev, const struct vfio_device_ops *ops, void *device_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d16c0)
Location: drivers/vfio/vfio.c:800
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff817d16c0-ffffffff817d1ab9: vfio_add_group_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_add_group_dev(struct device *dev, const struct vfio_device_ops *ops, void *device_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189c9b0)
Location: drivers/vfio/vfio.c:803
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff8189c9b0-ffffffff8189cbcc: vfio_add_group_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_add_group_dev(struct device *dev, const struct vfio_device_ops *ops, void *device_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818ab5e0)
Location: drivers/vfio/vfio.c:804
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff818ab5e0-ffffffff818ab7fc: vfio_add_group_dev (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfio_add_group_dev(struct device *dev, const struct vfio_device_ops *ops, void *device_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000ab0f30)
Location: drivers/vfio/vfio.c:800
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
c000000000ab0f30-c000000000ab1460: vfio_add_group_dev (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfio_add_group_dev(struct device *dev, const struct vfio_device_ops *ops, void *device_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177b770)
Location: drivers/vfio/vfio.c:800
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff8177b770-ffffffff8177bb69: vfio_add_group_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_add_group_dev(struct device *dev, const struct vfio_device_ops *ops, void *device_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c6540)
Location: drivers/vfio/vfio.c:800
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff817c6540-ffffffff817c6939: vfio_add_group_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_add_group_dev(struct device *dev, const struct vfio_device_ops *ops, void *device_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817e07e0)
Location: drivers/vfio/vfio.c:800
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff817e07e0-ffffffff817e0bd9: vfio_add_group_dev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
