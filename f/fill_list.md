# Function: <code>fill_list</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fill_list(unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (0)
Location: drivers/xen/unpopulated-alloc.c:18
Inline: False
Direct callers:
  - drivers/xen/unpopulated-alloc.c:xen_alloc_unpopulated_pages
```
**Symbols:**

```
ffffffff817436d0-ffffffff817438f5: fill_list (STB_LOCAL)
ffffffff81c06575-ffffffff81c065b6: fill_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fill_list(unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (0)
Location: drivers/xen/unpopulated-alloc.c:18
Inline: False
Direct callers:
  - drivers/xen/unpopulated-alloc.c:xen_alloc_unpopulated_pages
```
**Symbols:**

```
ffffffff817270c0-ffffffff817272eb: fill_list (STB_LOCAL)
ffffffff81bf820b-ffffffff81bf824c: fill_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fill_list(unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (0)
Location: drivers/xen/unpopulated-alloc.c:18
Inline: False
Direct callers:
  - drivers/xen/unpopulated-alloc.c:xen_alloc_unpopulated_pages
```
**Symbols:**

```
ffffffff817a6140-ffffffff817a636b: fill_list (STB_LOCAL)
ffffffff81cf735b-ffffffff81cf739c: fill_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fill_list(unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (0)
Location: drivers/xen/unpopulated-alloc.c:34
Inline: False
Direct callers:
  - drivers/xen/unpopulated-alloc.c:xen_alloc_unpopulated_pages
```
**Symbols:**

```
ffffffff818e0150-ffffffff818e0488: fill_list (STB_LOCAL)
ffffffff81ebf485-ffffffff81ebf501: fill_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fill_list(unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff81a34610)
Location: drivers/xen/unpopulated-alloc.c:34
Inline: False
Direct callers:
  - drivers/xen/unpopulated-alloc.c:xen_alloc_unpopulated_pages
```
**Symbols:**

```
ffffffff81a34610-ffffffff81a349a4: fill_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fill_list(unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff81a7e020)
Location: drivers/xen/unpopulated-alloc.c:34
Inline: False
Direct callers:
  - drivers/xen/unpopulated-alloc.c:xen_alloc_unpopulated_pages
```
**Symbols:**

```
ffffffff81a7e020-ffffffff81a7e3b4: fill_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fill_list(unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff81ad0500)
Location: drivers/xen/unpopulated-alloc.c:34
Inline: False
Direct callers:
  - drivers/xen/unpopulated-alloc.c:xen_alloc_unpopulated_pages
```
**Symbols:**

```
ffffffff81ad0500-ffffffff81ad0924: fill_list (STB_LOCAL)
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
