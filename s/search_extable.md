# Function: <code>search_extable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *first, const struct exception_table_entry *last, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106c010)
Location: arch/x86/mm/extable.c:82
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffffffff8106c010-ffffffff8106c051: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *first, const struct exception_table_entry *last, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff8142fa60)
Location: lib/extable.c:104
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffffffff8142fa60-ffffffff8142fab1: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *first, const struct exception_table_entry *last, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff8144bc90)
Location: lib/extable.c:104
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffffffff8144bc90-ffffffff8144bce1: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff818ec470)
Location: lib/extable.c:119
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffffffff818ec470-ffffffff818ec499: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff81972440)
Location: lib/extable.c:119
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffffffff81972440-ffffffff81972469: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff819ce870)
Location: lib/extable.c:119
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffffffff819ce870-ffffffff819ce899: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff81a07d30)
Location: lib/extable.c:119
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffffffff81a07d30-ffffffff81a07d59: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff81a77680)
Location: lib/extable.c:115
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffffffff81a77680-ffffffff81a776a9: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff81aaea70)
Location: lib/extable.c:116
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffffffff81aaea70-ffffffff81aaea99: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff815e87c0)
Location: lib/extable.c:116
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
  - kernel/bpf/core.c:search_bpf_extables
```
**Symbols:**

```
ffffffff815e87c0-ffffffff815e87e9: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff8160d870)
Location: lib/extable.c:116
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
  - kernel/bpf/core.c:search_bpf_extables
```
**Symbols:**

```
ffffffff8160d870-ffffffff8160d899: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff815f0fb0)
Location: lib/extable.c:112
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
  - kernel/bpf/core.c:search_bpf_extables
```
**Symbols:**

```
ffffffff815f0fb0-ffffffff815f0fd9: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff8165e0f0)
Location: lib/extable.c:112
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
  - kernel/bpf/core.c:search_bpf_extables
```
**Symbols:**

```
ffffffff8165e0f0-ffffffff8165e119: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff817777d0)
Location: lib/extable.c:112
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module/main.c:search_module_extables
  - kernel/bpf/core.c:search_bpf_extables
```
**Symbols:**

```
ffffffff817777d0-ffffffff81777808: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff82020420)
Location: lib/extable.c:112
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module/main.c:search_module_extables
  - kernel/bpf/core.c:search_bpf_extables
```
**Symbols:**

```
ffffffff82020420-ffffffff82020458: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff820a0460)
Location: lib/extable.c:112
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module/main.c:search_module_extables
  - kernel/bpf/core.c:search_bpf_extables
```
**Symbols:**

```
ffffffff820a0460-ffffffff820a0498: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff82178430)
Location: lib/extable.c:112
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module/main.c:search_module_extables
  - kernel/bpf/core.c:search_bpf_extables
```
**Symbols:**

```
ffffffff82178430-ffffffff82178468: search_extable (STB_GLOBAL)
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
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffff800010d85028)
Location: lib/extable.c:116
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffff800010d85028-ffff800010d8505c: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (c0e8002c)
Location: lib/extable.c:116
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
c0e8002c-c0e8006c: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (c000000000ec4070)
Location: lib/extable.c:116
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
c000000000ec4070-c000000000ec40c0: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffe0008aefb8)
Location: lib/extable.c:116
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffffffe0008aefb8-ffffffe0008aefe6: search_extable (STB_GLOBAL)
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
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff81a4d8c0)
Location: lib/extable.c:116
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffffffff81a4d8c0-ffffffff81a4d8e9: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff81a0a9d0)
Location: lib/extable.c:116
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffffffff81a0a9d0-ffffffff81a0a9f9: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff81ab9cb0)
Location: lib/extable.c:116
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffffffff81ab9cb0-ffffffff81ab9cd9: search_extable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct exception_table_entry *search_extable(const struct exception_table_entry *base, const size_t num, long unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/extable.c (ffffffff81ac6100)
Location: lib/extable.c:116
Inline: False
Direct callers:
  - kernel/extable.c:search_exception_tables
  - kernel/module.c:search_module_extables
```
**Symbols:**

```
ffffffff81ac6100-ffffffff81ac6129: search_extable (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct exception_table_entry *base</code>
</li>
<li>
<b>Param added. </b>
<code>const size_t num</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct exception_table_entry *first</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct exception_table_entry *last</code>
</li>
</ul>
</details>
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
