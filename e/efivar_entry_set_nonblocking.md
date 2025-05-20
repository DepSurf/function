# Function: <code>efivar_entry_set_nonblocking</code>

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
In drivers/firmware/efi/vars.c (ffffffff816d1347)
Location: drivers/firmware/efi/vars.c:674
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (ffffffff81734595)
Location: drivers/firmware/efi/vars.c:664
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (ffffffff817678bc)
Location: drivers/firmware/efi/vars.c:687
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (ffffffff8178611a)
Location: drivers/firmware/efi/vars.c:687
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (ffffffff817fc56a)
Location: drivers/firmware/efi/vars.c:687
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (ffffffff81845950)
Location: drivers/firmware/efi/vars.c:687
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (ffffffff81871b2e)
Location: drivers/firmware/efi/vars.c:715
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (ffffffff818b5e6e)
Location: drivers/firmware/efi/vars.c:702
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (ffffffff818e87ce)
Location: drivers/firmware/efi/vars.c:702
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int efivar_entry_set_nonblocking(efi_char16_t *name, efi_guid_t vendor, u32 attributes, long unsigned int size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bbde0)
Location: drivers/firmware/efi/vars.c:702
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
```
**Symbols:**

```
ffffffff819bbde0-ffffffff819bbeea: efivar_entry_set_nonblocking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int efivar_entry_set_nonblocking(efi_char16_t *name, efi_guid_t vendor, u32 attributes, long unsigned int size, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bdf70)
Location: drivers/firmware/efi/vars.c:694
Inline: False
Direct callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
```
**Symbols:**

```
ffffffff819bdf70-ffffffff819be07a: efivar_entry_set_nonblocking (STB_LOCAL)
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
In drivers/firmware/efi/vars.c (ffffffff819a303c)
Location: drivers/firmware/efi/vars.c:694
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (ffffffff81a4fd94)
Location: drivers/firmware/efi/vars.c:694
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (ffffffff81bbebe5)
Location: drivers/firmware/efi/vars.c:694
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffff800010b5bab0)
Location: drivers/firmware/efi/vars.c:702
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (c0c3c63c)
Location: drivers/firmware/efi/vars.c:702
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (ffffffff8188b54e)
Location: drivers/firmware/efi/vars.c:702
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (ffffffff81842ece)
Location: drivers/firmware/efi/vars.c:702
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (ffffffff818dd62e)
Location: drivers/firmware/efi/vars.c:702
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
In drivers/firmware/efi/vars.c (ffffffff818fa13e)
Location: drivers/firmware/efi/vars.c:702
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_set_safe
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
