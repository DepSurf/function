# Function: <code>regmap_name</code>

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
In drivers/base/regmap/regmap.c (ffffffff8156204b)
Location: drivers/base/regmap/internal.h:258
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (ffffffff815b7ac7)
Location: drivers/base/regmap/internal.h:260
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (ffffffff815e6e07)
Location: drivers/base/regmap/internal.h:261
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (ffffffff815fb807)
Location: drivers/base/regmap/internal.h:261
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (ffffffff816639b0)
Location: drivers/base/regmap/internal.h:263
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (ffffffff8169fb00)
Location: drivers/base/regmap/internal.h:271
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (ffffffff816bff10)
Location: drivers/base/regmap/internal.h:277
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (ffffffff816fad70)
Location: drivers/base/regmap/internal.h:274
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (ffffffff8171f120)
Location: drivers/base/regmap/internal.h:274
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (ffffffff817dad64)
Location: drivers/base/regmap/internal.h:274
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff817eff34)
Location: drivers/base/regmap/internal.h:277
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff817d4974)
Location: drivers/base/regmap/internal.h:277
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff8185fb44)
Location: drivers/base/regmap/internal.h:281
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff819a6caf)
Location: drivers/base/regmap/internal.h:287
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff81b19b0f)
Location: drivers/base/regmap/internal.h:287
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bulk
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bulk
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bulk
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff81b6873f)
Location: drivers/base/regmap/internal.h:293
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bulk
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bulk
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bulk
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff81bbc3cf)
Location: drivers/base/regmap/internal.h:293
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bulk
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bulk
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bulk
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bulk
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_get_offsets_regcache_sync
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
In drivers/base/regmap/regmap.c (ffff800010913ec4)
Location: drivers/base/regmap/internal.h:274
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (c09f8f68)
Location: drivers/base/regmap/internal.h:274
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (c0000000009b5084)
Location: drivers/base/regmap/internal.h:274
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (ffffffe0005951e4)
Location: drivers/base/regmap/internal.h:274
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (ffffffff816e5450)
Location: drivers/base/regmap/internal.h:274
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (ffffffff816bfa90)
Location: drivers/base/regmap/internal.h:274
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (ffffffff817125e0)
Location: drivers/base/regmap/internal.h:274
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
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
In drivers/base/regmap/regmap.c (ffffffff8172d7d0)
Location: drivers/base/regmap/internal.h:274
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regcache_drop_region
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_async
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regmap_bool
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_block
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:perf_trace_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_drop_region
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_async
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_bool
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_block
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regmap_reg
```
</details>
</li>
</ul>

## Differences
