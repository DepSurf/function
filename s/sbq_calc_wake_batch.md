# Function: <code>sbq_calc_wake_batch</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81482031)
Location: lib/sbitmap.c:183
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_resize
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
In lib/sbitmap.c (ffffffff8148b271)
Location: lib/sbitmap.c:273
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_resize
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
In lib/sbitmap.c (ffffffff814c7391)
Location: lib/sbitmap.c:273
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_resize
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
In lib/sbitmap.c (ffffffff814f8943)
Location: lib/sbitmap.c:273
Inline: True
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
In lib/sbitmap.c (ffffffff8150cdb3)
Location: lib/sbitmap.c:351
Inline: True
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
In lib/sbitmap.c (ffffffff8153b4a3)
Location: lib/sbitmap.c:338
Inline: True
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
In lib/sbitmap.c (ffffffff8155c283)
Location: lib/sbitmap.c:338
Inline: True
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
In lib/sbitmap.c (ffffffff815e5dd3)
Location: lib/sbitmap.c:321
Inline: True
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
In lib/sbitmap.c (ffffffff8160a183)
Location: lib/sbitmap.c:316
Inline: True
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
In lib/sbitmap.c (ffffffff815ed486)
Location: lib/sbitmap.c:398
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int sbq_calc_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:398
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
  - lib/sbitmap.c:sbitmap_queue_init_node
```
**Symbols:**

```
ffffffff81659c30-ffffffff81659ca0: sbq_calc_wake_batch (STB_LOCAL)
ffffffff81cded18-ffffffff81cded99: sbq_calc_wake_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int sbq_calc_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:391
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
  - lib/sbitmap.c:sbitmap_queue_init_node
```
**Symbols:**

```
ffffffff81772370-ffffffff817723ec: sbq_calc_wake_batch (STB_LOCAL)
ffffffff81ea51cf-ffffffff81ea5250: sbq_calc_wake_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int sbq_calc_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (ffffffff818a38d0)
Location: lib/sbitmap.c:391
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
**Symbols:**

```
ffffffff818a2bf0-ffffffff818a2c70: sbq_calc_wake_batch (STB_LOCAL)
ffffffff8208d654-ffffffff8208d6cf: sbq_calc_wake_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int sbq_calc_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (ffffffff818e5dbe)
Location: lib/sbitmap.c:384
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
**Symbols:**

```
ffffffff818e5150-ffffffff818e51c9: sbq_calc_wake_batch (STB_LOCAL)
ffffffff8210d9f2-ffffffff8210da5d: sbq_calc_wake_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int sbq_calc_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (ffffffff8192cdbe)
Location: lib/sbitmap.c:384
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
**Symbols:**

```
ffffffff8192c150-ffffffff8192c1c9: sbq_calc_wake_batch (STB_LOCAL)
ffffffff821eb62f-ffffffff821eb69a: sbq_calc_wake_batch.cold (STB_LOCAL)
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
In lib/sbitmap.c (ffff8000106691fc)
Location: lib/sbitmap.c:338
Inline: True
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
In lib/sbitmap.c (c0811e44)
Location: lib/sbitmap.c:338
Inline: True
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
In lib/sbitmap.c (c00000000081f4e4)
Location: lib/sbitmap.c:338
Inline: True
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
In lib/sbitmap.c (ffffffe0004945f0)
Location: lib/sbitmap.c:338
Inline: True
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
In lib/sbitmap.c (ffffffff81554873)
Location: lib/sbitmap.c:338
Inline: True
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
In lib/sbitmap.c (ffffffff81544af3)
Location: lib/sbitmap.c:338
Inline: True
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
In lib/sbitmap.c (ffffffff815505b3)
Location: lib/sbitmap.c:338
Inline: True
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
In lib/sbitmap.c (ffffffff8156a3f3)
Location: lib/sbitmap.c:338
Inline: True
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
