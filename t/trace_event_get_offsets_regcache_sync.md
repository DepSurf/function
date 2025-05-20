# Function: <code>trace_event_get_offsets_regcache_sync</code>

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
Location: drivers/base/regmap/trace.h:117
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff815b8038)
Location: drivers/base/regmap/trace.h:117
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff815e7378)
Location: drivers/base/regmap/trace.h:117
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff815fc517)
Location: drivers/base/regmap/trace.h:117
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff8166469c)
Location: drivers/base/regmap/trace.h:118
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff8169fcc1)
Location: drivers/base/regmap/trace.h:118
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff816c0451)
Location: drivers/base/regmap/trace.h:118
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff816fc7cd)
Location: drivers/base/regmap/trace.h:118
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff81720b7d)
Location: drivers/base/regmap/trace.h:118
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int trace_event_get_offsets_regcache_sync(struct trace_event_data_offsets_regcache_sync *__data_offsets, struct regmap *map, const char *type, const char *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d9b10)
Location: drivers/base/regmap/trace.h:118
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
```
**Symbols:**

```
ffffffff817d9b10-ffffffff817d9c15: trace_event_get_offsets_regcache_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int trace_event_get_offsets_regcache_sync(struct trace_event_data_offsets_regcache_sync *__data_offsets, struct regmap *map, const char *type, const char *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817ee940)
Location: drivers/base/regmap/trace.h:118
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
```
**Symbols:**

```
ffffffff817ee940-ffffffff817eea45: trace_event_get_offsets_regcache_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int trace_event_get_offsets_regcache_sync(struct trace_event_data_offsets_regcache_sync *__data_offsets, struct regmap *map, const char *type, const char *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d31f0)
Location: drivers/base/regmap/trace.h:118
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
```
**Symbols:**

```
ffffffff817d31f0-ffffffff817d32f5: trace_event_get_offsets_regcache_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trace_event_get_offsets_regcache_sync(struct trace_event_data_offsets_regcache_sync *__data_offsets, struct regmap *map, const char *type, const char *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8185e3f0)
Location: drivers/base/regmap/trace.h:118
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
```
**Symbols:**

```
ffffffff8185e3f0-ffffffff8185e4f5: trace_event_get_offsets_regcache_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trace_event_get_offsets_regcache_sync(struct trace_event_data_offsets_regcache_sync *__data_offsets, struct regmap *map, const char *type, const char *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff819a5ac0)
Location: drivers/base/regmap/trace.h:118
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
```
**Symbols:**

```
ffffffff819a5ac0-ffffffff819a5bc3: trace_event_get_offsets_regcache_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_event_get_offsets_regcache_sync(struct trace_event_data_offsets_regcache_sync *__data_offsets, struct regmap *map, const char *type, const char *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b17fe0)
Location: drivers/base/regmap/trace.h:152
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
```
**Symbols:**

```
ffffffff81b17fe0-ffffffff81b180d8: trace_event_get_offsets_regcache_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_event_get_offsets_regcache_sync(struct trace_event_data_offsets_regcache_sync *__data_offsets, struct regmap *map, const char *type, const char *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b66de0)
Location: drivers/base/regmap/trace.h:152
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
```
**Symbols:**

```
ffffffff81b66de0-ffffffff81b66ed8: trace_event_get_offsets_regcache_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_event_get_offsets_regcache_sync(struct trace_event_data_offsets_regcache_sync *__data_offsets, struct regmap *map, const char *type, const char *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81bbac30)
Location: drivers/base/regmap/trace.h:152
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
```
**Symbols:**

```
ffffffff81bbac30-ffffffff81bbad28: trace_event_get_offsets_regcache_sync (STB_LOCAL)
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
In drivers/base/regmap/regmap.c (ffff800010914050)
Location: drivers/base/regmap/trace.h:118
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
In drivers/base/regmap/regmap.c (c09f9f5c)
Location: drivers/base/regmap/trace.h:118
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
In drivers/base/regmap/regmap.c (c0000000009b62d4)
Location: drivers/base/regmap/trace.h:118
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffe000594cca)
Location: drivers/base/regmap/trace.h:118
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff816e6ead)
Location: drivers/base/regmap/trace.h:118
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff816c14ed)
Location: drivers/base/regmap/trace.h:118
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff8171403d)
Location: drivers/base/regmap/trace.h:118
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
In drivers/base/regmap/regmap.c (ffffffff8172f22d)
Location: drivers/base/regmap/trace.h:118
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:perf_trace_regcache_sync
  - drivers/base/regmap/regmap.c:trace_event_raw_event_regcache_sync
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
