# Function: <code>module_sect_read</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t module_sect_read(struct file *file, struct kobject *kobj, struct bin_attribute *battr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1524
Inline: False
```
**Symbols:**

```
ffffffff811618f0-ffffffff8116199a: module_sect_read (STB_LOCAL)
ffffffff811679e4-ffffffff811679f0: module_sect_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t module_sect_read(struct file *file, struct kobject *kobj, struct bin_attribute *battr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1583
Inline: False
```
**Symbols:**

```
ffffffff8115da00-ffffffff8115daaa: module_sect_read (STB_LOCAL)
ffffffff81be3ef6-ffffffff81be3f02: module_sect_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t module_sect_read(struct file *file, struct kobject *kobj, struct bin_attribute *battr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1493
Inline: False
```
**Symbols:**

```
ffffffff8115eac0-ffffffff8115eb6b: module_sect_read (STB_LOCAL)
ffffffff81bd5da7-ffffffff81bd5db3: module_sect_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t module_sect_read(struct file *file, struct kobject *kobj, struct bin_attribute *battr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1495
Inline: False
```
**Symbols:**

```
ffffffff81183b90-ffffffff81183c3b: module_sect_read (STB_LOCAL)
ffffffff81cb241b-ffffffff81cb2427: module_sect_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t module_sect_read(struct file *file, struct kobject *kobj, struct bin_attribute *battr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/sysfs.c (0)
Location: kernel/module/sysfs.c:34
Inline: False
```
**Symbols:**

```
ffffffff81192200-ffffffff811922d7: module_sect_read (STB_LOCAL)
ffffffff81e61c5b-ffffffff81e61c67: module_sect_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t module_sect_read(struct file *file, struct kobject *kobj, struct bin_attribute *battr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811cf970)
Location: kernel/module/sysfs.c:34
Inline: False
```
**Symbols:**

```
ffffffff811cf970-ffffffff811cfa4f: module_sect_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t module_sect_read(struct file *file, struct kobject *kobj, struct bin_attribute *battr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811e3b10)
Location: kernel/module/sysfs.c:34
Inline: False
```
**Symbols:**

```
ffffffff811e3b10-ffffffff811e3bec: module_sect_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t module_sect_read(struct file *file, struct kobject *kobj, struct bin_attribute *battr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/sysfs.c (ffffffff811f9870)
Location: kernel/module/sysfs.c:34
Inline: False
```
**Symbols:**

```
ffffffff811f9870-ffffffff811f994c: module_sect_read (STB_LOCAL)
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
