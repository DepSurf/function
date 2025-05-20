# Function: <code>efivar_entry_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff816d15f0)
Location: drivers/firmware/efi/vars.c:872
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
```
**Symbols:**

```
ffffffff816d15f0-ffffffff816d16d5: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81734810)
Location: drivers/firmware/efi/vars.c:863
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff81734810-ffffffff81734880: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81767540)
Location: drivers/firmware/efi/vars.c:882
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff81767540-ffffffff817675b9: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81785cd0)
Location: drivers/firmware/efi/vars.c:882
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff81785cd0-ffffffff81785d49: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817fc120)
Location: drivers/firmware/efi/vars.c:882
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff817fc120-ffffffff817fc19d: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81845640)
Location: drivers/firmware/efi/vars.c:882
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff81845640-ffffffff818456bd: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81871930)
Location: drivers/firmware/efi/vars.c:927
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff81871930-ffffffff818719c1: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818b5c70)
Location: drivers/firmware/efi/vars.c:914
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efi.c:efivar_ssdt_load
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff818b5c70-ffffffff818b5d02: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818e85d0)
Location: drivers/firmware/efi/vars.c:914
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efi.c:efivar_ssdt_load
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff818e85d0-ffffffff818e8662: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bbb20)
Location: drivers/firmware/efi/vars.c:914
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff819bbb20-ffffffff819bbbb2: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bdcb0)
Location: drivers/firmware/efi/vars.c:906
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff819bdcb0-ffffffff819bdd42: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819a2320)
Location: drivers/firmware/efi/vars.c:906
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff819a2320-ffffffff819a23b2: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81a4f260)
Location: drivers/firmware/efi/vars.c:909
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff81a4f260-ffffffff81a4f2f2: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81bbdfc0)
Location: drivers/firmware/efi/vars.c:909
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff81bbdfc0-ffffffff81bbe060: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff8163b6c0)
Location: fs/efivarfs/vars.c:596
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
```
**Symbols:**

```
ffffffff8163b6c0-ffffffff8163b72a: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff81673d00)
Location: fs/efivarfs/vars.c:596
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
```
**Symbols:**

```
ffffffff81673d00-ffffffff81673d6a: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff816b00c0)
Location: fs/efivarfs/vars.c:600
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
```
**Symbols:**

```
ffffffff816b00c0-ffffffff816b012a: efivar_entry_get (STB_GLOBAL)
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
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffff800010b5b8b8)
Location: drivers/firmware/efi/vars.c:914
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffff800010b5b8b8-ffff800010b5b964: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (c0c3c428)
Location: drivers/firmware/efi/vars.c:914
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
c0c3c428-c0c3c4d4: efivar_entry_get (STB_GLOBAL)
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
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff8188b350)
Location: drivers/firmware/efi/vars.c:914
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efi.c:efivar_ssdt_load
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff8188b350-ffffffff8188b3e2: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81842cd0)
Location: drivers/firmware/efi/vars.c:914
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efi.c:efivar_ssdt_load
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff81842cd0-ffffffff81842d62: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818dd430)
Location: drivers/firmware/efi/vars.c:914
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efi.c:efivar_ssdt_load
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff818dd430-ffffffff818dd4c2: efivar_entry_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int efivar_entry_get(struct efivar_entry *entry, u32 *attributes, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818f9f40)
Location: drivers/firmware/efi/vars.c:914
Inline: False
Direct callers:
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/firmware/efi/efi.c:efivar_ssdt_load
  - drivers/firmware/efi/efivars.c:efivar_show_raw
  - drivers/firmware/efi/efivars.c:efivar_data_read
  - drivers/firmware/efi/efivars.c:efivar_size_read
  - drivers/firmware/efi/efivars.c:efivar_attr_read
```
**Symbols:**

```
ffffffff818f9f40-ffffffff818f9fd2: efivar_entry_get (STB_GLOBAL)
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
