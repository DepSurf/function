# Function: <code>coredump_store</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816823c0)
Location: drivers/base/dd.c:289
Inline: False
```
**Symbols:**

```
ffffffff816823c0-ffffffff81682405: coredump_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816a1e60)
Location: drivers/base/dd.c:354
Inline: False
```
**Symbols:**

```
ffffffff816a1e60-ffffffff816a1ea5: coredump_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816dac20)
Location: drivers/base/dd.c:397
Inline: False
```
**Symbols:**

```
ffffffff816dac20-ffffffff816dac68: coredump_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816febe0)
Location: drivers/base/dd.c:397
Inline: False
```
**Symbols:**

```
ffffffff816febe0-ffffffff816fec28: coredump_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b8840)
Location: drivers/base/dd.c:366
Inline: False
```
**Symbols:**

```
ffffffff817b8840-ffffffff817b888b: coredump_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff817cd500)
Location: drivers/base/dd.c:390
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:104
Inline: False
```
**Symbols:**

```
ffffffff817cd500-ffffffff817cd54b: coredump_store (STB_LOCAL)
ffffffff819cc380-ffffffff819cc413: coredump_store (STB_LOCAL)
ffffffff81c2eda2-ffffffff81c2edd5: coredump_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff817b0e80)
Location: drivers/base/dd.c:404
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:104
Inline: False
```
**Symbols:**

```
ffffffff817b0e80-ffffffff817b0ecb: coredump_store (STB_LOCAL)
ffffffff819b1480-ffffffff819b1509: coredump_store (STB_LOCAL)
ffffffff81c21078-ffffffff81c210ab: coredump_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff8183a0c0)
Location: drivers/base/dd.c:404
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:104
Inline: False
```
**Symbols:**

```
ffffffff8183a0c0-ffffffff8183a10b: coredump_store (STB_LOCAL)
ffffffff81a5fb80-ffffffff81a5fc09: coredump_store (STB_LOCAL)
ffffffff81d32a53-ffffffff81d32a86: coredump_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (ffffffff8197c790)
Location: drivers/base/dd.c:418
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:104
Inline: False
```
**Symbols:**

```
ffffffff8197c790-ffffffff8197c7e0: coredump_store (STB_LOCAL)
ffffffff81bcff30-ffffffff81bcffbf: coredump_store (STB_LOCAL)
ffffffff81efef1b-ffffffff81efef4e: coredump_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81ae9930)
Location: drivers/base/dd.c:423
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81d7b0c0)
Location: drivers/remoteproc/remoteproc_sysfs.c:104
Inline: False
```
**Symbols:**

```
ffffffff81ae9930-ffffffff81ae9980: coredump_store (STB_LOCAL)
ffffffff81d7b0c0-ffffffff81d7b170: coredump_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81b37c00)
Location: drivers/base/dd.c:424
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81de9280)
Location: drivers/remoteproc/remoteproc_sysfs.c:104
Inline: False
```
**Symbols:**

```
ffffffff81b37c00-ffffffff81b37c50: coredump_store (STB_LOCAL)
ffffffff81de9280-ffffffff81de9330: coredump_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81b8f6a0)
Location: drivers/base/dd.c:424
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81e9f4c0)
Location: drivers/remoteproc/remoteproc_sysfs.c:104
Inline: False
```
**Symbols:**

```
ffffffff81b8f6a0-ffffffff81b8f6f0: coredump_store (STB_LOCAL)
ffffffff81e9f4c0-ffffffff81e9f570: coredump_store (STB_LOCAL)
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
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108e9b60)
Location: drivers/base/dd.c:397
Inline: False
```
**Symbols:**

```
ffff8000108e9b60-ffff8000108e9bb8: coredump_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d7c10)
Location: drivers/base/dd.c:397
Inline: False
```
**Symbols:**

```
c09d7c10-c09d7c58: coredump_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c0000000009808b0)
Location: drivers/base/dd.c:397
Inline: False
```
**Symbols:**

```
c0000000009808b0-c000000000980938: coredump_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057da8c)
Location: drivers/base/dd.c:397
Inline: False
```
**Symbols:**

```
ffffffe00057da8c-ffffffe00057dad8: coredump_store (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816c43d0)
Location: drivers/base/dd.c:397
Inline: False
```
**Symbols:**

```
ffffffff816c43d0-ffffffff816c4418: coredump_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8169f680)
Location: drivers/base/dd.c:397
Inline: False
```
**Symbols:**

```
ffffffff8169f680-ffffffff8169f6c8: coredump_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816f28a0)
Location: drivers/base/dd.c:397
Inline: False
```
**Symbols:**

```
ffffffff816f28a0-ffffffff816f28e8: coredump_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t coredump_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8170d0e0)
Location: drivers/base/dd.c:397
Inline: False
```
**Symbols:**

```
ffffffff8170d0e0-ffffffff8170d128: coredump_store (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
