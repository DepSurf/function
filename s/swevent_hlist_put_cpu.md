# Function: <code>swevent_hlist_put_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8117a7d0)
Location: kernel/events/core.c:6791
Inline: True
Direct callers:
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:perf_swevent_init
```
**Symbols:**

```
ffffffff8117a7d0-ffffffff8117a828: swevent_hlist_put_cpu.isra.84 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118a0d0)
Location: kernel/events/core.c:7385
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff8118a0d0-ffffffff8118a128: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811994c0)
Location: kernel/events/core.c:7498
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff811994c0-ffffffff81199518: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a1410)
Location: kernel/events/core.c:7721
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff811a1410-ffffffff811a1468: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b4f90)
Location: kernel/events/core.c:7718
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff811b4f90-ffffffff811b4fe8: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d3df0)
Location: kernel/events/core.c:8100
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff811d3df0-ffffffff811d3e48: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e42f0)
Location: kernel/events/core.c:8109
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff811e42f0-ffffffff811e4348: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fb5e0)
Location: kernel/events/core.c:8413
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff811fb5e0-ffffffff811fb638: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208990)
Location: kernel/events/core.c:8529
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff81208990-ffffffff812089e8: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81231410)
Location: kernel/events/core.c:9079
Inline: False
Direct callers:
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:swevent_hlist_get
```
**Symbols:**

```
ffffffff81231410-ffffffff81231475: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123b080)
Location: kernel/events/core.c:9345
Inline: False
Direct callers:
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:swevent_hlist_get
```
**Symbols:**

```
ffffffff8123b080-ffffffff8123b0e5: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f840)
Location: kernel/events/core.c:9475
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff8123f840-ffffffff8123f8a5: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127a060)
Location: kernel/events/core.c:9594
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff8127a060-ffffffff8127a0df: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cd570)
Location: kernel/events/core.c:9529
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff812cd570-ffffffff812cd608: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813354b0)
Location: kernel/events/core.c:9854
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff813354b0-ffffffff81335548: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81366200)
Location: kernel/events/core.c:9883
Inline: False
Direct callers:
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:swevent_hlist_get
```
**Symbols:**

```
ffffffff81366200-ffffffff81366293: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138f320)
Location: kernel/events/core.c:9953
Inline: False
Direct callers:
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:swevent_hlist_get
```
**Symbols:**

```
ffffffff8138f320-ffffffff8138f3b3: swevent_hlist_put_cpu (STB_LOCAL)
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
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010291d98)
Location: kernel/events/core.c:8529
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffff800010291d98-ffff800010291e0c: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c3258)
Location: kernel/events/core.c:8529
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
c04c3258-c04c32c4: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000340410)
Location: kernel/events/core.c:8529
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
c000000000340410-c0000000003404c0: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c465c)
Location: kernel/events/core.c:8529
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffe0001c465c-ffffffe0001c46c8: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200fb0)
Location: kernel/events/core.c:8529
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff81200fb0-ffffffff81201008: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f3d00)
Location: kernel/events/core.c:8529
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff811f3d00-ffffffff811f3d58: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fed80)
Location: kernel/events/core.c:8529
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff811fed80-ffffffff811fedd8: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void swevent_hlist_put_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120de10)
Location: kernel/events/core.c:8529
Inline: False
Direct callers:
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
```
**Symbols:**

```
ffffffff8120de10-ffffffff8120de68: swevent_hlist_put_cpu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
