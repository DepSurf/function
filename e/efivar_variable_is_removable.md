# Function: <code>efivar_variable_is_removable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff816d0c40)
Location: drivers/firmware/efi/vars.c:267
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff816d0c40-ffffffff816d0d47: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81733e70)
Location: drivers/firmware/efi/vars.c:282
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81733e70-ffffffff81733f51: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81766ed0)
Location: drivers/firmware/efi/vars.c:290
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81766ed0-ffffffff81766fb1: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81785650)
Location: drivers/firmware/efi/vars.c:290
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81785650-ffffffff81785731: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817fba90)
Location: drivers/firmware/efi/vars.c:290
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff817fba90-ffffffff817fbb71: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81845ad0)
Location: drivers/firmware/efi/vars.c:290
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81845ad0-ffffffff81845b99: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81871cc0)
Location: drivers/firmware/efi/vars.c:290
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81871cc0-ffffffff81871d84: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818b55f0)
Location: drivers/firmware/efi/vars.c:277
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff818b55f0-ffffffff818b56ac: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818e7f50)
Location: drivers/firmware/efi/vars.c:277
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff818e7f50-ffffffff818e800c: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bc1b0)
Location: drivers/firmware/efi/vars.c:277
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff819bc1b0-ffffffff819bc267: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819be310)
Location: drivers/firmware/efi/vars.c:273
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff819be310-ffffffff819be3c7: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819a2870)
Location: drivers/firmware/efi/vars.c:273
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff819a2870-ffffffff819a292a: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81a4f710)
Location: drivers/firmware/efi/vars.c:273
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81a4f710-ffffffff81a4f8b4: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81bbe510)
Location: drivers/firmware/efi/vars.c:273
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81bbe510-ffffffff81bbe6c7: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff8163aef0)
Location: fs/efivarfs/vars.c:264
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff8163aef0-ffffffff8163b0a7: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff816734f0)
Location: fs/efivarfs/vars.c:264
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff816734f0-ffffffff816736a7: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff816af890)
Location: fs/efivarfs/vars.c:264
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff816af890-ffffffff816afa47: efivar_variable_is_removable (STB_GLOBAL)
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
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffff800010b5b160)
Location: drivers/firmware/efi/vars.c:277
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffff800010b5b160-ffff800010b5b24c: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (c0c3bcb0)
Location: drivers/firmware/efi/vars.c:277
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
c0c3bcb0-c0c3bdec: efivar_variable_is_removable (STB_GLOBAL)
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
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff8188acd0)
Location: drivers/firmware/efi/vars.c:277
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff8188acd0-ffffffff8188ad8c: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81842650)
Location: drivers/firmware/efi/vars.c:277
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81842650-ffffffff8184270c: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818dcdb0)
Location: drivers/firmware/efi/vars.c:277
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff818dcdb0-ffffffff818dce6c: efivar_variable_is_removable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool efivar_variable_is_removable(efi_guid_t vendor, const char *var_name, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818f98c0)
Location: drivers/firmware/efi/vars.c:277
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff818f98c0-ffffffff818f997c: efivar_variable_is_removable (STB_GLOBAL)
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
