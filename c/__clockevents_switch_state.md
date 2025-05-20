# Function: <code>__clockevents_switch_state</code>

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
In kernel/time/clockevents.c (ffffffff810fbe33)
Location: kernel/time/clockevents.c:97
Inline: True
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
In kernel/time/clockevents.c (ffffffff81103173)
Location: kernel/time/clockevents.c:97
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110a863)
Location: kernel/time/clockevents.c:97
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110c7b3)
Location: kernel/time/clockevents.c:97
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81117a03)
Location: kernel/time/clockevents.c:97
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8112450d)
Location: kernel/time/clockevents.c:97
Inline: True
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
In kernel/time/clockevents.c (ffffffff8112fc06)
Location: kernel/time/clockevents.c:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113a6c0)
Location: kernel/time/clockevents.c:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8114632e)
Location: kernel/time/clockevents.c:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81156537)
Location: kernel/time/clockevents.c:91
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
```
**Symbols:**

```
ffffffff811559d0-ffffffff81155a7d: __clockevents_switch_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811526d7)
Location: kernel/time/clockevents.c:91
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
```
**Symbols:**

```
ffffffff81151b70-ffffffff81151c1d: __clockevents_switch_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81153b27)
Location: kernel/time/clockevents.c:91
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
```
**Symbols:**

```
ffffffff81153000-ffffffff811530ad: __clockevents_switch_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81178217)
Location: kernel/time/clockevents.c:91
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
```
**Symbols:**

```
ffffffff81177890-ffffffff81177963: __clockevents_switch_state (STB_LOCAL)
ffffffff81cb2031-ffffffff81cb2045: __clockevents_switch_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811ad3a5)
Location: kernel/time/clockevents.c:91
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
```
**Symbols:**

```
ffffffff811aca00-ffffffff811acaeb: __clockevents_switch_state (STB_LOCAL)
ffffffff81e63595-ffffffff81e635b5: __clockevents_switch_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811ed8f5)
Location: kernel/time/clockevents.c:91
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
```
**Symbols:**

```
ffffffff811ece70-ffffffff811ecf5b: __clockevents_switch_state (STB_LOCAL)
ffffffff8205bd08-ffffffff8205bd28: __clockevents_switch_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81202025)
Location: kernel/time/clockevents.c:91
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
```
**Symbols:**

```
ffffffff812015a0-ffffffff81201678: __clockevents_switch_state (STB_LOCAL)
ffffffff820da508-ffffffff820da51d: __clockevents_switch_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (ffffffff812184c5)
Location: kernel/time/clockevents.c:91
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
```
**Symbols:**

```
ffffffff81217a40-ffffffff81217b18: __clockevents_switch_state (STB_LOCAL)
ffffffff821b5e82-ffffffff821b5e97: __clockevents_switch_state.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffff8000101b0d74)
Location: kernel/time/clockevents.c:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (c03fb7bc)
Location: kernel/time/clockevents.c:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (c000000000215aa4)
Location: kernel/time/clockevents.c:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffe000139b28)
Location: kernel/time/clockevents.c:91
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113eade)
Location: kernel/time/clockevents.c:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811315fe)
Location: kernel/time/clockevents.c:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113c7fe)
Location: kernel/time/clockevents.c:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811492ee)
Location: kernel/time/clockevents.c:91
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
