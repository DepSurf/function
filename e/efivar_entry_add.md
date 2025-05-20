# Function: <code>efivar_entry_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff816d1490)
Location: drivers/firmware/efi/vars.c:517
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff816d1490-ffffffff816d14ea: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817346b0)
Location: drivers/firmware/efi/vars.c:507
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff817346b0-ffffffff8173470a: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81767160)
Location: drivers/firmware/efi/vars.c:524
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff81767160-ffffffff817671c5: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81785a40)
Location: drivers/firmware/efi/vars.c:524
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff81785a40-ffffffff81785aa7: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817fbe80)
Location: drivers/firmware/efi/vars.c:524
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff817fbe80-ffffffff817fbee7: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818453b0)
Location: drivers/firmware/efi/vars.c:524
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff818453b0-ffffffff81845417: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81871500)
Location: drivers/firmware/efi/vars.c:539
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff81871500-ffffffff81871567: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818b5840)
Location: drivers/firmware/efi/vars.c:526
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff818b5840-ffffffff818b58a7: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818e81a0)
Location: drivers/firmware/efi/vars.c:526
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff818e81a0-ffffffff818e8207: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bb870)
Location: drivers/firmware/efi/vars.c:526
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff819bb870-ffffffff819bb8d7: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bda00)
Location: drivers/firmware/efi/vars.c:518
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff819bda00-ffffffff819bda67: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819a2070)
Location: drivers/firmware/efi/vars.c:518
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff819a2070-ffffffff819a20d7: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81a4efb0)
Location: drivers/firmware/efi/vars.c:518
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff81a4efb0-ffffffff81a4f017: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81bbdca0)
Location: drivers/firmware/efi/vars.c:518
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff81bbdca0-ffffffff81bbdd11: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff8163b3b0)
Location: fs/efivarfs/vars.c:457
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
**Symbols:**

```
ffffffff8163b3b0-ffffffff8163b408: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff816739f0)
Location: fs/efivarfs/vars.c:457
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
**Symbols:**

```
ffffffff816739f0-ffffffff81673a48: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff816afdb0)
Location: fs/efivarfs/vars.c:461
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
**Symbols:**

```
ffffffff816afdb0-ffffffff816afe08: efivar_entry_add (STB_GLOBAL)
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
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffff800010b5b3e0)
Location: drivers/firmware/efi/vars.c:526
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffff800010b5b3e0-ffff800010b5b454: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (c0c3bf9c)
Location: drivers/firmware/efi/vars.c:526
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
c0c3bf9c-c0c3c004: efivar_entry_add (STB_GLOBAL)
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
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff8188af20)
Location: drivers/firmware/efi/vars.c:526
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff8188af20-ffffffff8188af87: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818428a0)
Location: drivers/firmware/efi/vars.c:526
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff818428a0-ffffffff81842907: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818dd000)
Location: drivers/firmware/efi/vars.c:526
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff818dd000-ffffffff818dd067: efivar_entry_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int efivar_entry_add(struct efivar_entry *entry, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818f9b10)
Location: drivers/firmware/efi/vars.c:526
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
  - drivers/firmware/efi/efi.c:efivar_ssdt_iter
  - drivers/firmware/efi/efivars.c:efivar_create_sysfs_entry
```
**Symbols:**

```
ffffffff818f9b10-ffffffff818f9b77: efivar_entry_add (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
