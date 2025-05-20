# Function: <code>__rb_reserve_next</code>

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
In kernel/trace/ring_buffer.c (ffffffff81147906)
Location: kernel/trace/ring_buffer.c:2687
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
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
In kernel/trace/ring_buffer.c (ffffffff81151ba6)
Location: kernel/trace/ring_buffer.c:2681
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_reserve_next_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115a3e0)
Location: kernel/trace/ring_buffer.c:2650
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff8115a3e0-ffffffff8115a542: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115d480)
Location: kernel/trace/ring_buffer.c:2652
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff8115d480-ffffffff8115d5b7: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116a6b0)
Location: kernel/trace/ring_buffer.c:2645
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff8116a6b0-ffffffff8116a7e7: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81179380)
Location: kernel/trace/ring_buffer.c:2775
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81179380-ffffffff811794e3: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81186a50)
Location: kernel/trace/ring_buffer.c:2838
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81186a50-ffffffff81186bb3: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81193c30)
Location: kernel/trace/ring_buffer.c:2815
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81193c30-ffffffff81193db9: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119f750)
Location: kernel/trace/ring_buffer.c:2816
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff8119f750-ffffffff8119f8d9: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b6140)
Location: kernel/trace/ring_buffer.c:2885
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff811b6140-ffffffff811b62ae: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b3a00)
Location: kernel/trace/ring_buffer.c:3348
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff811b3a00-ffffffff811b3d60: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3435
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff811b4550-ffffffff811b4985: __rb_reserve_next (STB_LOCAL)
ffffffff81bd7283-ffffffff81bd72ae: __rb_reserve_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3435
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff811de720-ffffffff811deb98: __rb_reserve_next (STB_LOCAL)
ffffffff81cb48ca-ffffffff81cb4920: __rb_reserve_next.cold (STB_LOCAL)
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
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3473
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81215720-ffffffff81215b9c: __rb_reserve_next.constprop.0 (STB_LOCAL)
ffffffff81e658c4-ffffffff81e6591a: __rb_reserve_next.constprop.0.cold (STB_LOCAL)
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
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3552
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff8125ed80-ffffffff8125f227: __rb_reserve_next.constprop.0 (STB_LOCAL)
ffffffff8205cff1-ffffffff8205d01c: __rb_reserve_next.constprop.0.cold (STB_LOCAL)
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
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3555
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81275f80-ffffffff81276432: __rb_reserve_next.constprop.0 (STB_LOCAL)
ffffffff820db9b2-ffffffff820db9dd: __rb_reserve_next.constprop.0.cold (STB_LOCAL)
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
In kernel/trace/ring_buffer.c (ffffffff81290bf0)
Location: kernel/trace/ring_buffer.c:3461
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81290bf0-ffffffff81290f45: __rb_reserve_next.constprop.0 (STB_LOCAL)
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
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021b7a8)
Location: kernel/trace/ring_buffer.c:2816
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffff80001021b7a8-ffff80001021b96c: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c045a1fc)
Location: kernel/trace/ring_buffer.c:2816
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
c045a1fc-c045a3cc: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029cc00)
Location: kernel/trace/ring_buffer.c:2816
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
c00000000029cc00-c00000000029ce44: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000178482)
Location: kernel/trace/ring_buffer.c:2816
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffe000178482-ffffffe0001785cc: __rb_reserve_next (STB_LOCAL)
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
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197d70)
Location: kernel/trace/ring_buffer.c:2816
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81197d70-ffffffff81197ef9: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118b520)
Location: kernel/trace/ring_buffer.c:2816
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff8118b520-ffffffff8118b6a9: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81195b40)
Location: kernel/trace/ring_buffer.c:2816
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81195b40-ffffffff81195cc9: __rb_reserve_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ring_buffer_event *__rb_reserve_next(struct ring_buffer_per_cpu *cpu_buffer, struct rb_event_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a39d0)
Location: kernel/trace/ring_buffer.c:2816
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
```
**Symbols:**

```
ffffffff811a39d0-ffffffff811a3b59: __rb_reserve_next (STB_LOCAL)
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
