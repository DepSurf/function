# Function: <code>raw_table_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff816cef50)
Location: drivers/firmware/dmi_scan.c:654
Inline: False
```
**Symbols:**

```
ffffffff816cef50-ffffffff816cef75: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff817322b0)
Location: drivers/firmware/dmi_scan.c:676
Inline: False
```
**Symbols:**

```
ffffffff817322b0-ffffffff817322d5: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81765280)
Location: drivers/firmware/dmi_scan.c:676
Inline: False
```
**Symbols:**

```
ffffffff81765280-ffffffff817652a5: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81783aa0)
Location: drivers/firmware/dmi_scan.c:701
Inline: False
```
**Symbols:**

```
ffffffff81783aa0-ffffffff81783ac5: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff817f9e70)
Location: drivers/firmware/dmi_scan.c:701
Inline: False
```
**Symbols:**

```
ffffffff817f9e70-ffffffff817f9e95: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81843520)
Location: drivers/firmware/dmi_scan.c:708
Inline: False
```
**Symbols:**

```
ffffffff81843520-ffffffff81843545: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff8186f530)
Location: drivers/firmware/dmi_scan.c:708
Inline: False
```
**Symbols:**

```
ffffffff8186f530-ffffffff8186f555: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818b3890)
Location: drivers/firmware/dmi_scan.c:706
Inline: False
```
**Symbols:**

```
ffffffff818b3890-ffffffff818b38b7: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818e61b0)
Location: drivers/firmware/dmi_scan.c:706
Inline: False
```
```
In drivers/firmware/efi/rci2-table.c (ffffffff818ee320)
Location: drivers/firmware/efi/rci2-table.c:43
Inline: False
```
**Symbols:**

```
ffffffff818e61b0-ffffffff818e61d7: raw_table_read (STB_LOCAL)
ffffffff818ee320-ffffffff818ee347: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff819b9500)
Location: drivers/firmware/dmi_scan.c:742
Inline: False
```
```
In drivers/firmware/efi/rci2-table.c (ffffffff819c1df0)
Location: drivers/firmware/efi/rci2-table.c:43
Inline: False
```
**Symbols:**

```
ffffffff819b9500-ffffffff819b9529: raw_table_read (STB_LOCAL)
ffffffff819c1df0-ffffffff819c1e19: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff819bb970)
Location: drivers/firmware/dmi_scan.c:742
Inline: False
```
```
In drivers/firmware/efi/rci2-table.c (ffffffff819c2850)
Location: drivers/firmware/efi/rci2-table.c:43
Inline: False
```
**Symbols:**

```
ffffffff819bb970-ffffffff819bb999: raw_table_read (STB_LOCAL)
ffffffff819c2850-ffffffff819c2879: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff819a0180)
Location: drivers/firmware/dmi_scan.c:743
Inline: False
```
```
In drivers/firmware/efi/rci2-table.c (ffffffff819a6c90)
Location: drivers/firmware/efi/rci2-table.c:43
Inline: False
```
**Symbols:**

```
ffffffff819a0180-ffffffff819a01a9: raw_table_read (STB_LOCAL)
ffffffff819a6c90-ffffffff819a6cb9: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81a4ce50)
Location: drivers/firmware/dmi_scan.c:743
Inline: False
```
```
In drivers/firmware/efi/rci2-table.c (ffffffff81a54030)
Location: drivers/firmware/efi/rci2-table.c:43
Inline: False
```
**Symbols:**

```
ffffffff81a4ce50-ffffffff81a4ce79: raw_table_read (STB_LOCAL)
ffffffff81a54030-ffffffff81a54059: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81bbb650)
Location: drivers/firmware/dmi_scan.c:743
Inline: False
```
```
In drivers/firmware/efi/rci2-table.c (ffffffff81bc3520)
Location: drivers/firmware/efi/rci2-table.c:43
Inline: False
```
**Symbols:**

```
ffffffff81bbb650-ffffffff81bbb68a: raw_table_read (STB_LOCAL)
ffffffff81bc3520-ffffffff81bc355a: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81d61230)
Location: drivers/firmware/dmi_scan.c:749
Inline: False
```
```
In drivers/firmware/efi/rci2-table.c (ffffffff81d68130)
Location: drivers/firmware/efi/rci2-table.c:43
Inline: False
```
**Symbols:**

```
ffffffff81d61230-ffffffff81d6126a: raw_table_read (STB_LOCAL)
ffffffff81d68130-ffffffff81d6816a: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81dcc2f0)
Location: drivers/firmware/dmi_scan.c:749
Inline: False
```
```
In drivers/firmware/efi/rci2-table.c (ffffffff81dd3280)
Location: drivers/firmware/efi/rci2-table.c:43
Inline: False
```
**Symbols:**

```
ffffffff81dcc2f0-ffffffff81dcc32a: raw_table_read (STB_LOCAL)
ffffffff81dd3280-ffffffff81dd32ba: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81e84e30)
Location: drivers/firmware/dmi_scan.c:749
Inline: False
```
```
In drivers/firmware/efi/rci2-table.c (ffffffff81e8b290)
Location: drivers/firmware/efi/rci2-table.c:43
Inline: False
```
**Symbols:**

```
ffffffff81e84e30-ffffffff81e84e6a: raw_table_read (STB_LOCAL)
ffffffff81e8b290-ffffffff81e8b2ca: raw_table_read (STB_LOCAL)
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
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffff800010b4d8d0)
Location: drivers/firmware/dmi_scan.c:706
Inline: False
```
**Symbols:**

```
ffff800010b4d8d0-ffff800010b4d920: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (c0c349b8)
Location: drivers/firmware/dmi_scan.c:706
Inline: False
```
**Symbols:**

```
c0c349b8-c0c349f0: raw_table_read (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81888f30)
Location: drivers/firmware/dmi_scan.c:706
Inline: False
```
**Symbols:**

```
ffffffff81888f30-ffffffff81888f57: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818408b0)
Location: drivers/firmware/dmi_scan.c:706
Inline: False
```
```
In drivers/firmware/efi/rci2-table.c (ffffffff818489b0)
Location: drivers/firmware/efi/rci2-table.c:43
Inline: False
```
**Symbols:**

```
ffffffff818408b0-ffffffff818408d7: raw_table_read (STB_LOCAL)
ffffffff818489b0-ffffffff818489d7: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818db010)
Location: drivers/firmware/dmi_scan.c:706
Inline: False
```
**Symbols:**

```
ffffffff818db010-ffffffff818db037: raw_table_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t raw_table_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff818f7b30)
Location: drivers/firmware/dmi_scan.c:706
Inline: False
```
```
In drivers/firmware/efi/rci2-table.c (ffffffff818ffdc0)
Location: drivers/firmware/efi/rci2-table.c:43
Inline: False
```
**Symbols:**

```
ffffffff818f7b30-ffffffff818f7b57: raw_table_read (STB_LOCAL)
ffffffff818ffdc0-ffffffff818ffde7: raw_table_read (STB_LOCAL)
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
