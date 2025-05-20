# Function: <code>pcpu_chunk_depopulated</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811b1915)
Location: mm/percpu.c:792
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811caaae)
Location: mm/percpu.c:787
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811dabd0)
Location: mm/percpu.c:787
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811e457a)
Location: mm/percpu.c:778
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811f9a93)
Location: mm/percpu.c:1255
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8121bc98)
Location: mm/percpu.c:1252
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122ec78)
Location: mm/percpu.c:1262
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123e250)
Location: mm/percpu.c:1496
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124c6a3)
Location: mm/percpu.c:1496
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
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
In mm/percpu.c (ffffffff8127a8e1)
Location: mm/percpu.c:1468
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
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
In mm/percpu.c (ffffffff81285073)
Location: mm/percpu.c:1505
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
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
In mm/percpu.c (ffffffff8128afe9)
Location: mm/percpu.c:1506
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pcpu_chunk_depopulated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1547
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
```
**Symbols:**

```
ffffffff812c8eb0-ffffffff812c8f21: pcpu_chunk_depopulated (STB_LOCAL)
ffffffff81cbafeb-ffffffff81cbafff: pcpu_chunk_depopulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pcpu_chunk_depopulated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1547
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
```
**Symbols:**

```
ffffffff81326b60-ffffffff81326bdb: pcpu_chunk_depopulated (STB_LOCAL)
ffffffff81e6cba0-ffffffff81e6cbb4: pcpu_chunk_depopulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pcpu_chunk_depopulated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1544
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
```
**Symbols:**

```
ffffffff8139b800-ffffffff8139b87b: pcpu_chunk_depopulated (STB_LOCAL)
ffffffff82063040-ffffffff82063054: pcpu_chunk_depopulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pcpu_chunk_depopulated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1544
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
```
**Symbols:**

```
ffffffff813ce7e0-ffffffff813ce85b: pcpu_chunk_depopulated (STB_LOCAL)
ffffffff820e28dd-ffffffff820e28f1: pcpu_chunk_depopulated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pcpu_chunk_depopulated(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1544
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
```
**Symbols:**

```
ffffffff813f9340-ffffffff813f93bb: pcpu_chunk_depopulated (STB_LOCAL)
ffffffff821bf2ce-ffffffff821bf2e2: pcpu_chunk_depopulated.cold (STB_LOCAL)
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
In mm/percpu.c (ffff8000102e2d44)
Location: mm/percpu.c:1496
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0506ff4)
Location: mm/percpu.c:1496
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0000000003a3894)
Location: mm/percpu.c:1496
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
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
In mm/percpu.c (ffffffe0001f9ee4)
Location: mm/percpu.c:1496
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81244cf3)
Location: mm/percpu.c:1496
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812379fd)
Location: mm/percpu.c:1496
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81242a93)
Location: mm/percpu.c:1496
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81251f7a)
Location: mm/percpu.c:1496
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
