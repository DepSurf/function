# Function: <code>oom_reap_task_mm</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811f2f25)
Location: mm/oom_kill.c:522
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81204fd1)
Location: mm/oom_kill.c:557
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121ca99)
Location: mm/oom_kill.c:567
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122a479)
Location: mm/oom_kill.c:567
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool oom_reap_task_mm(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:568
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff812571b0-ffffffff81257367: oom_reap_task_mm (STB_LOCAL)
ffffffff81257a19-ffffffff81257a7e: oom_reap_task_mm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool oom_reap_task_mm(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:570
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_reaper
```
**Symbols:**

```
ffffffff81261d90-ffffffff81261f47: oom_reap_task_mm (STB_LOCAL)
ffffffff81be6d8c-ffffffff81be6df0: oom_reap_task_mm.cold (STB_LOCAL)
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
In mm/oom_kill.c (ffffffff812668e4)
Location: mm/oom_kill.c:569
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
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
In mm/oom_kill.c (ffffffff812a2eb4)
Location: mm/oom_kill.c:570
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
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
In mm/oom_kill.c (ffffffff812face9)
Location: mm/oom_kill.c:567
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
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
In mm/oom_kill.c (ffffffff8136381b)
Location: mm/oom_kill.c:568
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
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
In mm/oom_kill.c (ffffffff81395cee)
Location: mm/oom_kill.c:568
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
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
In mm/oom_kill.c (ffffffff813bfaae)
Location: mm/oom_kill.c:565
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b8490)
Location: mm/oom_kill.c:567
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
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
In mm/oom_kill.c (c04e4c30)
Location: mm/oom_kill.c:567
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c000000000370600)
Location: mm/oom_kill.c:567
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001dc21e)
Location: mm/oom_kill.c:567
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81222ac9)
Location: mm/oom_kill.c:567
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81215c79)
Location: mm/oom_kill.c:567
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81220869)
Location: mm/oom_kill.c:567
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122f981)
Location: mm/oom_kill.c:567
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
