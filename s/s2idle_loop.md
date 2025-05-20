# Function: <code>s2idle_loop</code>

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
In kernel/power/suspend.c (ffffffff810d8c0e)
Location: kernel/power/suspend.c:105
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
Location: kernel/power/suspend.c:109
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
In kernel/power/suspend.c (ffffffff810e948f)
Location: kernel/power/suspend.c:110
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
In kernel/power/suspend.c (ffffffff810f4aaf)
Location: kernel/power/suspend.c:116
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (ffffffff810fcd88)
Location: kernel/power/suspend.c:120
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
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
In kernel/power/suspend.c (ffffffff81109223)
Location: kernel/power/suspend.c:120
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
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
In kernel/power/suspend.c (ffffffff81113fea)
Location: kernel/power/suspend.c:120
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
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
In kernel/power/suspend.c (ffffffff81110c84)
Location: kernel/power/suspend.c:120
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void s2idle_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff81111270)
Location: kernel/power/suspend.c:120
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff81111270-ffffffff8111146a: s2idle_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void s2idle_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff81130cd0)
Location: kernel/power/suspend.c:120
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff81130cd0-ffffffff81130ec3: s2idle_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void s2idle_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:118
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff811524c0-ffffffff81152728: s2idle_loop (STB_LOCAL)
ffffffff81e59ae3-ffffffff81e59b2d: s2idle_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void s2idle_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/suspend.c (0)
Location: kernel/power/suspend.c:120
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff81181730-ffffffff811819d4: s2idle_loop (STB_LOCAL)
ffffffff820583b5-ffffffff820583dd: s2idle_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void s2idle_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff81192720)
Location: kernel/power/suspend.c:120
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff81192720-ffffffff811929a7: s2idle_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void s2idle_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffffffff811a1110)
Location: kernel/power/suspend.c:120
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff811a1110-ffffffff811a1397: s2idle_loop (STB_LOCAL)
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
void s2idle_loop();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/suspend.c (ffff8000101705a8)
Location: kernel/power/suspend.c:120
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffff8000101705a8-ffff8000101708c4: s2idle_loop (STB_LOCAL)
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
In kernel/power/suspend.c (c03bb608)
Location: kernel/power/suspend.c:120
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
In kernel/power/suspend.c (c0000000001c8f1c)
Location: kernel/power/suspend.c:120
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
In kernel/power/suspend.c (ffffffff810f292b)
Location: kernel/power/suspend.c:120
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
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
In kernel/power/suspend.c (ffffffff810ff6f3)
Location: kernel/power/suspend.c:120
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
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
In kernel/power/suspend.c (ffffffff8110aa03)
Location: kernel/power/suspend.c:120
Inline: True
Inline callers:
  - kernel/power/suspend.c:suspend_enter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
