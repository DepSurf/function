# Function: <code>memtype_check_insert</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int memtype_check_insert(struct memtype *entry_new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810910f0)
Location: arch/x86/mm/pat/memtype_interval.c:116
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_reserve
```
**Symbols:**

```
ffffffff810910f0-ffffffff8109113b: memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int memtype_check_insert(struct memtype *entry_new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090ab0)
Location: arch/x86/mm/pat/memtype_interval.c:116
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_reserve
```
**Symbols:**

```
ffffffff81090ab0-ffffffff81090afb: memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int memtype_check_insert(struct memtype *entry_new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (0)
Location: arch/x86/mm/pat/memtype_interval.c:116
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_reserve
```
**Symbols:**

```
ffffffff81bcbc5c-ffffffff81bcbcec: memtype_check_insert.cold (STB_LOCAL)
ffffffff81091550-ffffffff81091633: memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int memtype_check_insert(struct memtype *entry_new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (0)
Location: arch/x86/mm/pat/memtype_interval.c:116
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_reserve
```
**Symbols:**

```
ffffffff81ca1870-ffffffff81ca1900: memtype_check_insert.cold (STB_LOCAL)
ffffffff810a10d0-ffffffff810a11b3: memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int memtype_check_insert(struct memtype *entry_new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (0)
Location: arch/x86/mm/pat/memtype_interval.c:116
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_reserve
```
**Symbols:**

```
ffffffff81e50e90-ffffffff81e50f1e: memtype_check_insert.cold (STB_LOCAL)
ffffffff810b5190-ffffffff810b5287: memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memtype_check_insert(struct memtype *entry_new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810cfff0)
Location: arch/x86/mm/pat/memtype_interval.c:116
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_reserve
```
**Symbols:**

```
ffffffff810cfff0-ffffffff810d01cd: memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int memtype_check_insert(struct memtype *entry_new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d3610)
Location: arch/x86/mm/pat/memtype_interval.c:116
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_reserve
```
**Symbols:**

```
ffffffff810d3610-ffffffff810d37e8: memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int memtype_check_insert(struct memtype *entry_new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810dbda0)
Location: arch/x86/mm/pat/memtype_interval.c:116
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:memtype_reserve
```
**Symbols:**

```
ffffffff810dbda0-ffffffff810dbf78: memtype_check_insert (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
