# Function: <code>__ioremap_check_ram</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __ioremap_check_ram(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106b8e0)
Location: arch/x86/mm/ioremap.c:56
Inline: False
```
**Symbols:**

```
ffffffff8106b8e0-ffffffff8106b959: __ioremap_check_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __ioremap_check_ram(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106b7c0)
Location: arch/x86/mm/ioremap.c:55
Inline: False
```
**Symbols:**

```
ffffffff8106b7c0-ffffffff8106b839: __ioremap_check_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __ioremap_check_ram(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106f3e0)
Location: arch/x86/mm/ioremap.c:55
Inline: False
```
**Symbols:**

```
ffffffff8106f3e0-ffffffff8106f453: __ioremap_check_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __ioremap_check_ram(long unsigned int start_pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106eb30)
Location: arch/x86/mm/ioremap.c:56
Inline: False
```
**Symbols:**

```
ffffffff8106eb30-ffffffff8106eba2: __ioremap_check_ram (STB_LOCAL)
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
In arch/x86/mm/ioremap.c (ffffffff81073bee)
Location: arch/x86/mm/ioremap.c:64
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
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
In arch/x86/mm/ioremap.c (ffffffff8107662e)
Location: arch/x86/mm/ioremap.c:64
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
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
In arch/x86/mm/ioremap.c (ffffffff8107cc7e)
Location: arch/x86/mm/ioremap.c:64
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_res_check
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
In arch/x86/mm/ioremap.c (ffffffff810808ea)
Location: arch/x86/mm/ioremap.c:68
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
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
In arch/x86/mm/ioremap.c (ffffffff810815ba)
Location: arch/x86/mm/ioremap.c:69
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int __ioremap_check_ram(struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81088500)
Location: arch/x86/mm/ioremap.c:69
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
**Symbols:**

```
ffffffff81088500-ffffffff810885de: __ioremap_check_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int __ioremap_check_ram(struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81088740)
Location: arch/x86/mm/ioremap.c:69
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
**Symbols:**

```
ffffffff81088740-ffffffff8108881e: __ioremap_check_ram (STB_LOCAL)
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
In arch/x86/mm/ioremap.c (ffffffff8108944c)
Location: arch/x86/mm/ioremap.c:69
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
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
In arch/x86/mm/ioremap.c (ffffffff810988dc)
Location: arch/x86/mm/ioremap.c:69
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int __ioremap_check_ram(struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810ab480)
Location: arch/x86/mm/ioremap.c:69
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
**Symbols:**

```
ffffffff810ab480-ffffffff810ab5e3: __ioremap_check_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int __ioremap_check_ram(struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c58c0)
Location: arch/x86/mm/ioremap.c:70
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
**Symbols:**

```
ffffffff810c58c0-ffffffff810c5a1d: __ioremap_check_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int __ioremap_check_ram(struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810c9050)
Location: arch/x86/mm/ioremap.c:70
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
**Symbols:**

```
ffffffff810c9050-ffffffff810c9187: __ioremap_check_ram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int __ioremap_check_ram(struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff810d0d10)
Location: arch/x86/mm/ioremap.c:70
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
```
**Symbols:**

```
ffffffff810d0d10-ffffffff810d0e98: __ioremap_check_ram (STB_LOCAL)
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
In arch/x86/mm/ioremap.c (ffffffff810805ba)
Location: arch/x86/mm/ioremap.c:69
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
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
In arch/x86/mm/ioremap.c (ffffffff8106f50a)
Location: arch/x86/mm/ioremap.c:69
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
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
In arch/x86/mm/ioremap.c (ffffffff8108056a)
Location: arch/x86/mm/ioremap.c:69
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
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
In arch/x86/mm/ioremap.c (ffffffff8108268a)
Location: arch/x86/mm/ioremap.c:69
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_collect_map_flags
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
