# Function: <code>perf_event_exit_cpu</code>

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
In kernel/events/core.c (ffffffff811797c5)
Location: kernel/events/core.c:9318
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118a065)
Location: kernel/events/core.c:10518
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff81196f20-ffffffff81196f2d: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81199455)
Location: kernel/events/core.c:10792
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff811a6930-ffffffff811a693d: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a1015)
Location: kernel/events/core.c:11089
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff811ae100-ffffffff811ae10d: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b4cc5)
Location: kernel/events/core.c:11122
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff811c1c60-ffffffff811c1c6d: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d3b25)
Location: kernel/events/core.c:11674
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff811e1ff0-ffffffff811e1ffd: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e3f55)
Location: kernel/events/core.c:11717
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff811f2460-ffffffff811f246d: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fb12e)
Location: kernel/events/core.c:12082
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff8120a080-ffffffff8120a08d: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812081fe)
Location: kernel/events/core.c:12199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff812173f0-ffffffff812173fd: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81230e8e)
Location: kernel/events/core.c:12802
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff81242dc0-ffffffff81242dcd: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123aa9e)
Location: kernel/events/core.c:13085
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff8124d510-ffffffff8124d51d: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f26e)
Location: kernel/events/core.c:13278
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff81251e50-ffffffff81251e5d: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81279dde)
Location: kernel/events/core.c:13399
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff8128d6d0-ffffffff8128d6dd: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cd1b1)
Location: kernel/events/core.c:13369
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff812e2440-ffffffff812e2458: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81337b8e)
Location: kernel/events/core.c:13596
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff8134a9d0-ffffffff8134a9e8: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136857e)
Location: kernel/events/core.c:13638
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff8137ba10-ffffffff8137ba28: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139149e)
Location: kernel/events/core.c:13736
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff813a4c50-ffffffff813a4c68: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010295438)
Location: kernel/events/core.c:12199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffff8000102a16b0-ffff8000102a16c8: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c3240)
Location: kernel/events/core.c:12199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
c04d1820-c04d1838: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033fde4)
Location: kernel/events/core.c:12199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
c000000000353b00-c000000000353b30: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001d0996)
Location: kernel/events/core.c:12199
Inline: True
```
**Symbols:**

```
ffffffe0001d0996-ffffffe0001d09a4: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120081e)
Location: kernel/events/core.c:12199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff8120fa40-ffffffff8120fa4d: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f356e)
Location: kernel/events/core.c:12199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff812027d0-ffffffff812027dd: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fe5ee)
Location: kernel/events/core.c:12199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff8120d7e0-ffffffff8120d7ed: perf_event_exit_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int perf_event_exit_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120d64e)
Location: kernel/events/core.c:12199
Inline: True
Inline callers:
  - kernel/events/core.c:perf_reboot
```
**Symbols:**

```
ffffffff8121c680-ffffffff8121c68d: perf_event_exit_cpu (STB_GLOBAL)
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
