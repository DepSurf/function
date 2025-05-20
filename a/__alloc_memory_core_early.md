# Function: <code>__alloc_memory_core_early</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *__alloc_memory_core_early(int nid, u64 size, u64 align, u64 goal, u64 limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81f8ab79)
Location: mm/nobootmem.c:35
Inline: False
Direct callers:
  - mm/nobootmem.c:___alloc_bootmem_node_nopanic
  - mm/nobootmem.c:___alloc_bootmem_node_nopanic
```
**Symbols:**

```
ffffffff81f8ab79-ffffffff81f8ac2e: __alloc_memory_core_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__alloc_memory_core_early(int nid, u64 size, u64 align, u64 goal, u64 limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81fb47bf)
Location: mm/nobootmem.c:36
Inline: False
Direct callers:
  - mm/nobootmem.c:___alloc_bootmem_node_nopanic
  - mm/nobootmem.c:___alloc_bootmem_node_nopanic
```
**Symbols:**

```
ffffffff81fb47bf-ffffffff81fb486b: __alloc_memory_core_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__alloc_memory_core_early(int nid, u64 size, u64 align, u64 goal, u64 limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81ff11ab)
Location: mm/nobootmem.c:39
Inline: False
Direct callers:
  - mm/nobootmem.c:___alloc_bootmem_node_nopanic
  - mm/nobootmem.c:___alloc_bootmem_node_nopanic
```
**Symbols:**

```
ffffffff81ff11ab-ffffffff81ff1257: __alloc_memory_core_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__alloc_memory_core_early(int nid, u64 size, u64 align, u64 goal, u64 limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff820d35e3)
Location: mm/nobootmem.c:39
Inline: False
Direct callers:
  - mm/nobootmem.c:___alloc_bootmem_node_nopanic
  - mm/nobootmem.c:___alloc_bootmem_node_nopanic
```
**Symbols:**

```
ffffffff820d35e3-ffffffff820d3694: __alloc_memory_core_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__alloc_memory_core_early(int nid, u64 size, u64 align, u64 goal, u64 limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff826dc003)
Location: mm/nobootmem.c:40
Inline: False
Direct callers:
  - mm/nobootmem.c:___alloc_bootmem_node_nopanic
  - mm/nobootmem.c:___alloc_bootmem_node_nopanic
```
**Symbols:**

```
ffffffff826dc003-ffffffff826dc0b4: __alloc_memory_core_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__alloc_memory_core_early(int nid, u64 size, u64 align, u64 goal, u64 limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff827064f0)
Location: mm/nobootmem.c:40
Inline: False
Direct callers:
  - mm/nobootmem.c:___alloc_bootmem_node_nopanic
  - mm/nobootmem.c:___alloc_bootmem_node_nopanic
  - mm/nobootmem.c:___alloc_bootmem_nopanic
```
**Symbols:**

```
ffffffff827064f0-ffffffff827065a1: __alloc_memory_core_early (STB_LOCAL)
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
