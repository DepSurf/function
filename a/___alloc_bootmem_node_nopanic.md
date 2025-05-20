# Function: <code>___alloc_bootmem_node_nopanic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *___alloc_bootmem_node_nopanic(pg_data_t *pgdat, long unsigned int size, long unsigned int align, long unsigned int goal, long unsigned int limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81f8aef9)
Location: mm/nobootmem.c:316
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
  - mm/nobootmem.c:__alloc_bootmem_low_node
```
**Symbols:**

```
ffffffff81f8aef9-ffffffff81f8af60: ___alloc_bootmem_node_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *___alloc_bootmem_node_nopanic(pg_data_t *pgdat, long unsigned int size, long unsigned int align, long unsigned int goal, long unsigned int limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81fb4b3c)
Location: mm/nobootmem.c:317
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
```
**Symbols:**

```
ffffffff81fb4b3c-ffffffff81fb4ba3: ___alloc_bootmem_node_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *___alloc_bootmem_node_nopanic(pg_data_t *pgdat, long unsigned int size, long unsigned int align, long unsigned int goal, long unsigned int limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81ff1522)
Location: mm/nobootmem.c:320
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
```
**Symbols:**

```
ffffffff81ff1522-ffffffff81ff1589: ___alloc_bootmem_node_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *___alloc_bootmem_node_nopanic(pg_data_t *pgdat, long unsigned int size, long unsigned int align, long unsigned int goal, long unsigned int limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff820d39ac)
Location: mm/nobootmem.c:304
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
```
**Symbols:**

```
ffffffff820d39ac-ffffffff820d3a18: ___alloc_bootmem_node_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *___alloc_bootmem_node_nopanic(pg_data_t *pgdat, long unsigned int size, long unsigned int align, long unsigned int goal, long unsigned int limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff826dc3cc)
Location: mm/nobootmem.c:305
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
```
**Symbols:**

```
ffffffff826dc3cc-ffffffff826dc438: ___alloc_bootmem_node_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *___alloc_bootmem_node_nopanic(pg_data_t *pgdat, long unsigned int size, long unsigned int align, long unsigned int goal, long unsigned int limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff8270689d)
Location: mm/nobootmem.c:305
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_node
  - mm/nobootmem.c:__alloc_bootmem_node
  - mm/nobootmem.c:__alloc_bootmem_node_nopanic
```
**Symbols:**

```
ffffffff8270689d-ffffffff82706909: ___alloc_bootmem_node_nopanic (STB_GLOBAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
