# Function: <code>efivar_unlock</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void efivar_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81d636e0)
Location: drivers/firmware/efi/vars.c:161
Inline: True
Direct callers:
  - fs/efivarfs/vars.c:efivar_entry_iter
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_get
  - fs/efivarfs/vars.c:efivar_entry_size
  - fs/efivarfs/vars.c:efivar_entry_delete
  - fs/efivarfs/vars.c:efivar_entry_delete
  - fs/efivarfs/vars.c:efivar_entry_add
  - fs/efivarfs/vars.c:efivar_init
```
**Symbols:**

```
ffffffff81d636e0-ffffffff81d636fd: efivar_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void efivar_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81dce820)
Location: drivers/firmware/efi/vars.c:165
Inline: True
Direct callers:
  - fs/efivarfs/vars.c:efivar_entry_iter
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_get
  - fs/efivarfs/vars.c:efivar_entry_size
  - fs/efivarfs/vars.c:efivar_entry_delete
  - fs/efivarfs/vars.c:efivar_entry_delete
  - fs/efivarfs/vars.c:efivar_entry_add
  - fs/efivarfs/vars.c:efivar_init
```
**Symbols:**

```
ffffffff81dce820-ffffffff81dce83d: efivar_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void efivar_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81e87550)
Location: drivers/firmware/efi/vars.c:173
Inline: True
Direct callers:
  - fs/efivarfs/vars.c:efivar_entry_iter
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_set_get_size
  - fs/efivarfs/vars.c:efivar_entry_get
  - fs/efivarfs/vars.c:efivar_entry_size
  - fs/efivarfs/vars.c:efivar_entry_delete
  - fs/efivarfs/vars.c:efivar_entry_delete
  - fs/efivarfs/vars.c:efivar_entry_add
  - fs/efivarfs/vars.c:efivar_init
```
**Symbols:**

```
ffffffff81e87550-ffffffff81e8756d: efivar_unlock (STB_GLOBAL)
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
