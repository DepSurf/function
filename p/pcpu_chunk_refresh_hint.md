# Function: <code>pcpu_chunk_refresh_hint</code>

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
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811f9cb0)
Location: mm/percpu.c:579
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff811f9cb0-ffffffff811f9deb: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81219e40)
Location: mm/percpu.c:576
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff81219e40-ffffffff81219f31: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122cd50)
Location: mm/percpu.c:584
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff8122cd50-ffffffff8122ce41: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123c030)
Location: mm/percpu.c:718
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff8123c030-ffffffff8123c0e9: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124a480)
Location: mm/percpu.c:718
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff8124a480-ffffffff8124a539: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812786b0)
Location: mm/percpu.c:692
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff812786b0-ffffffff81278769: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81282f40)
Location: mm/percpu.c:701
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff81282f40-ffffffff81282ff9: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81288060)
Location: mm/percpu.c:702
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff81288060-ffffffff81288142: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c7790)
Location: mm/percpu.c:749
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff812c7790-ffffffff812c7872: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81324bd0)
Location: mm/percpu.c:749
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff81324bd0-ffffffff81324cb8: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813996f0)
Location: mm/percpu.c:745
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff813996f0-ffffffff813997d8: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813cc780)
Location: mm/percpu.c:745
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff813cc780-ffffffff813cc868: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813f70f0)
Location: mm/percpu.c:745
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff813f70f0-ffffffff813f71d8: pcpu_chunk_refresh_hint (STB_LOCAL)
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
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e04f0)
Location: mm/percpu.c:718
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffff8000102e04f0-ffff8000102e05ec: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0504cb8)
Location: mm/percpu.c:718
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
c0504cb8-c0504db0: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c00000000039fd30)
Location: mm/percpu.c:718
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
c00000000039fd30-c00000000039fe64: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001f7b74)
Location: mm/percpu.c:718
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffe0001f7b74-ffffffe0001f7c18: pcpu_chunk_refresh_hint (STB_LOCAL)
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
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81242ad0)
Location: mm/percpu.c:718
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff81242ad0-ffffffff81242b89: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81235aa0)
Location: mm/percpu.c:718
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff81235aa0-ffffffff81235b59: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81240870)
Location: mm/percpu.c:718
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff81240870-ffffffff81240929: pcpu_chunk_refresh_hint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcpu_chunk_refresh_hint(struct pcpu_chunk *chunk, bool full_scan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124fff0)
Location: mm/percpu.c:718
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
**Symbols:**

```
ffffffff8124fff0-ffffffff812500a9: pcpu_chunk_refresh_hint (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool full_scan</code>
</li>
</ul>
</details>
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
