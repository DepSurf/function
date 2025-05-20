# Function: <code>suspend_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int suspend_prepare(suspend_state_t state);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810cebda)
Location: kernel/power/suspend.c:267
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
```
In drivers/regulator/core.c (ffffffff814d8050)
Location: drivers/regulator/core.c:809
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_suspend_prepare
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff814d8050-ffffffff814d809c: suspend_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int suspend_prepare(suspend_state_t state);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810d369b)
Location: kernel/power/suspend.c:267
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
```
In drivers/regulator/core.c (ffffffff81528f90)
Location: drivers/regulator/core.c:784
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_suspend_prepare
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81528f90-ffffffff81528fe2: suspend_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int suspend_prepare(suspend_state_t state);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810da22b)
Location: kernel/power/suspend.c:290
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
```
In drivers/regulator/core.c (ffffffff81555440)
Location: drivers/regulator/core.c:785
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_suspend_prepare
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff81555440-ffffffff81555492: suspend_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int suspend_prepare(suspend_state_t state);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810d9316)
Location: kernel/power/suspend.c:315
Inline: True
Inline callers:
  - kernel/power/suspend.c:pm_suspend
```
```
In drivers/regulator/core.c (ffffffff815699d0)
Location: drivers/regulator/core.c:785
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_suspend_prepare
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff815699d0-ffffffff81569a22: suspend_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int suspend_prepare(suspend_state_t state);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff810e1450)
Location: kernel/power/suspend.c:342
Inline: True
```
```
In drivers/regulator/core.c (ffffffff815cdbb0)
Location: drivers/regulator/core.c:785
Inline: False
Direct callers:
  - drivers/regulator/core.c:_regulator_suspend_prepare
  - drivers/regulator/core.c:set_machine_constraints
```
**Symbols:**

```
ffffffff815cdbb0-ffffffff815cdc02: suspend_prepare (STB_LOCAL)
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
In kernel/power/suspend.c (ffffffff810e9abc)
Location: kernel/power/suspend.c:343
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
In kernel/power/suspend.c (ffffffff810f50dc)
Location: kernel/power/suspend.c:349
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
In kernel/power/suspend.c (ffffffff810fd5e3)
Location: kernel/power/suspend.c:353
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
In kernel/power/suspend.c (ffffffff81109a2f)
Location: kernel/power/suspend.c:343
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int suspend_prepare(suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff81114408)
Location: kernel/power/suspend.c:343
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
```
**Symbols:**

```
ffffffff81114408-ffffffff81114513: suspend_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int suspend_prepare(suspend_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff81bdecd0)
Location: kernel/power/suspend.c:345
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
```
**Symbols:**

```
ffffffff81bdecd0-ffffffff81bded9f: suspend_prepare (STB_LOCAL)
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
In kernel/power/suspend.c (ffffffff81bd1007)
Location: kernel/power/suspend.c:345
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
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
In kernel/power/suspend.c (ffffffff8113155b)
Location: kernel/power/suspend.c:343
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
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
In kernel/power/suspend.c (ffffffff81152f7a)
Location: kernel/power/suspend.c:344
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
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
In kernel/power/suspend.c (ffffffff81182369)
Location: kernel/power/suspend.c:351
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
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
In kernel/power/suspend.c (ffffffff8119323d)
Location: kernel/power/suspend.c:351
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
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
In kernel/power/suspend.c (ffffffff811a1c2d)
Location: kernel/power/suspend.c:351
Inline: True
Inline callers:
  - kernel/power/suspend.c:enter_state
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
In kernel/power/suspend.c (ffff8000101711d4)
Location: kernel/power/suspend.c:343
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
In kernel/power/suspend.c (c03bbcfc)
Location: kernel/power/suspend.c:343
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
In kernel/power/suspend.c (c0000000001c96f4)
Location: kernel/power/suspend.c:343
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
In kernel/power/suspend.c (ffffffff810f2f1c)
Location: kernel/power/suspend.c:343
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
In kernel/power/suspend.c (ffffffff810ffeff)
Location: kernel/power/suspend.c:343
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
In kernel/power/suspend.c (ffffffff8110b29f)
Location: kernel/power/suspend.c:343
Inline: True
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
