# Function: <code>lru_add_drain_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119e050)
Location: mm/swap.c:807
Inline: False
Direct callers:
  - mm/page_alloc.c:page_alloc_cpu_notify
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:__pagevec_release
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff8119e050-ffffffff8119e11c: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b38e0)
Location: mm/swap.c:584
Inline: False
Direct callers:
  - mm/page_alloc.c:page_alloc_cpu_notify
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811b38e0-ffffffff811b39d9: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c3f70)
Location: mm/swap.c:585
Inline: False
Direct callers:
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811c3f70-ffffffff811c4069: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cc360)
Location: mm/swap.c:604
Inline: False
Direct callers:
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811cc360-ffffffff811cc459: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e1350)
Location: mm/swap.c:604
Inline: False
Direct callers:
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811e1350-ffffffff811e1449: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81202a70)
Location: mm/swap.c:577
Inline: False
Direct callers:
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81202a70-ffffffff81202ba9: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812153f0)
Location: mm/swap.c:571
Inline: False
Direct callers:
  - mm/page_alloc.c:page_alloc_cpu_dead
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff812153f0-ffffffff81215529: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81224e10)
Location: mm/swap.c:572
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffff81224e10-ffffffff81224f48: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81232ba0)
Location: mm/swap.c:589
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffff81232ba0-ffffffff81232d15: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81260080)
Location: mm/swap.c:626
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffff81260080-ffffffff8126022a: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126aa90)
Location: mm/swap.c:611
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffff8126aa90-ffffffff8126abdc: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126fc70)
Location: mm/swap.c:614
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffff8126fc70-ffffffff8126fdb5: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812acf70)
Location: mm/swap.c:592
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffff812acf70-ffffffff812ad193: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81306fe0)
Location: mm/swap.c:596
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffff81306fe0-ffffffff813071f8: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81370b00)
Location: mm/swap.c:676
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffff81370b00-ffffffff81370cae: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813a2ce0)
Location: mm/swap.c:646
Inline: False
Direct callers:
  - mm/swap.c:__folio_batch_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffff813a2ce0-ffffffff813a2e8e: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813cc960)
Location: mm/swap.c:646
Inline: False
Direct callers:
  - mm/swap.c:__folio_batch_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/swap.c:lru_add_drain_cpu_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffff813cc960-ffffffff813ccb0e: lru_add_drain_cpu (STB_GLOBAL)
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
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c2bb0)
Location: mm/swap.c:589
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffff8000102c2bb0-ffff8000102c2d38: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04edcd8)
Location: mm/swap.c:589
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
c04edcd8-c04ede18: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037cd10)
Location: mm/swap.c:589
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
c00000000037cd10-c00000000037cef4: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e3e8e)
Location: mm/swap.c:589
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffe0001e3e8e-ffffffe0001e400e: lru_add_drain_cpu (STB_GLOBAL)
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
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122b1f0)
Location: mm/swap.c:589
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffff8122b1f0-ffffffff8122b365: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121e300)
Location: mm/swap.c:589
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffff8121e300-ffffffff8121e460: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81228f90)
Location: mm/swap.c:589
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:lru_add_drain_per_cpu
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffff81228f90-ffffffff81229105: lru_add_drain_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void lru_add_drain_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81238350)
Location: mm/swap.c:589
Inline: False
Direct callers:
  - mm/swap.c:lru_add_drain
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:page_alloc_cpu_dead
```
**Symbols:**

```
ffffffff81238350-ffffffff812384c5: lru_add_drain_cpu (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
