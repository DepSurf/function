# Function: <code>search_kernel_exception_table</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c66d5)
Location: kernel/extable.c:45
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff810c6690-ffffffff810c66ca: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810ce745)
Location: kernel/extable.c:46
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff810ce700-ffffffff810ce73a: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c9265)
Location: kernel/extable.c:46
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff810c9220-ffffffff810c925a: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810cacf5)
Location: kernel/extable.c:46
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff810cacb0-ffffffff810cacea: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810dddd5)
Location: kernel/extable.c:46
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff810ddd90-ffffffff810dddca: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810f7a15)
Location: kernel/extable.c:47
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff810f79c0-ffffffff810f7a04: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff8111a225)
Location: kernel/extable.c:47
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff8111a1c0-ffffffff8111a204: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff81127495)
Location: kernel/extable.c:47
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff81127430-ffffffff81127474: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff81131a75)
Location: kernel/extable.c:47
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff81131a10-ffffffff81131a54: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffff800010125230)
Location: kernel/extable.c:45
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffff8000101251d0-ffff800010125214: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (c0378038)
Location: kernel/extable.c:45
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
c0377fe8-c0378024: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (c00000000016efb0)
Location: kernel/extable.c:45
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
Direct callers:
  - arch/powerpc/kernel/mce_power.c:mce_handle_error
```
**Symbols:**

```
c00000000016ef30-c00000000016ef84: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffe0000dcfe2)
Location: kernel/extable.c:45
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffe0000dcf8e-ffffffe0000dcfcc: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c0a55)
Location: kernel/extable.c:45
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff810c0a10-ffffffff810c0a4a: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810af245)
Location: kernel/extable.c:45
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff810af200-ffffffff810af23a: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810bffa5)
Location: kernel/extable.c:45
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff810bff60-ffffffff810bff9a: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const struct exception_table_entry *search_kernel_exception_table(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c83d5)
Location: kernel/extable.c:45
Inline: True
Inline callers:
  - kernel/extable.c:search_exception_tables
```
**Symbols:**

```
ffffffff810c8390-ffffffff810c83ca: search_kernel_exception_table (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
