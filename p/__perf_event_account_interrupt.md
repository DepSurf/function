# Function: <code>__perf_event_account_interrupt</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119a630)
Location: kernel/events/core.c:7097
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
ffffffff8119a630-ffffffff8119a6ff: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a21b0)
Location: kernel/events/core.c:7320
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
ffffffff811a21b0-ffffffff811a2289: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b62d0)
Location: kernel/events/core.c:7317
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
ffffffff811b62d0-ffffffff811b63a9: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d5dd0)
Location: kernel/events/core.c:7699
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
ffffffff811d5dd0-ffffffff811d5ea2: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e6470)
Location: kernel/events/core.c:7708
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
ffffffff811e6470-ffffffff811e6549: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fdc80)
Location: kernel/events/core.c:8012
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
ffffffff811fdc80-ffffffff811fdd54: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120af30)
Location: kernel/events/core.c:8128
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
ffffffff8120af30-ffffffff8120b004: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242510)
Location: kernel/events/core.c:8678
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_account_interrupt
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff81236e30-ffffffff81236f06: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124cd00)
Location: kernel/events/core.c:8944
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_account_interrupt
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff81240a30-ffffffff81240b06: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81251360)
Location: kernel/events/core.c:9073
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_account_interrupt
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff812447d0-ffffffff812448a6: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128c160)
Location: kernel/events/core.c:9192
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_account_interrupt
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff8127f770-ffffffff8127f846: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e0c75)
Location: kernel/events/core.c:9127
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_account_interrupt
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff812d4770-ffffffff812d4853: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81349135)
Location: kernel/events/core.c:9404
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_account_interrupt
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff8133cba0-ffffffff8133cc83: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8137a145)
Location: kernel/events/core.c:9433
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_account_interrupt
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff8136dd20-ffffffff8136ddfc: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:9503
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
ffffffff81396df0-ffffffff81396f2b: __perf_event_account_interrupt (STB_LOCAL)
ffffffff821bdfec-ffffffff821be001: __perf_event_account_interrupt.cold (STB_LOCAL)
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
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010296970)
Location: kernel/events/core.c:8128
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
ffff800010296970-ffff800010296ac0: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c1dbc)
Location: kernel/events/core.c:8128
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
c04c1dbc-c04c1f08: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000341d70)
Location: kernel/events/core.c:8128
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
c000000000341d70-c000000000341f3c: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c5252)
Location: kernel/events/core.c:8128
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
ffffffe0001c5252-ffffffe0001c5370: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81203550)
Location: kernel/events/core.c:8128
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
ffffffff81203550-ffffffff81203624: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f6610)
Location: kernel/events/core.c:8128
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
ffffffff811f6610-ffffffff811f6723: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201320)
Location: kernel/events/core.c:8128
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
ffffffff81201320-ffffffff812013f4: __perf_event_account_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __perf_event_account_interrupt(struct perf_event *event, int throttle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812106a0)
Location: kernel/events/core.c:8128
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_event_account_interrupt
```
**Symbols:**

```
ffffffff812106a0-ffffffff81210774: __perf_event_account_interrupt (STB_LOCAL)
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
