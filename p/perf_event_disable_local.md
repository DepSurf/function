# Function: <code>perf_event_disable_local</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81194d26)
Location: kernel/events/core.c:1948
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811912e0-ffffffff811912eb: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a4786)
Location: kernel/events/core.c:1980
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811a09c0-ffffffff811a09cb: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811abdc6)
Location: kernel/events/core.c:1993
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811a8390-ffffffff811a839b: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bf73d)
Location: kernel/events/core.c:1986
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811bbb00-ffffffff811bbb0b: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811df9f1)
Location: kernel/events/core.c:2183
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffff811dbc90-ffffffff811dbc9b: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811efe3f)
Location: kernel/events/core.c:2183
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811ec050-ffffffff811ec05b: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207653)
Location: kernel/events/core.c:2185
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812039e0-ffffffff812039eb: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812149c3)
Location: kernel/events/core.c:2270
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812105d0-ffffffff812105db: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81240f03)
Location: kernel/events/core.c:2417
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8123c7e0-ffffffff8123c7eb: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124b4a9)
Location: kernel/events/core.c:2457
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81246a80-ffffffff81246a8b: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124f520)
Location: kernel/events/core.c:2459
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8124a7f0-ffffffff8124a7fb: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128a1a0)
Location: kernel/events/core.c:2534
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81284120-ffffffff8128412b: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812deb50)
Location: kernel/events/core.c:2447
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812d84b0-ffffffff812d84c6: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81346c95)
Location: kernel/events/core.c:2452
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_irq
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff813409d0-ffffffff813409e6: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81377d95)
Location: kernel/events/core.c:2452
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_irq
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81371970-ffffffff81371986: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a1075)
Location: kernel/events/core.c:2490
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_irq
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff8139ac70-ffffffff8139ac86: perf_event_disable_local (STB_GLOBAL)
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
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102a0ce8)
Location: kernel/events/core.c:2270
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffff80001029a888-ffff80001029a89c: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04ce67c)
Location: kernel/events/core.c:2270
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
c04c9f30-c04c9f44: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034fc7c)
Location: kernel/events/core.c:2270
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
c00000000034a610-c00000000034a61c: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001ce44a)
Location: kernel/events/core.c:2270
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
```
**Symbols:**

```
ffffffe0001cd1d6-ffffffe0001cd1ee: perf_event_disable_local (STB_GLOBAL)
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
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120d013)
Location: kernel/events/core.c:2270
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81208c20-ffffffff81208c2b: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ffde3)
Location: kernel/events/core.c:2270
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff811fb9b0-ffffffff811fb9bb: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120adb3)
Location: kernel/events/core.c:2270
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff812069c0-ffffffff812069cb: perf_event_disable_local (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void perf_event_disable_local(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81219bc3)
Location: kernel/events/core.c:2270
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pending_event
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint
```
**Symbols:**

```
ffffffff81215730-ffffffff8121573b: perf_event_disable_local (STB_GLOBAL)
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
