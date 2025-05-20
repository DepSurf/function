# Function: <code>__reserve_bp_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81186a00)
Location: kernel/events/hw_breakpoint.c:280
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
**Symbols:**

```
ffffffff81186a00-ffffffff81186b83: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81198ec0)
Location: kernel/events/hw_breakpoint.c:280
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
ffffffff81198ec0-ffffffff8119904d: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811a88a0)
Location: kernel/events/hw_breakpoint.c:280
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
ffffffff811a88a0-ffffffff811a8a3d: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811b0050)
Location: kernel/events/hw_breakpoint.c:280
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
ffffffff811b0050-ffffffff811b01e2: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811c3b70)
Location: kernel/events/hw_breakpoint.c:280
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
ffffffff811c3b70-ffffffff811c3ce7: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811e3da0)
Location: kernel/events/hw_breakpoint.c:281
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
ffffffff811e3da0-ffffffff811e3f23: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811f4250)
Location: kernel/events/hw_breakpoint.c:281
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
ffffffff811f4250-ffffffff811f43d3: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8120bf40)
Location: kernel/events/hw_breakpoint.c:268
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
ffffffff8120bf40-ffffffff8120c0a5: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81219220)
Location: kernel/events/hw_breakpoint.c:268
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
ffffffff81219220-ffffffff81219385: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81245060)
Location: kernel/events/hw_breakpoint.c:277
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
**Symbols:**

```
ffffffff81245060-ffffffff8124512e: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8124f6b0)
Location: kernel/events/hw_breakpoint.c:277
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
**Symbols:**

```
ffffffff8124f6b0-ffffffff8124f77e: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81253e40)
Location: kernel/events/hw_breakpoint.c:277
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
**Symbols:**

```
ffffffff81253e40-ffffffff81254044: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8128f830)
Location: kernel/events/hw_breakpoint.c:277
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
**Symbols:**

```
ffffffff8128f830-ffffffff8128fabf: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff812e4840)
Location: kernel/events/hw_breakpoint.c:277
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
**Symbols:**

```
ffffffff812e4840-ffffffff812e4abd: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/hw_breakpoint.c (0)
Location: kernel/events/hw_breakpoint.c:592
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
**Symbols:**

```
ffffffff8134e130-ffffffff8134e1c3: __reserve_bp_slot (STB_LOCAL)
ffffffff82061ea4-ffffffff82061eb9: __reserve_bp_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/hw_breakpoint.c (0)
Location: kernel/events/hw_breakpoint.c:592
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
**Symbols:**

```
ffffffff8137f350-ffffffff8137f3e3: __reserve_bp_slot (STB_LOCAL)
ffffffff820e163e-ffffffff820e1653: __reserve_bp_slot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/hw_breakpoint.c (0)
Location: kernel/events/hw_breakpoint.c:572
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
```
**Symbols:**

```
ffffffff813a8580-ffffffff813a85f8: __reserve_bp_slot (STB_LOCAL)
ffffffff821be0a1-ffffffff821be0b6: __reserve_bp_slot.cold (STB_LOCAL)
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
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffff8000102a42e0)
Location: kernel/events/hw_breakpoint.c:268
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
ffff8000102a42e0-ffff8000102a44c4: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (c04d3904)
Location: kernel/events/hw_breakpoint.c:268
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
c04d3904-c04d3adc: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (c000000000356950)
Location: kernel/events/hw_breakpoint.c:268
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
c000000000356950-c000000000356c18: __reserve_bp_slot (STB_LOCAL)
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
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81211870)
Location: kernel/events/hw_breakpoint.c:268
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
ffffffff81211870-ffffffff812119d5: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81204600)
Location: kernel/events/hw_breakpoint.c:268
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
ffffffff81204600-ffffffff81204765: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8120f610)
Location: kernel/events/hw_breakpoint.c:268
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
ffffffff8120f610-ffffffff8120f775: __reserve_bp_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __reserve_bp_slot(struct perf_event *bp, u64 bp_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8121e520)
Location: kernel/events/hw_breakpoint.c:268
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:dbg_reserve_bp_slot
  - kernel/events/hw_breakpoint.c:reserve_bp_slot
```
**Symbols:**

```
ffffffff8121e520-ffffffff8121e685: __reserve_bp_slot (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 bp_type</code>
</li>
</ul>
</details>
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
