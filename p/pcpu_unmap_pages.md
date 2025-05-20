# Function: <code>pcpu_unmap_pages</code>

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
In mm/percpu.c (ffffffff811b17da)
Location: mm/percpu-vm.c:151
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
In mm/percpu.c (ffffffff811ca963)
Location: mm/percpu-vm.c:151
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
In mm/percpu.c (ffffffff811daa83)
Location: mm/percpu-vm.c:151
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
In mm/percpu.c (ffffffff811e43f6)
Location: mm/percpu-vm.c:150
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
In mm/percpu.c (ffffffff811f97eb)
Location: mm/percpu-vm.c:153
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:153
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:153
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:152
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
In mm/percpu.c (ffffffff8124c594)
Location: mm/percpu-vm.c:152
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcpu_unmap_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81279310)
Location: mm/percpu-vm.c:152
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
```
**Symbols:**

```
ffffffff81279310-ffffffff81279420: pcpu_unmap_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcpu_unmap_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81283bb0)
Location: mm/percpu-vm.c:152
Inline: False
Direct callers:
  - mm/percpu.c:__pcpu_balance_workfn
```
**Symbols:**

```
ffffffff81283bb0-ffffffff81283cc0: pcpu_unmap_pages (STB_LOCAL)
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
In mm/percpu.c (ffffffff8128aed8)
Location: mm/percpu-vm.c:153
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
void pcpu_unmap_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu-vm.c:153
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
```
**Symbols:**

```
ffffffff812c81f0-ffffffff812c830c: pcpu_unmap_pages (STB_LOCAL)
ffffffff81cbad2c-ffffffff81cbad47: pcpu_unmap_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pcpu_unmap_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu-vm.c:153
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
```
**Symbols:**

```
ffffffff81325b00-ffffffff81325c2a: pcpu_unmap_pages (STB_LOCAL)
ffffffff81e6c679-ffffffff81e6c694: pcpu_unmap_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pcpu_unmap_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu-vm.c:153
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
```
**Symbols:**

```
ffffffff8139b630-ffffffff8139b762: pcpu_unmap_pages (STB_LOCAL)
ffffffff82063011-ffffffff8206302c: pcpu_unmap_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pcpu_unmap_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu-vm.c:153
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
```
**Symbols:**

```
ffffffff813ce610-ffffffff813ce742: pcpu_unmap_pages (STB_LOCAL)
ffffffff820e28ae-ffffffff820e28c9: pcpu_unmap_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pcpu_unmap_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu-vm.c:153
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
```
**Symbols:**

```
ffffffff813f9170-ffffffff813f92a2: pcpu_unmap_pages (STB_LOCAL)
ffffffff821bf29f-ffffffff821bf2ba: pcpu_unmap_pages.cold (STB_LOCAL)
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:152
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:152
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:152
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
In mm/percpu.c (ffffffe0001f9daa)
Location: mm/percpu-vm.c:152
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
In mm/percpu.c (ffffffff81244be4)
Location: mm/percpu-vm.c:152
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
In mm/percpu.c (ffffffff812378ee)
Location: mm/percpu-vm.c:152
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
In mm/percpu.c (ffffffff81242984)
Location: mm/percpu-vm.c:152
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
In mm/percpu.c (ffffffff81251e6b)
Location: mm/percpu-vm.c:152
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
