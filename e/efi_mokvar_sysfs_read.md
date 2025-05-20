# Function: <code>efi_mokvar_sysfs_read</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t efi_mokvar_sysfs_read(struct file *file, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff819c2910)
Location: drivers/firmware/efi/mokvar-table.c:265
Inline: False
```
**Symbols:**

```
ffffffff819c2910-ffffffff819c2976: efi_mokvar_sysfs_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t efi_mokvar_sysfs_read(struct file *file, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff819a6d50)
Location: drivers/firmware/efi/mokvar-table.c:268
Inline: False
```
**Symbols:**

```
ffffffff819a6d50-ffffffff819a6db6: efi_mokvar_sysfs_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t efi_mokvar_sysfs_read(struct file *file, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff81a54100)
Location: drivers/firmware/efi/mokvar-table.c:268
Inline: False
```
**Symbols:**

```
ffffffff81a54100-ffffffff81a54166: efi_mokvar_sysfs_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t efi_mokvar_sysfs_read(struct file *file, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff81bc35f0)
Location: drivers/firmware/efi/mokvar-table.c:268
Inline: False
```
**Symbols:**

```
ffffffff81bc35f0-ffffffff81bc3666: efi_mokvar_sysfs_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t efi_mokvar_sysfs_read(struct file *file, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff81d68230)
Location: drivers/firmware/efi/mokvar-table.c:268
Inline: False
```
**Symbols:**

```
ffffffff81d68230-ffffffff81d682a6: efi_mokvar_sysfs_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t efi_mokvar_sysfs_read(struct file *file, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff81dd3380)
Location: drivers/firmware/efi/mokvar-table.c:268
Inline: False
```
**Symbols:**

```
ffffffff81dd3380-ffffffff81dd33f6: efi_mokvar_sysfs_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t efi_mokvar_sysfs_read(struct file *file, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff81e8b390)
Location: drivers/firmware/efi/mokvar-table.c:268
Inline: False
```
**Symbols:**

```
ffffffff81e8b390-ffffffff81e8b406: efi_mokvar_sysfs_read (STB_LOCAL)
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
