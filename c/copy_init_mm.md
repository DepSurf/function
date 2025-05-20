# Function: <code>copy_init_mm</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81099db0)
Location: kernel/fork.c:2341
Inline: False
Direct callers:
  - arch/x86/mm/init.c:poking_init
```
**Symbols:**

```
ffffffff81099db0-ffffffff81099dc9: copy_init_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0390)
Location: kernel/fork.c:2326
Inline: False
Direct callers:
  - arch/x86/mm/init.c:poking_init
```
**Symbols:**

```
ffffffff810a0390-ffffffff810a03a9: copy_init_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a7270)
Location: kernel/fork.c:2413
Inline: False
Direct callers:
  - arch/x86/mm/init.c:poking_init
```
**Symbols:**

```
ffffffff810a7270-ffffffff810a7289: copy_init_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a2f40)
Location: kernel/fork.c:2426
Inline: False
Direct callers:
  - arch/x86/mm/init.c:poking_init
```
**Symbols:**

```
ffffffff810a2f40-ffffffff810a2f59: copy_init_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3a50)
Location: kernel/fork.c:2436
Inline: False
Direct callers:
  - arch/x86/mm/init.c:poking_init
```
**Symbols:**

```
ffffffff810a3a50-ffffffff810a3a69: copy_init_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b5270)
Location: kernel/fork.c:2529
Inline: False
Direct callers:
  - arch/x86/mm/init.c:poking_init
```
**Symbols:**

```
ffffffff810b5270-ffffffff810b5289: copy_init_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cb570)
Location: kernel/fork.c:2589
Inline: False
Direct callers:
  - arch/x86/mm/init.c:poking_init
```
**Symbols:**

```
ffffffff810cb570-ffffffff810cb591: copy_init_mm (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f4bf8)
Location: kernel/fork.c:2326
Inline: False
```
**Symbols:**

```
ffff8000100f4bf8-ffff8000100f4c20: copy_init_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c035339c)
Location: kernel/fork.c:2326
Inline: False
```
**Symbols:**

```
c035339c-c03533c4: copy_init_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013ac40)
Location: kernel/fork.c:2326
Inline: False
```
**Symbols:**

```
c00000000013ac40-c00000000013ac60: copy_init_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c1370)
Location: kernel/fork.c:2326
Inline: False
```
**Symbols:**

```
ffffffe0000c1370-ffffffe0000c139c: copy_init_mm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81099cb0)
Location: kernel/fork.c:2326
Inline: False
Direct callers:
  - arch/x86/mm/init.c:poking_init
```
**Symbols:**

```
ffffffff81099cb0-ffffffff81099cc9: copy_init_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810886f0)
Location: kernel/fork.c:2326
Inline: False
Direct callers:
  - arch/x86/mm/init.c:poking_init
```
**Symbols:**

```
ffffffff810886f0-ffffffff81088709: copy_init_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81099c60)
Location: kernel/fork.c:2326
Inline: False
Direct callers:
  - arch/x86/mm/init.c:poking_init
```
**Symbols:**

```
ffffffff81099c60-ffffffff81099c79: copy_init_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mm_struct *copy_init_mm();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a18b0)
Location: kernel/fork.c:2326
Inline: False
Direct callers:
  - arch/x86/mm/init.c:poking_init
```
**Symbols:**

```
ffffffff810a18b0-ffffffff810a18c9: copy_init_mm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
