# Function: <code>reserve_bp_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81186ba0)
Location: kernel/events/hw_breakpoint.c:314
Inline: False
```
**Symbols:**

```
ffffffff81186ba0-ffffffff81186bd4: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81199060)
Location: kernel/events/hw_breakpoint.c:314
Inline: False
```
**Symbols:**

```
ffffffff81199060-ffffffff81199094: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811a8a50)
Location: kernel/events/hw_breakpoint.c:314
Inline: False
```
**Symbols:**

```
ffffffff811a8a50-ffffffff811a8a84: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811b0200)
Location: kernel/events/hw_breakpoint.c:314
Inline: False
```
**Symbols:**

```
ffffffff811b0200-ffffffff811b0234: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811c3d00)
Location: kernel/events/hw_breakpoint.c:314
Inline: False
```
**Symbols:**

```
ffffffff811c3d00-ffffffff811c3d34: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811e3f40)
Location: kernel/events/hw_breakpoint.c:315
Inline: False
```
**Symbols:**

```
ffffffff811e3f40-ffffffff811e3f7a: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811f43f0)
Location: kernel/events/hw_breakpoint.c:315
Inline: False
```
**Symbols:**

```
ffffffff811f43f0-ffffffff811f442a: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8120c0c0)
Location: kernel/events/hw_breakpoint.c:302
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff8120c0c0-ffffffff8120c100: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff812193a0)
Location: kernel/events/hw_breakpoint.c:302
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff812193a0-ffffffff812193e0: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff812452d2)
Location: kernel/events/hw_breakpoint.c:316
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff81245150-ffffffff81245192: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8124f922)
Location: kernel/events/hw_breakpoint.c:316
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff8124f7a0-ffffffff8124f7e2: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff812541f2)
Location: kernel/events/hw_breakpoint.c:316
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff81254070-ffffffff812540b2: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8128fc62)
Location: kernel/events/hw_breakpoint.c:316
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff8128fae0-ffffffff8128fb22: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff812e4c91)
Location: kernel/events/hw_breakpoint.c:316
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff812e4ae0-ffffffff812e4b25: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8134e493)
Location: kernel/events/hw_breakpoint.c:623
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff8134e220-ffffffff8134e265: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8137f6b3)
Location: kernel/events/hw_breakpoint.c:623
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff8137f440-ffffffff8137f485: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff813a88b3)
Location: kernel/events/hw_breakpoint.c:598
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff813a8680-ffffffff813a86c5: reserve_bp_slot (STB_GLOBAL)
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
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffff8000102a4528)
Location: kernel/events/hw_breakpoint.c:302
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffff8000102a4528-ffff8000102a457c: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (c04d3b30)
Location: kernel/events/hw_breakpoint.c:302
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
c04d3b30-c04d3b7c: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (c000000000356ca0)
Location: kernel/events/hw_breakpoint.c:302
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
c000000000356ca0-c000000000356d14: reserve_bp_slot (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff812119f0)
Location: kernel/events/hw_breakpoint.c:302
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff812119f0-ffffffff81211a30: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81204780)
Location: kernel/events/hw_breakpoint.c:302
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff81204780-ffffffff812047c0: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8120f790)
Location: kernel/events/hw_breakpoint.c:302
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff8120f790-ffffffff8120f7d0: reserve_bp_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8121e6a0)
Location: kernel/events/hw_breakpoint.c:302
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff8121e6a0-ffffffff8121e6e0: reserve_bp_slot (STB_GLOBAL)
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
