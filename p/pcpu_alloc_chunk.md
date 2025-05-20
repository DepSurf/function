# Function: <code>pcpu_alloc_chunk</code>

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
In mm/percpu.c (ffffffff811b0ed6)
Location: mm/percpu.c:724
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (ffffffff811ca096)
Location: mm/percpu.c:719
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (ffffffff811da1a6)
Location: mm/percpu.c:719
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (ffffffff811e3806)
Location: mm/percpu.c:709
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (ffffffff811f9296)
Location: mm/percpu.c:1160
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (ffffffff8121ae65)
Location: mm/percpu.c:1157
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (ffffffff8122de15)
Location: mm/percpu.c:1165
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (ffffffff8123dbb5)
Location: mm/percpu.c:1404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (ffffffff8124c005)
Location: mm/percpu.c:1404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_chunk(gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812794e0)
Location: mm/percpu.c:1376
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff812794e0-ffffffff812795c8: pcpu_alloc_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_chunk(enum pcpu_chunk_type type, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81283d20)
Location: mm/percpu.c:1396
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff81283d20-ffffffff81283e3b: pcpu_alloc_chunk (STB_LOCAL)
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
In mm/percpu.c (ffffffff81289333)
Location: mm/percpu.c:1397
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_chunk(gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c83d0)
Location: mm/percpu.c:1441
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff812c83d0-ffffffff812c84e8: pcpu_alloc_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_chunk(gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81325d10)
Location: mm/percpu.c:1441
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff81325d10-ffffffff81325e36: pcpu_alloc_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_chunk(gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8139a830)
Location: mm/percpu.c:1438
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff8139a830-ffffffff8139a956: pcpu_alloc_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_chunk(gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813cd8d0)
Location: mm/percpu.c:1438
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff813cd8d0-ffffffff813cd9f6: pcpu_alloc_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_chunk(gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813f8240)
Location: mm/percpu.c:1438
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
```
**Symbols:**

```
ffffffff813f8240-ffffffff813f8366: pcpu_alloc_chunk (STB_LOCAL)
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
In mm/percpu.c (ffff8000102e28ec)
Location: mm/percpu.c:1404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (c0506ba4)
Location: mm/percpu.c:1404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (c0000000003a2a14)
Location: mm/percpu.c:1404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (ffffffe0001f94e4)
Location: mm/percpu.c:1404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (ffffffff81244655)
Location: mm/percpu.c:1404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (ffffffff81237625)
Location: mm/percpu.c:1404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (ffffffff812423f5)
Location: mm/percpu.c:1404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
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
In mm/percpu.c (ffffffff81251ba5)
Location: mm/percpu.c:1404
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum pcpu_chunk_type type</code>
</li>
<li>
<b>Param reordered. </b>
<code>gfp</code> ➡️ <code>type, gfp</code>
</li>
</ul>
</details>
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
