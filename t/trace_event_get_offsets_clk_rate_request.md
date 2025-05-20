# Function: <code>trace_event_get_offsets_clk_rate_request</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_event_get_offsets_clk_rate_request(struct trace_event_data_offsets_clk_rate_request *__data_offsets, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f4f20)
Location: include/trace/events/clk.h:267
Inline: False
Direct callers:
  - drivers/clk/clk.c:perf_trace_clk_rate_request
  - drivers/clk/clk.c:trace_event_raw_event_clk_rate_request
```
**Symbols:**

```
ffffffff819f4f20-ffffffff819f4fea: trace_event_get_offsets_clk_rate_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_event_get_offsets_clk_rate_request(struct trace_event_data_offsets_clk_rate_request *__data_offsets, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a3d6b0)
Location: include/trace/events/clk.h:267
Inline: False
Direct callers:
  - drivers/clk/clk.c:perf_trace_clk_rate_request
  - drivers/clk/clk.c:trace_event_raw_event_clk_rate_request
```
**Symbols:**

```
ffffffff81a3d6b0-ffffffff81a3d777: trace_event_get_offsets_clk_rate_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_event_get_offsets_clk_rate_request(struct trace_event_data_offsets_clk_rate_request *__data_offsets, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a88fa0)
Location: include/trace/events/clk.h:267
Inline: False
Direct callers:
  - drivers/clk/clk.c:perf_trace_clk_rate_request
  - drivers/clk/clk.c:trace_event_raw_event_clk_rate_request
```
**Symbols:**

```
ffffffff81a88fa0-ffffffff81a89067: trace_event_get_offsets_clk_rate_request (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
