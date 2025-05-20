# Function: <code>__gnet_stats_copy_queue_cpu</code>

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
In net/core/gen_stats.c (ffffffff8170f1d9)
Location: net/core/gen_stats.c:222
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
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
In net/core/gen_stats.c (ffffffff81776a47)
Location: net/core/gen_stats.c:241
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
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
In net/core/gen_stats.c (ffffffff817a3cc7)
Location: net/core/gen_stats.c:239
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
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
In net/core/gen_stats.c (ffffffff817c1d67)
Location: net/core/gen_stats.c:239
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
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
In net/core/gen_stats.c (ffffffff8183b79a)
Location: net/core/gen_stats.c:239
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __gnet_stats_copy_queue_cpu(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81885c60)
Location: net/core/gen_stats.c:251
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
**Symbols:**

```
ffffffff81885c60-ffffffff81885cc7: __gnet_stats_copy_queue_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __gnet_stats_copy_queue_cpu(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818a6390)
Location: net/core/gen_stats.c:286
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
**Symbols:**

```
ffffffff818a6390-ffffffff818a63f1: __gnet_stats_copy_queue_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __gnet_stats_copy_queue_cpu(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818f1780)
Location: net/core/gen_stats.c:282
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
**Symbols:**

```
ffffffff818f1780-ffffffff818f17e0: __gnet_stats_copy_queue_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __gnet_stats_copy_queue_cpu(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819236d0)
Location: net/core/gen_stats.c:282
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
**Symbols:**

```
ffffffff819236d0-ffffffff81923730: __gnet_stats_copy_queue_cpu (STB_LOCAL)
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
In net/core/gen_stats.c (0)
Location: net/core/gen_stats.c:286
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_queue
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
In net/core/gen_stats.c (0)
Location: net/core/gen_stats.c:286
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_queue
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
In net/core/gen_stats.c (ffffffff819dce71)
Location: net/core/gen_stats.c:286
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_queue
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
In net/core/gen_stats.c (0)
Location: net/core/gen_stats.c:286
Inline: True
Inline callers:
  - net/core/gen_stats.c:__gnet_stats_copy_queue
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __gnet_stats_copy_queue_cpu(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffff800010bbec60)
Location: net/core/gen_stats.c:282
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
**Symbols:**

```
ffff800010bbec60-ffff800010bbed10: __gnet_stats_copy_queue_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __gnet_stats_copy_queue_cpu(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (c0cda688)
Location: net/core/gen_stats.c:282
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
**Symbols:**

```
c0cda688-c0cda728: __gnet_stats_copy_queue_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __gnet_stats_copy_queue_cpu(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (c000000000c97d30)
Location: net/core/gen_stats.c:282
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
**Symbols:**

```
c000000000c97d30-c000000000c97e28: __gnet_stats_copy_queue_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __gnet_stats_copy_queue_cpu(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffe00074c68c)
Location: net/core/gen_stats.c:282
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
**Symbols:**

```
ffffffe00074c68c-ffffffe00074c720: __gnet_stats_copy_queue_cpu (STB_LOCAL)
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
void __gnet_stats_copy_queue_cpu(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818c36d0)
Location: net/core/gen_stats.c:282
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
**Symbols:**

```
ffffffff818c36d0-ffffffff818c3730: __gnet_stats_copy_queue_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __gnet_stats_copy_queue_cpu(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8187d610)
Location: net/core/gen_stats.c:282
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
**Symbols:**

```
ffffffff8187d610-ffffffff8187d670: __gnet_stats_copy_queue_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __gnet_stats_copy_queue_cpu(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819146d0)
Location: net/core/gen_stats.c:282
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
**Symbols:**

```
ffffffff819146d0-ffffffff81914730: __gnet_stats_copy_queue_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __gnet_stats_copy_queue_cpu(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819358a0)
Location: net/core/gen_stats.c:282
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
**Symbols:**

```
ffffffff819358a0-ffffffff81935900: __gnet_stats_copy_queue_cpu (STB_LOCAL)
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
