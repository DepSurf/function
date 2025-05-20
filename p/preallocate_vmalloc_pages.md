# Function: <code>preallocate_vmalloc_pages</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void preallocate_vmalloc_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff82fd3293)
Location: arch/x86/mm/init_64.c:1240
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff82fd3293-ffffffff82fd33c8: preallocate_vmalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void preallocate_vmalloc_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff831de119)
Location: arch/x86/mm/init_64.c:1285
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff831de119-ffffffff831de24e: preallocate_vmalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void preallocate_vmalloc_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff832c137d)
Location: arch/x86/mm/init_64.c:1285
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff832c137d-ffffffff832c14e7: preallocate_vmalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void preallocate_vmalloc_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff834739dd)
Location: arch/x86/mm/init_64.c:1285
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff834739dd-ffffffff83473b4a: preallocate_vmalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void preallocate_vmalloc_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff83e9b130)
Location: arch/x86/mm/init_64.c:1286
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff83e9b130-ffffffff83e9b351: preallocate_vmalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void preallocate_vmalloc_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff836bebd0)
Location: arch/x86/mm/init_64.c:1286
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff836bebd0-ffffffff836bedf1: preallocate_vmalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void preallocate_vmalloc_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff838ef670)
Location: arch/x86/mm/init_64.c:1286
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff838ef670-ffffffff838ef891: preallocate_vmalloc_pages (STB_LOCAL)
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
