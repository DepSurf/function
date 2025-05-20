# Function: <code>pcpu_post_unmap_tlb_flush</code>

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
In mm/percpu.c (ffffffff811b0bba)
Location: mm/percpu-vm.c:183
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff811c9de6)
Location: mm/percpu-vm.c:183
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff811d9ee2)
Location: mm/percpu-vm.c:183
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff811e35fa)
Location: mm/percpu-vm.c:182
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff811f8ea7)
Location: mm/percpu-vm.c:185
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff8121a8b6)
Location: mm/percpu-vm.c:185
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff8122d866)
Location: mm/percpu-vm.c:185
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff8123d58c)
Location: mm/percpu-vm.c:184
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff8124b9dc)
Location: mm/percpu-vm.c:184
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff81279a9c)
Location: mm/percpu-vm.c:184
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_map_pages
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
In mm/percpu.c (ffffffff8128432c)
Location: mm/percpu-vm.c:184
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_map_pages
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
In mm/percpu.c (ffffffff81288f7e)
Location: mm/percpu-vm.c:185
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_map_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcpu_post_unmap_tlb_flush(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c8080)
Location: mm/percpu-vm.c:185
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_map_pages
```
**Symbols:**

```
ffffffff812c8080-ffffffff812c80c4: pcpu_post_unmap_tlb_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcpu_post_unmap_tlb_flush(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81325910)
Location: mm/percpu-vm.c:185
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_map_pages
```
**Symbols:**

```
ffffffff81325910-ffffffff81325965: pcpu_post_unmap_tlb_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcpu_post_unmap_tlb_flush(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8139a510)
Location: mm/percpu-vm.c:185
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_map_pages
```
**Symbols:**

```
ffffffff8139a510-ffffffff8139a565: pcpu_post_unmap_tlb_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcpu_post_unmap_tlb_flush(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813cd5a0)
Location: mm/percpu-vm.c:185
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_map_pages
```
**Symbols:**

```
ffffffff813cd5a0-ffffffff813cd5f5: pcpu_post_unmap_tlb_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcpu_post_unmap_tlb_flush(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813f7f10)
Location: mm/percpu-vm.c:185
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_map_pages
```
**Symbols:**

```
ffffffff813f7f10-ffffffff813f7f65: pcpu_post_unmap_tlb_flush (STB_LOCAL)
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
In mm/percpu.c (ffff8000102e1e14)
Location: mm/percpu-vm.c:184
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (c0505e64)
Location: mm/percpu-vm.c:184
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (c0000000003a1d84)
Location: mm/percpu-vm.c:184
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffe0001f8ad2)
Location: mm/percpu-vm.c:184
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff8124402c)
Location: mm/percpu-vm.c:184
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff81236ffc)
Location: mm/percpu-vm.c:184
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff81241dcc)
Location: mm/percpu-vm.c:184
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff8125156c)
Location: mm/percpu-vm.c:184
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
