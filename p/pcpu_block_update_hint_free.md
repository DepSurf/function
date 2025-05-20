# Function: <code>pcpu_block_update_hint_free</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811fa1ac)
Location: mm/percpu.c:784
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
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
In mm/percpu.c (ffffffff8121a345)
Location: mm/percpu.c:781
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
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
In mm/percpu.c (ffffffff8122d257)
Location: mm/percpu.c:789
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
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
In mm/percpu.c (ffffffff8123cf3c)
Location: mm/percpu.c:931
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
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
In mm/percpu.c (ffffffff8124b38c)
Location: mm/percpu.c:931
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcpu_block_update_hint_free(struct pcpu_chunk *chunk, int bit_off, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812790a0)
Location: mm/percpu.c:903
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
```
**Symbols:**

```
ffffffff812790a0-ffffffff81279310: pcpu_block_update_hint_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcpu_block_update_hint_free(struct pcpu_chunk *chunk, int bit_off, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81283910)
Location: mm/percpu.c:912
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
```
**Symbols:**

```
ffffffff81283910-ffffffff81283ba6: pcpu_block_update_hint_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcpu_block_update_hint_free(struct pcpu_chunk *chunk, int bit_off, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812894e0)
Location: mm/percpu.c:913
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
```
**Symbols:**

```
ffffffff812894e0-ffffffff8128979d: pcpu_block_update_hint_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pcpu_block_update_hint_free(struct pcpu_chunk *chunk, int bit_off, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:960
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
```
**Symbols:**

```
ffffffff812c9200-ffffffff812c9476: pcpu_block_update_hint_free (STB_LOCAL)
ffffffff81cbafff-ffffffff81cbb019: pcpu_block_update_hint_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pcpu_block_update_hint_free(struct pcpu_chunk *chunk, int bit_off, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:959
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
```
**Symbols:**

```
ffffffff81327680-ffffffff81327953: pcpu_block_update_hint_free (STB_LOCAL)
ffffffff81e6cc14-ffffffff81e6cc2e: pcpu_block_update_hint_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pcpu_block_update_hint_free(struct pcpu_chunk *chunk, int bit_off, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:963
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
```
**Symbols:**

```
ffffffff8139c4f0-ffffffff8139c7b6: pcpu_block_update_hint_free (STB_LOCAL)
ffffffff820630a0-ffffffff820630bb: pcpu_block_update_hint_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pcpu_block_update_hint_free(struct pcpu_chunk *chunk, int bit_off, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:963
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
```
**Symbols:**

```
ffffffff813cf5d0-ffffffff813cf896: pcpu_block_update_hint_free (STB_LOCAL)
ffffffff820e293d-ffffffff820e2958: pcpu_block_update_hint_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pcpu_block_update_hint_free(struct pcpu_chunk *chunk, int bit_off, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:963
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
```
**Symbols:**

```
ffffffff813fa1d0-ffffffff813fa496: pcpu_block_update_hint_free (STB_LOCAL)
ffffffff821bf32e-ffffffff821bf349: pcpu_block_update_hint_free.cold (STB_LOCAL)
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
In mm/percpu.c (ffff8000102e1588)
Location: mm/percpu.c:931
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
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
In mm/percpu.c (c0506708)
Location: mm/percpu.c:931
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
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
In mm/percpu.c (c0000000003a23ac)
Location: mm/percpu.c:931
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
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
In mm/percpu.c (ffffffe0001f9146)
Location: mm/percpu.c:931
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
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
In mm/percpu.c (ffffffff812439dc)
Location: mm/percpu.c:931
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
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
In mm/percpu.c (ffffffff812369ac)
Location: mm/percpu.c:931
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
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
In mm/percpu.c (ffffffff8124177c)
Location: mm/percpu.c:931
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
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
In mm/percpu.c (ffffffff81250efc)
Location: mm/percpu.c:931
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
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
