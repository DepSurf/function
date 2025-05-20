# Function: <code>klp_try_switch_task</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff810f8e61)
Location: kernel/livepatch/transition.c:285
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool klp_try_switch_task(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811034d0)
Location: kernel/livepatch/transition.c:310
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff811034d0-ffffffff811037c6: klp_try_switch_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool klp_try_switch_task(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8110ba70)
Location: kernel/livepatch/transition.c:298
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff8110ba70-ffffffff8110bd65: klp_try_switch_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool klp_try_switch_task(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81117260)
Location: kernel/livepatch/transition.c:298
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff81117260-ffffffff81117555: klp_try_switch_task (STB_LOCAL)
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
In kernel/livepatch/transition.c (ffffffff811218d3)
Location: kernel/livepatch/transition.c:281
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff81121540-ffffffff811217f3: klp_try_switch_task.part.0 (STB_LOCAL)
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
In kernel/livepatch/transition.c (ffffffff8112def3)
Location: kernel/livepatch/transition.c:281
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff8112db60-ffffffff8112de13: klp_try_switch_task.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8113c8d3)
Location: kernel/livepatch/transition.c:281
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff8113c330-ffffffff8113c44e: klp_try_switch_task.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81136fe3)
Location: kernel/livepatch/transition.c:281
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff81136a40-ffffffff81136b5e: klp_try_switch_task.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81137cb3)
Location: kernel/livepatch/transition.c:282
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff81137680-ffffffff8113792e: klp_try_switch_task.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8115aa03)
Location: kernel/livepatch/transition.c:282
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff8115a530-ffffffff8115a649: klp_try_switch_task.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool klp_try_switch_task(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81183b80)
Location: kernel/livepatch/transition.c:289
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff81183b80-ffffffff81183cf3: klp_try_switch_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool klp_try_switch_task(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811beda0)
Location: kernel/livepatch/transition.c:289
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff811beda0-ffffffff811bef13: klp_try_switch_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool klp_try_switch_task(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811d19c0)
Location: kernel/livepatch/transition.c:314
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff811d19c0-ffffffff811d1b5c: klp_try_switch_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool klp_try_switch_task(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811e6640)
Location: kernel/livepatch/transition.c:314
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff811e6640-ffffffff811e67dc: klp_try_switch_task (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (c0000000001f2f40)
Location: kernel/livepatch/transition.c:281
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
c0000000001f29d0-c0000000001f2da0: klp_try_switch_task.part.0 (STB_LOCAL)
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
In kernel/livepatch/transition.c (ffffffff811264d3)
Location: kernel/livepatch/transition.c:281
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff81126140-ffffffff811263f3: klp_try_switch_task.part.0 (STB_LOCAL)
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
In kernel/livepatch/transition.c (ffffffff81118f33)
Location: kernel/livepatch/transition.c:281
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff81118ba0-ffffffff81118e53: klp_try_switch_task.part.0 (STB_LOCAL)
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
In kernel/livepatch/transition.c (ffffffff811243c3)
Location: kernel/livepatch/transition.c:281
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff81124030-ffffffff811242e3: klp_try_switch_task.part.0 (STB_LOCAL)
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
In kernel/livepatch/transition.c (ffffffff81130a23)
Location: kernel/livepatch/transition.c:281
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff81130670-ffffffff81130921: klp_try_switch_task.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
