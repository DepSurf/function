# Function: <code>i2c_sysfs_delete_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81679130)
Location: drivers/i2c/i2c-core.c:1265
Inline: False
```
**Symbols:**

```
ffffffff81679130-ffffffff8167930c: i2c_sysfs_delete_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816da440)
Location: drivers/i2c/i2c-core.c:1433
Inline: False
```
**Symbols:**

```
ffffffff816da440-ffffffff816da61a: i2c_sysfs_delete_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170aa10)
Location: drivers/i2c/i2c-core.c:1569
Inline: False
```
**Symbols:**

```
ffffffff8170aa10-ffffffff8170abea: i2c_sysfs_delete_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8171f1c0)
Location: drivers/i2c/i2c-core-base.c:1015
Inline: False
```
**Symbols:**

```
ffffffff8171f1c0-ffffffff8171f396: i2c_sysfs_delete_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81790eb0)
Location: drivers/i2c/i2c-core-base.c:1032
Inline: False
```
**Symbols:**

```
ffffffff81790eb0-ffffffff8179108b: i2c_sysfs_delete_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d38f0)
Location: drivers/i2c/i2c-core-base.c:1011
Inline: False
```
**Symbols:**

```
ffffffff817d38f0-ffffffff817d3acb: i2c_sysfs_delete_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fab80)
Location: drivers/i2c/i2c-core-base.c:1023
Inline: False
```
**Symbols:**

```
ffffffff817fab80-ffffffff817fad5b: i2c_sysfs_delete_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1112
Inline: False
```
**Symbols:**

```
ffffffff8183b900-ffffffff8183b9e9: i2c_sysfs_delete_device (STB_LOCAL)
ffffffff8183d8e8-ffffffff8183d9ef: i2c_sysfs_delete_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1117
Inline: False
```
**Symbols:**

```
ffffffff8186d290-ffffffff8186d379: i2c_sysfs_delete_device (STB_LOCAL)
ffffffff8186f2d8-ffffffff8186f3df: i2c_sysfs_delete_device.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab05f8)
Location: drivers/i2c/i2c-core-base.c:1117
Inline: False
```
**Symbols:**

```
ffff800010ab05f8-ffff800010ab07ec: i2c_sysfs_delete_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b91b48)
Location: drivers/i2c/i2c-core-base.c:1117
Inline: False
```
**Symbols:**

```
c0b91b48-c0b91d10: i2c_sysfs_delete_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b93570)
Location: drivers/i2c/i2c-core-base.c:1117
Inline: False
```
**Symbols:**

```
c000000000b93570-c000000000b937cc: i2c_sysfs_delete_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b8746)
Location: drivers/i2c/i2c-core-base.c:1117
Inline: False
```
**Symbols:**

```
ffffffe0006b8746-ffffffe0006b88d6: i2c_sysfs_delete_device (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1117
Inline: False
```
**Symbols:**

```
ffffffff81861420-ffffffff81861509: i2c_sysfs_delete_device (STB_LOCAL)
ffffffff81863468-ffffffff8186356f: i2c_sysfs_delete_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t i2c_sysfs_delete_device(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1117
Inline: False
```
**Symbols:**

```
ffffffff8187c630-ffffffff8187c719: i2c_sysfs_delete_device (STB_LOCAL)
ffffffff8187e6c8-ffffffff8187e7cf: i2c_sysfs_delete_device.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
