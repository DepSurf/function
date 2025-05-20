# Function: <code>vfio_register_notifier</code>

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
int vfio_register_notifier(struct device *dev, enum vfio_notify_type type, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d11e0)
Location: drivers/vfio/vfio.c:2127
Inline: False
```
**Symbols:**

```
ffffffff817d11e0-ffffffff817d130c: vfio_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_register_notifier(struct device *dev, enum vfio_notify_type type, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189beb0)
Location: drivers/vfio/vfio.c:2291
Inline: False
```
**Symbols:**

```
ffffffff8189beb0-ffffffff8189c02f: vfio_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_register_notifier(struct device *dev, enum vfio_notify_type type, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818aaac0)
Location: drivers/vfio/vfio.c:2297
Inline: False
```
**Symbols:**

```
ffffffff818aaac0-ffffffff818aac3f: vfio_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_register_notifier(struct device *dev, enum vfio_notify_type type, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188e180)
Location: drivers/vfio/vfio.c:2196
Inline: False
```
**Symbols:**

```
ffffffff8188e180-ffffffff8188e2ff: vfio_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_register_notifier(struct device *dev, enum vfio_notify_type type, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff819217c0)
Location: drivers/vfio/vfio.c:2303
Inline: False
```
**Symbols:**

```
ffffffff819217c0-ffffffff8192193f: vfio_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_register_notifier(struct vfio_device *device, enum vfio_notify_type type, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff81a76bc0)
Location: drivers/vfio/vfio.c:2074
Inline: False
```
**Symbols:**

```
ffffffff81a76bc0-ffffffff81a76c6b: vfio_register_notifier (STB_GLOBAL)
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
int vfio_register_notifier(struct device *dev, enum vfio_notify_type type, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aafe70)
Location: drivers/vfio/vfio.c:2127
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvdia_v100_nvlink2_init
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvdia_v100_nvlink2_init
```
**Symbols:**

```
c000000000aafe70-c000000000ab0044: vfio_register_notifier (STB_GLOBAL)
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
int vfio_register_notifier(struct device *dev, enum vfio_notify_type type, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177b290)
Location: drivers/vfio/vfio.c:2127
Inline: False
```
**Symbols:**

```
ffffffff8177b290-ffffffff8177b3bc: vfio_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_register_notifier(struct device *dev, enum vfio_notify_type type, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c6060)
Location: drivers/vfio/vfio.c:2127
Inline: False
```
**Symbols:**

```
ffffffff817c6060-ffffffff817c618c: vfio_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_register_notifier(struct device *dev, enum vfio_notify_type type, long unsigned int *events, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817e0300)
Location: drivers/vfio/vfio.c:2127
Inline: False
```
**Symbols:**

```
ffffffff817e0300-ffffffff817e042c: vfio_register_notifier (STB_GLOBAL)
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
