# Function: <code>parse_synth_field</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811a3d1d)
Location: kernel/trace/trace_events_hist.c:750
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_synth_event
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
In kernel/trace/trace_events_hist.c (ffffffff811af339)
Location: kernel/trace/trace_events_hist.c:813
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct synth_field *parse_synth_field(int argc, const char **argv, int *consumed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:967
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811beb40-ffffffff811bf036: parse_synth_field (STB_LOCAL)
ffffffff811c0f08-ffffffff811c0f14: parse_synth_field.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct synth_field *parse_synth_field(int argc, const char **argv, int *consumed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1037
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811ca360-ffffffff811ca890: parse_synth_field (STB_LOCAL)
ffffffff811cc6ab-ffffffff811cc6b7: parse_synth_field.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct synth_field *parse_synth_field(int argc, const char **argv, int *consumed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811df440)
Location: kernel/trace/trace_events_synth.c:462
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff811df440-ffffffff811df6c4: parse_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct synth_field *parse_synth_field(int argc, const char **argv, int *consumed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dd030)
Location: kernel/trace/trace_events_synth.c:582
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff811dd030-ffffffff811dd4ca: parse_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct synth_field *parse_synth_field(int argc, char **argv, int *consumed, int *field_version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811de390)
Location: kernel/trace/trace_events_synth.c:600
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff811de390-ffffffff811de815: parse_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct synth_field *parse_synth_field(int argc, char **argv, int *consumed, int *field_version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8120dc10)
Location: kernel/trace/trace_events_synth.c:600
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff8120dc10-ffffffff8120e095: parse_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct synth_field *parse_synth_field(int argc, char **argv, int *consumed, int *field_version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81249f80)
Location: kernel/trace/trace_events_synth.c:608
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff81249f80-ffffffff8124a521: parse_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct synth_field *parse_synth_field(int argc, char **argv, int *consumed, int *field_version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81298b50)
Location: kernel/trace/trace_events_synth.c:619
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff81298b50-ffffffff81299107: parse_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct synth_field *parse_synth_field(int argc, char **argv, int *consumed, int *field_version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b5d10)
Location: kernel/trace/trace_events_synth.c:688
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff812b5d10-ffffffff812b63cd: parse_synth_field (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct synth_field *parse_synth_field(int argc, char **argv, int *consumed, int *field_version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812d2380)
Location: kernel/trace/trace_events_synth.c:689
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
**Symbols:**

```
ffffffff812d2380-ffffffff812d2a12: parse_synth_field (STB_LOCAL)
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
struct synth_field *parse_synth_field(int argc, const char **argv, int *consumed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff80001024b908)
Location: kernel/trace/trace_events_hist.c:1037
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffff80001024b908-ffff80001024bda4: parse_synth_field (STB_LOCAL)
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
struct synth_field *parse_synth_field(int argc, const char **argv, int *consumed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e3670)
Location: kernel/trace/trace_events_hist.c:1037
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
c0000000002e3670-c0000000002e4a10: parse_synth_field (STB_LOCAL)
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
struct synth_field *parse_synth_field(int argc, const char **argv, int *consumed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1037
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811c2980-ffffffff811c2eb0: parse_synth_field (STB_LOCAL)
ffffffff811c4ccb-ffffffff811c4cd7: parse_synth_field.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct synth_field *parse_synth_field(int argc, const char **argv, int *consumed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1037
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811b5760-ffffffff811b5c90: parse_synth_field (STB_LOCAL)
ffffffff811b7aab-ffffffff811b7ab7: parse_synth_field.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct synth_field *parse_synth_field(int argc, const char **argv, int *consumed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1037
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811c0750-ffffffff811c0c80: parse_synth_field (STB_LOCAL)
ffffffff811c2a9b-ffffffff811c2aa7: parse_synth_field.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct synth_field *parse_synth_field(int argc, const char **argv, int *consumed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1037
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811ce7f0-ffffffff811ced20: parse_synth_field (STB_LOCAL)
ffffffff811d0b3b-ffffffff811d0b47: parse_synth_field.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>int *field_version</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char **argv</code> ➡️ <code>char **argv</code>
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
