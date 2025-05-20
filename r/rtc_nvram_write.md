# Function: <code>rtc_nvram_write</code>

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
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff8171b3a0)
Location: drivers/rtc/nvmem.c:38
Inline: False
```
**Symbols:**

```
ffffffff8171b3a0-ffffffff8171b405: rtc_nvram_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff8178c640)
Location: drivers/rtc/nvmem.c:38
Inline: False
```
**Symbols:**

```
ffffffff8178c640-ffffffff8178c6a5: rtc_nvram_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff817cec90)
Location: drivers/rtc/nvmem.c:36
Inline: False
```
**Symbols:**

```
ffffffff817cec90-ffffffff817cecf7: rtc_nvram_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff817f5dc0)
Location: drivers/rtc/nvmem.c:35
Inline: False
```
**Symbols:**

```
ffffffff817f5dc0-ffffffff817f5e23: rtc_nvram_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:32
Inline: False
```
**Symbols:**

```
ffffffff81836ac0-ffffffff81836af6: rtc_nvram_write (STB_LOCAL)
ffffffff81836c5d-ffffffff81836c90: rtc_nvram_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:32
Inline: False
```
**Symbols:**

```
ffffffff81868430-ffffffff81868466: rtc_nvram_write (STB_LOCAL)
ffffffff818685cd-ffffffff81868600: rtc_nvram_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:32
Inline: False
```
**Symbols:**

```
ffffffff8193c020-ffffffff8193c055: rtc_nvram_write (STB_LOCAL)
ffffffff8193c1c0-ffffffff8193c1f3: rtc_nvram_write.cold (STB_LOCAL)
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
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffff800010aaa140)
Location: drivers/rtc/nvmem.c:32
Inline: False
```
**Symbols:**

```
ffff800010aaa140-ffff800010aaa1c4: rtc_nvram_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (c0b88f34)
Location: drivers/rtc/nvmem.c:32
Inline: False
```
**Symbols:**

```
c0b88f34-c0b88fa8: rtc_nvram_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (c000000000b8c420)
Location: drivers/rtc/nvmem.c:32
Inline: False
```
**Symbols:**

```
c000000000b8c420-c000000000b8c4b8: rtc_nvram_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffe0006b566a)
Location: drivers/rtc/nvmem.c:32
Inline: False
```
**Symbols:**

```
ffffffe0006b566a-ffffffe0006b56de: rtc_nvram_write (STB_LOCAL)
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
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:32
Inline: False
```
**Symbols:**

```
ffffffff8181b0e0-ffffffff8181b116: rtc_nvram_write (STB_LOCAL)
ffffffff8181b27d-ffffffff8181b2b0: rtc_nvram_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:32
Inline: False
```
**Symbols:**

```
ffffffff817e27d0-ffffffff817e2806: rtc_nvram_write (STB_LOCAL)
ffffffff817e296d-ffffffff817e29a0: rtc_nvram_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:32
Inline: False
```
**Symbols:**

```
ffffffff8185c5c0-ffffffff8185c5f6: rtc_nvram_write (STB_LOCAL)
ffffffff8185c75d-ffffffff8185c790: rtc_nvram_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t rtc_nvram_write(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:32
Inline: False
```
**Symbols:**

```
ffffffff81877840-ffffffff81877876: rtc_nvram_write (STB_LOCAL)
ffffffff818779dd-ffffffff81877a10: rtc_nvram_write.cold (STB_LOCAL)
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
