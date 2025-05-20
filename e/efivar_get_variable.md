# Function: <code>efivar_get_variable</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
efi_status_t efivar_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81d634d0)
Location: drivers/firmware/efi/vars.c:172
Inline: False
Direct callers:
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_get
  - fs/efivarfs/vars.c:efivar_entry_size
```
**Symbols:**

```
ffffffff81d634d0-ffffffff81d634fd: efivar_get_variable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
efi_status_t efivar_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81dce5b0)
Location: drivers/firmware/efi/vars.c:176
Inline: False
Direct callers:
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_get
  - fs/efivarfs/vars.c:efivar_entry_size
```
**Symbols:**

```
ffffffff81dce5b0-ffffffff81dce5dd: efivar_get_variable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
efi_status_t efivar_get_variable(efi_char16_t *name, efi_guid_t *vendor, u32 *attr, long unsigned int *size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81e872b0)
Location: drivers/firmware/efi/vars.c:184
Inline: False
Direct callers:
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_get
  - fs/efivarfs/vars.c:efivar_entry_size
```
**Symbols:**

```
ffffffff81e872b0-ffffffff81e872dd: efivar_get_variable (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
