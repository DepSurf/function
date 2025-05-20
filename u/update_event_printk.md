# Function: <code>update_event_printk</code>

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
In kernel/trace/trace_events.c (ffffffff81160c22)
Location: kernel/trace/trace_events.c:2218
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_enum_update
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
In kernel/trace/trace_events.c (ffffffff8116b330)
Location: kernel/trace/trace_events.c:2123
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_enum_update
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
In kernel/trace/trace_events.c (ffffffff81176620)
Location: kernel/trace/trace_events.c:2092
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_enum_update
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
In kernel/trace/trace_events.c (ffffffff8117942a)
Location: kernel/trace/trace_events.c:2132
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
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
In kernel/trace/trace_events.c (ffffffff81186b88)
Location: kernel/trace/trace_events.c:2136
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
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
In kernel/trace/trace_events.c (ffffffff81195c11)
Location: kernel/trace/trace_events.c:2136
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
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
In kernel/trace/trace_events.c (ffffffff811a3d81)
Location: kernel/trace/trace_events.c:2137
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
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
In kernel/trace/trace_events.c (ffffffff811b1c4d)
Location: kernel/trace/trace_events.c:2127
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
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
In kernel/trace/trace_events.c (ffffffff811bd2cd)
Location: kernel/trace/trace_events.c:2126
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_event_printk(struct trace_event_call *call, struct trace_eval_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d34e0)
Location: kernel/trace/trace_events.c:2331
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
**Symbols:**

```
ffffffff811d34e0-ffffffff811d364b: update_event_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_event_printk(struct trace_event_call *call, struct trace_eval_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d0630)
Location: kernel/trace/trace_events.c:2344
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
**Symbols:**

```
ffffffff811d0630-ffffffff811d079b: update_event_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_event_printk(struct trace_event_call *call, struct trace_eval_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d1750)
Location: kernel/trace/trace_events.c:2555
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
**Symbols:**

```
ffffffff811d1750-ffffffff811d1933: update_event_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_event_printk(struct trace_event_call *call, struct trace_eval_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811fe4b0)
Location: kernel/trace/trace_events.c:2560
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
**Symbols:**

```
ffffffff811fe4b0-ffffffff811fe693: update_event_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_event_printk(struct trace_event_call *call, struct trace_eval_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81238f50)
Location: kernel/trace/trace_events.c:2579
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
**Symbols:**

```
ffffffff81238f50-ffffffff812390b9: update_event_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_event_printk(struct trace_event_call *call, struct trace_eval_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81286ce0)
Location: kernel/trace/trace_events.c:2600
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
**Symbols:**

```
ffffffff81286ce0-ffffffff81286e46: update_event_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_event_printk(struct trace_event_call *call, struct trace_eval_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812a39d0)
Location: kernel/trace/trace_events.c:2594
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
**Symbols:**

```
ffffffff812a39d0-ffffffff812a3b36: update_event_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_event_printk(struct trace_event_call *call, struct trace_eval_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812bf200)
Location: kernel/trace/trace_events.c:2742
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
**Symbols:**

```
ffffffff812bf200-ffffffff812bf366: update_event_printk (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffff80001023c5f8)
Location: kernel/trace/trace_events.c:2126
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
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
In kernel/trace/trace_events.c (c0477f18)
Location: kernel/trace/trace_events.c:2126
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
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
In kernel/trace/trace_events.c (c0000000002cb424)
Location: kernel/trace/trace_events.c:2126
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
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
In kernel/trace/trace_events.c (ffffffe0001927cc)
Location: kernel/trace/trace_events.c:2126
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
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
In kernel/trace/trace_events.c (ffffffff811b58ed)
Location: kernel/trace/trace_events.c:2126
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
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
In kernel/trace/trace_events.c (ffffffff811a86ed)
Location: kernel/trace/trace_events.c:2126
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
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
In kernel/trace/trace_events.c (ffffffff811b36bd)
Location: kernel/trace/trace_events.c:2126
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
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
In kernel/trace/trace_events.c (ffffffff811c175d)
Location: kernel/trace/trace_events.c:2126
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
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
