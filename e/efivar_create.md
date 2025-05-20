# Function: <code>efivar_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff816d2c40)
Location: drivers/firmware/efi/efivars.c:414
Inline: False
```
**Symbols:**

```
ffffffff816d2c40-ffffffff816d2e63: efivar_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff81736330)
Location: drivers/firmware/efi/efivars.c:414
Inline: False
```
**Symbols:**

```
ffffffff81736330-ffffffff81736553: efivar_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff817694c0)
Location: drivers/firmware/efi/efivars.c:414
Inline: False
```
**Symbols:**

```
ffffffff817694c0-ffffffff817696e4: efivar_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff81787bd0)
Location: drivers/firmware/efi/efivars.c:414
Inline: False
```
**Symbols:**

```
ffffffff81787bd0-ffffffff81787dae: efivar_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff817fe070)
Location: drivers/firmware/efi/efivars.c:414
Inline: False
```
**Symbols:**

```
ffffffff817fe070-ffffffff817fe24b: efivar_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:414
Inline: False
```
**Symbols:**

```
ffffffff81847800-ffffffff818479d0: efivar_create (STB_LOCAL)
ffffffff81847dca-ffffffff81847dfb: efivar_create.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:406
Inline: False
```
**Symbols:**

```
ffffffff81873aa0-ffffffff81873c68: efivar_create (STB_LOCAL)
ffffffff818741d7-ffffffff81874208: efivar_create.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:350
Inline: False
```
**Symbols:**

```
ffffffff818b7ca0-ffffffff818b7e67: efivar_create (STB_LOCAL)
ffffffff818b83cd-ffffffff818b83fe: efivar_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:364
Inline: False
```
**Symbols:**

```
ffffffff818ea690-ffffffff818ea857: efivar_create (STB_LOCAL)
ffffffff818eadce-ffffffff818eadff: efivar_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:364
Inline: False
```
**Symbols:**

```
ffffffff819bdeb0-ffffffff819be077: efivar_create (STB_LOCAL)
ffffffff819be51d-ffffffff819be54e: efivar_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:362
Inline: False
```
**Symbols:**

```
ffffffff819bfb30-ffffffff819bfcf7: efivar_create (STB_LOCAL)
ffffffff81c2bd05-ffffffff81c2bd36: efivar_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:362
Inline: False
```
**Symbols:**

```
ffffffff819a4230-ffffffff819a43f7: efivar_create (STB_LOCAL)
ffffffff81c1e061-ffffffff81c1e092: efivar_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:362
Inline: False
```
**Symbols:**

```
ffffffff81a514e0-ffffffff81a516a7: efivar_create (STB_LOCAL)
ffffffff81d2f549-ffffffff81d2f57a: efivar_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:363
Inline: False
```
**Symbols:**

```
ffffffff81bc03a0-ffffffff81bc0547: efivar_create (STB_LOCAL)
ffffffff81efb69f-ffffffff81efb6d0: efivar_create.cold (STB_LOCAL)
```
</details>
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
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffff800010b5d8d8)
Location: drivers/firmware/efi/efivars.c:364
Inline: False
```
**Symbols:**

```
ffff800010b5d8d8-ffff800010b5da8c: efivar_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (c0c3e680)
Location: drivers/firmware/efi/efivars.c:364
Inline: False
```
**Symbols:**

```
c0c3e680-c0c3e7c0: efivar_create (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:364
Inline: False
```
**Symbols:**

```
ffffffff8188d410-ffffffff8188d5d7: efivar_create (STB_LOCAL)
ffffffff8188db4e-ffffffff8188db7f: efivar_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:364
Inline: False
```
**Symbols:**

```
ffffffff81844d90-ffffffff81844f57: efivar_create (STB_LOCAL)
ffffffff818454ce-ffffffff818454ff: efivar_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:364
Inline: False
```
**Symbols:**

```
ffffffff818df4f0-ffffffff818df6b7: efivar_create (STB_LOCAL)
ffffffff818dfc2e-ffffffff818dfc5f: efivar_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t efivar_create(struct file *filp, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:364
Inline: False
```
**Symbols:**

```
ffffffff818fbf90-ffffffff818fc157: efivar_create (STB_LOCAL)
ffffffff818fc6ce-ffffffff818fc6ff: efivar_create.cold (STB_LOCAL)
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
