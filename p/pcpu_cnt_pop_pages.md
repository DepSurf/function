# Function: <code>pcpu_cnt_pop_pages</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pcpu_cnt_pop_pages(struct pcpu_chunk *chunk, int bit_off, int bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811f9d13)
Location: mm/percpu.c:524
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_refresh_hint
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff811f8160-ffffffff811f81b2: pcpu_cnt_pop_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pcpu_cnt_pop_pages(struct pcpu_chunk *chunk, int bit_off, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81219410)
Location: mm/percpu.c:521
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff81219410-ffffffff81219462: pcpu_cnt_pop_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pcpu_cnt_pop_pages(struct pcpu_chunk *chunk, int bit_off, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122c370)
Location: mm/percpu.c:529
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_first_chunk
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff8122c370-ffffffff8122c3c2: pcpu_cnt_pop_pages (STB_LOCAL)
```
</details>
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
