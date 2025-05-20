# Function: <code>sriov_numvfs_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8143c320)
Location: drivers/pci/pci-sysfs.c:465
Inline: False
```
**Symbols:**

```
ffffffff8143c320-ffffffff8143c44b: sriov_numvfs_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81488160)
Location: drivers/pci/pci-sysfs.c:470
Inline: False
```
**Symbols:**

```
ffffffff81488160-ffffffff8148828b: sriov_numvfs_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814a9940)
Location: drivers/pci/pci-sysfs.c:471
Inline: False
```
**Symbols:**

```
ffffffff814a9940-ffffffff814a9a6b: sriov_numvfs_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814b3cb0)
Location: drivers/pci/pci-sysfs.c:593
Inline: False
```
**Symbols:**

```
ffffffff814b3cb0-ffffffff814b3e29: sriov_numvfs_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814f3490)
Location: drivers/pci/pci-sysfs.c:594
Inline: False
```
**Symbols:**

```
ffffffff814f3490-ffffffff814f3612: sriov_numvfs_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff815236e0)
Location: drivers/pci/pci-sysfs.c:580
Inline: False
```
**Symbols:**

```
ffffffff815236e0-ffffffff81523869: sriov_numvfs_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81539540)
Location: drivers/pci/pci-sysfs.c:579
Inline: False
```
**Symbols:**

```
ffffffff81539540-ffffffff815396c9: sriov_numvfs_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-sysfs.c (0)
Location: drivers/pci/pci-sysfs.c:581
Inline: False
```
**Symbols:**

```
ffffffff81568ec0-ffffffff81568fe8: sriov_numvfs_store (STB_LOCAL)
ffffffff81569986-ffffffff815699e5: sriov_numvfs_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:267
Inline: False
```
**Symbols:**

```
ffffffff815acd00-ffffffff815ace31: sriov_numvfs_store (STB_LOCAL)
ffffffff815ae2b0-ffffffff815ae30f: sriov_numvfs_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:286
Inline: False
```
**Symbols:**

```
ffffffff81655f00-ffffffff81656031: sriov_numvfs_store (STB_LOCAL)
ffffffff81657550-ffffffff816575af: sriov_numvfs_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:287
Inline: False
```
**Symbols:**

```
ffffffff816764a0-ffffffff816765d1: sriov_numvfs_store (STB_LOCAL)
ffffffff81bfdb81-ffffffff81bfdbe0: sriov_numvfs_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:374
Inline: False
```
**Symbols:**

```
ffffffff81658c40-ffffffff81658d71: sriov_numvfs_store (STB_LOCAL)
ffffffff81befa8a-ffffffff81befae9: sriov_numvfs_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:374
Inline: False
```
**Symbols:**

```
ffffffff816cabe0-ffffffff816cad11: sriov_numvfs_store (STB_LOCAL)
ffffffff81ceaea6-ffffffff81ceaf27: sriov_numvfs_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:416
Inline: False
```
**Symbols:**

```
ffffffff817f1150-ffffffff817f129a: sriov_numvfs_store (STB_LOCAL)
ffffffff81eb1eeb-ffffffff81eb1f6b: sriov_numvfs_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff819195b0)
Location: drivers/pci/iov.c:416
Inline: False
```
**Symbols:**

```
ffffffff819195b0-ffffffff8191977a: sriov_numvfs_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8195cbd0)
Location: drivers/pci/iov.c:416
Inline: False
```
**Symbols:**

```
ffffffff8195cbd0-ffffffff8195cd9a: sriov_numvfs_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff819a61f0)
Location: drivers/pci/iov.c:415
Inline: False
```
**Symbols:**

```
ffffffff819a61f0-ffffffff819a63ba: sriov_numvfs_store (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffff800010716b00)
Location: drivers/pci/iov.c:267
Inline: False
```
**Symbols:**

```
ffff800010716b00-ffff800010716c98: sriov_numvfs_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c08a1334)
Location: drivers/pci/iov.c:267
Inline: False
```
**Symbols:**

```
c08a1334-c08a14c0: sriov_numvfs_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c000000000886da0)
Location: drivers/pci/iov.c:267
Inline: False
```
**Symbols:**

```
c000000000886da0-c000000000886fc4: sriov_numvfs_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffe0004dfedc)
Location: drivers/pci/iov.c:267
Inline: False
```
**Symbols:**

```
ffffffe0004dfedc-ffffffe0004e0034: sriov_numvfs_store (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:267
Inline: False
```
**Symbols:**

```
ffffffff815a04d0-ffffffff815a0601: sriov_numvfs_store (STB_LOCAL)
ffffffff815a1a70-ffffffff815a1acf: sriov_numvfs_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:267
Inline: False
```
**Symbols:**

```
ffffffff8158f660-ffffffff8158f791: sriov_numvfs_store (STB_LOCAL)
ffffffff81590c10-ffffffff81590c6f: sriov_numvfs_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:267
Inline: False
```
**Symbols:**

```
ffffffff815a0a50-ffffffff815a0b81: sriov_numvfs_store (STB_LOCAL)
ffffffff815a2000-ffffffff815a205f: sriov_numvfs_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t sriov_numvfs_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/iov.c (0)
Location: drivers/pci/iov.c:267
Inline: False
```
**Symbols:**

```
ffffffff815bae80-ffffffff815bafb1: sriov_numvfs_store (STB_LOCAL)
ffffffff815bc400-ffffffff815bc45f: sriov_numvfs_store.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
