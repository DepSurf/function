# Function: <code>__flush_work</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __flush_work(struct work_struct *work, bool from_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ad4c0)
Location: kernel/workqueue.c:2904
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff810ad4c0-ffffffff810ad69b: __flush_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __flush_work(struct work_struct *work, bool from_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b67a0)
Location: kernel/workqueue.c:2927
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff810b67a0-ffffffff810b6983: __flush_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool __flush_work(struct work_struct *work, bool from_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3024
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff810bcc10-ffffffff810bcddc: __flush_work (STB_LOCAL)
ffffffff810bf05c-ffffffff810bf085: __flush_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __flush_work(struct work_struct *work, bool from_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2890)
Location: kernel/workqueue.c:3033
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff810c2890-ffffffff810c2a60: __flush_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c8f00)
Location: kernel/workqueue.c:3030
Inline: True
Direct callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff810c8f00-ffffffff810c8f6d: __flush_work.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4070)
Location: kernel/workqueue.c:3036
Inline: True
Direct callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff810c4070-ffffffff810c40dd: __flush_work.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5700)
Location: kernel/workqueue.c:3037
Inline: True
Direct callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff810c5700-ffffffff810c590a: __flush_work.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3076
Inline: True
Direct callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff810d82e0-ffffffff810d8557: __flush_work.isra.0 (STB_LOCAL)
ffffffff81ca517c-ffffffff81ca5191: __flush_work.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3059
Inline: True
Direct callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff810f3010-ffffffff810f32a1: __flush_work.isra.0 (STB_LOCAL)
ffffffff81e54b09-ffffffff81e54b1e: __flush_work.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3059
Inline: True
Direct callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff811132f0-ffffffff81113639: __flush_work.isra.0 (STB_LOCAL)
ffffffff820565cd-ffffffff820565e2: __flush_work.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3375
Inline: True
Direct callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff8111f8f0-ffffffff8111fc39: __flush_work.isra.0 (STB_LOCAL)
ffffffff820d4b09-ffffffff820d4b1e: __flush_work.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3396
Inline: True
Direct callers:
  - kernel/workqueue.c:work_on_cpu_safe_key
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff81129e40-ffffffff8112a14f: __flush_work.isra.0 (STB_LOCAL)
ffffffff821afa40-ffffffff821afa55: __flush_work.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffff80001011e7c0)
Location: kernel/workqueue.c:3033
Inline: True
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_rcu_work
  - kernel/workqueue.c:flush_rcu_work
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffff80001011e7c0-ffff80001011ea20: __flush_work.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __flush_work(struct work_struct *work, bool from_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0373598)
Location: kernel/workqueue.c:3033
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
c0373598-c0373800: __flush_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (c0000000001697d0)
Location: kernel/workqueue.c:3033
Inline: True
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_rcu_work
  - kernel/workqueue.c:flush_rcu_work
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
c0000000001697d0-c000000000169b30: __flush_work.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d7fba)
Location: kernel/workqueue.c:3033
Inline: True
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_rcu_work
  - kernel/workqueue.c:flush_rcu_work
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffe0000d7fba-ffffffe0000d81ec: __flush_work.isra.0 (STB_LOCAL)
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
bool __flush_work(struct work_struct *work, bool from_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bcc00)
Location: kernel/workqueue.c:3033
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff810bcc00-ffffffff810bcdd0: __flush_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __flush_work(struct work_struct *work, bool from_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ab450)
Location: kernel/workqueue.c:3033
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff810ab450-ffffffff810ab614: __flush_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __flush_work(struct work_struct *work, bool from_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bc160)
Location: kernel/workqueue.c:3033
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff810bc160-ffffffff810bc330: __flush_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __flush_work(struct work_struct *work, bool from_cancel);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c3260)
Location: kernel/workqueue.c:3033
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
```
**Symbols:**

```
ffffffff810c3260-ffffffff810c342a: __flush_work (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
