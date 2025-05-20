# Function: <code>valid_state</code>

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
In kernel/power/suspend.c (ffffffff810ce066)
Location: kernel/power/suspend.c:103
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff810d3530)
Location: kernel/power/suspend.c:103
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff810da0c0)
Location: kernel/power/suspend.c:116
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff810d919f)
Location: kernel/power/suspend.c:141
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff810e0809)
Location: kernel/power/suspend.c:168
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff810e8e49)
Location: kernel/power/suspend.c:169
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff810f4469)
Location: kernel/power/suspend.c:175
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff810fc9d9)
Location: kernel/power/suspend.c:179
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff81108dc9)
Location: kernel/power/suspend.c:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool valid_state(suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff81113ac9)
Location: kernel/power/suspend.c:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
Direct callers:
  - kernel/power/suspend.c:enter_state
```
**Symbols:**

```
ffffffff81113980-ffffffff811139b4: valid_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool valid_state(suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff81110799)
Location: kernel/power/suspend.c:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
Direct callers:
  - kernel/power/suspend.c:enter_state
```
**Symbols:**

```
ffffffff81110670-ffffffff811106a4: valid_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool valid_state(suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff811111d9)
Location: kernel/power/suspend.c:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
Direct callers:
  - kernel/power/suspend.c:enter_state
```
**Symbols:**

```
ffffffff811110b0-ffffffff811110e4: valid_state (STB_LOCAL)
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
In kernel/power/suspend.c (ffffffff81131708)
Location: kernel/power/suspend.c:160
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff81152f84)
Location: kernel/power/suspend.c:158
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff8118247a)
Location: kernel/power/suspend.c:163
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff8119334e)
Location: kernel/power/suspend.c:163
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff811a1d3e)
Location: kernel/power/suspend.c:163
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffff80001017038c)
Location: kernel/power/suspend.c:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (c03baf7c)
Location: kernel/power/suspend.c:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (c0000000001c8528)
Location: kernel/power/suspend.c:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff810f22c9)
Location: kernel/power/suspend.c:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff810ff299)
Location: kernel/power/suspend.c:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
In kernel/power/suspend.c (ffffffff8110a599)
Location: kernel/power/suspend.c:162
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_set_ops
  - kernel/power/suspend.c:suspend_set_ops
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
</ul>
