# Function: <code>test_event_printk</code>

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
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void test_event_printk(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:257
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_raw_init
```
**Symbols:**

```
ffffffff811d48a0-ffffffff811d4daa: test_event_printk (STB_LOCAL)
ffffffff81bd7e5e-ffffffff81bd7e8e: test_event_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void test_event_printk(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:258
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_raw_init
```
**Symbols:**

```
ffffffff81201710-ffffffff81201c57: test_event_printk (STB_LOCAL)
ffffffff81cb64b7-ffffffff81cb658b: test_event_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void test_event_printk(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:267
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_raw_init
```
**Symbols:**

```
ffffffff8123cb30-ffffffff8123d104: test_event_printk (STB_LOCAL)
ffffffff81e6742f-ffffffff81e6755e: test_event_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void test_event_printk(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:282
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_raw_init
```
**Symbols:**

```
ffffffff8128a150-ffffffff8128a768: test_event_printk (STB_LOCAL)
ffffffff8205dfe9-ffffffff8205e0e8: test_event_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void test_event_printk(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:284
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_raw_init
```
**Symbols:**

```
ffffffff812a70b0-ffffffff812a76a3: test_event_printk (STB_LOCAL)
ffffffff820dca88-ffffffff820dcb1f: test_event_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void test_event_printk(struct trace_event_call *call);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:284
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_raw_init
```
**Symbols:**

```
ffffffff812c2760-ffffffff812c2d53: test_event_printk (STB_LOCAL)
ffffffff821b888a-ffffffff821b8921: test_event_printk.cold (STB_LOCAL)
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
