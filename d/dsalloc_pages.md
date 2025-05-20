# Function: <code>dsalloc_pages</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100dea0)
Location: arch/x86/events/intel/ds.c:318
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff8100dea0-ffffffff8100df04: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100e660)
Location: arch/x86/events/intel/ds.c:318
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff8100e660-ffffffff8100e6c4: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100eb30)
Location: arch/x86/events/intel/ds.c:318
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff8100eb30-ffffffff8100eb90: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810109f0)
Location: arch/x86/events/intel/ds.c:318
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff810109f0-ffffffff81010a52: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810110d0)
Location: arch/x86/events/intel/ds.c:318
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff810110d0-ffffffff81011132: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010da0)
Location: arch/x86/events/intel/ds.c:319
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:alloc_bts_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff81010da0-ffffffff81010df6: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810103f0)
Location: arch/x86/events/intel/ds.c:319
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:alloc_bts_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff810103f0-ffffffff81010452: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011380)
Location: arch/x86/events/intel/ds.c:384
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff81011380-ffffffff810113e2: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81012170)
Location: arch/x86/events/intel/ds.c:384
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff81012170-ffffffff81012206: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81013b00)
Location: arch/x86/events/intel/ds.c:433
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff81013b00-ffffffff81013ba2: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810181d0)
Location: arch/x86/events/intel/ds.c:440
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff810181d0-ffffffff81018272: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81017ab0)
Location: arch/x86/events/intel/ds.c:488
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff81017ab0-ffffffff81017b52: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101d5f0)
Location: arch/x86/events/intel/ds.c:493
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
**Symbols:**

```
ffffffff8101d5f0-ffffffff8101d692: dsalloc_pages (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810110d0)
Location: arch/x86/events/intel/ds.c:318
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff810110d0-ffffffff81011132: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fe70)
Location: arch/x86/events/intel/ds.c:318
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff8100fe70-ffffffff8100fed2: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011090)
Location: arch/x86/events/intel/ds.c:318
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff81011090-ffffffff810110f2: dsalloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *dsalloc_pages(size_t size, gfp_t flags, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810112a0)
Location: arch/x86/events/intel/ds.c:318
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff810112a0-ffffffff81011302: dsalloc_pages (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
