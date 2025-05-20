# Function: <code>vfio_unregister_notifier</code>

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
int vfio_unregister_notifier(struct device *dev, enum vfio_notify_type type, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d1310)
Location: drivers/vfio/vfio.c:2156
Inline: False
```
**Symbols:**

```
ffffffff817d1310-ffffffff817d13e2: vfio_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_unregister_notifier(struct device *dev, enum vfio_notify_type type, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189c2f0)
Location: drivers/vfio/vfio.c:2320
Inline: False
```
**Symbols:**

```
ffffffff8189c2f0-ffffffff8189c3ff: vfio_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_unregister_notifier(struct device *dev, enum vfio_notify_type type, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818aaf00)
Location: drivers/vfio/vfio.c:2326
Inline: False
```
**Symbols:**

```
ffffffff818aaf00-ffffffff818ab00f: vfio_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_unregister_notifier(struct device *dev, enum vfio_notify_type type, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188e640)
Location: drivers/vfio/vfio.c:2225
Inline: False
```
**Symbols:**

```
ffffffff8188e640-ffffffff8188e74f: vfio_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_unregister_notifier(struct device *dev, enum vfio_notify_type type, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81921c80)
Location: drivers/vfio/vfio.c:2332
Inline: False
```
**Symbols:**

```
ffffffff81921c80-ffffffff81921d8f: vfio_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_unregister_notifier(struct vfio_device *device, enum vfio_notify_type type, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a76b30)
Location: drivers/vfio/vfio.c:2096
Inline: False
```
**Symbols:**

```
ffffffff81a76b30-ffffffff81a76bbd: vfio_unregister_notifier (STB_GLOBAL)
```
</details>
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
int vfio_unregister_notifier(struct device *dev, enum vfio_notify_type type, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000ab0050)
Location: drivers/vfio/vfio.c:2156
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvdia_v100_nvlink2_init
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvgpu_release
```
**Symbols:**

```
c000000000ab0050-c000000000ab0194: vfio_unregister_notifier (STB_GLOBAL)
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
int vfio_unregister_notifier(struct device *dev, enum vfio_notify_type type, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177b3c0)
Location: drivers/vfio/vfio.c:2156
Inline: False
```
**Symbols:**

```
ffffffff8177b3c0-ffffffff8177b492: vfio_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_unregister_notifier(struct device *dev, enum vfio_notify_type type, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c6190)
Location: drivers/vfio/vfio.c:2156
Inline: False
```
**Symbols:**

```
ffffffff817c6190-ffffffff817c6262: vfio_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_unregister_notifier(struct device *dev, enum vfio_notify_type type, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817e0430)
Location: drivers/vfio/vfio.c:2156
Inline: False
```
**Symbols:**

```
ffffffff817e0430-ffffffff817e0502: vfio_unregister_notifier (STB_GLOBAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vfio_device *device</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
</ul>
</details>
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
