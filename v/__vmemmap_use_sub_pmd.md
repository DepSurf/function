# Function: <code>__vmemmap_use_sub_pmd</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __vmemmap_use_sub_pmd(long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c2ee0d)
Location: arch/x86/mm/init_64.c:867
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
```
**Symbols:**

```
ffffffff81c2ee0d-ffffffff81c2ee17: __vmemmap_use_sub_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __vmemmap_use_sub_pmd(long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4d50e)
Location: arch/x86/mm/init_64.c:868
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
```
**Symbols:**

```
ffffffff81d4d50e-ffffffff81d4d518: __vmemmap_use_sub_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __vmemmap_use_sub_pmd(long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1d20c)
Location: arch/x86/mm/init_64.c:867
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
```
**Symbols:**

```
ffffffff81f1d20c-ffffffff81f1d222: __vmemmap_use_sub_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __vmemmap_use_sub_pmd(long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c5340)
Location: arch/x86/mm/init_64.c:868
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_check_pmd
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
```
**Symbols:**

```
ffffffff820c5340-ffffffff820c5373: __vmemmap_use_sub_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __vmemmap_use_sub_pmd(long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff821493a0)
Location: arch/x86/mm/init_64.c:868
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_check_pmd
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
```
**Symbols:**

```
ffffffff821493a0-ffffffff821493d3: __vmemmap_use_sub_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __vmemmap_use_sub_pmd(long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222be60)
Location: arch/x86/mm/init_64.c:868
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_check_pmd
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
```
**Symbols:**

```
ffffffff8222be60-ffffffff8222be93: __vmemmap_use_sub_pmd (STB_LOCAL)
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
