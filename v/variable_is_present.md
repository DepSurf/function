# Function: <code>variable_is_present</code>

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
In drivers/firmware/efi/vars.c (ffffffff816d1942)
Location: drivers/firmware/efi/vars.c:339
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
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
In drivers/firmware/efi/vars.c (ffffffff81734a64)
Location: drivers/firmware/efi/vars.c:332
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
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
In drivers/firmware/efi/vars.c (ffffffff81767fff)
Location: drivers/firmware/efi/vars.c:340
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81786911)
Location: drivers/firmware/efi/vars.c:340
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817fcd7c)
Location: drivers/firmware/efi/vars.c:340
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818464db)
Location: drivers/firmware/efi/vars.c:340
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81872719)
Location: drivers/firmware/efi/vars.c:350
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818b691b)
Location: drivers/firmware/efi/vars.c:337
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818e927b)
Location: drivers/firmware/efi/vars.c:337
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool variable_is_present(efi_char16_t *variable_name, efi_guid_t *vendor, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bb5d0)
Location: drivers/firmware/efi/vars.c:337
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
**Symbols:**

```
ffffffff819bb5d0-ffffffff819bb6d6: variable_is_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool variable_is_present(efi_char16_t *variable_name, efi_guid_t *vendor, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bd760)
Location: drivers/firmware/efi/vars.c:333
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
**Symbols:**

```
ffffffff819bd760-ffffffff819bd866: variable_is_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819a2b54)
Location: drivers/firmware/efi/vars.c:333
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81a4fae4)
Location: drivers/firmware/efi/vars.c:333
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81bbe8cb)
Location: drivers/firmware/efi/vars.c:333
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff8163b23b)
Location: fs/efivarfs/vars.c:291
Inline: True
Inline callers:
  - fs/efivarfs/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff81673860)
Location: fs/efivarfs/vars.c:291
Inline: True
Inline callers:
  - fs/efivarfs/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/efivarfs/vars.c (ffffffff816afc13)
Location: fs/efivarfs/vars.c:291
Inline: True
Inline callers:
  - fs/efivarfs/vars.c:efivar_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffff800010b5c570)
Location: drivers/firmware/efi/vars.c:337
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
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
In drivers/firmware/efi/vars.c (c0c3d158)
Location: drivers/firmware/efi/vars.c:337
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff8188bffb)
Location: drivers/firmware/efi/vars.c:337
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff8184397b)
Location: drivers/firmware/efi/vars.c:337
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818de0db)
Location: drivers/firmware/efi/vars.c:337
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818fabeb)
Location: drivers/firmware/efi/vars.c:337
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
