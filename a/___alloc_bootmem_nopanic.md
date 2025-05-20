# Function: <code>___alloc_bootmem_nopanic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *___alloc_bootmem_nopanic(long unsigned int size, long unsigned int align, long unsigned int goal, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81f8ac4d)
Location: mm/nobootmem.c:234
Inline: True
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_nopanic
  - mm/nobootmem.c:__alloc_bootmem
  - mm/nobootmem.c:__alloc_bootmem_low
  - mm/nobootmem.c:__alloc_bootmem_low_nopanic
```
**Symbols:**

```
ffffffff81f8ac4d-ffffffff81f8acc6: ___alloc_bootmem_nopanic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *___alloc_bootmem_nopanic(long unsigned int size, long unsigned int align, long unsigned int goal, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81fb488a)
Location: mm/nobootmem.c:235
Inline: True
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_nopanic
  - mm/nobootmem.c:__alloc_bootmem_low
  - mm/nobootmem.c:__alloc_bootmem
  - mm/nobootmem.c:__alloc_bootmem_nopanic
```
**Symbols:**

```
ffffffff81fb488a-ffffffff81fb4905: ___alloc_bootmem_nopanic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *___alloc_bootmem_nopanic(long unsigned int size, long unsigned int align, long unsigned int goal, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81ff1276)
Location: mm/nobootmem.c:238
Inline: True
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_nopanic
  - mm/nobootmem.c:__alloc_bootmem_low
  - mm/nobootmem.c:__alloc_bootmem
  - mm/nobootmem.c:__alloc_bootmem_nopanic
```
**Symbols:**

```
ffffffff81ff1276-ffffffff81ff12f1: ___alloc_bootmem_nopanic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *___alloc_bootmem_nopanic(long unsigned int size, long unsigned int align, long unsigned int goal, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff820d36b8)
Location: mm/nobootmem.c:222
Inline: True
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_nopanic
  - mm/nobootmem.c:__alloc_bootmem_low
  - mm/nobootmem.c:__alloc_bootmem
  - mm/nobootmem.c:__alloc_bootmem_nopanic
```
**Symbols:**

```
ffffffff820d36b8-ffffffff820d3717: ___alloc_bootmem_nopanic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *___alloc_bootmem_nopanic(long unsigned int size, long unsigned int align, long unsigned int goal, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff826dc0d8)
Location: mm/nobootmem.c:223
Inline: True
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_nopanic
  - mm/nobootmem.c:__alloc_bootmem_low
  - mm/nobootmem.c:__alloc_bootmem
  - mm/nobootmem.c:__alloc_bootmem_nopanic
```
**Symbols:**

```
ffffffff826dc0d8-ffffffff826dc137: ___alloc_bootmem_nopanic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *___alloc_bootmem_nopanic(long unsigned int size, long unsigned int align, long unsigned int goal, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff827065a1)
Location: mm/nobootmem.c:223
Inline: False
Direct callers:
  - mm/nobootmem.c:__alloc_bootmem_low_nopanic
  - mm/nobootmem.c:__alloc_bootmem_low
  - mm/nobootmem.c:__alloc_bootmem
  - mm/nobootmem.c:__alloc_bootmem_nopanic
```
**Symbols:**

```
ffffffff827065a1-ffffffff82706600: ___alloc_bootmem_nopanic (STB_LOCAL)
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
