# Function: <code>eprobe_trigger_func</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void eprobe_trigger_func(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff8120a120)
Location: kernel/trace/trace_eprobe.c:542
Inline: False
```
**Symbols:**

```
ffffffff8120a120-ffffffff8120a132: eprobe_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void eprobe_trigger_func(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81245fc0)
Location: kernel/trace/trace_eprobe.c:606
Inline: False
```
**Symbols:**

```
ffffffff81245fc0-ffffffff81245fdc: eprobe_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void eprobe_trigger_func(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81295670)
Location: kernel/trace/trace_eprobe.c:561
Inline: False
```
**Symbols:**

```
ffffffff81295670-ffffffff8129569c: eprobe_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void eprobe_trigger_func(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812b2580)
Location: kernel/trace/trace_eprobe.c:465
Inline: False
```
**Symbols:**

```
ffffffff812b2580-ffffffff812b25ac: eprobe_trigger_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void eprobe_trigger_func(struct event_trigger_data *data, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812ceb30)
Location: kernel/trace/trace_eprobe.c:469
Inline: False
```
**Symbols:**

```
ffffffff812ceb30-ffffffff812ceb5c: eprobe_trigger_func (STB_LOCAL)
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
