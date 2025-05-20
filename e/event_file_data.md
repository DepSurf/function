# Function: <code>event_file_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8115d758)
Location: kernel/trace/trace.h:1143
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81165b9f)
Location: kernel/trace/trace.h:1143
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:trigger_next
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:event_trigger_open
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
In kernel/trace/trace_events.c (ffffffff81168dcd)
Location: kernel/trace/trace.h:1318
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117088d)
Location: kernel/trace/trace.h:1318
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_hist.c (ffffffff81172d60)
Location: kernel/trace/trace.h:1318
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff8117422d)
Location: kernel/trace/trace.h:1338
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117bffd)
Location: kernel/trace/trace.h:1338
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_hist.c (ffffffff8117e55d)
Location: kernel/trace/trace.h:1338
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff81176e3a)
Location: kernel/trace/trace.h:1457
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117eccd)
Location: kernel/trace/trace.h:1457
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_hist.c (ffffffff8118115e)
Location: kernel/trace/trace.h:1457
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff81184606)
Location: kernel/trace/trace.h:1459
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8118c578)
Location: kernel/trace/trace.h:1459
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_hist.c (ffffffff8118ea95)
Location: kernel/trace/trace.h:1459
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff811936ff)
Location: kernel/trace/trace.h:1464
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8119afc8)
Location: kernel/trace/trace.h:1464
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_hist.c (ffffffff8119fba5)
Location: kernel/trace/trace.h:1464
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff811a186f)
Location: kernel/trace/trace.h:1527
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811a91c8)
Location: kernel/trace/trace.h:1527
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_hist.c (ffffffff811aecb5)
Location: kernel/trace/trace.h:1527
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff811af793)
Location: kernel/trace/trace.h:1575
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b7128)
Location: kernel/trace/trace.h:1575
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bd1bf)
Location: kernel/trace/trace.h:1575
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff811bae13)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c2797)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c855f)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff811d36c3)
Location: kernel/trace/trace.h:1662
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dcb88)
Location: kernel/trace/trace.h:1662
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_inject.c (ffffffff811dd938)
Location: kernel/trace/trace.h:1662
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e2a6f)
Location: kernel/trace/trace.h:1662
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff811d0813)
Location: kernel/trace/trace.h:1519
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811d9cb8)
Location: kernel/trace/trace.h:1519
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_inject.c (ffffffff811daa38)
Location: kernel/trace/trace.h:1519
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e068f)
Location: kernel/trace/trace.h:1519
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff811d19b3)
Location: kernel/trace/trace.h:1489
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811da827)
Location: kernel/trace/trace.h:1489
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_inject.c (ffffffff811dbfa8)
Location: kernel/trace/trace.h:1489
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e1800)
Location: kernel/trace/trace.h:1489
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff811fe713)
Location: kernel/trace/trace.h:1507
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81207d97)
Location: kernel/trace/trace.h:1507
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_inject.c (ffffffff8120b6d8)
Location: kernel/trace/trace.h:1507
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In kernel/trace/trace_events_hist.c (ffffffff81211980)
Location: kernel/trace/trace.h:1507
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff81239513)
Location: kernel/trace/trace.h:1518
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81243891)
Location: kernel/trace/trace.h:1518
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_inject.c (ffffffff812477e8)
Location: kernel/trace/trace.h:1518
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In kernel/trace/trace_events_hist.c (ffffffff8124de90)
Location: kernel/trace/trace.h:1518
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff81286123)
Location: kernel/trace/trace.h:1506
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81291441)
Location: kernel/trace/trace.h:1506
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_inject.c (ffffffff81295e68)
Location: kernel/trace/trace.h:1506
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In kernel/trace/trace_events_hist.c (ffffffff8129cfa0)
Location: kernel/trace/trace.h:1506
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff812a2de3)
Location: kernel/trace/trace.h:1539
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812ae70f)
Location: kernel/trace/trace.h:1539
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_inject.c (ffffffff812b2e08)
Location: kernel/trace/trace.h:1539
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In kernel/trace/trace_events_hist.c (ffffffff812ba930)
Location: kernel/trace/trace.h:1539
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff812bebb3)
Location: kernel/trace/trace.h:1557
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cac2f)
Location: kernel/trace/trace.h:1557
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_inject.c (ffffffff812cf3b8)
Location: kernel/trace/trace.h:1557
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:event_inject_write
```
```
In kernel/trace/trace_events_hist.c (ffffffff812d6f80)
Location: kernel/trace/trace.h:1557
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffff8000102394e4)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffff800010241ef4)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_hist.c (ffff800010248c6c)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0474f68)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (c047db44)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
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
In kernel/trace/trace_events.c (c0000000002c6cc0)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (c0000000002d3e18)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_hist.c (c0000000002dd3d4)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffe0001903d0)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffe000196db4)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
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
In kernel/trace/trace_events.c (ffffffff811b3433)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811badb7)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c0b7f)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff811a6233)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811adb97)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b395f)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff811b1203)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b8b87)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_hist.c (ffffffff811be94f)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
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
In kernel/trace/trace_events.c (ffffffff811bf2a3)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_id_read
  - kernel/trace/trace_events.c:f_start
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events.c:f_next
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:event_enable_read
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c6c27)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:trigger_start
  - kernel/trace/trace_events_trigger.c:trigger_next
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cc9ef)
Location: kernel/trace/trace.h:1595
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_show
```
</details>
</li>
</ul>

## Differences
