# Function: <code>perf_event_init_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_event_init_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117ad20)
Location: kernel/events/core.c:9274
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff8117ad20-ffffffff8117adb3: perf_event_init_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81196e70)
Location: kernel/events/core.c:10467
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff81196e70-ffffffff81196f12: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a6880)
Location: kernel/events/core.c:10741
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff811a6880-ffffffff811a6922: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ae060)
Location: kernel/events/core.c:11066
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff811ae060-ffffffff811ae0f7: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811c1bc0)
Location: kernel/events/core.c:11099
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff811c1bc0-ffffffff811c1c57: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e1f50)
Location: kernel/events/core.c:11651
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff811e1f50-ffffffff811e1fe7: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f23c0)
Location: kernel/events/core.c:11694
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff811f23c0-ffffffff811f2457: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:12059
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff8120a175-ffffffff8120a188: perf_event_init_cpu.cold (STB_LOCAL)
ffffffff81209f80-ffffffff8120a07e: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812172f0)
Location: kernel/events/core.c:12176
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff812172f0-ffffffff812173eb: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81242d30)
Location: kernel/events/core.c:12779
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff81242d30-ffffffff81242dc0: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124d480)
Location: kernel/events/core.c:13062
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff8124d480-ffffffff8124d510: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81251d50)
Location: kernel/events/core.c:13255
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff81251d50-ffffffff81251e4b: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128d570)
Location: kernel/events/core.c:13376
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff8128d570-ffffffff8128d6ce: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e22d0)
Location: kernel/events/core.c:13346
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff812e22d0-ffffffff812e243f: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8134a870)
Location: kernel/events/core.c:13576
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff8134a870-ffffffff8134a9c0: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8137b8b0)
Location: kernel/events/core.c:13618
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff8137b8b0-ffffffff8137ba00: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a4ab0)
Location: kernel/events/core.c:13716
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff813a4ab0-ffffffff813a4c38: perf_event_init_cpu (STB_GLOBAL)
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
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102a1568)
Location: kernel/events/core.c:12176
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffff8000102a1568-ffff8000102a16b0: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04d1710)
Location: kernel/events/core.c:12176
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
c04d1710-c04d1820: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000353940)
Location: kernel/events/core.c:12176
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
c000000000353940-c000000000353af8: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001d0864)
Location: kernel/events/core.c:12176
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffe0001d0864-ffffffe0001d0996: perf_event_init_cpu (STB_GLOBAL)
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
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120f940)
Location: kernel/events/core.c:12176
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff8120f940-ffffffff8120fa3b: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812026d0)
Location: kernel/events/core.c:12176
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff812026d0-ffffffff812027cb: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120d6e0)
Location: kernel/events/core.c:12176
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff8120d6e0-ffffffff8120d7db: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perf_event_init_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8121c580)
Location: kernel/events/core.c:12176
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init
```
**Symbols:**

```
ffffffff8121c580-ffffffff8121c67b: perf_event_init_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int cpu</code> ➡️ <code>unsigned int cpu</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
