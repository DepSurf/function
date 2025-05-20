# Function: <code>efivar_supports_writes</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int efivar_supports_writes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bb3e0)
Location: drivers/firmware/efi/vars.c:1233
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
```
**Symbols:**

```
ffffffff819bb3e0-ffffffff819bb408: efivar_supports_writes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int efivar_supports_writes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bd590)
Location: drivers/firmware/efi/vars.c:1215
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
```
**Symbols:**

```
ffffffff819bd590-ffffffff819bd5b8: efivar_supports_writes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int efivar_supports_writes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819a1d20)
Location: drivers/firmware/efi/vars.c:1215
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
```
**Symbols:**

```
ffffffff819a1d20-ffffffff819a1d48: efivar_supports_writes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int efivar_supports_writes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81a4ece0)
Location: drivers/firmware/efi/vars.c:1218
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
```
**Symbols:**

```
ffffffff81a4ece0-ffffffff81a4ed08: efivar_supports_writes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int efivar_supports_writes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81bbd9e0)
Location: drivers/firmware/efi/vars.c:1218
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_init
```
**Symbols:**

```
ffffffff81bbd9e0-ffffffff81bbda0e: efivar_supports_writes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efivar_supports_writes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81d63490)
Location: drivers/firmware/efi/vars.c:120
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
```
**Symbols:**

```
ffffffff81d63490-ffffffff81d634be: efivar_supports_writes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool efivar_supports_writes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81dce570)
Location: drivers/firmware/efi/vars.c:124
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
```
**Symbols:**

```
ffffffff81dce570-ffffffff81dce59b: efivar_supports_writes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool efivar_supports_writes();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81e873ce)
Location: drivers/firmware/efi/vars.c:132
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivars_register
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
```
**Symbols:**

```
ffffffff81e87270-ffffffff81e8729b: efivar_supports_writes (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
