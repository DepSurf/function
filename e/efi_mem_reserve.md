# Function: <code>efi_mem_reserve</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82021e43)
Location: drivers/firmware/efi/efi.c:420
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff82021e43-ffffffff82021e74: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82104b45)
Location: drivers/firmware/efi/efi.c:419
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff82104b45-ffffffff82104b7b: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8270e1f4)
Location: drivers/firmware/efi/efi.c:439
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff8270e1f4-ffffffff8270e22a: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8273846e)
Location: drivers/firmware/efi/efi.c:450
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff8273846e-ffffffff827384a4: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff828f237b)
Location: drivers/firmware/efi/efi.c:460
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff828f237b-ffffffff828f23b1: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8290d9db)
Location: drivers/firmware/efi/efi.c:460
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff8290d9db-ffffffff8290da13: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff829173d4)
Location: drivers/firmware/efi/efi.c:448
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff829173d4-ffffffff8291740c: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82d29a7b)
Location: drivers/firmware/efi/efi.c:493
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff82d29a7b-ffffffff82d29ab3: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff830181a0)
Location: drivers/firmware/efi/efi.c:497
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff830181a0-ffffffff830181d8: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83223078)
Location: drivers/firmware/efi/efi.c:497
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff83223078-ffffffff832230b0: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8330cdf9)
Location: drivers/firmware/efi/efi.c:497
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff8330cdf9-ffffffff8330ce31: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff834c68b3)
Location: drivers/firmware/efi/efi.c:508
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff834c68b3-ffffffff834c68f3: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83f07870)
Location: drivers/firmware/efi/efi.c:516
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff83f07870-ffffffff83f078ca: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8372d920)
Location: drivers/firmware/efi/efi.c:551
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff8372d920-ffffffff8372d992: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83961d00)
Location: drivers/firmware/efi/efi.c:573
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff83961d00-ffffffff83961d72: efi_mem_reserve (STB_GLOBAL)
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
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffff8000114a5b14)
Location: drivers/firmware/efi/efi.c:448
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffff8000114a5b14-ffff8000114a5b68: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (c15a7db4)
Location: drivers/firmware/efi/efi.c:448
Inline: False
Direct callers:
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
c15a7db4-c15a7e04: efi_mem_reserve (STB_GLOBAL)
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
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff828fc7da)
Location: drivers/firmware/efi/efi.c:448
Inline: False
Direct callers:
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff828fc7da-ffffffff828fc812: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff828f4076)
Location: drivers/firmware/efi/efi.c:448
Inline: False
Direct callers:
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff828f4076-ffffffff828f40ae: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82911a09)
Location: drivers/firmware/efi/efi.c:448
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff82911a09-ffffffff82911a41: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void efi_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82918436)
Location: drivers/firmware/efi/efi.c:448
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff82918436-ffffffff8291846e: efi_mem_reserve (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
