# Function: <code>pci_write_resource_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8143bce0)
Location: drivers/pci/pci-sysfs.c:1114
Inline: False
```
**Symbols:**

```
ffffffff8143bce0-ffffffff8143bd49: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81488490)
Location: drivers/pci/pci-sysfs.c:1112
Inline: False
```
**Symbols:**

```
ffffffff81488490-ffffffff814884e8: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814a9c70)
Location: drivers/pci/pci-sysfs.c:1114
Inline: False
```
**Symbols:**

```
ffffffff814a9c70-ffffffff814a9cc8: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814b3f60)
Location: drivers/pci/pci-sysfs.c:1263
Inline: False
```
**Symbols:**

```
ffffffff814b3f60-ffffffff814b402a: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814f3750)
Location: drivers/pci/pci-sysfs.c:1298
Inline: False
```
**Symbols:**

```
ffffffff814f3750-ffffffff814f3836: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81523970)
Location: drivers/pci/pci-sysfs.c:1248
Inline: False
```
**Symbols:**

```
ffffffff81523970-ffffffff81523a5f: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff815397d0)
Location: drivers/pci/pci-sysfs.c:1247
Inline: False
```
**Symbols:**

```
ffffffff815397d0-ffffffff815398bf: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff815690f0)
Location: drivers/pci/pci-sysfs.c:1248
Inline: False
```
**Symbols:**

```
ffffffff815690f0-ffffffff815691de: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8158a150)
Location: drivers/pci/pci-sysfs.c:1101
Inline: True
```
**Symbols:**

```
ffffffff8158a150-ffffffff8158a207: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81631240)
Location: drivers/pci/pci-sysfs.c:1086
Inline: True
```
**Symbols:**

```
ffffffff81631240-ffffffff816312fa: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff816568e0)
Location: drivers/pci/pci-sysfs.c:1097
Inline: True
```
**Symbols:**

```
ffffffff816568e0-ffffffff8165699a: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81639500)
Location: drivers/pci/pci-sysfs.c:1125
Inline: True
```
**Symbols:**

```
ffffffff81639500-ffffffff816395ba: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff816a99c0)
Location: drivers/pci/pci-sysfs.c:1125
Inline: True
```
**Symbols:**

```
ffffffff816a99c0-ffffffff816a9af0: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff817cc440)
Location: drivers/pci/pci-sysfs.c:1120
Inline: True
```
**Symbols:**

```
ffffffff817cc440-ffffffff817cc586: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff818ea660)
Location: drivers/pci/pci-sysfs.c:1128
Inline: True
```
**Symbols:**

```
ffffffff818ea660-ffffffff818ea7a6: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8192dbe0)
Location: drivers/pci/pci-sysfs.c:1128
Inline: True
```
**Symbols:**

```
ffffffff8192dbe0-ffffffff8192dd17: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81976560)
Location: drivers/pci/pci-sysfs.c:1145
Inline: True
```
**Symbols:**

```
ffffffff81976560-ffffffff81976697: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffff8000106eeca0)
Location: drivers/pci/pci-sysfs.c:1101
Inline: True
```
**Symbols:**

```
ffff8000106eeca0-ffff8000106eed7c: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (c0889aa0)
Location: drivers/pci/pci-sysfs.c:1101
Inline: True
```
**Symbols:**

```
c0889aa0-c0889b84: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (c00000000086b4c0)
Location: drivers/pci/pci-sysfs.c:1101
Inline: True
```
**Symbols:**

```
c00000000086b4c0-c00000000086b6b0: pci_write_resource_io (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8157dfe0)
Location: drivers/pci/pci-sysfs.c:1101
Inline: True
```
**Symbols:**

```
ffffffff8157dfe0-ffffffff8157e097: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8156cdb0)
Location: drivers/pci/pci-sysfs.c:1101
Inline: True
```
**Symbols:**

```
ffffffff8156cdb0-ffffffff8156ce67: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8157dea0)
Location: drivers/pci/pci-sysfs.c:1101
Inline: True
```
**Symbols:**

```
ffffffff8157dea0-ffffffff8157df57: pci_write_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t pci_write_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81598350)
Location: drivers/pci/pci-sysfs.c:1101
Inline: True
```
**Symbols:**

```
ffffffff81598350-ffffffff81598407: pci_write_resource_io (STB_LOCAL)
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
