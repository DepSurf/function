# Function: <code>tick_device_uses_broadcast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff810fd910)
Location: kernel/time/tick-broadcast.c:158
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
```
**Symbols:**

```
ffffffff810fd910-ffffffff810fdabf: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81104c80)
Location: kernel/time/tick-broadcast.c:158
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
```
**Symbols:**

```
ffffffff81104c80-ffffffff81104e35: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8110c3b0)
Location: kernel/time/tick-broadcast.c:158
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
```
**Symbols:**

```
ffffffff8110c3b0-ffffffff8110c567: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8110df70)
Location: kernel/time/tick-broadcast.c:161
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
```
**Symbols:**

```
ffffffff8110df70-ffffffff8110e128: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff811191f0)
Location: kernel/time/tick-broadcast.c:161
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
```
**Symbols:**

```
ffffffff811191f0-ffffffff811193a8: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-broadcast.c (0)
Location: kernel/time/tick-broadcast.c:161
Inline: False
```
**Symbols:**

```
ffffffff81126549-ffffffff81126587: tick_device_uses_broadcast.cold.11 (STB_LOCAL)
ffffffff81125d80-ffffffff81125f15: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-broadcast.c (0)
Location: kernel/time/tick-broadcast.c:157
Inline: False
```
**Symbols:**

```
ffffffff81131c29-ffffffff81131c67: tick_device_uses_broadcast.cold.12 (STB_LOCAL)
ffffffff81131460-ffffffff811315f5: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-broadcast.c (0)
Location: kernel/time/tick-broadcast.c:163
Inline: False
```
**Symbols:**

```
ffffffff8113c759-ffffffff8113c797: tick_device_uses_broadcast.cold (STB_LOCAL)
ffffffff8113bfd0-ffffffff8113c15f: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-broadcast.c (0)
Location: kernel/time/tick-broadcast.c:163
Inline: False
```
**Symbols:**

```
ffffffff81148369-ffffffff811483a7: tick_device_uses_broadcast.cold (STB_LOCAL)
ffffffff81147be0-ffffffff81147d6f: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-broadcast.c (0)
Location: kernel/time/tick-broadcast.c:163
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
```
**Symbols:**

```
ffffffff811581a9-ffffffff811581e7: tick_device_uses_broadcast.cold (STB_LOCAL)
ffffffff81157a10-ffffffff81157baa: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-broadcast.c (0)
Location: kernel/time/tick-broadcast.c:163
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
```
**Symbols:**

```
ffffffff81be3ce2-ffffffff81be3d20: tick_device_uses_broadcast.cold (STB_LOCAL)
ffffffff81153b00-ffffffff81153c9a: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-broadcast.c (0)
Location: kernel/time/tick-broadcast.c:175
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
```
**Symbols:**

```
ffffffff81bd5bfc-ffffffff81bd5c3a: tick_device_uses_broadcast.cold (STB_LOCAL)
ffffffff81154f70-ffffffff8115510e: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81179c50)
Location: kernel/time/tick-broadcast.c:246
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
```
**Symbols:**

```
ffffffff81179c50-ffffffff81179ddc: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff811af160)
Location: kernel/time/tick-broadcast.c:246
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
```
**Symbols:**

```
ffffffff811af160-ffffffff811af2a6: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff811ef990)
Location: kernel/time/tick-broadcast.c:246
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
```
**Symbols:**

```
ffffffff811ef990-ffffffff811efad6: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff81204130)
Location: kernel/time/tick-broadcast.c:247
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
```
**Symbols:**

```
ffffffff81204130-ffffffff81204278: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffffffff8121a6f0)
Location: kernel/time/tick-broadcast.c:247
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
```
**Symbols:**

```
ffffffff8121a6f0-ffffffff8121a838: tick_device_uses_broadcast (STB_GLOBAL)
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
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (ffff8000101b30f8)
Location: kernel/time/tick-broadcast.c:163
Inline: False
```
**Symbols:**

```
ffff8000101b30f8-ffff8000101b33ec: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (c03fd3b8)
Location: kernel/time/tick-broadcast.c:163
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_setup_device
```
**Symbols:**

```
c03fd3b8-c03fd608: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-broadcast.c (c0000000002187c0)
Location: kernel/time/tick-broadcast.c:163
Inline: False
```
**Symbols:**

```
c0000000002187c0-c000000000218be8: tick_device_uses_broadcast (STB_GLOBAL)
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
In kernel/time/tick-common.c (0)
Location: kernel/time/tick-internal.h:78
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-broadcast.c (0)
Location: kernel/time/tick-broadcast.c:163
Inline: False
```
**Symbols:**

```
ffffffff81140989-ffffffff811409c7: tick_device_uses_broadcast.cold (STB_LOCAL)
ffffffff81140200-ffffffff8114038f: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-broadcast.c (0)
Location: kernel/time/tick-broadcast.c:163
Inline: False
```
**Symbols:**

```
ffffffff81133709-ffffffff81133747: tick_device_uses_broadcast.cold (STB_LOCAL)
ffffffff81132f80-ffffffff8113310f: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-broadcast.c (0)
Location: kernel/time/tick-broadcast.c:163
Inline: False
```
**Symbols:**

```
ffffffff8113e839-ffffffff8113e877: tick_device_uses_broadcast.cold (STB_LOCAL)
ffffffff8113e0b0-ffffffff8113e23f: tick_device_uses_broadcast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tick_device_uses_broadcast(struct clock_event_device *dev, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-broadcast.c (0)
Location: kernel/time/tick-broadcast.c:163
Inline: False
```
**Symbols:**

```
ffffffff8114b349-ffffffff8114b387: tick_device_uses_broadcast.cold (STB_LOCAL)
ffffffff8114abc0-ffffffff8114ad4f: tick_device_uses_broadcast (STB_GLOBAL)
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
