# Function: <code>efi_memattr_apply_permissions</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff81fe4427)
Location: drivers/firmware/efi/memattr.c:134
Inline: False
```
**Symbols:**

```
ffffffff81fe4427-ffffffff81fe46e0: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff82022163)
Location: drivers/firmware/efi/memattr.c:134
Inline: False
```
**Symbols:**

```
ffffffff82022163-ffffffff8202241c: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff82104e9b)
Location: drivers/firmware/efi/memattr.c:135
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff82104e9b-ffffffff82105140: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff8270e564)
Location: drivers/firmware/efi/memattr.c:135
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff8270e564-ffffffff8270e809: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff827387d9)
Location: drivers/firmware/efi/memattr.c:135
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff827387d9-ffffffff82738a58: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff828f2785)
Location: drivers/firmware/efi/memattr.c:135
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff828f2785-ffffffff828f2a04: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff8290ddf9)
Location: drivers/firmware/efi/memattr.c:132
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff8290ddf9-ffffffff8290e0bb: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff829177f5)
Location: drivers/firmware/efi/memattr.c:132
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff829177f5-ffffffff82917aab: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff82d29ede)
Location: drivers/firmware/efi/memattr.c:133
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff82d29ede-ffffffff82d2a071: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff83018603)
Location: drivers/firmware/efi/memattr.c:133
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff83018603-ffffffff83018796: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff832234db)
Location: drivers/firmware/efi/memattr.c:128
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff832234db-ffffffff83223774: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff8330d2e1)
Location: drivers/firmware/efi/memattr.c:128
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff8330d2e1-ffffffff8330d57a: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff834c6de9)
Location: drivers/firmware/efi/memattr.c:128
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff834c6de9-ffffffff834c7087: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff83f08020)
Location: drivers/firmware/efi/memattr.c:128
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff83f08020-ffffffff83f083a4: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff8372e140)
Location: drivers/firmware/efi/memattr.c:128
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff8372e140-ffffffff8372e4e9: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff83962540)
Location: drivers/firmware/efi/memattr.c:128
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff83962540-ffffffff839628e9: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffff8000114a60a8)
Location: drivers/firmware/efi/memattr.c:132
Inline: False
Direct callers:
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
```
**Symbols:**

```
ffff8000114a60a8-ffff8000114a63a8: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (c15a8344)
Location: drivers/firmware/efi/memattr.c:132
Inline: False
Direct callers:
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
```
**Symbols:**

```
c15a8344-c15a8784: efi_memattr_apply_permissions (STB_GLOBAL)
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
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff828fcbfb)
Location: drivers/firmware/efi/memattr.c:132
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff828fcbfb-ffffffff828fceb1: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff828f4497)
Location: drivers/firmware/efi/memattr.c:132
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff828f4497-ffffffff828f474d: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff82911e2a)
Location: drivers/firmware/efi/memattr.c:132
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff82911e2a-ffffffff829120e0: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int efi_memattr_apply_permissions(struct mm_struct *mm, efi_memattr_perm_setter fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memattr.c (ffffffff82918857)
Location: drivers/firmware/efi/memattr.c:132
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
```
**Symbols:**

```
ffffffff82918857-ffffffff82918b0d: efi_memattr_apply_permissions (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
