# Function: <code>perf_mmap_free_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_mmap_free_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811851e0)
Location: kernel/events/ring_buffer.c:664
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
**Symbols:**

```
ffffffff811851e0-ffffffff8118522c: perf_mmap_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_mmap_free_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81197040)
Location: kernel/events/ring_buffer.c:735
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
**Symbols:**

```
ffffffff81197040-ffffffff81197093: perf_mmap_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_mmap_free_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811a6a50)
Location: kernel/events/ring_buffer.c:735
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
**Symbols:**

```
ffffffff811a6a50-ffffffff811a6a9d: perf_mmap_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_mmap_free_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811ae220)
Location: kernel/events/ring_buffer.c:747
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
**Symbols:**

```
ffffffff811ae220-ffffffff811ae26d: perf_mmap_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_mmap_free_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811c1e90)
Location: kernel/events/ring_buffer.c:758
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
**Symbols:**

```
ffffffff811c1e90-ffffffff811c1edd: perf_mmap_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_mmap_free_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811e2250)
Location: kernel/events/ring_buffer.c:760
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
**Symbols:**

```
ffffffff811e2250-ffffffff811e229d: perf_mmap_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_mmap_free_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811f26c0)
Location: kernel/events/ring_buffer.c:773
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
**Symbols:**

```
ffffffff811f26c0-ffffffff811f270d: perf_mmap_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_mmap_free_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120a390)
Location: kernel/events/ring_buffer.c:802
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
**Symbols:**

```
ffffffff8120a390-ffffffff8120a3dd: perf_mmap_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_mmap_free_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81217670)
Location: kernel/events/ring_buffer.c:802
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
**Symbols:**

```
ffffffff81217670-ffffffff812176bd: perf_mmap_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812442b5)
Location: kernel/events/ring_buffer.c:793
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8124e965)
Location: kernel/events/ring_buffer.c:795
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
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
In kernel/events/ring_buffer.c (ffffffff81253275)
Location: kernel/events/ring_buffer.c:797
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
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
In kernel/events/ring_buffer.c (ffffffff8128eb95)
Location: kernel/events/ring_buffer.c:797
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812e3a85)
Location: kernel/events/ring_buffer.c:797
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8134c145)
Location: kernel/events/ring_buffer.c:800
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8137d195)
Location: kernel/events/ring_buffer.c:800
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff813a63f5)
Location: kernel/events/ring_buffer.c:807
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffff8000102a318c)
Location: kernel/events/ring_buffer.c:802
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c000000000355624)
Location: kernel/events/ring_buffer.c:802
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffe0001d1a0a)
Location: kernel/events/ring_buffer.c:802
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void perf_mmap_free_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120fcc0)
Location: kernel/events/ring_buffer.c:802
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
**Symbols:**

```
ffffffff8120fcc0-ffffffff8120fd0d: perf_mmap_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_mmap_free_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81202a50)
Location: kernel/events/ring_buffer.c:802
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
**Symbols:**

```
ffffffff81202a50-ffffffff81202a9d: perf_mmap_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_mmap_free_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120da60)
Location: kernel/events/ring_buffer.c:802
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
**Symbols:**

```
ffffffff8120da60-ffffffff8120daad: perf_mmap_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_mmap_free_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8121c910)
Location: kernel/events/ring_buffer.c:802
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free
  - kernel/events/ring_buffer.c:rb_free
```
**Symbols:**

```
ffffffff8121c910-ffffffff8121c95d: perf_mmap_free_page (STB_LOCAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
