# Function: <code>perf_event_disable_inatomic</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119a78d)
Location: kernel/events/core.c:1999
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff811a09d0-ffffffff811a09e9: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a2327)
Location: kernel/events/core.c:2012
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff811a83a0-ffffffff811a83b9: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b644a)
Location: kernel/events/core.c:2005
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff811bbb10-ffffffff811bbb29: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d5f40)
Location: kernel/events/core.c:2202
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff811dbca0-ffffffff811dbcb9: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e65e0)
Location: kernel/events/core.c:2202
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff811ec060-ffffffff811ec079: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fde01)
Location: kernel/events/core.c:2204
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff812039f0-ffffffff81203a0c: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120b0b1)
Location: kernel/events/core.c:2289
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff812105e0-ffffffff812105fc: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81236fb1)
Location: kernel/events/core.c:2436
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff8123c7f0-ffffffff8123c80c: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81240bb1)
Location: kernel/events/core.c:2476
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff81246a90-ffffffff81246aac: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81244962)
Location: kernel/events/core.c:2478
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff8124a800-ffffffff8124a81c: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127f902)
Location: kernel/events/core.c:2553
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff81284130-ffffffff8128414c: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d4923)
Location: kernel/events/core.c:2466
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff812d84d0-ffffffff812d84f9: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133ce48)
Location: kernel/events/core.c:2471
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff81340a00-ffffffff81340a26: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136dfbb)
Location: kernel/events/core.c:2471
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff813719a0-ffffffff813719c6: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813970eb)
Location: kernel/events/core.c:2509
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff8139aca0-ffffffff8139acc6: perf_event_disable_inatomic (STB_GLOBAL)
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
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029a8a0)
Location: kernel/events/core.c:2289
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffff80001029a8a0-ffff80001029a8d0: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c1fcc)
Location: kernel/events/core.c:2289
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
c04c9f44-c04c9f74: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000342044)
Location: kernel/events/core.c:2289
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
Direct callers:
  - arch/powerpc/kernel/hw_breakpoint.c:hw_breakpoint_handler
```
**Symbols:**

```
c00000000034a620-c00000000034a65c: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c53f2)
Location: kernel/events/core.c:2289
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffe0001cd1ee-ffffffe0001cd212: perf_event_disable_inatomic (STB_GLOBAL)
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
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812036d1)
Location: kernel/events/core.c:2289
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff81208c30-ffffffff81208c4c: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f67d1)
Location: kernel/events/core.c:2289
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff811fb9c0-ffffffff811fb9dc: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812014a1)
Location: kernel/events/core.c:2289
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff812069d0-ffffffff812069ec: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_inatomic(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81210821)
Location: kernel/events/core.c:2289
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
```
**Symbols:**

```
ffffffff81215740-ffffffff8121575c: perf_event_disable_inatomic (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
