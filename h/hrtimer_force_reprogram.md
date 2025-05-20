# Function: <code>hrtimer_force_reprogram</code>

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
In kernel/time/hrtimer.c (ffffffff810eeefb)
Location: kernel/time/hrtimer.c:565
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
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
In kernel/time/hrtimer.c (ffffffff810f5fbb)
Location: kernel/time/hrtimer.c:555
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fcb60)
Location: kernel/time/hrtimer.c:555
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff810fcb60-ffffffff810fcbe6: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810ff0a0)
Location: kernel/time/hrtimer.c:556
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff810ff0a0-ffffffff810ff126: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81109e80)
Location: kernel/time/hrtimer.c:556
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81109e80-ffffffff81109f06: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81115640)
Location: kernel/time/hrtimer.c:617
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81115640-ffffffff811156b8: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81120c80)
Location: kernel/time/hrtimer.c:608
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81120c80-ffffffff81120cf8: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b490)
Location: kernel/time/hrtimer.c:607
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff8112b490-ffffffff8112b509: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81137570)
Location: kernel/time/hrtimer.c:628
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81137570-ffffffff811375e9: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81146920)
Location: kernel/time/hrtimer.c:628
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81146920-ffffffff811469e9: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81142f55)
Location: kernel/time/hrtimer.c:661
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:retrigger_next_event
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
In kernel/time/hrtimer.c (ffffffff811445d5)
Location: kernel/time/hrtimer.c:661
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:retrigger_next_event
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
In kernel/time/hrtimer.c (ffffffff8116793e)
Location: kernel/time/hrtimer.c:690
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119b2ef)
Location: kernel/time/hrtimer.c:690
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811d9b5f)
Location: kernel/time/hrtimer.c:690
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811edc8f)
Location: kernel/time/hrtimer.c:692
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81203fef)
Location: kernel/time/hrtimer.c:692
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a09a8)
Location: kernel/time/hrtimer.c:628
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffff8000101a09a8-ffff8000101a0a3c: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ea75c)
Location: kernel/time/hrtimer.c:628
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
c03ea75c-c03ea80c: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000201b70)
Location: kernel/time/hrtimer.c:628
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
c000000000201b70-c000000000201c60: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e230)
Location: kernel/time/hrtimer.c:628
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffe00012e230-ffffffe00012e2b6: hrtimer_force_reprogram (STB_LOCAL)
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
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112fd20)
Location: kernel/time/hrtimer.c:628
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff8112fd20-ffffffff8112fd99: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122790)
Location: kernel/time/hrtimer.c:628
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81122790-ffffffff81122809: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112da40)
Location: kernel/time/hrtimer.c:628
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff8112da40-ffffffff8112dab9: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hrtimer_force_reprogram(struct hrtimer_cpu_base *cpu_base, int skip_equal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a370)
Location: kernel/time/hrtimer.c:628
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff8113a370-ffffffff8113a3e9: hrtimer_force_reprogram (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
