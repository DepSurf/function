# Function: <code>e820__range_remove</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff820ab7e1)
Location: arch/x86/kernel/e820.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff820ab7e1-ffffffff820ab930: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826b1fb7)
Location: arch/x86/kernel/e820.c:511
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff826b1fb7-ffffffff826b2106: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826db683)
Location: arch/x86/kernel/e820.c:513
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff826db683-ffffffff826db7ce: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82891a6a)
Location: arch/x86/kernel/e820.c:512
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff82891a6a-ffffffff82891bb5: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828a8fc7)
Location: arch/x86/kernel/e820.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff828a8fc7-ffffffff828a9105: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ac02b)
Location: arch/x86/kernel/e820.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff828ac02b-ffffffff828ac169: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82cd133b)
Location: arch/x86/kernel/e820.c:527
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff82cd133b-ffffffff82cd1479: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82fbd18b)
Location: arch/x86/kernel/e820.c:541
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff82fbd18b-ffffffff82fbd2c9: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff831c789c)
Location: arch/x86/kernel/e820.c:541
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff831c789c-ffffffff831c79dd: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff832a8a83)
Location: arch/x86/kernel/e820.c:541
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff832a8a83-ffffffff832a8bc4: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83458072)
Location: arch/x86/kernel/e820.c:541
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff83458072-ffffffff834581d6: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83e770d0)
Location: arch/x86/kernel/e820.c:541
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff83e770d0-ffffffff83e772d3: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83699130)
Location: arch/x86/kernel/e820.c:541
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff83699130-ffffffff83699497: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff838c8eb0)
Location: arch/x86/kernel/e820.c:541
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memopt
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff838c8eb0-ffffffff838c9217: e820__range_remove (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8289a03d)
Location: arch/x86/kernel/e820.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff8289a03d-ffffffff8289a17b: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828922fb)
Location: arch/x86/kernel/e820.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff828922fb-ffffffff82892439: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ad01d)
Location: arch/x86/kernel/e820.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff828ad01d-ffffffff828ad15b: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 e820__range_remove(u64 start, u64 size, enum e820_type old_type, bool check_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ad03b)
Location: arch/x86/kernel/e820.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memmap_opt
  - arch/x86/kernel/e820.c:parse_memopt
```
**Symbols:**

```
ffffffff828ad03b-ffffffff828ad179: e820__range_remove (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
