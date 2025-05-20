# Function: <code>__perf_event_overflow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81183870)
Location: kernel/events/core.c:6405
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff81183870-ffffffff81183a35: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118a710)
Location: kernel/events/core.c:7002
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff8118a710-ffffffff8118a8bd: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119a700)
Location: kernel/events/core.c:7141
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff8119a700-ffffffff8119a7ea: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a2290)
Location: kernel/events/core.c:7364
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff811a2290-ffffffff811a2377: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b63b0)
Location: kernel/events/core.c:7361
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff811b63b0-ffffffff811b649a: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d5eb0)
Location: kernel/events/core.c:7743
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff811d5eb0-ffffffff811d5f9a: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e6550)
Location: kernel/events/core.c:7752
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff811e6550-ffffffff811e663a: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fdd60)
Location: kernel/events/core.c:8056
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff811fdd60-ffffffff811fde50: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120b010)
Location: kernel/events/core.c:8172
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff8120b010-ffffffff8120b100: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81236f10)
Location: kernel/events/core.c:8722
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff81236f10-ffffffff81237000: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81240b10)
Location: kernel/events/core.c:8988
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff81240b10-ffffffff81240c00: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812448b0)
Location: kernel/events/core.c:9117
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff812448b0-ffffffff812449ae: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127f850)
Location: kernel/events/core.c:9236
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff8127f850-ffffffff8127f94e: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d4860)
Location: kernel/events/core.c:9171
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff812d4860-ffffffff812d4987: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133cca0)
Location: kernel/events/core.c:9461
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff8133cca0-ffffffff8133cf64: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136de10)
Location: kernel/events/core.c:9490
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff8136de10-ffffffff8136e0d7: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81396f40)
Location: kernel/events/core.c:9560
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_swevent_event
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff81396f40-ffffffff81397207: __perf_event_overflow (STB_LOCAL)
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
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029a8d0)
Location: kernel/events/core.c:8172
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffff80001029a8d0-ffff80001029a9e0: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c1f08)
Location: kernel/events/core.c:8172
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
c04c1f08-c04c2004: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000341f40)
Location: kernel/events/core.c:8172
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
c000000000341f40-c0000000003420c4: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c5370)
Location: kernel/events/core.c:8172
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffe0001c5370-ffffffe0001c5426: __perf_event_overflow (STB_LOCAL)
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
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81203630)
Location: kernel/events/core.c:8172
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff81203630-ffffffff81203720: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f6730)
Location: kernel/events/core.c:8172
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff811f6730-ffffffff811f6820: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201400)
Location: kernel/events/core.c:8172
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff81201400-ffffffff812014f0: __perf_event_overflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __perf_event_overflow(struct perf_event *event, int throttle, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81210780)
Location: kernel/events/core.c:8172
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_hrtimer
  - kernel/events/core.c:perf_swevent_overflow
  - kernel/events/core.c:perf_event_overflow
```
**Symbols:**

```
ffffffff81210780-ffffffff81210870: __perf_event_overflow (STB_LOCAL)
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
