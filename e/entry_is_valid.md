# Function: <code>entry_is_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff81fe44f3)
Location: drivers/firmware/efi/memattr.c:57
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff8202222f)
Location: drivers/firmware/efi/memattr.c:57
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff82104f4f)
Location: drivers/firmware/efi/memattr.c:58
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff8270e618)
Location: drivers/firmware/efi/memattr.c:58
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff827388a2)
Location: drivers/firmware/efi/memattr.c:58
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff828f284e)
Location: drivers/firmware/efi/memattr.c:58
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff8290dee0)
Location: drivers/firmware/efi/memattr.c:55
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff829178d0)
Location: drivers/firmware/efi/memattr.c:55
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool entry_is_valid(const efi_memory_desc_t *in, efi_memory_desc_t *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff819bca3f)
Location: drivers/firmware/efi/memattr.c:56
Inline: False
Direct callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
**Symbols:**

```
ffffffff819bca3f-ffffffff819bcb5f: entry_is_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool entry_is_valid(const efi_memory_desc_t *in, efi_memory_desc_t *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff81c2b83a)
Location: drivers/firmware/efi/memattr.c:56
Inline: False
Direct callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
**Symbols:**

```
ffffffff81c2b83a-ffffffff81c2b95a: entry_is_valid (STB_LOCAL)
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
In drivers/firmware/efi/memattr.c (ffffffff832235b6)
Location: drivers/firmware/efi/memattr.c:56
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff8330d3bc)
Location: drivers/firmware/efi/memattr.c:56
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff834c6ecd)
Location: drivers/firmware/efi/memattr.c:56
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff83f080fe)
Location: drivers/firmware/efi/memattr.c:56
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff8372e239)
Location: drivers/firmware/efi/memattr.c:56
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff83962639)
Location: drivers/firmware/efi/memattr.c:56
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffff8000114a619c)
Location: drivers/firmware/efi/memattr.c:55
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (c15a8488)
Location: drivers/firmware/efi/memattr.c:55
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff828fccd6)
Location: drivers/firmware/efi/memattr.c:55
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff828f4572)
Location: drivers/firmware/efi/memattr.c:55
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff82911f05)
Location: drivers/firmware/efi/memattr.c:55
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
In drivers/firmware/efi/memattr.c (ffffffff82918932)
Location: drivers/firmware/efi/memattr.c:55
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
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
