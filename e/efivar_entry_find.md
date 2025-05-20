# Function: <code>efivar_entry_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff816d0d50)
Location: drivers/firmware/efi/vars.c:776
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff816d0d50-ffffffff816d0ecb: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81733f60)
Location: drivers/firmware/efi/vars.c:767
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff81733f60-ffffffff817340e0: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81766fc0)
Location: drivers/firmware/efi/vars.c:789
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff81766fc0-ffffffff81767140: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817858b0)
Location: drivers/firmware/efi/vars.c:789
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff817858b0-ffffffff81785a1a: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817fbcf0)
Location: drivers/firmware/efi/vars.c:789
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff817fbcf0-ffffffff817fbe5a: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81845220)
Location: drivers/firmware/efi/vars.c:789
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff81845220-ffffffff8184538a: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81871370)
Location: drivers/firmware/efi/vars.c:827
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff81871370-ffffffff818714da: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818b56b0)
Location: drivers/firmware/efi/vars.c:814
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff818b56b0-ffffffff818b581c: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818e8010)
Location: drivers/firmware/efi/vars.c:814
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff818e8010-ffffffff818e817c: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bb6e0)
Location: drivers/firmware/efi/vars.c:814
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff819bb6e0-ffffffff819bb846: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bd870)
Location: drivers/firmware/efi/vars.c:806
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff819bd870-ffffffff819bd9d6: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819a1ee0)
Location: drivers/firmware/efi/vars.c:806
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff819a1ee0-ffffffff819a204a: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:809
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff81d2f0d5-ffffffff81d2f0e9: efivar_entry_find.cold (STB_LOCAL)
ffffffff81a4f300-ffffffff81a4f476: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:809
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff81efb56f-ffffffff81efb584: efivar_entry_find.cold (STB_LOCAL)
ffffffff81bbe060-ffffffff81bbe1e5: efivar_entry_find (STB_GLOBAL)
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
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffff800010b5b250)
Location: drivers/firmware/efi/vars.c:814
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffff800010b5b250-ffff800010b5b3b8: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (c0c3bdec)
Location: drivers/firmware/efi/vars.c:814
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
c0c3bdec-c0c3bf78: efivar_entry_find (STB_GLOBAL)
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
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff8188ad90)
Location: drivers/firmware/efi/vars.c:814
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff8188ad90-ffffffff8188aefc: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81842710)
Location: drivers/firmware/efi/vars.c:814
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff81842710-ffffffff8184287c: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818dce70)
Location: drivers/firmware/efi/vars.c:814
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff818dce70-ffffffff818dcfdc: efivar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct efivar_entry *efivar_entry_find(efi_char16_t *name, efi_guid_t guid, struct list_head *head, bool remove);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818f9980)
Location: drivers/firmware/efi/vars.c:814
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set
  - drivers/firmware/efi/efivars.c:efivar_update_sysfs_entry
  - drivers/firmware/efi/efivars.c:efivar_delete
```
**Symbols:**

```
ffffffff818f9980-ffffffff818f9aec: efivar_entry_find (STB_GLOBAL)
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
