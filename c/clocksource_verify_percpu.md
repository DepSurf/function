# Function: <code>clocksource_verify_percpu</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void clocksource_verify_percpu(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:238
Inline: False
Direct callers:
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff811496e0-ffffffff811498d6: clocksource_verify_percpu (STB_LOCAL)
ffffffff81bd589a-ffffffff81bd590e: clocksource_verify_percpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clocksource_verify_percpu(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8116db12)
Location: kernel/time/clocksource.c:326
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
Direct callers:
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff8116d8a0-ffffffff8116d93a: clocksource_verify_percpu.part.0 (STB_LOCAL)
ffffffff81cb1865-ffffffff81cb1a6e: clocksource_verify_percpu.part.0.cold (STB_LOCAL)
ffffffff8116d940-ffffffff8116d95b: clocksource_verify_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clocksource_verify_percpu(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811a1cad)
Location: kernel/time/clocksource.c:332
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
Direct callers:
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff811a19d0-ffffffff811a1aa6: clocksource_verify_percpu.part.0 (STB_LOCAL)
ffffffff81e62e10-ffffffff81e63019: clocksource_verify_percpu.part.0.cold (STB_LOCAL)
ffffffff811a1ab0-ffffffff811a1adb: clocksource_verify_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clocksource_verify_percpu(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811e10fd)
Location: kernel/time/clocksource.c:332
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
Direct callers:
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff811e0bb0-ffffffff811e0ed7: clocksource_verify_percpu.part.0 (STB_LOCAL)
ffffffff8205b9a6-ffffffff8205b9ca: clocksource_verify_percpu.part.0.cold (STB_LOCAL)
ffffffff811e0ef0-ffffffff811e0f1b: clocksource_verify_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clocksource_verify_percpu(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811f565a)
Location: kernel/time/clocksource.c:335
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
Direct callers:
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff811f5110-ffffffff811f5437: clocksource_verify_percpu.part.0 (STB_LOCAL)
ffffffff820da1a8-ffffffff820da1cc: clocksource_verify_percpu.part.0.cold (STB_LOCAL)
ffffffff811f5450-ffffffff811f547b: clocksource_verify_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clocksource_verify_percpu(struct clocksource *cs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8120b7fa)
Location: kernel/time/clocksource.c:337
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
Direct callers:
  - kernel/time/clocksource.c:__clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff8120b2b0-ffffffff8120b5d7: clocksource_verify_percpu.part.0 (STB_LOCAL)
ffffffff821b5aa7-ffffffff821b5acb: clocksource_verify_percpu.part.0.cold (STB_LOCAL)
ffffffff8120b5f0-ffffffff8120b61b: clocksource_verify_percpu (STB_GLOBAL)
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
