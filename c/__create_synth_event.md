# Function: <code>__create_synth_event</code>

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
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __create_synth_event(int argc, const char *name, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1094
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff811af240-ffffffff811afc79: __create_synth_event (STB_LOCAL)
ffffffff811b2648-ffffffff811b2680: __create_synth_event.cold.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __create_synth_event(int argc, const char *name, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1248
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff811c07d0-ffffffff811c0c88: __create_synth_event (STB_LOCAL)
ffffffff811c0f14-ffffffff811c0f3e: __create_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __create_synth_event(int argc, const char *name, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1318
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff811cc080-ffffffff811cc538: __create_synth_event (STB_LOCAL)
ffffffff811cc6b7-ffffffff811cc6e1: __create_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __create_synth_event(int argc, const char *name, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dfc40)
Location: kernel/trace/trace_events_synth.c:974
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff811dfc40-ffffffff811dfeae: __create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __create_synth_event(int argc, const char *name, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dd4d0)
Location: kernel/trace/trace_events_synth.c:1194
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff811dd4d0-ffffffff811dd891: __create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __create_synth_event(const char *name, const char *raw_fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811de820)
Location: kernel/trace/trace_events_synth.c:1181
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff811de820-ffffffff811dec9a: __create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __create_synth_event(const char *name, const char *raw_fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8120e0a0)
Location: kernel/trace/trace_events_synth.c:1179
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff8120e0a0-ffffffff8120e574: __create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __create_synth_event(const char *name, const char *raw_fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8124a530)
Location: kernel/trace/trace_events_synth.c:1187
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff8124a530-ffffffff8124ab17: __create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __create_synth_event(const char *name, const char *raw_fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81299120)
Location: kernel/trace/trace_events_synth.c:1197
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff81299120-ffffffff812996f7: __create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __create_synth_event(const char *name, const char *raw_fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b63e0)
Location: kernel/trace/trace_events_synth.c:1270
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff812b63e0-ffffffff812b6aa4: __create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __create_synth_event(const char *name, const char *raw_fields);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812d2a30)
Location: kernel/trace/trace_events_synth.c:1271
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff812d2a30-ffffffff812d30f4: __create_synth_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __create_synth_event(int argc, const char *name, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff80001024bda8)
Location: kernel/trace/trace_events_hist.c:1318
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
**Symbols:**

```
ffff80001024bda8-ffff80001024c220: __create_synth_event (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __create_synth_event(int argc, const char *name, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e6fe0)
Location: kernel/trace/trace_events_hist.c:1318
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
**Symbols:**

```
c0000000002e6fe0-c0000000002e75b8: __create_synth_event (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __create_synth_event(int argc, const char *name, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1318
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff811c46a0-ffffffff811c4b58: __create_synth_event (STB_LOCAL)
ffffffff811c4cd7-ffffffff811c4d01: __create_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __create_synth_event(int argc, const char *name, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1318
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff811b7480-ffffffff811b7938: __create_synth_event (STB_LOCAL)
ffffffff811b7ab7-ffffffff811b7ae1: __create_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __create_synth_event(int argc, const char *name, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1318
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff811c2470-ffffffff811c2928: __create_synth_event (STB_LOCAL)
ffffffff811c2aa7-ffffffff811c2ad1: __create_synth_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __create_synth_event(int argc, const char *name, const char **argv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1318
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:synth_event_create
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
**Symbols:**

```
ffffffff811d0510-ffffffff811d09c8: __create_synth_event (STB_LOCAL)
ffffffff811d0b47-ffffffff811d0b71: __create_synth_event.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *raw_fields</code>
</li>
<li>
<b>Param removed. </b>
<code>int argc</code>
</li>
<li>
<b>Param removed. </b>
<code>const char **argv</code>
</li>
<li>
<b>Param reordered. </b>
<code>argc, name, argv</code> ➡️ <code>name, raw_fields</code>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
