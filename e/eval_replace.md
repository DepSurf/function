# Function: <code>eval_replace</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81179500)
Location: kernel/trace/trace_events.c:2110
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
In kernel/trace/trace_events.c (ffffffff81186c53)
Location: kernel/trace/trace_events.c:2114
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
In kernel/trace/trace_events.c (ffffffff81195cd5)
Location: kernel/trace/trace_events.c:2114
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
In kernel/trace/trace_events.c (ffffffff811a3e45)
Location: kernel/trace/trace_events.c:2115
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
In kernel/trace/trace_events.c (ffffffff811b1d1b)
Location: kernel/trace/trace_events.c:2105
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
In kernel/trace/trace_events.c (ffffffff811bd39b)
Location: kernel/trace/trace_events.c:2104
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
char *eval_replace(char *ptr, struct trace_eval_map *map, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d3450)
Location: kernel/trace/trace_events.c:2309
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:update_event_printk
```
**Symbols:**

```
ffffffff811d3450-ffffffff811d34d6: eval_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *eval_replace(char *ptr, struct trace_eval_map *map, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d05a0)
Location: kernel/trace/trace_events.c:2322
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:update_event_printk
```
**Symbols:**

```
ffffffff811d05a0-ffffffff811d0626: eval_replace (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffffffff811d17fe)
Location: kernel/trace/trace_events.c:2533
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:update_event_printk
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
In kernel/trace/trace_events.c (ffffffff811fe55e)
Location: kernel/trace/trace_events.c:2538
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:update_event_printk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *eval_replace(char *ptr, struct trace_eval_map *map, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81238eb0)
Location: kernel/trace/trace_events.c:2557
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:update_event_fields
  - kernel/trace/trace_events.c:update_event_printk
```
**Symbols:**

```
ffffffff81238eb0-ffffffff81238f41: eval_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *eval_replace(char *ptr, struct trace_eval_map *map, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81286c30)
Location: kernel/trace/trace_events.c:2578
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:update_event_fields
  - kernel/trace/trace_events.c:update_event_printk
```
**Symbols:**

```
ffffffff81286c30-ffffffff81286cc1: eval_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *eval_replace(char *ptr, struct trace_eval_map *map, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812a3920)
Location: kernel/trace/trace_events.c:2572
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:update_event_fields
  - kernel/trace/trace_events.c:update_event_printk
```
**Symbols:**

```
ffffffff812a3920-ffffffff812a39b1: eval_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *eval_replace(char *ptr, struct trace_eval_map *map, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812bf150)
Location: kernel/trace/trace_events.c:2720
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:update_event_fields
  - kernel/trace/trace_events.c:update_event_printk
```
**Symbols:**

```
ffffffff812bf150-ffffffff812bf1e1: eval_replace (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffff80001023c684)
Location: kernel/trace/trace_events.c:2104
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
In kernel/trace/trace_events.c (c0477fd4)
Location: kernel/trace/trace_events.c:2104
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
In kernel/trace/trace_events.c (c0000000002cb508)
Location: kernel/trace/trace_events.c:2104
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
In kernel/trace/trace_events.c (ffffffe0001928a0)
Location: kernel/trace/trace_events.c:2104
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
In kernel/trace/trace_events.c (ffffffff811b59bb)
Location: kernel/trace/trace_events.c:2104
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
In kernel/trace/trace_events.c (ffffffff811a87bb)
Location: kernel/trace/trace_events.c:2104
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
In kernel/trace/trace_events.c (ffffffff811b378b)
Location: kernel/trace/trace_events.c:2104
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
In kernel/trace/trace_events.c (ffffffff811c182b)
Location: kernel/trace/trace_events.c:2104
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
