# Function: <code>update_traceon_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void update_traceon_count(void **data, bool on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff81156c00)
Location: kernel/trace/trace_functions.c:264
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffff81156c00-ffffffff81156c59: update_traceon_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void update_traceon_count(void **data, bool on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff81161480)
Location: kernel/trace/trace_functions.c:270
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffff81161480-ffffffff811614d3: update_traceon_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void update_traceon_count(void **data, bool on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff8116bee0)
Location: kernel/trace/trace_functions.c:270
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffff8116bee0-ffffffff8116bf33: update_traceon_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff8116f3f0)
Location: kernel/trace/trace_functions.c:270
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffff8116f3f0-ffffffff8116f44e: update_traceon_count.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff8117c4e0)
Location: kernel/trace/trace_functions.c:281
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffff8117c4e0-ffffffff8117c53e: update_traceon_count.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff8118b610)
Location: kernel/trace/trace_functions.c:281
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffff8118b610-ffffffff8118b66e: update_traceon_count.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff81198f40)
Location: kernel/trace/trace_functions.c:281
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffff81198f40-ffffffff81198f99: update_traceon_count.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811a6b40)
Location: kernel/trace/trace_functions.c:281
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffff811a6b40-ffffffff811a6b9b: update_traceon_count.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811b2330)
Location: kernel/trace/trace_functions.c:281
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffff811b2330-ffffffff811b238b: update_traceon_count.constprop.0 (STB_LOCAL)
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
In kernel/trace/trace_functions.c (ffffffff811ca200)
Location: kernel/trace/trace_functions.c:281
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
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
In kernel/trace/trace_functions.c (ffffffff811c7881)
Location: kernel/trace/trace_functions.c:284
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
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
In kernel/trace/trace_functions.c (ffffffff811c8881)
Location: kernel/trace/trace_functions.c:448
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
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
In kernel/trace/trace_functions.c (ffffffff811f4251)
Location: kernel/trace/trace_functions.c:448
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff8122ddb1)
Location: kernel/trace/trace_functions.c:443
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff81279c41)
Location: kernel/trace/trace_functions.c:443
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff81291681)
Location: kernel/trace/trace_functions.c:443
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff812acc91)
Location: kernel/trace/trace_functions.c:443
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffff80001022fe68)
Location: kernel/trace/trace_functions.c:281
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffff80001022fe68-ffff80001022fee0: update_traceon_count.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_functions.c (c046bea4)
Location: kernel/trace/trace_functions.c:281
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (c0000000002ba0f0)
Location: kernel/trace/trace_functions.c:281
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
c0000000002ba0f0-c0000000002ba1d0: update_traceon_count.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffe0001880e2)
Location: kernel/trace/trace_functions.c:281
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffe0001880e2-ffffffe000188150: update_traceon_count.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811aa950)
Location: kernel/trace/trace_functions.c:281
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffff811aa950-ffffffff811aa9ab: update_traceon_count.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff8119d8a0)
Location: kernel/trace/trace_functions.c:281
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffff8119d8a0-ffffffff8119d8fb: update_traceon_count.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811a8720)
Location: kernel/trace/trace_functions.c:281
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffff811a8720-ffffffff811a877b: update_traceon_count.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions.c (ffffffff811b64e0)
Location: kernel/trace/trace_functions.c:281
Inline: True
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
```
**Symbols:**

```
ffffffff811b64e0-ffffffff811b653b: update_traceon_count.constprop.0 (STB_LOCAL)
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
</ul>
