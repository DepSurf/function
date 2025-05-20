# Function: <code>memtype_reserve_io</code>

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
int memtype_reserve_io(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81090230)
Location: arch/x86/mm/pat/memtype.c:763
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff81090230-ffffffff81090344: memtype_reserve_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int memtype_reserve_io(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff8108ff30)
Location: arch/x86/mm/pat/memtype.c:763
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff8108ff30-ffffffff81090044: memtype_reserve_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int memtype_reserve_io(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff81090aa0)
Location: arch/x86/mm/pat/memtype.c:763
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff81090aa0-ffffffff81090bb4: memtype_reserve_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int memtype_reserve_io(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810a05f0)
Location: arch/x86/mm/pat/memtype.c:768
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff810a05f0-ffffffff810a06f8: memtype_reserve_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int memtype_reserve_io(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810b4570)
Location: arch/x86/mm/pat/memtype.c:776
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff810b4570-ffffffff810b468e: memtype_reserve_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memtype_reserve_io(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810cf220)
Location: arch/x86/mm/pat/memtype.c:729
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff810cf220-ffffffff810cf33e: memtype_reserve_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int memtype_reserve_io(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810d27d0)
Location: arch/x86/mm/pat/memtype.c:729
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff810d27d0-ffffffff810d28ee: memtype_reserve_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int memtype_reserve_io(resource_size_t start, resource_size_t end, enum page_cache_mode *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810daf60)
Location: arch/x86/mm/pat/memtype.c:729
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype.c:arch_io_reserve_memtype_wc
```
**Symbols:**

```
ffffffff810daf60-ffffffff810db07e: memtype_reserve_io (STB_GLOBAL)
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
