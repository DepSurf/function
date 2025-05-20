# Function: <code>enter_state</code>

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
In kernel/power/suspend.c (ffffffff810cea02)
Location: kernel/power/suspend.c:468
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810d3521)
Location: kernel/power/suspend.c:470
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810da0b1)
Location: kernel/power/suspend.c:493
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810d9190)
Location: kernel/power/suspend.c:516
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810e132b)
Location: kernel/power/suspend.c:539
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810e9976)
Location: kernel/power/suspend.c:544
Inline: True
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
In kernel/power/suspend.c (ffffffff810f4f96)
Location: kernel/power/suspend.c:550
Inline: True
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
In kernel/power/suspend.c (ffffffff810fd4b2)
Location: kernel/power/suspend.c:557
Inline: True
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
In kernel/power/suspend.c (ffffffff811098fe)
Location: kernel/power/suspend.c:547
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int enter_state(suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff811145ea)
Location: kernel/power/suspend.c:547
Inline: False
```
**Symbols:**

```
ffffffff811145ea-ffffffff8111476e: enter_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int enter_state(suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff81bdee7b)
Location: kernel/power/suspend.c:547
Inline: False
```
**Symbols:**

```
ffffffff81bdee7b-ffffffff81bdefff: enter_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int enter_state(suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff81bd0f1d)
Location: kernel/power/suspend.c:547
Inline: False
```
**Symbols:**

```
ffffffff81bd0f1d-ffffffff81bd1152: enter_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int enter_state(suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:545
Inline: False
```
**Symbols:**

```
ffffffff811314c0-ffffffff811318ef: enter_state (STB_LOCAL)
ffffffff81ca9cbe-ffffffff81ca9cfc: enter_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int enter_state(suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:546
Inline: False
```
**Symbols:**

```
ffffffff81152ef0-ffffffff811534cf: enter_state (STB_LOCAL)
ffffffff81e59c54-ffffffff81e59cde: enter_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int enter_state(suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:553
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
```
**Symbols:**

```
ffffffff811822d0-ffffffff811828e5: enter_state (STB_LOCAL)
ffffffff82058423-ffffffff82058474: enter_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int enter_state(suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:553
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
```
**Symbols:**

```
ffffffff811931b0-ffffffff8119379e: enter_state (STB_LOCAL)
ffffffff820d6d0b-ffffffff820d6d1f: enter_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int enter_state(suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:553
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
```
**Symbols:**

```
ffffffff811a1ba0-ffffffff811a218e: enter_state (STB_LOCAL)
ffffffff821b1fa1-ffffffff821b1fb5: enter_state.cold (STB_LOCAL)
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
In kernel/power/suspend.c (ffff8000101710a0)
Location: kernel/power/suspend.c:547
Inline: True
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
In kernel/power/suspend.c (c03bbbac)
Location: kernel/power/suspend.c:547
Inline: True
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
In kernel/power/suspend.c (c0000000001c9550)
Location: kernel/power/suspend.c:547
Inline: True
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810f2deb)
Location: kernel/power/suspend.c:547
Inline: True
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
In kernel/power/suspend.c (ffffffff810ffdce)
Location: kernel/power/suspend.c:547
Inline: True
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
In kernel/power/suspend.c (ffffffff8110b16e)
Location: kernel/power/suspend.c:547
Inline: True
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
