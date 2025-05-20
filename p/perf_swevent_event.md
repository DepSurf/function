# Function: <code>perf_swevent_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81183c40)
Location: kernel/events/core.c:6551
Inline: False
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
  - kernel/events/core.c:perf_bp_event
```
**Symbols:**

```
ffffffff81183c40-ffffffff81183cb4: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118a980)
Location: kernel/events/core.c:7145
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff8118a980-ffffffff8118a9f9: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119aa00)
Location: kernel/events/core.c:7258
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff8119aa00-ffffffff8119aa79: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a2440)
Location: kernel/events/core.c:7481
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff811a2440-ffffffff811a24b6: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b6560)
Location: kernel/events/core.c:7478
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff811b6560-ffffffff811b65d4: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d6070)
Location: kernel/events/core.c:7860
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff811d6070-ffffffff811d60e4: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e6710)
Location: kernel/events/core.c:7869
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff811e6710-ffffffff811e6784: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fdf20)
Location: kernel/events/core.c:8173
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff811fdf20-ffffffff811fdf95: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120b1d0)
Location: kernel/events/core.c:8289
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff8120b1d0-ffffffff8120b245: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81237210)
Location: kernel/events/core.c:8839
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff81237210-ffffffff8123728c: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81240e10)
Location: kernel/events/core.c:9105
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
```
**Symbols:**

```
ffffffff81240e10-ffffffff81240e8c: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81244bc0)
Location: kernel/events/core.c:9235
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff81244bc0-ffffffff81244c3c: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127fb60)
Location: kernel/events/core.c:9354
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff8127fb60-ffffffff8127fbdc: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d4bf0)
Location: kernel/events/core.c:9289
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff812d4bf0-ffffffff812d4c9b: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133d1d0)
Location: kernel/events/core.c:9614
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff8133d1d0-ffffffff8133d27b: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136e340)
Location: kernel/events/core.c:9643
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff8136e340-ffffffff8136e3eb: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81397380)
Location: kernel/events/core.c:9713
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:perf_tp_event_target_task
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff81397380-ffffffff813974de: perf_swevent_event (STB_LOCAL)
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
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102a0858)
Location: kernel/events/core.c:8289
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffff8000102a0858-ffff8000102a0910: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04d0800)
Location: kernel/events/core.c:8289
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
c04d0800-c04d0944: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003522a0)
Location: kernel/events/core.c:8289
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
c0000000003522a0-c000000000352400: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c54d6)
Location: kernel/events/core.c:8289
Inline: False
Direct callers:
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffe0001c54d6-ffffffe0001c5576: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812037f0)
Location: kernel/events/core.c:8289
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff812037f0-ffffffff81203865: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f68f0)
Location: kernel/events/core.c:8289
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff811f68f0-ffffffff811f6965: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812015c0)
Location: kernel/events/core.c:8289
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff812015c0-ffffffff81201635: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_swevent_event(struct perf_event *event, u64 nr, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81210940)
Location: kernel/events/core.c:8289
Inline: False
Direct callers:
  - kernel/events/core.c:perf_bp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:perf_tp_event
  - kernel/events/core.c:___perf_sw_event
```
**Symbols:**

```
ffffffff81210940-ffffffff812109b5: perf_swevent_event (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
