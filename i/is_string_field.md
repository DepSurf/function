# Function: <code>is_string_field</code>

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
In kernel/trace/trace_events_filter.c (0)
Location: kernel/trace/trace_events_filter.c:969
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8116ed46)
Location: kernel/trace/trace.h:1279
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:replace_preds
```
```
In kernel/trace/trace_events_hist.c (ffffffff81173703)
Location: kernel/trace/trace.h:1279
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8117a4e6)
Location: kernel/trace/trace.h:1299
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:replace_preds
```
```
In kernel/trace/trace_events_hist.c (ffffffff8117f2d1)
Location: kernel/trace/trace.h:1299
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_field
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8117d188)
Location: kernel/trace/trace.h:1415
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:replace_preds
```
```
In kernel/trace/trace_events_hist.c (ffffffff81181edf)
Location: kernel/trace/trace.h:1415
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_field
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8118aa18)
Location: kernel/trace/trace.h:1417
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:replace_preds
```
```
In kernel/trace/trace_events_hist.c (ffffffff8118f891)
Location: kernel/trace/trace.h:1417
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_field
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81198f07)
Location: kernel/trace/trace.h:1418
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_hist.c (ffffffff811a290f)
Location: kernel/trace/trace.h:1418
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:create_hist_field
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811a712e)
Location: kernel/trace/trace.h:1481
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b099b)
Location: kernel/trace/trace.h:1481
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811b4f89)
Location: kernel/trace/trace.h:1528
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_hist.c (ffffffff811be4cf)
Location: kernel/trace/trace.h:1528
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811c0672)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c9d0e)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811da3ee)
Location: kernel/trace/trace.h:1615
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_inject.c (ffffffff811dd76f)
Location: kernel/trace/trace.h:1615
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_events_inject.c:trace_alloc_entry
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_inject.c:parse_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e1e31)
Location: kernel/trace/trace.h:1615
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_tracing_map_fields
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d74d0)
Location: kernel/trace/trace.h:1471
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_inject.c (ffffffff811da86f)
Location: kernel/trace/trace.h:1471
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_events_inject.c:trace_alloc_entry
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_inject.c:parse_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff811dfa51)
Location: kernel/trace/trace.h:1471
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_tracing_map_fields
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d87ed)
Location: kernel/trace/trace.h:1441
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_inject.c (ffffffff811dbde1)
Location: kernel/trace/trace.h:1441
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_events_inject.c:trace_alloc_entry
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_inject.c:parse_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e5717)
Location: kernel/trace/trace.h:1441
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8120593b)
Location: kernel/trace/trace.h:1459
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_inject.c (ffffffff8120b511)
Location: kernel/trace/trace.h:1459
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_entry
  - kernel/trace/trace_events_inject.c:trace_alloc_entry
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_inject.c:parse_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff81215e20)
Location: kernel/trace/trace.h:1459
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812411b9)
Location: kernel/trace/trace.h:1469
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_eprobe.c (ffffffff81244f7d)
Location: kernel/trace/trace.h:1469
Inline: True
```
```
In kernel/trace/trace_events_inject.c (ffffffff81247480)
Location: kernel/trace/trace.h:1469
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:trace_alloc_entry
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_inject.c:parse_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff81253bbc)
Location: kernel/trace/trace.h:1469
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8128ecb1)
Location: kernel/trace/trace.h:1456
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_eprobe.c (ffffffff81292e1d)
Location: kernel/trace/trace.h:1456
Inline: True
```
```
In kernel/trace/trace_events_inject.c (ffffffff81295ae0)
Location: kernel/trace/trace.h:1456
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:trace_alloc_entry
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_inject.c:parse_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff812a30c4)
Location: kernel/trace/trace.h:1456
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812abd34)
Location: kernel/trace/trace.h:1489
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_eprobe.c (ffffffff812b1444)
Location: kernel/trace/trace.h:1489
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_events_inject.c (ffffffff812b29f0)
Location: kernel/trace/trace.h:1489
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:trace_alloc_entry
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_inject.c:parse_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff812c0ea2)
Location: kernel/trace/trace.h:1489
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812c804a)
Location: kernel/trace/trace.h:1507
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_eprobe.c (ffffffff812cd9f4)
Location: kernel/trace/trace.h:1507
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
```
```
In kernel/trace/trace_events_inject.c (ffffffff812cefa0)
Location: kernel/trace/trace.h:1507
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:trace_alloc_entry
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_events_inject.c:parse_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff812de859)
Location: kernel/trace/trace.h:1507
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffff80001023fcd4)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_hist.c (ffff800010249ae0)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
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
In kernel/trace/trace_events_filter.c (c047b628)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c0000000002d056c)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_hist.c (c0000000002e32d8)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
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
In kernel/trace/trace_events_filter.c (ffffffe0001951a6)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811b8c92)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c232e)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811aba72)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b510e)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811b6a62)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c00fe)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811c4b02)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_hist.c (ffffffff811ce19e)
Location: kernel/trace/trace.h:1548
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_field
```
</details>
</li>
</ul>

## Differences
