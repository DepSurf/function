# Function: <code>tick_switch_to_oneshot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff810fdfb0)
Location: kernel/time/tick-oneshot.c:76
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff810fdfb0-ffffffff810fe064: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff81105340)
Location: kernel/time/tick-oneshot.c:76
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff81105340-ffffffff811053f4: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff8110ca90)
Location: kernel/time/tick-oneshot.c:76
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff8110ca90-ffffffff8110cb44: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff8110e970)
Location: kernel/time/tick-oneshot.c:76
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff8110e970-ffffffff8110ea24: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff81119c10)
Location: kernel/time/tick-oneshot.c:77
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff81119c10-ffffffff81119cc4: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-oneshot.c (0)
Location: kernel/time/tick-oneshot.c:77
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff81126877-ffffffff811268e5: tick_switch_to_oneshot.cold.3 (STB_LOCAL)
ffffffff811267c0-ffffffff8112681c: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-oneshot.c (0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff81131f57-ffffffff81131fc5: tick_switch_to_oneshot.cold.3 (STB_LOCAL)
ffffffff81131ea0-ffffffff81131efc: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-oneshot.c (0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff8113caa7-ffffffff8113cb19: tick_switch_to_oneshot.cold (STB_LOCAL)
ffffffff8113c9e0-ffffffff8113ca41: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-oneshot.c (0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff81148647-ffffffff811486b9: tick_switch_to_oneshot.cold (STB_LOCAL)
ffffffff81148580-ffffffff811485e1: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-oneshot.c (0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
```
**Symbols:**

```
ffffffff81158487-ffffffff811584f9: tick_switch_to_oneshot.cold (STB_LOCAL)
ffffffff811583c0-ffffffff81158423: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-oneshot.c (0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_nohz_switch_to_nohz
```
**Symbols:**

```
ffffffff81be3d20-ffffffff81be3d92: tick_switch_to_oneshot.cold (STB_LOCAL)
ffffffff81154460-ffffffff811544c3: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-oneshot.c (0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff81bd5c3a-ffffffff81bd5cac: tick_switch_to_oneshot.cold (STB_LOCAL)
ffffffff811558d0-ffffffff81155933: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-oneshot.c (0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff81cb20d6-ffffffff81cb2148: tick_switch_to_oneshot.cold (STB_LOCAL)
ffffffff8117a540-ffffffff8117a5a3: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-oneshot.c (0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff81e63646-ffffffff81e6369d: tick_switch_to_oneshot.cold (STB_LOCAL)
ffffffff811afa30-ffffffff811afa98: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff811f03c0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff811f03c0-ffffffff811f0470: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff81204b20)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff81204b20-ffffffff81204bd0: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffff8121b0e0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff8121b0e0-ffffffff8121b190: tick_switch_to_oneshot (STB_GLOBAL)
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
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffff8000101b4748)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffff8000101b4748-ffff8000101b4814: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (c03fe388)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
c03fe388-c03fe45c: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (c0000000002199f0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
c0000000002199f0-c000000000219afc: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/tick-oneshot.c (ffffffe00013aaee)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffe00013aaee-ffffffe00013abbc: tick_switch_to_oneshot (STB_GLOBAL)
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
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-oneshot.c (0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff81140c67-ffffffff81140cd9: tick_switch_to_oneshot.cold (STB_LOCAL)
ffffffff81140ba0-ffffffff81140c01: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-oneshot.c (0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff811339c7-ffffffff81133a39: tick_switch_to_oneshot.cold (STB_LOCAL)
ffffffff81133920-ffffffff81133981: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-oneshot.c (0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff8113eb17-ffffffff8113eb89: tick_switch_to_oneshot.cold (STB_LOCAL)
ffffffff8113ea50-ffffffff8113eab1: tick_switch_to_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tick_switch_to_oneshot(void (*handler)(struct clock_event_device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/tick-oneshot.c (0)
Location: kernel/time/tick-oneshot.c:73
Inline: False
Direct callers:
  - kernel/time/tick-oneshot.c:tick_init_highres
  - kernel/time/tick-sched.c:tick_check_oneshot_change
```
**Symbols:**

```
ffffffff8114b627-ffffffff8114b699: tick_switch_to_oneshot.cold (STB_LOCAL)
ffffffff8114b560-ffffffff8114b5c1: tick_switch_to_oneshot (STB_GLOBAL)
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
