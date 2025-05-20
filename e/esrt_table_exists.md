# Function: <code>esrt_table_exists</code>

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
In drivers/firmware/efi/esrt.c (ffffffff816d36c5)
Location: drivers/firmware/efi/esrt.c:218
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffffffff81fe4838)
Location: drivers/firmware/efi/esrt.c:215
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffffffff8202297a)
Location: drivers/firmware/efi/esrt.c:216
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffffffff82105681)
Location: drivers/firmware/efi/esrt.c:216
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffffffff8270ed4a)
Location: drivers/firmware/efi/esrt.c:213
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffffffff82739004)
Location: drivers/firmware/efi/esrt.c:213
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffffffff828f2fbf)
Location: drivers/firmware/efi/esrt.c:213
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffffffff8290e8d9)
Location: drivers/firmware/efi/esrt.c:214
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffffffff829182b3)
Location: drivers/firmware/efi/esrt.c:214
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int esrt_table_exists();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/esrt.c (ffffffff819be8a5)
Location: drivers/firmware/efi/esrt.c:214
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
Direct callers:
  - drivers/firmware/efi/esrt.c:register_entries
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff819be880-ffffffff819be89c: esrt_table_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int esrt_table_exists();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/esrt.c (ffffffff819c0255)
Location: drivers/firmware/efi/esrt.c:214
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
Direct callers:
  - drivers/firmware/efi/esrt.c:register_entries
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff819c0230-ffffffff819c024c: esrt_table_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int esrt_table_exists();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/esrt.c (ffffffff819a4965)
Location: drivers/firmware/efi/esrt.c:214
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
Direct callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff819a4940-ffffffff819a495c: esrt_table_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int esrt_table_exists();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/esrt.c (ffffffff81a51c15)
Location: drivers/firmware/efi/esrt.c:214
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
Direct callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff81a51bf0-ffffffff81a51c0c: esrt_table_exists (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int esrt_table_exists();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/esrt.c (ffffffff81bc0ba5)
Location: drivers/firmware/efi/esrt.c:216
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
Direct callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff81bc0b70-ffffffff81bc0b92: esrt_table_exists (STB_LOCAL)
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
In drivers/firmware/efi/esrt.c (ffffffff83f08b65)
Location: drivers/firmware/efi/esrt.c:216
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffffffff8372eca5)
Location: drivers/firmware/efi/esrt.c:212
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffffffff839630a4)
Location: drivers/firmware/efi/esrt.c:212
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffff8000114a6d28)
Location: drivers/firmware/efi/esrt.c:214
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (c15a9340)
Location: drivers/firmware/efi/esrt.c:214
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffffffff828fd6b9)
Location: drivers/firmware/efi/esrt.c:214
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffffffff828f4f55)
Location: drivers/firmware/efi/esrt.c:214
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffffffff829128e8)
Location: drivers/firmware/efi/esrt.c:214
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In drivers/firmware/efi/esrt.c (ffffffff82919315)
Location: drivers/firmware/efi/esrt.c:214
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
