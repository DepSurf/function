# Function: <code>sbitmap_queue_update_wake_batch</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814f8940)
Location: lib/sbitmap.c:346
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff814f8940-ffffffff814f89a9: sbitmap_queue_update_wake_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8150cdb0)
Location: lib/sbitmap.c:425
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff8150cdb0-ffffffff8150ce19: sbitmap_queue_update_wake_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8153b4a0)
Location: lib/sbitmap.c:412
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff8153b4a0-ffffffff8153b509: sbitmap_queue_update_wake_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8155c280)
Location: lib/sbitmap.c:412
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff8155c280-ffffffff8155c2e9: sbitmap_queue_update_wake_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815e5fd0)
Location: lib/sbitmap.c:395
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff815e5fd0-ffffffff815e6039: sbitmap_queue_update_wake_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8160a5b0)
Location: lib/sbitmap.c:390
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff8160a5b0-ffffffff8160a619: sbitmap_queue_update_wake_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815ed790)
Location: lib/sbitmap.c:460
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff815ed790-ffffffff815ed7fb: sbitmap_queue_update_wake_batch (STB_LOCAL)
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
In lib/sbitmap.c (ffffffff8165a5d4)
Location: lib/sbitmap.c:460
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
  - lib/sbitmap.c:sbitmap_queue_resize
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
In lib/sbitmap.c (ffffffff81772bcb)
Location: lib/sbitmap.c:471
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
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
In lib/sbitmap.c (ffffffff818a38d0)
Location: lib/sbitmap.c:453
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
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
In lib/sbitmap.c (ffffffff818e5dbe)
Location: lib/sbitmap.c:446
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
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
In lib/sbitmap.c (ffffffff8192cdbe)
Location: lib/sbitmap.c:441
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffff8000106691f8)
Location: lib/sbitmap.c:412
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffff8000106691f8-ffff800010669278: sbitmap_queue_update_wake_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c0811e38)
Location: lib/sbitmap.c:412
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
c0811e38-c0811ec0: sbitmap_queue_update_wake_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c00000000081f4e0)
Location: lib/sbitmap.c:412
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
c00000000081f4e0-c00000000081f59c: sbitmap_queue_update_wake_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffe0004945e8)
Location: lib/sbitmap.c:412
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffe0004945e8-ffffffe000494666: sbitmap_queue_update_wake_batch (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81554870)
Location: lib/sbitmap.c:412
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff81554870-ffffffff815548d9: sbitmap_queue_update_wake_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81544af0)
Location: lib/sbitmap.c:412
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff81544af0-ffffffff81544b59: sbitmap_queue_update_wake_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815505b0)
Location: lib/sbitmap.c:412
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff815505b0-ffffffff81550619: sbitmap_queue_update_wake_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sbitmap_queue_update_wake_batch(struct sbitmap_queue *sbq, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8156a3f0)
Location: lib/sbitmap.c:412
Inline: True
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_min_shallow_depth
  - lib/sbitmap.c:sbitmap_queue_resize
```
**Symbols:**

```
ffffffff8156a3f0-ffffffff8156a459: sbitmap_queue_update_wake_batch (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
