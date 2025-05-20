# Function: <code>add_sysfs_runtime_map_entry</code>

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
In drivers/firmware/efi/runtime-map.c (ffffffff81fb71f3)
Location: drivers/firmware/efi/runtime-map.c:109
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
In drivers/firmware/efi/runtime-map.c (ffffffff81fe4ca5)
Location: drivers/firmware/efi/runtime-map.c:109
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
In drivers/firmware/efi/runtime-map.c (ffffffff82022dfa)
Location: drivers/firmware/efi/runtime-map.c:105
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
In drivers/firmware/efi/runtime-map.c (ffffffff82105b11)
Location: drivers/firmware/efi/runtime-map.c:105
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
In drivers/firmware/efi/runtime-map.c (ffffffff8270f1da)
Location: drivers/firmware/efi/runtime-map.c:105
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
In drivers/firmware/efi/runtime-map.c (ffffffff82739516)
Location: drivers/firmware/efi/runtime-map.c:105
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
In drivers/firmware/efi/runtime-map.c (ffffffff828f34e5)
Location: drivers/firmware/efi/runtime-map.c:105
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
In drivers/firmware/efi/runtime-map.c (ffffffff8290edee)
Location: drivers/firmware/efi/runtime-map.c:104
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
In drivers/firmware/efi/runtime-map.c (ffffffff829187bd)
Location: drivers/firmware/efi/runtime-map.c:104
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct efi_runtime_map_entry *add_sysfs_runtime_map_entry(struct kobject *kobj, int nr, efi_memory_desc_t *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-map.c (ffffffff819bfcd1)
Location: drivers/firmware/efi/runtime-map.c:104
Inline: False
Direct callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff819bfcd1-ffffffff819bfdcc: add_sysfs_runtime_map_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct efi_runtime_map_entry *add_sysfs_runtime_map_entry(struct kobject *kobj, int nr, efi_memory_desc_t *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-map.c (ffffffff81c2c8b6)
Location: drivers/firmware/efi/runtime-map.c:104
Inline: False
Direct callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff81c2c8b6-ffffffff81c2c9b1: add_sysfs_runtime_map_entry (STB_LOCAL)
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
In drivers/firmware/efi/runtime-map.c (ffffffff83224407)
Location: drivers/firmware/efi/runtime-map.c:104
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
In drivers/firmware/efi/runtime-map.c (ffffffff8330e201)
Location: drivers/firmware/efi/runtime-map.c:104
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct efi_runtime_map_entry *add_sysfs_runtime_map_entry(struct kobject *kobj, int nr, efi_memory_desc_t *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-map.c (ffffffff81efc4bd)
Location: drivers/firmware/efi/runtime-map.c:105
Inline: False
Direct callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff81efc4bd-ffffffff81efc5b6: add_sysfs_runtime_map_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct efi_runtime_map_entry *add_sysfs_runtime_map_entry(struct kobject *kobj, int nr, efi_memory_desc_t *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/runtime-map.c (ffffffff810d9cb0)
Location: arch/x86/platform/efi/runtime-map.c:105
Inline: False
Direct callers:
  - arch/x86/platform/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff810d9cb0-ffffffff810d9ded: add_sysfs_runtime_map_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct efi_runtime_map_entry *add_sysfs_runtime_map_entry(struct kobject *kobj, int nr, efi_memory_desc_t *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/runtime-map.c (ffffffff810e5240)
Location: arch/x86/platform/efi/runtime-map.c:105
Inline: False
Direct callers:
  - arch/x86/platform/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff810e5240-ffffffff810e537d: add_sysfs_runtime_map_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct efi_runtime_map_entry *add_sysfs_runtime_map_entry(struct kobject *kobj, int nr, efi_memory_desc_t *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/runtime-map.c (ffffffff810ed600)
Location: arch/x86/platform/efi/runtime-map.c:105
Inline: False
Direct callers:
  - arch/x86/platform/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff810ed600-ffffffff810ed762: add_sysfs_runtime_map_entry (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/runtime-map.c (ffffffff828fdbc3)
Location: drivers/firmware/efi/runtime-map.c:104
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
In drivers/firmware/efi/runtime-map.c (ffffffff828f545f)
Location: drivers/firmware/efi/runtime-map.c:104
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
In drivers/firmware/efi/runtime-map.c (ffffffff82912df2)
Location: drivers/firmware/efi/runtime-map.c:104
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
In drivers/firmware/efi/runtime-map.c (ffffffff8291981f)
Location: drivers/firmware/efi/runtime-map.c:104
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
