# Function: <code>tick_set_oneshot_wakeup_device</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool tick_set_oneshot_wakeup_device(struct clock_event_device *newdev, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81179eb2)
Location: kernel/time/tick-broadcast.c:115
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
Direct callers:
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81178e70-ffffffff81178fb8: tick_set_oneshot_wakeup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool tick_set_oneshot_wakeup_device(struct clock_event_device *newdev, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff811ae3ca)
Location: kernel/time/tick-broadcast.c:115
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
Direct callers:
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff811ae190-ffffffff811ae2ec: tick_set_oneshot_wakeup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool tick_set_oneshot_wakeup_device(struct clock_event_device *newdev, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff811eeafa)
Location: kernel/time/tick-broadcast.c:115
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
Direct callers:
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff811ee860-ffffffff811ee9bc: tick_set_oneshot_wakeup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool tick_set_oneshot_wakeup_device(struct clock_event_device *newdev, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8120322a)
Location: kernel/time/tick-broadcast.c:116
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
Direct callers:
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81202f90-ffffffff812030ea: tick_set_oneshot_wakeup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool tick_set_oneshot_wakeup_device(struct clock_event_device *newdev, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff812197ea)
Location: kernel/time/tick-broadcast.c:116
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline
Direct callers:
  - kernel/time/tick-broadcast.c:tick_install_broadcast_device
```
**Symbols:**

```
ffffffff81219550-ffffffff812196aa: tick_set_oneshot_wakeup_device (STB_LOCAL)
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
