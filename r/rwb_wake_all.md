# Function: <code>rwb_wake_all</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81449c40)
Location: block/blk-wbt.c:109
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_disable_default
  - block/blk-wbt.c:wbt_set_queue_depth
```
**Symbols:**

```
ffffffff81449c40-ffffffff81449ca0: rwb_wake_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814580c0)
Location: block/blk-wbt.c:109
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff814580c0-ffffffff81458117: rwb_wake_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81483e20)
Location: block/blk-wbt.c:109
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff81483e20-ffffffff81483e77: rwb_wake_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814b8c10)
Location: block/blk-wbt.c:135
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff814b8c10-ffffffff814b8c53: rwb_wake_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814ccc00)
Location: block/blk-wbt.c:114
Inline: False
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:scale_up
  - block/blk-wbt.c:wbt_rqw_done
```
**Symbols:**

```
ffffffff814ccc00-ffffffff814ccc4c: rwb_wake_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814fb450)
Location: block/blk-wbt.c:115
Inline: False
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:scale_up
  - block/blk-wbt.c:wbt_rqw_done
```
**Symbols:**

```
ffffffff814fb450-ffffffff814fb49c: rwb_wake_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815193a0)
Location: block/blk-wbt.c:115
Inline: False
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
```
**Symbols:**

```
ffffffff815193a0-ffffffff815193ec: rwb_wake_all (STB_LOCAL)
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
In block/blk-wbt.c (ffffffff8157a364)
Location: block/blk-wbt.c:115
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
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
In block/blk-wbt.c (ffffffff81597224)
Location: block/blk-wbt.c:115
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
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
In block/blk-wbt.c (ffffffff8159df3f)
Location: block/blk-wbt.c:116
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
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
In block/blk-wbt.c (ffffffff816066e1)
Location: block/blk-wbt.c:116
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
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
In block/blk-wbt.c (ffffffff816ba70f)
Location: block/blk-wbt.c:116
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
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
In block/blk-wbt.c (ffffffff8177acdf)
Location: block/blk-wbt.c:117
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
  - block/blk-wbt.c:wbt_set_min_lat
  - block/blk-wbt.c:wbt_rqw_done
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
In block/blk-wbt.c (ffffffff817ba6df)
Location: block/blk-wbt.c:184
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_update_limits
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
In block/blk-wbt.c (ffffffff817fee4f)
Location: block/blk-wbt.c:182
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_update_limits
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
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffff8000106208f8)
Location: block/blk-wbt.c:115
Inline: False
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
```
**Symbols:**

```
ffff8000106208f8-ffff800010620958: rwb_wake_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c07c87e0)
Location: block/blk-wbt.c:115
Inline: False
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
```
**Symbols:**

```
c07c87e0-c07c8834: rwb_wake_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c0000000007c0a60)
Location: block/blk-wbt.c:115
Inline: False
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
```
**Symbols:**

```
c0000000007c0a60-c0000000007c0adc: rwb_wake_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffe0004531d2)
Location: block/blk-wbt.c:115
Inline: False
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
```
**Symbols:**

```
ffffffe0004531d2-ffffffe000453224: rwb_wake_all (STB_LOCAL)
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
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81511980)
Location: block/blk-wbt.c:115
Inline: False
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
```
**Symbols:**

```
ffffffff81511980-ffffffff815119cc: rwb_wake_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81501ca0)
Location: block/blk-wbt.c:115
Inline: False
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
```
**Symbols:**

```
ffffffff81501ca0-ffffffff81501cec: rwb_wake_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8150da10)
Location: block/blk-wbt.c:115
Inline: False
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
```
**Symbols:**

```
ffffffff8150da10-ffffffff8150da5c: rwb_wake_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rwb_wake_all(struct rq_wb *rwb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81527030)
Location: block/blk-wbt.c:115
Inline: False
Direct callers:
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:__wbt_update_limits
  - block/blk-wbt.c:wbt_rqw_done
```
**Symbols:**

```
ffffffff81527030-ffffffff8152707c: rwb_wake_all (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
