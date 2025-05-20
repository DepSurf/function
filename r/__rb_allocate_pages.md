# Function: <code>__rb_allocate_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __rb_allocate_pages(int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81148200)
Location: kernel/trace/ring_buffer.c:1140
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81148200-ffffffff81148368: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81150040)
Location: kernel/trace/ring_buffer.c:1131
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81150040-ffffffff811501a7: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115b170)
Location: kernel/trace/ring_buffer.c:1129
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff8115b170-ffffffff8115b2d2: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115e060)
Location: kernel/trace/ring_buffer.c:1131
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff8115e060-ffffffff8115e1ad: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116b010)
Location: kernel/trace/ring_buffer.c:1134
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff8116b010-ffffffff8116b159: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117a080)
Location: kernel/trace/ring_buffer.c:1163
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff8117a080-ffffffff8117a29a: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81187050)
Location: kernel/trace/ring_buffer.c:1211
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81187050-ffffffff81187267: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81194460)
Location: kernel/trace/ring_buffer.c:1188
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81194460-ffffffff8119467b: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119ff20)
Location: kernel/trace/ring_buffer.c:1189
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff8119ff20-ffffffff811a013b: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5550)
Location: kernel/trace/ring_buffer.c:1191
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff811b5550-ffffffff811b576d: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __rb_allocate_pages(struct ring_buffer_per_cpu *cpu_buffer, long int nr_pages, struct list_head *pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b2e20)
Location: kernel/trace/ring_buffer.c:1435
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff811b2e20-ffffffff811b304b: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __rb_allocate_pages(struct ring_buffer_per_cpu *cpu_buffer, long int nr_pages, struct list_head *pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b36b0)
Location: kernel/trace/ring_buffer.c:1518
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff811b36b0-ffffffff811b38db: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __rb_allocate_pages(struct ring_buffer_per_cpu *cpu_buffer, long int nr_pages, struct list_head *pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dd470)
Location: kernel/trace/ring_buffer.c:1518
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff811dd470-ffffffff811dd6db: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __rb_allocate_pages(struct ring_buffer_per_cpu *cpu_buffer, long int nr_pages, struct list_head *pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812141f0)
Location: kernel/trace/ring_buffer.c:1554
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff812141f0-ffffffff8121447c: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __rb_allocate_pages(struct ring_buffer_per_cpu *cpu_buffer, long int nr_pages, struct list_head *pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125dd00)
Location: kernel/trace/ring_buffer.c:1616
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff8125dd00-ffffffff8125df8c: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __rb_allocate_pages(struct ring_buffer_per_cpu *cpu_buffer, long int nr_pages, struct list_head *pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81274f70)
Location: kernel/trace/ring_buffer.c:1610
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81274f70-ffffffff812751fc: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __rb_allocate_pages(struct ring_buffer_per_cpu *cpu_buffer, long int nr_pages, struct list_head *pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128f880)
Location: kernel/trace/ring_buffer.c:1439
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff8128f880-ffffffff8128fb2f: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010217790)
Location: kernel/trace/ring_buffer.c:1189
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffff800010217790-ffff8000102179b4: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (c04571ac)
Location: kernel/trace/ring_buffer.c:1189
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
c04571ac-c0457384: __rb_allocate_pages.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029b6b0)
Location: kernel/trace/ring_buffer.c:1189
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
c00000000029b6b0-c00000000029b9a0: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000177ad2)
Location: kernel/trace/ring_buffer.c:1189
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffe000177ad2-ffffffe000177c2a: __rb_allocate_pages.isra.0 (STB_LOCAL)
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
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81198540)
Location: kernel/trace/ring_buffer.c:1189
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81198540-ffffffff8119875b: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118ba50)
Location: kernel/trace/ring_buffer.c:1189
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff8118ba50-ffffffff8118bc6b: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196310)
Location: kernel/trace/ring_buffer.c:1189
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff81196310-ffffffff8119652b: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __rb_allocate_pages(long int nr_pages, struct list_head *pages, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a3f20)
Location: kernel/trace/ring_buffer.c:1189
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
**Symbols:**

```
ffffffff811a3f20-ffffffff811a413b: __rb_allocate_pages (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int nr_pages</code> ➡️ <code>long int nr_pages</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ring_buffer_per_cpu *cpu_buffer</code>
</li>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
<li>
<b>Param reordered. </b>
<code>nr_pages, pages, cpu</code> ➡️ <code>cpu_buffer, nr_pages, pages</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
