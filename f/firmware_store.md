# Function: <code>firmware_store</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t firmware_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:22
Inline: False
```
**Symbols:**

```
ffffffff818f6ab0-ffffffff818f6b5a: firmware_store (STB_LOCAL)
ffffffff818f6b95-ffffffff818f6bfd: firmware_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t firmware_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:23
Inline: False
```
**Symbols:**

```
ffffffff819ccbe0-ffffffff819ccc8a: firmware_store (STB_LOCAL)
ffffffff819cccc5-ffffffff819ccd2d: firmware_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t firmware_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff819cc4c0)
Location: drivers/remoteproc/remoteproc_sysfs.c:152
Inline: False
```
**Symbols:**

```
ffffffff819cc4c0-ffffffff819cc4eb: firmware_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t firmware_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff819b1600)
Location: drivers/remoteproc/remoteproc_sysfs.c:149
Inline: False
```
**Symbols:**

```
ffffffff819b1600-ffffffff819b162b: firmware_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t firmware_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81a5fd00)
Location: drivers/remoteproc/remoteproc_sysfs.c:149
Inline: False
```
**Symbols:**

```
ffffffff81a5fd00-ffffffff81a5fd2b: firmware_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t firmware_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81bd0080)
Location: drivers/remoteproc/remoteproc_sysfs.c:149
Inline: False
```
**Symbols:**

```
ffffffff81bd0080-ffffffff81bd00b7: firmware_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t firmware_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81d7b280)
Location: drivers/remoteproc/remoteproc_sysfs.c:149
Inline: False
```
**Symbols:**

```
ffffffff81d7b280-ffffffff81d7b2b7: firmware_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t firmware_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81de9440)
Location: drivers/remoteproc/remoteproc_sysfs.c:149
Inline: False
```
**Symbols:**

```
ffffffff81de9440-ffffffff81de9477: firmware_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t firmware_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81e9f680)
Location: drivers/remoteproc/remoteproc_sysfs.c:149
Inline: False
```
**Symbols:**

```
ffffffff81e9f680-ffffffff81e9f6b7: firmware_store (STB_LOCAL)
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
ssize_t firmware_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (ffff800010b82cc8)
Location: drivers/remoteproc/remoteproc_sysfs.c:22
Inline: False
```
**Symbols:**

```
ffff800010b82cc8-ffff800010b82dd8: firmware_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t firmware_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (c0c66030)
Location: drivers/remoteproc/remoteproc_sysfs.c:22
Inline: False
```
**Symbols:**

```
c0c66030-c0c6612c: firmware_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t firmware_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (c000000000c5fe50)
Location: drivers/remoteproc/remoteproc_sysfs.c:22
Inline: False
```
**Symbols:**

```
c000000000c5fe50-c000000000c5ffc4: firmware_store (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t firmware_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:22
Inline: False
```
**Symbols:**

```
ffffffff81897de0-ffffffff81897e8a: firmware_store (STB_LOCAL)
ffffffff81897ec5-ffffffff81897f2d: firmware_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t firmware_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_sysfs.c (0)
Location: drivers/remoteproc/remoteproc_sysfs.c:22
Inline: False
```
**Symbols:**

```
ffffffff81908540-ffffffff819085ea: firmware_store (STB_LOCAL)
ffffffff81908625-ffffffff8190868d: firmware_store.cold (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
