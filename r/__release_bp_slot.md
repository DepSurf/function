# Function: <code>__release_bp_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __release_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811869d0)
Location: kernel/events/hw_breakpoint.c:327
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:release_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
```
**Symbols:**

```
ffffffff811869d0-ffffffff811869f1: __release_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __release_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81198e90)
Location: kernel/events/hw_breakpoint.c:327
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffffffff81198e90-ffffffff81198eb1: __release_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __release_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811a8870)
Location: kernel/events/hw_breakpoint.c:327
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffffffff811a8870-ffffffff811a8891: __release_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __release_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811b0020)
Location: kernel/events/hw_breakpoint.c:327
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffffffff811b0020-ffffffff811b0041: __release_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __release_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811c3b40)
Location: kernel/events/hw_breakpoint.c:327
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffffffff811c3b40-ffffffff811c3b61: __release_bp_slot (STB_LOCAL)
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
In kernel/events/hw_breakpoint.c (ffffffff811e3d70)
Location: kernel/events/hw_breakpoint.c:328
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffffffff811e3d70-ffffffff811e3d91: __release_bp_slot.isra.12 (STB_LOCAL)
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
In kernel/events/hw_breakpoint.c (ffffffff811f4220)
Location: kernel/events/hw_breakpoint.c:328
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffffffff811f4220-ffffffff811f4241: __release_bp_slot.isra.13 (STB_LOCAL)
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
In kernel/events/hw_breakpoint.c (ffffffff8120bf10)
Location: kernel/events/hw_breakpoint.c:315
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffffffff8120bf10-ffffffff8120bf33: __release_bp_slot.isra.0 (STB_LOCAL)
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
In kernel/events/hw_breakpoint.c (ffffffff812191f0)
Location: kernel/events/hw_breakpoint.c:315
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffffffff812191f0-ffffffff81219213: __release_bp_slot.isra.0 (STB_LOCAL)
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
In kernel/events/hw_breakpoint.c (ffffffff812455d4)
Location: kernel/events/hw_breakpoint.c:329
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff8124fc24)
Location: kernel/events/hw_breakpoint.c:329
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff81254504)
Location: kernel/events/hw_breakpoint.c:329
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff8128ff74)
Location: kernel/events/hw_breakpoint.c:329
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff812e4faf)
Location: kernel/events/hw_breakpoint.c:329
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff8134e7d9)
Location: kernel/events/hw_breakpoint.c:632
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff8137f969)
Location: kernel/events/hw_breakpoint.c:632
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
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
In kernel/events/hw_breakpoint.c (ffffffff813a8633)
Location: kernel/events/hw_breakpoint.c:607
Inline: True
Inline callers:
  - kernel/events/hw_breakpoint.c:bp_perf_event_destroy
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
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
void __release_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffff8000102a44c8)
Location: kernel/events/hw_breakpoint.c:315
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffff8000102a44c8-ffff8000102a4510: __release_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __release_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (c04d3adc)
Location: kernel/events/hw_breakpoint.c:315
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
c04d3adc-c04d3b18: __release_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __release_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (c000000000356c20)
Location: kernel/events/hw_breakpoint.c:315
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
c000000000356c20-c000000000356c84: __release_bp_slot (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81211840)
Location: kernel/events/hw_breakpoint.c:315
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffffffff81211840-ffffffff81211863: __release_bp_slot.isra.0 (STB_LOCAL)
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
In kernel/events/hw_breakpoint.c (ffffffff812045d0)
Location: kernel/events/hw_breakpoint.c:315
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffffffff812045d0-ffffffff812045f3: __release_bp_slot.isra.0 (STB_LOCAL)
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
In kernel/events/hw_breakpoint.c (ffffffff8120f5e0)
Location: kernel/events/hw_breakpoint.c:315
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffffffff8120f5e0-ffffffff8120f603: __release_bp_slot.isra.0 (STB_LOCAL)
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
In kernel/events/hw_breakpoint.c (ffffffff8121e4f0)
Location: kernel/events/hw_breakpoint.c:315
Inline: True
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_release_bp_slot
  - kernel/events/hw_breakpoint.c:release_bp_slot
```
**Symbols:**

```
ffffffff8121e4f0-ffffffff8121e513: __release_bp_slot.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
