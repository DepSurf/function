# Function: <code>create_synth_event</code>

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
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int create_synth_event(int argc, char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1016
Inline: False
```
**Symbols:**

```
ffffffff811a3b70-ffffffff811a44da: create_synth_event (STB_LOCAL)
ffffffff811a4516-ffffffff811a454e: create_synth_event.cold.48 (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int create_synth_event(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dfeb0)
Location: kernel/trace/trace_events_synth.c:1642
Inline: False
```
**Symbols:**

```
ffffffff811dfeb0-ffffffff811dff34: create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int create_synth_event(int argc, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dd8a0)
Location: kernel/trace/trace_events_synth.c:1942
Inline: False
```
**Symbols:**

```
ffffffff811dd8a0-ffffffff811dd924: create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int create_synth_event(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811deca0)
Location: kernel/trace/trace_events_synth.c:2044
Inline: False
```
**Symbols:**

```
ffffffff811deca0-ffffffff811dee2f: create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int create_synth_event(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8120e580)
Location: kernel/trace/trace_events_synth.c:2044
Inline: False
```
**Symbols:**

```
ffffffff8120e580-ffffffff8120e721: create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int create_synth_event(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8124ab20)
Location: kernel/trace/trace_events_synth.c:2053
Inline: False
```
**Symbols:**

```
ffffffff8124ab20-ffffffff8124ad00: create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int create_synth_event(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81299710)
Location: kernel/trace/trace_events_synth.c:2061
Inline: False
```
**Symbols:**

```
ffffffff81299710-ffffffff812998f0: create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int create_synth_event(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b6ac0)
Location: kernel/trace/trace_events_synth.c:2134
Inline: False
```
**Symbols:**

```
ffffffff812b6ac0-ffffffff812b6d3f: create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int create_synth_event(const char *raw_command);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812d3110)
Location: kernel/trace/trace_events_synth.c:2135
Inline: False
```
**Symbols:**

```
ffffffff812d3110-ffffffff812d338f: create_synth_event (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *raw_command</code>
</li>
<li>
<b>Param removed. </b>
<code>int argc</code>
</li>
<li>
<b>Param removed. </b>
<code>const char **argv</code>
</li>
</ul>
</details>
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
