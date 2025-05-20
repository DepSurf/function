# Function: <code>efi_mokvar_entry_next</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct efi_mokvar_table_entry *efi_mokvar_entry_next(struct efi_mokvar_table_entry **mokvar_entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff819c2a1e)
Location: drivers/firmware/efi/mokvar-table.c:203
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_entry_find
Direct callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff819c2980-ffffffff819c29c6: efi_mokvar_entry_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct efi_mokvar_table_entry *efi_mokvar_entry_next(struct efi_mokvar_table_entry **mokvar_entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff819a6e5e)
Location: drivers/firmware/efi/mokvar-table.c:206
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_entry_find
Direct callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff819a6dc0-ffffffff819a6e06: efi_mokvar_entry_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct efi_mokvar_table_entry *efi_mokvar_entry_next(struct efi_mokvar_table_entry **mokvar_entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff81a5420e)
Location: drivers/firmware/efi/mokvar-table.c:206
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_entry_find
Direct callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff81a54170-ffffffff81a541b6: efi_mokvar_entry_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct efi_mokvar_table_entry *efi_mokvar_entry_next(struct efi_mokvar_table_entry **mokvar_entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff81bc36e2)
Location: drivers/firmware/efi/mokvar-table.c:206
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_entry_find
Direct callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
**Symbols:**

```
ffffffff81bc3670-ffffffff81bc36c6: efi_mokvar_entry_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct efi_mokvar_table_entry *efi_mokvar_entry_next(struct efi_mokvar_table_entry **mokvar_entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff83f0a222)
Location: drivers/firmware/efi/mokvar-table.c:206
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_entry_find
```
**Symbols:**

```
ffffffff81d682c0-ffffffff81d68316: efi_mokvar_entry_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct efi_mokvar_table_entry *efi_mokvar_entry_next(struct efi_mokvar_table_entry **mokvar_entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff83730342)
Location: drivers/firmware/efi/mokvar-table.c:206
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_entry_find
```
**Symbols:**

```
ffffffff81dd3410-ffffffff81dd3466: efi_mokvar_entry_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct efi_mokvar_table_entry *efi_mokvar_entry_next(struct efi_mokvar_table_entry **mokvar_entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/mokvar-table.c (ffffffff83964874)
Location: drivers/firmware/efi/mokvar-table.c:206
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_entry_find
```
**Symbols:**

```
ffffffff81e8b420-ffffffff81e8b476: efi_mokvar_entry_next (STB_GLOBAL)
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
