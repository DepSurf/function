# Function: <code>rtc_nvram_read</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff8171b410)
Location: drivers/rtc/nvmem.c:26
Inline: False
```
**Symbols:**

```
ffffffff8171b410-ffffffff8171b475: rtc_nvram_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff8178c6b0)
Location: drivers/rtc/nvmem.c:26
Inline: False
```
**Symbols:**

```
ffffffff8178c6b0-ffffffff8178c715: rtc_nvram_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff817ced00)
Location: drivers/rtc/nvmem.c:24
Inline: False
```
**Symbols:**

```
ffffffff817ced00-ffffffff817ced67: rtc_nvram_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff817f5e30)
Location: drivers/rtc/nvmem.c:25
Inline: False
```
**Symbols:**

```
ffffffff817f5e30-ffffffff817f5e93: rtc_nvram_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:22
Inline: False
```
**Symbols:**

```
ffffffff81836b00-ffffffff81836b36: rtc_nvram_read (STB_LOCAL)
ffffffff81836c90-ffffffff81836cc3: rtc_nvram_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:22
Inline: False
```
**Symbols:**

```
ffffffff81868470-ffffffff818684a6: rtc_nvram_read (STB_LOCAL)
ffffffff81868600-ffffffff81868633: rtc_nvram_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:22
Inline: False
```
**Symbols:**

```
ffffffff8193c060-ffffffff8193c095: rtc_nvram_read (STB_LOCAL)
ffffffff8193c1f3-ffffffff8193c226: rtc_nvram_read.cold (STB_LOCAL)
```
</details>
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
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffff800010aaa1c8)
Location: drivers/rtc/nvmem.c:22
Inline: False
```
**Symbols:**

```
ffff800010aaa1c8-ffff800010aaa250: rtc_nvram_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (c0b88fa8)
Location: drivers/rtc/nvmem.c:22
Inline: False
```
**Symbols:**

```
c0b88fa8-c0b8901c: rtc_nvram_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (c000000000b8c4c0)
Location: drivers/rtc/nvmem.c:22
Inline: False
```
**Symbols:**

```
c000000000b8c4c0-c000000000b8c558: rtc_nvram_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffe0006b56de)
Location: drivers/rtc/nvmem.c:22
Inline: False
```
**Symbols:**

```
ffffffe0006b56de-ffffffe0006b5752: rtc_nvram_read (STB_LOCAL)
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
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:22
Inline: False
```
**Symbols:**

```
ffffffff8181b120-ffffffff8181b156: rtc_nvram_read (STB_LOCAL)
ffffffff8181b2b0-ffffffff8181b2e3: rtc_nvram_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:22
Inline: False
```
**Symbols:**

```
ffffffff817e2810-ffffffff817e2846: rtc_nvram_read (STB_LOCAL)
ffffffff817e29a0-ffffffff817e29d3: rtc_nvram_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:22
Inline: False
```
**Symbols:**

```
ffffffff8185c600-ffffffff8185c636: rtc_nvram_read (STB_LOCAL)
ffffffff8185c790-ffffffff8185c7c3: rtc_nvram_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t rtc_nvram_read(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:22
Inline: False
```
**Symbols:**

```
ffffffff81877880-ffffffff818778b6: rtc_nvram_read (STB_LOCAL)
ffffffff81877a10-ffffffff81877a43: rtc_nvram_read.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
