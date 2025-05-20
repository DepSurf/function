# Function: <code>latency_exceeded</code>

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
In block/blk-wbt.c (ffffffff8144a2e1)
Location: block/blk-wbt.c:332
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff8145836b)
Location: block/blk-wbt.c:280
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff814840cb)
Location: block/blk-wbt.c:279
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff814b91fb)
Location: block/blk-wbt.c:308
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff814cd4bb)
Location: block/blk-wbt.c:233
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff814fc091)
Location: block/blk-wbt.c:234
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff8151a021)
Location: block/blk-wbt.c:234
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int latency_exceeded(struct rq_wb *rwb, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8157a710)
Location: block/blk-wbt.c:234
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff8157a710-ffffffff8157a951: latency_exceeded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int latency_exceeded(struct rq_wb *rwb, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815972b0)
Location: block/blk-wbt.c:234
Inline: False
Direct callers:
  - block/blk-wbt.c:wb_timer_fn
```
**Symbols:**

```
ffffffff815972b0-ffffffff815974a7: latency_exceeded (STB_LOCAL)
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
In block/blk-wbt.c (ffffffff8159e5db)
Location: block/blk-wbt.c:235
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff81606d0d)
Location: block/blk-wbt.c:235
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff816ba81b)
Location: block/blk-wbt.c:235
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff8177adfb)
Location: block/blk-wbt.c:236
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff817ba984)
Location: block/blk-wbt.c:304
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff817ff0f4)
Location: block/blk-wbt.c:303
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffff800010621e30)
Location: block/blk-wbt.c:234
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (c07c9308)
Location: block/blk-wbt.c:234
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (c0000000007c1e74)
Location: block/blk-wbt.c:234
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffe000453cda)
Location: block/blk-wbt.c:234
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff81512601)
Location: block/blk-wbt.c:234
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff81502921)
Location: block/blk-wbt.c:234
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff8150e691)
Location: block/blk-wbt.c:234
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
In block/blk-wbt.c (ffffffff81527df1)
Location: block/blk-wbt.c:234
Inline: True
Inline callers:
  - block/blk-wbt.c:wb_timer_fn
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
</ul>
