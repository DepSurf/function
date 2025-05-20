# Function: <code>efi_systab_init</code>

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
In arch/x86/platform/efi/efi.c (ffffffff81f7a1b8)
Location: arch/x86/platform/efi/efi.c:256
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff81fa2a1a)
Location: arch/x86/platform/efi/efi.c:234
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff81fde424)
Location: arch/x86/platform/efi/efi.c:293
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff820bf21f)
Location: arch/x86/platform/efi/efi.c:294
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff826c734b)
Location: arch/x86/platform/efi/efi.c:295
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff826f1461)
Location: arch/x86/platform/efi/efi.c:295
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff828a8205)
Location: arch/x86/platform/efi/efi.c:294
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff828c0d21)
Location: arch/x86/platform/efi/efi.c:296
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff828c71ac)
Location: arch/x86/platform/efi/efi.c:319
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int efi_systab_init(long unsigned int phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff82ce9d05)
Location: arch/x86/platform/efi/efi.c:340
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff82ce9d05-ffffffff82ce9e64: efi_systab_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int efi_systab_init(long unsigned int phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff82fd7770)
Location: arch/x86/platform/efi/efi.c:342
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff82fd7770-ffffffff82fd78cf: efi_systab_init (STB_LOCAL)
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
In arch/x86/platform/efi/efi.c (ffffffff831e26c2)
Location: arch/x86/platform/efi/efi.c:342
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
In arch/x86/platform/efi/efi.c (ffffffff832c6047)
Location: arch/x86/platform/efi/efi.c:342
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
In arch/x86/platform/efi/efi.c (ffffffff83478e4b)
Location: arch/x86/platform/efi/efi.c:345
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efi_systab_init(long unsigned int phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff83ea21d0)
Location: arch/x86/platform/efi/efi.c:368
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff83ea21d0-ffffffff83ea2312: efi_systab_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efi_systab_init(long unsigned int phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff836c6430)
Location: arch/x86/platform/efi/efi.c:371
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff836c6430-ffffffff836c656d: efi_systab_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efi_systab_init(long unsigned int phys);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff838f7030)
Location: arch/x86/platform/efi/efi.c:371
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff838f7030-ffffffff838f716d: efi_systab_init (STB_LOCAL)
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
In arch/x86/platform/efi/efi.c (ffffffff828b2144)
Location: arch/x86/platform/efi/efi.c:319
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff828aa2b6)
Location: arch/x86/platform/efi/efi.c:319
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff828c5043)
Location: arch/x86/platform/efi/efi.c:319
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
In arch/x86/platform/efi/efi.c (ffffffff828c81e9)
Location: arch/x86/platform/efi/efi.c:319
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_init
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
