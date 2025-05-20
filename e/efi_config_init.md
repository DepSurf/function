# Function: <code>efi_config_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81fb6b18)
Location: drivers/firmware/efi/efi.c:450
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff81fb6b18-ffffffff81fb6bb2: efi_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81fe42d6)
Location: drivers/firmware/efi/efi.c:520
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff81fe42d6-ffffffff81fe4370: efi_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82022012)
Location: drivers/firmware/efi/efi.c:552
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff82022012-ffffffff820220ac: efi_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82104d32)
Location: drivers/firmware/efi/efi.c:554
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff82104d32-ffffffff82104dd1: efi_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8270e3ed)
Location: drivers/firmware/efi/efi.c:575
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff8270e3ed-ffffffff8270e48c: efi_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82738662)
Location: drivers/firmware/efi/efi.c:589
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff82738662-ffffffff82738701: efi_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff828f260e)
Location: drivers/firmware/efi/efi.c:635
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff828f260e-ffffffff828f26ad: efi_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8290dc6e)
Location: drivers/firmware/efi/efi.c:636
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff8290dc6e-ffffffff8290dd1a: efi_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8291766a)
Location: drivers/firmware/efi/efi.c:626
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff8291766a-ffffffff82917716: efi_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff82cea6e9)
Location: arch/x86/platform/efi/efi.c:413
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff82fd7fa2)
Location: arch/x86/platform/efi/efi.c:415
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff831e27ff)
Location: arch/x86/platform/efi/efi.c:415
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff832c6184)
Location: arch/x86/platform/efi/efi.c:415
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff83478f78)
Location: arch/x86/platform/efi/efi.c:418
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff83ea3046)
Location: arch/x86/platform/efi/efi.c:441
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff836c7296)
Location: arch/x86/platform/efi/efi.c:444
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff838f7e96)
Location: arch/x86/platform/efi/efi.c:444
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffff8000114a5de8)
Location: drivers/firmware/efi/efi.c:626
Inline: False
```
**Symbols:**

```
ffff8000114a5de8-ffff8000114a5ea8: efi_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (c15a80d0)
Location: drivers/firmware/efi/efi.c:626
Inline: False
```
**Symbols:**

```
c15a80d0-c15a816c: efi_config_init (STB_GLOBAL)
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
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff828fca70)
Location: drivers/firmware/efi/efi.c:626
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff828fca70-ffffffff828fcb1c: efi_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff828f430c)
Location: drivers/firmware/efi/efi.c:626
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff828f430c-ffffffff828f43b8: efi_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82911c9f)
Location: drivers/firmware/efi/efi.c:626
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff82911c9f-ffffffff82911d4b: efi_config_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int efi_config_init(efi_config_table_type_t *arch_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff829186cc)
Location: drivers/firmware/efi/efi.c:626
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff829186cc-ffffffff82918778: efi_config_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
