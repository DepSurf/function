# Function: <code>tick_broadcast_oneshot_offline</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8113c204)
Location: kernel/time/tick-broadcast.c:963
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
In kernel/time/tick-broadcast.c (ffffffff81147e14)
Location: kernel/time/tick-broadcast.c:963
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
In kernel/time/tick-broadcast.c (ffffffff81157c54)
Location: kernel/time/tick-broadcast.c:963
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
In kernel/time/tick-broadcast.c (ffffffff81153d44)
Location: kernel/time/tick-broadcast.c:980
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
In kernel/time/tick-broadcast.c (ffffffff811551b4)
Location: kernel/time/tick-broadcast.c:992
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
In kernel/time/tick-broadcast.c (ffffffff81179e89)
Location: kernel/time/tick-broadcast.c:1100
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tick_broadcast_oneshot_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff811ae390)
Location: kernel/time/tick-broadcast.c:1100
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
```
**Symbols:**

```
ffffffff811ae390-ffffffff811ae472: tick_broadcast_oneshot_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tick_broadcast_oneshot_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff811eeac0)
Location: kernel/time/tick-broadcast.c:1100
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
```
**Symbols:**

```
ffffffff811eeac0-ffffffff811eeba2: tick_broadcast_oneshot_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tick_broadcast_oneshot_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff812031f0)
Location: kernel/time/tick-broadcast.c:1160
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
```
**Symbols:**

```
ffffffff812031f0-ffffffff812032d2: tick_broadcast_oneshot_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tick_broadcast_oneshot_offline(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff812197b0)
Location: kernel/time/tick-broadcast.c:1160
Inline: False
Direct callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_offline
```
**Symbols:**

```
ffffffff812197b0-ffffffff81219892: tick_broadcast_oneshot_offline (STB_LOCAL)
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
In kernel/time/tick-broadcast.c (ffff8000101b3510)
Location: kernel/time/tick-broadcast.c:963
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
In kernel/time/tick-broadcast.c (c03fd6d4)
Location: kernel/time/tick-broadcast.c:963
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
In kernel/time/tick-broadcast.c (c000000000218d40)
Location: kernel/time/tick-broadcast.c:963
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
In kernel/time/tick-broadcast.c (ffffffff81140434)
Location: kernel/time/tick-broadcast.c:963
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
In kernel/time/tick-broadcast.c (ffffffff811331b4)
Location: kernel/time/tick-broadcast.c:963
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
In kernel/time/tick-broadcast.c (ffffffff8113e2e4)
Location: kernel/time/tick-broadcast.c:963
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
In kernel/time/tick-broadcast.c (ffffffff8114adf4)
Location: kernel/time/tick-broadcast.c:963
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
