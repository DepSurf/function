# Function: <code>efivar_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool atomic, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff816d17e0)
Location: drivers/firmware/efi/vars.c:428
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffffffff816d17e0-ffffffff816d1b04: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81734900)
Location: drivers/firmware/efi/vars.c:421
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffffffff81734900-ffffffff81734c6c: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81767e50)
Location: drivers/firmware/efi/vars.c:429
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffffffff81767e50-ffffffff817681ff: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81786730)
Location: drivers/firmware/efi/vars.c:429
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffffffff81786730-ffffffff81786ad1: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817fcb90)
Location: drivers/firmware/efi/vars.c:429
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffffffff817fcb90-ffffffff817fcf3c: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:429
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffffffff818466e7-ffffffff81846735: efivar_init.cold.15 (STB_LOCAL)
ffffffff81846320-ffffffff81846685: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:439
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffffffff81872943-ffffffff81872991: efivar_init.cold.15 (STB_LOCAL)
ffffffff81872550-ffffffff818728e1: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:426
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efi.c:efivar_ssdt_load
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffffffff818b6b23-ffffffff818b6b85: efivar_init.cold (STB_LOCAL)
ffffffff818b6770-ffffffff818b6ac1: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:426
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efi.c:efivar_ssdt_load
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffffffff818e9483-ffffffff818e94e5: efivar_init.cold (STB_LOCAL)
ffffffff818e90d0-ffffffff818e9421: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:426
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffffffff819bc8b8-ffffffff819bc918: efivar_init.cold (STB_LOCAL)
ffffffff819bc270-ffffffff819bc4e3: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:414
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
```
**Symbols:**

```
ffffffff81c2b7b9-ffffffff81c2b818: efivar_init.cold (STB_LOCAL)
ffffffff819be3d0-ffffffff819be681: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:414
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
```
**Symbols:**

```
ffffffff81c1dc52-ffffffff81c1dcba: efivar_init.cold (STB_LOCAL)
ffffffff819a2930-ffffffff819a2cbf: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:414
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
```
**Symbols:**

```
ffffffff81d2f118-ffffffff81d2f180: efivar_init.cold (STB_LOCAL)
ffffffff81a4f8c0-ffffffff81a4fc4f: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:414
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
```
**Symbols:**

```
ffffffff81efb5b4-ffffffff81efb622: efivar_init.cold (STB_LOCAL)
ffffffff81bbe6d0-ffffffff81bbea8b: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff8163b0c0)
Location: fs/efivarfs/vars.c:372
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
```
**Symbols:**

```
ffffffff8163b0c0-ffffffff8163b397: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff816736c0)
Location: fs/efivarfs/vars.c:372
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
```
**Symbols:**

```
ffffffff816736c0-ffffffff816739dc: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *, struct list_head *), void *data, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff816afa60)
Location: fs/efivarfs/vars.c:371
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
```
**Symbols:**

```
ffffffff816afa60-ffffffff816afd95: efivar_init (STB_GLOBAL)
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
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffff800010b5c3c8)
Location: drivers/firmware/efi/vars.c:426
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffff800010b5c3c8-ffff800010b5c714: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (c0c3cf9c)
Location: drivers/firmware/efi/vars.c:426
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
c0c3cf9c-c0c3d378: efivar_init (STB_GLOBAL)
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
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:426
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efi.c:efivar_ssdt_load
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffffffff8188c203-ffffffff8188c265: efivar_init.cold (STB_LOCAL)
ffffffff8188be50-ffffffff8188c1a1: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:426
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efi.c:efivar_ssdt_load
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffffffff81843b83-ffffffff81843be5: efivar_init.cold (STB_LOCAL)
ffffffff818437d0-ffffffff81843b21: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:426
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efi.c:efivar_ssdt_load
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffffffff818de2e3-ffffffff818de345: efivar_init.cold (STB_LOCAL)
ffffffff818ddf30-ffffffff818de281: efivar_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int efivar_init(int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *), void *data, bool duplicates, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:426
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efi.c:efivar_ssdt_load
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entries
```
**Symbols:**

```
ffffffff818fadf3-ffffffff818fae55: efivar_init.cold (STB_LOCAL)
ffffffff818faa40-ffffffff818fad91: efivar_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool atomic</code>
</li>
<li>
<b>Param reordered. </b>
<code>func, data, atomic, duplicates, head</code> ➡️ <code>func, data, duplicates, head</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool duplicates</code>
</li>
<li>
<b>Param reordered. </b>
<code>func, data, duplicates, head</code> ➡️ <code>func, data, head</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *)</code> ➡️ <code>int (*func)(efi_char16_t *, efi_guid_t, long unsigned int, void *, struct list_head *)</code>
</li>
</ul>
</details>
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
