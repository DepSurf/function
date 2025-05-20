# Function: <code>____napi_schedule</code>

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
In net/core/dev.c (ffffffff817156c8)
Location: net/core/dev.c:3209
Inline: True
Inline callers:
  - net/core/dev.c:__napi_schedule_irqoff
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_cpu_callback
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
In net/core/dev.c (ffffffff81781df9)
Location: net/core/dev.c:3461
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_callback
  - net/core/dev.c:__napi_schedule_irqoff
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff817af6f9)
Location: net/core/dev.c:3455
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff817cdfc9)
Location: net/core/dev.c:3541
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff8184acc9)
Location: net/core/dev.c:3587
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff818950a9)
Location: net/core/dev.c:3668
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff818b5b79)
Location: net/core/dev.c:3963
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff818ff4d8)
Location: net/core/dev.c:3972
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff81931838)
Location: net/core/dev.c:3874
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a06f94)
Location: net/core/dev.c:4235
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff81a08544)
Location: net/core/dev.c:4264
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff819eecc8)
Location: net/core/dev.c:4347
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff81aa0039)
Location: net/core/dev.c:4315
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff81c15ab4)
Location: net/core/dev.c:4344
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff81dc6e94)
Location: net/core/dev.c:4331
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff81e36684)
Location: net/core/dev.c:4291
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff81ef4974)
Location: net/core/dev.c:4439
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffff800010bd015c)
Location: net/core/dev.c:3874
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule_irqoff
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (c0ce63e4)
Location: net/core/dev.c:3874
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule_irqoff
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (c000000000cacea8)
Location: net/core/dev.c:3874
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule_irqoff
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffe00075a1d0)
Location: net/core/dev.c:3874
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule_irqoff
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff818d1838)
Location: net/core/dev.c:3874
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff8188b6c2)
Location: net/core/dev.c:3874
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff81922838)
Location: net/core/dev.c:3874
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
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
In net/core/dev.c (ffffffff81943a08)
Location: net/core/dev.c:3874
Inline: True
Inline callers:
  - net/core/dev.c:dev_cpu_dead
  - net/core/dev.c:__napi_schedule
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:rps_trigger_softirq
```
</details>
</li>
</ul>

## Differences
