# Function: <code>onmatch_destroy</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void onmatch_destroy(struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119c270)
Location: kernel/trace/trace_events_hist.c:3481
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff8119c270-ffffffff8119c2f7: onmatch_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void onmatch_destroy(struct action_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aa5c0)
Location: kernel/trace/trace_events_hist.c:3588
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff811aa5c0-ffffffff811aa62e: onmatch_destroy (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811be2c8)
Location: kernel/trace/trace_events_hist.c:4018
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff811c9c0a)
Location: kernel/trace/trace_events_hist.c:4135
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff811e4fda)
Location: kernel/trace/trace_events_hist.c:3231
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:onmatch_parse
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
In kernel/trace/trace_events_hist.c (ffffffff811e2a0a)
Location: kernel/trace/trace_events_hist.c:3241
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:onmatch_parse
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
In kernel/trace/trace_events_hist.c (ffffffff811e3992)
Location: kernel/trace/trace_events_hist.c:3307
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:onmatch_parse
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
In kernel/trace/trace_events_hist.c (ffffffff81213bac)
Location: kernel/trace/trace_events_hist.c:3363
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:onmatch_parse
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
In kernel/trace/trace_events_hist.c (ffffffff8124f77a)
Location: kernel/trace/trace_events_hist.c:3740
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:onmatch_parse
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
In kernel/trace/trace_events_hist.c (ffffffff8129e8fa)
Location: kernel/trace/trace_events_hist.c:3792
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:onmatch_parse
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
In kernel/trace/trace_events_hist.c (ffffffff812bc57a)
Location: kernel/trace/trace_events_hist.c:3830
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:onmatch_parse
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
In kernel/trace/trace_events_hist.c (ffffffff812d8a6a)
Location: kernel/trace/trace_events_hist.c:3823
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:onmatch_parse
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
In kernel/trace/trace_events_hist.c (ffff800010249910)
Location: kernel/trace/trace_events_hist.c:4135
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e313c)
Location: kernel/trace/trace_events_hist.c:4135
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/trace/trace_events_hist.c (ffffffff811c222a)
Location: kernel/trace/trace_events_hist.c:4135
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff811b500a)
Location: kernel/trace/trace_events_hist.c:4135
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff811bfffa)
Location: kernel/trace/trace_events_hist.c:4135
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff811ce09a)
Location: kernel/trace/trace_events_hist.c:4135
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
</ul>
