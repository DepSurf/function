# Function: <code>tick_shutdown_broadcast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tick_shutdown_broadcast(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff810fd360)
Location: kernel/time/tick-broadcast.c:442
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff810fd360-ffffffff810fd3e2: tick_shutdown_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tick_shutdown_broadcast(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff811046c0)
Location: kernel/time/tick-broadcast.c:442
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff811046c0-ffffffff81104742: tick_shutdown_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tick_shutdown_broadcast(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8110bdf0)
Location: kernel/time/tick-broadcast.c:441
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff8110bdf0-ffffffff8110be79: tick_shutdown_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tick_shutdown_broadcast(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8110e1a0)
Location: kernel/time/tick-broadcast.c:444
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff8110e1a0-ffffffff8110e229: tick_shutdown_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tick_shutdown_broadcast(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81119420)
Location: kernel/time/tick-broadcast.c:444
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff81119420-ffffffff811194a9: tick_shutdown_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tick_shutdown_broadcast(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81125f90)
Location: kernel/time/tick-broadcast.c:444
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff81125f90-ffffffff81126019: tick_shutdown_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tick_shutdown_broadcast(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81131670)
Location: kernel/time/tick-broadcast.c:438
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff81131670-ffffffff811316f9: tick_shutdown_broadcast (STB_GLOBAL)
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
In kernel/time/tick-broadcast.c (ffffffff8113c228)
Location: kernel/time/tick-broadcast.c:442
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (ffffffff81147e38)
Location: kernel/time/tick-broadcast.c:442
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (ffffffff81157c78)
Location: kernel/time/tick-broadcast.c:442
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (ffffffff81153d68)
Location: kernel/time/tick-broadcast.c:442
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (ffffffff811551d8)
Location: kernel/time/tick-broadcast.c:454
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (ffffffff81179f0e)
Location: kernel/time/tick-broadcast.c:523
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (ffffffff811af36b)
Location: kernel/time/tick-broadcast.c:523
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (ffffffff811efbcb)
Location: kernel/time/tick-broadcast.c:523
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (ffffffff8120436b)
Location: kernel/time/tick-broadcast.c:524
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (ffffffff8121a92b)
Location: kernel/time/tick-broadcast.c:524
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (ffff8000101b3550)
Location: kernel/time/tick-broadcast.c:442
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (c03fd6f8)
Location: kernel/time/tick-broadcast.c:442
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (c000000000218d88)
Location: kernel/time/tick-broadcast.c:442
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/time/tick-broadcast.c (ffffffff81140458)
Location: kernel/time/tick-broadcast.c:442
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (ffffffff811331d8)
Location: kernel/time/tick-broadcast.c:442
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (ffffffff8113e308)
Location: kernel/time/tick-broadcast.c:442
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
In kernel/time/tick-broadcast.c (ffffffff8114ae18)
Location: kernel/time/tick-broadcast.c:442
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
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
</ul>
