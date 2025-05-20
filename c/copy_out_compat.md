# Function: <code>copy_out_compat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff816d2d5b)
Location: drivers/firmware/efi/efivars.c:241
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff8173644c)
Location: drivers/firmware/efi/efivars.c:241
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff8176959e)
Location: drivers/firmware/efi/efivars.c:241
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff81787070)
Location: drivers/firmware/efi/efivars.c:241
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff81787070-ffffffff81787133: copy_out_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff817fd500)
Location: drivers/firmware/efi/efivars.c:241
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff817fd500-ffffffff817fd5c3: copy_out_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff81846d20)
Location: drivers/firmware/efi/efivars.c:241
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff81846d20-ffffffff81846ddf: copy_out_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff81872f80)
Location: drivers/firmware/efi/efivars.c:233
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff81872f80-ffffffff8187303f: copy_out_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff818b7170)
Location: drivers/firmware/efi/efivars.c:177
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff818b7170-ffffffff818b722f: copy_out_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff818e9ad0)
Location: drivers/firmware/efi/efivars.c:186
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff818e9ad0-ffffffff818e9b8f: copy_out_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff819bd1f0)
Location: drivers/firmware/efi/efivars.c:186
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff819bd1f0-ffffffff819bd2af: copy_out_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff819bef30)
Location: drivers/firmware/efi/efivars.c:184
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff819bef30-ffffffff819befef: copy_out_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff819a3630)
Location: drivers/firmware/efi/efivars.c:184
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff819a3630-ffffffff819a36ef: copy_out_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff81a508d0)
Location: drivers/firmware/efi/efivars.c:184
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff81a508d0-ffffffff81a5098f: copy_out_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff81bbf7c0)
Location: drivers/firmware/efi/efivars.c:184
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff81bbf7c0-ffffffff81bbf88d: copy_out_compat (STB_LOCAL)
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
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffff800010b5ce10)
Location: drivers/firmware/efi/efivars.c:186
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffff800010b5ce10-ffff800010b5ce84: copy_out_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (0)
Location: drivers/firmware/efi/efivars.c:186
Inline: False
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
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff8188c850)
Location: drivers/firmware/efi/efivars.c:186
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff8188c850-ffffffff8188c90f: copy_out_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff818441d0)
Location: drivers/firmware/efi/efivars.c:186
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff818441d0-ffffffff8184428f: copy_out_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff818de930)
Location: drivers/firmware/efi/efivars.c:186
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff818de930-ffffffff818de9ef: copy_out_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void copy_out_compat(struct efi_variable *dst, struct compat_efi_variable *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff818fb3d0)
Location: drivers/firmware/efi/efivars.c:186
Inline: False
Direct callers:
  - drivers/firmware/efi/efivars.c:efivar_create
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
**Symbols:**

```
ffffffff818fb3d0-ffffffff818fb48f: copy_out_compat (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
