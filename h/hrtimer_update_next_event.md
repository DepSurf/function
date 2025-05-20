# Function: <code>hrtimer_update_next_event</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base *cpu_base);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811436fe)
Location: kernel/time/hrtimer.c:594
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
Direct callers:
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81142880-ffffffff81142925: hrtimer_update_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base *cpu_base);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811448ae)
Location: kernel/time/hrtimer.c:594
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
Direct callers:
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81143f10-ffffffff81143fb7: hrtimer_update_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base *cpu_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81167130)
Location: kernel/time/hrtimer.c:594
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff81167130-ffffffff811671d7: hrtimer_update_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base *cpu_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119a960)
Location: kernel/time/hrtimer.c:594
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff8119a960-ffffffff8119aa16: hrtimer_update_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base *cpu_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811d9130)
Location: kernel/time/hrtimer.c:594
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff811d9130-ffffffff811d91e6: hrtimer_update_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base *cpu_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ed590)
Location: kernel/time/hrtimer.c:596
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff811ed590-ffffffff811ed646: hrtimer_update_next_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ktime_t hrtimer_update_next_event(struct hrtimer_cpu_base *cpu_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff812038f0)
Location: kernel/time/hrtimer.c:596
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:__hrtimer_start_range_ns
  - kernel/time/hrtimer.c:__remove_hrtimer
  - kernel/time/hrtimer.c:retrigger_next_event
  - kernel/time/hrtimer.c:retrigger_next_event
```
**Symbols:**

```
ffffffff812038f0-ffffffff812039a6: hrtimer_update_next_event (STB_LOCAL)
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
