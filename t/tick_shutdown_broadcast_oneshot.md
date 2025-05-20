# Function: <code>tick_shutdown_broadcast_oneshot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tick_shutdown_broadcast_oneshot(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff810fdd00)
Location: kernel/time/tick-broadcast.c:947
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff810fdd00-ffffffff810fdd47: tick_shutdown_broadcast_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tick_shutdown_broadcast_oneshot(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81105090)
Location: kernel/time/tick-broadcast.c:947
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff81105090-ffffffff811050d7: tick_shutdown_broadcast_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tick_shutdown_broadcast_oneshot(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8110c7e0)
Location: kernel/time/tick-broadcast.c:949
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff8110c7e0-ffffffff8110c830: tick_shutdown_broadcast_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tick_shutdown_broadcast_oneshot(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8110e6b0)
Location: kernel/time/tick-broadcast.c:952
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff8110e6b0-ffffffff8110e700: tick_shutdown_broadcast_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tick_shutdown_broadcast_oneshot(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81119930)
Location: kernel/time/tick-broadcast.c:952
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff81119930-ffffffff81119980: tick_shutdown_broadcast_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tick_shutdown_broadcast_oneshot(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff811264a0)
Location: kernel/time/tick-broadcast.c:960
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff811264a0-ffffffff811264f0: tick_shutdown_broadcast_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tick_shutdown_broadcast_oneshot(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81131b80)
Location: kernel/time/tick-broadcast.c:954
Inline: False
Direct callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff81131b80-ffffffff81131bd0: tick_shutdown_broadcast_oneshot (STB_GLOBAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
