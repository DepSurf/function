# Function: <code>trace_event_get_offsets_dma_fence</code>

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
In drivers/dma-buf/dma-fence.c (ffffffff8162991e)
Location: include/trace/events/dma_fence.h:51
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff8163f8ee)
Location: include/trace/events/dma_fence.h:51
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff816a8453)
Location: include/trace/events/dma_fence.h:12
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff816e4749)
Location: include/trace/events/dma_fence.h:12
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff81707b39)
Location: include/trace/events/dma_fence.h:12
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff81742d69)
Location: include/trace/events/dma_fence.h:12
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff81766d39)
Location: include/trace/events/dma_fence.h:12
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int trace_event_get_offsets_dma_fence(struct trace_event_data_offsets_dma_fence *__data_offsets, struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818263d0)
Location: include/trace/events/dma_fence.h:12
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
```
**Symbols:**

```
ffffffff818263d0-ffffffff8182648a: trace_event_get_offsets_dma_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int trace_event_get_offsets_dma_fence(struct trace_event_data_offsets_dma_fence *__data_offsets, struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81836ef0)
Location: include/trace/events/dma_fence.h:12
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
```
**Symbols:**

```
ffffffff81836ef0-ffffffff81836faa: trace_event_get_offsets_dma_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int trace_event_get_offsets_dma_fence(struct trace_event_data_offsets_dma_fence *__data_offsets, struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff8181a0b0)
Location: include/trace/events/dma_fence.h:12
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
```
**Symbols:**

```
ffffffff8181a0b0-ffffffff8181a16a: trace_event_get_offsets_dma_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trace_event_get_offsets_dma_fence(struct trace_event_data_offsets_dma_fence *__data_offsets, struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff818a4560)
Location: include/trace/events/dma_fence.h:12
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
```
**Symbols:**

```
ffffffff818a4560-ffffffff818a461a: trace_event_get_offsets_dma_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trace_event_get_offsets_dma_fence(struct trace_event_data_offsets_dma_fence *__data_offsets, struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff819edeb0)
Location: include/trace/events/dma_fence.h:12
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
```
**Symbols:**

```
ffffffff819edeb0-ffffffff819edf74: trace_event_get_offsets_dma_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_event_get_offsets_dma_fence(struct trace_event_data_offsets_dma_fence *__data_offsets, struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81b6b290)
Location: include/trace/events/dma_fence.h:12
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
```
**Symbols:**

```
ffffffff81b6b290-ffffffff81b6b354: trace_event_get_offsets_dma_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_event_get_offsets_dma_fence(struct trace_event_data_offsets_dma_fence *__data_offsets, struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81bbe700)
Location: include/trace/events/dma_fence.h:12
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
```
**Symbols:**

```
ffffffff81bbe700-ffffffff81bbe7c4: trace_event_get_offsets_dma_fence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_event_get_offsets_dma_fence(struct trace_event_data_offsets_dma_fence *__data_offsets, struct dma_fence *fence);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-fence.c (ffffffff81c12e50)
Location: include/trace/events/dma_fence.h:12
Inline: False
Direct callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
```
**Symbols:**

```
ffffffff81c12e50-ffffffff81c12f14: trace_event_get_offsets_dma_fence (STB_LOCAL)
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
In drivers/dma-buf/dma-fence.c (ffff800010966e58)
Location: include/trace/events/dma_fence.h:12
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
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
In drivers/dma-buf/dma-fence.c (c0a3dec0)
Location: include/trace/events/dma_fence.h:12
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
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
In drivers/dma-buf/dma-fence.c (c000000000a1f184)
Location: include/trace/events/dma_fence.h:12
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
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
In drivers/dma-buf/dma-fence.c (ffffffe0005d3724)
Location: include/trace/events/dma_fence.h:12
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff8171b429)
Location: include/trace/events/dma_fence.h:12
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff816f4889)
Location: include/trace/events/dma_fence.h:12
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff8175a1f9)
Location: include/trace/events/dma_fence.h:12
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
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
In drivers/dma-buf/dma-fence.c (ffffffff817757b9)
Location: include/trace/events/dma_fence.h:12
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:perf_trace_dma_fence
  - drivers/dma-buf/dma-fence.c:trace_event_raw_event_dma_fence
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
