# Function: <code>suspend_enter</code>

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
In kernel/power/suspend.c (ffffffff810ce39b)
Location: kernel/power/suspend.c:313
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (ffffffff810d2efa)
Location: kernel/power/suspend.c:315
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (ffffffff810d9a8b)
Location: kernel/power/suspend.c:338
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (ffffffff810d8a5e)
Location: kernel/power/suspend.c:363
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (ffffffff810e0b5d)
Location: kernel/power/suspend.c:390
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (ffffffff810e913e)
Location: kernel/power/suspend.c:391
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (ffffffff810f475e)
Location: kernel/power/suspend.c:397
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int suspend_enter(suspend_state_t state, bool *wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:401
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff810fcba0-ffffffff810fd0e1: suspend_enter (STB_LOCAL)
ffffffff810fd3e7-ffffffff810fd454: suspend_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int suspend_enter(suspend_state_t state, bool *wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:391
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff81108f90-ffffffff81109510: suspend_enter (STB_LOCAL)
ffffffff81109808-ffffffff811098a0: suspend_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int suspend_enter(suspend_state_t state, bool *wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:391
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff81113d90-ffffffff8111413a: suspend_enter (STB_LOCAL)
ffffffff81114513-ffffffff811145a9: suspend_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int suspend_enter(suspend_state_t state, bool *wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:391
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff81110a30-ffffffff81110dac: suspend_enter (STB_LOCAL)
ffffffff81bded9f-ffffffff81bdee3a: suspend_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int suspend_enter(suspend_state_t state, bool *wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:391
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff811114e0-ffffffff81111803: suspend_enter (STB_LOCAL)
ffffffff81bd0e46-ffffffff81bd0edc: suspend_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int suspend_enter(suspend_state_t state, bool *wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:389
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff81130f40-ffffffff81131278: suspend_enter (STB_LOCAL)
ffffffff81ca9b94-ffffffff81ca9c66: suspend_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int suspend_enter(suspend_state_t state, bool *wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:390
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff81152870-ffffffff81152c3e: suspend_enter (STB_LOCAL)
ffffffff81e59b2d-ffffffff81e59bfc: suspend_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int suspend_enter(suspend_state_t state, bool *wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:397
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff81181b80-ffffffff81181fb7: suspend_enter (STB_LOCAL)
ffffffff820583dd-ffffffff8205840e: suspend_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int suspend_enter(suspend_state_t state, bool *wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:397
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff81192a60-ffffffff81192e93: suspend_enter (STB_LOCAL)
ffffffff820d6cc5-ffffffff820d6cf6: suspend_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int suspend_enter(suspend_state_t state, bool *wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:397
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff811a1450-ffffffff811a1883: suspend_enter (STB_LOCAL)
ffffffff821b1f5b-ffffffff821b1f8c: suspend_enter.cold (STB_LOCAL)
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
int suspend_enter(suspend_state_t state, bool *wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffff800010170948)
Location: kernel/power/suspend.c:391
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffff800010170948-ffff800010170d38: suspend_enter (STB_LOCAL)
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
In kernel/power/suspend.c (c03bb2d0)
Location: kernel/power/suspend.c:391
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (c0000000001c8a0c)
Location: kernel/power/suspend.c:391
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (ffffffff810f2596)
Location: kernel/power/suspend.c:391
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int suspend_enter(suspend_state_t state, bool *wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:391
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff810ff460-ffffffff810ff9e0: suspend_enter (STB_LOCAL)
ffffffff810ffcd8-ffffffff810ffd70: suspend_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int suspend_enter(suspend_state_t state, bool *wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:391
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff8110a770-ffffffff8110ad43: suspend_enter (STB_LOCAL)
ffffffff8110b078-ffffffff8110b110: suspend_enter.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
