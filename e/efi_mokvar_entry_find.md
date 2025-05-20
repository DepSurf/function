# Function: <code>efi_mokvar_entry_find</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct efi_mokvar_table_entry *efi_mokvar_entry_find(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff819c29d0)
Location: drivers/firmware/efi/mokvar-table.c:243
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff819c29d0-ffffffff819c2a4e: efi_mokvar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct efi_mokvar_table_entry *efi_mokvar_entry_find(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff819a6e10)
Location: drivers/firmware/efi/mokvar-table.c:246
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff819a6e10-ffffffff819a6e8e: efi_mokvar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct efi_mokvar_table_entry *efi_mokvar_entry_find(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff81a541c0)
Location: drivers/firmware/efi/mokvar-table.c:246
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff81a541c0-ffffffff81a5423e: efi_mokvar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct efi_mokvar_table_entry *efi_mokvar_entry_find(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff81bc36d0)
Location: drivers/firmware/efi/mokvar-table.c:246
Inline: False
Direct callers:
  - security/integrity/platform_certs/machine_keyring.c:trust_moklist
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff81bc36d0-ffffffff81bc374a: efi_mokvar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct efi_mokvar_table_entry *efi_mokvar_entry_find(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff81d68330)
Location: drivers/firmware/efi/mokvar-table.c:246
Inline: False
Direct callers:
  - security/integrity/platform_certs/machine_keyring.c:trust_moklist
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff81d68330-ffffffff81d683aa: efi_mokvar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct efi_mokvar_table_entry *efi_mokvar_entry_find(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff81dd3480)
Location: drivers/firmware/efi/mokvar-table.c:246
Inline: False
Direct callers:
  - security/integrity/platform_certs/machine_keyring.c:trust_moklist
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff81dd3480-ffffffff81dd34fa: efi_mokvar_entry_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct efi_mokvar_table_entry *efi_mokvar_entry_find(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff81e8b490)
Location: drivers/firmware/efi/mokvar-table.c:246
Inline: False
Direct callers:
  - security/integrity/platform_certs/machine_keyring.c:imputed_trust_enabled
  - security/integrity/platform_certs/load_uefi.c:load_moklist_certs
```
**Symbols:**

```
ffffffff81e8b490-ffffffff81e8b50a: efi_mokvar_entry_find (STB_GLOBAL)
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
