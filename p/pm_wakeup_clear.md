# Function: <code>pm_wakeup_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pm_wakeup_clear();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155c710)
Location: drivers/base/power/wakeup.c:871
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff8155c710-ffffffff8155c72c: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pm_wakeup_clear();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815ae9d0)
Location: drivers/base/power/wakeup.c:869
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff815ae9d0-ffffffff815ae9ec: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pm_wakeup_clear();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dd7d0)
Location: drivers/base/power/wakeup.c:869
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff815dd7d0-ffffffff815dd7ec: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f2430)
Location: drivers/base/power/wakeup.c:875
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff815f2430-ffffffff815f2454: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816599d0)
Location: drivers/base/power/wakeup.c:876
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff816599d0-ffffffff816599f4: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81695610)
Location: drivers/base/power/wakeup.c:875
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff81695610-ffffffff81695634: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b5c80)
Location: drivers/base/power/wakeup.c:881
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff816b5c80-ffffffff816b5ca4: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816efab0)
Location: drivers/base/power/wakeup.c:865
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff816efab0-ffffffff816efad4: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81713ae0)
Location: drivers/base/power/wakeup.c:885
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff81713ae0-ffffffff81713b04: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817cf5b0)
Location: drivers/base/power/wakeup.c:944
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff817cf5b0-ffffffff817cf5d4: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e3bb0)
Location: drivers/base/power/wakeup.c:944
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff817e3bb0-ffffffff817e3bd4: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c7ff0)
Location: drivers/base/power/wakeup.c:945
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:s2idle_loop
```
**Symbols:**

```
ffffffff817c7ff0-ffffffff817c8014: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pm_wakeup_clear(unsigned int irq_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81852420)
Location: drivers/base/power/wakeup.c:946
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81852420-ffffffff81852484: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pm_wakeup_clear(unsigned int irq_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81998290)
Location: drivers/base/power/wakeup.c:947
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81998290-ffffffff81998338: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pm_wakeup_clear(unsigned int irq_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b092f0)
Location: drivers/base/power/wakeup.c:917
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81b092f0-ffffffff81b09398: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pm_wakeup_clear(unsigned int irq_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b57310)
Location: drivers/base/power/wakeup.c:912
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81b57310-ffffffff81b573b8: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pm_wakeup_clear(unsigned int irq_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81baf900)
Location: drivers/base/power/wakeup.c:912
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81baf900-ffffffff81baf9a8: pm_wakeup_clear (STB_GLOBAL)
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
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffff8000109050d0)
Location: drivers/base/power/wakeup.c:885
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:s2idle_loop
```
**Symbols:**

```
ffff8000109050d0-ffff800010905108: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c09eeef0)
Location: drivers/base/power/wakeup.c:885
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
c09eeef0-c09eef20: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a3b80)
Location: drivers/base/power/wakeup.c:885
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
c0000000009a3b80-c0000000009a3bb0: pm_wakeup_clear (STB_GLOBAL)
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
In kernel/power/process.c (0)
Location: include/linux/suspend.h:528
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d9e10)
Location: drivers/base/power/wakeup.c:885
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff816d9e10-ffffffff816d9e34: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b4490)
Location: drivers/base/power/wakeup.c:885
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff816b4490-ffffffff816b44b4: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817077a0)
Location: drivers/base/power/wakeup.c:885
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff817077a0-ffffffff817077c4: pm_wakeup_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pm_wakeup_clear(bool reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817221d0)
Location: drivers/base/power/wakeup.c:885
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff817221d0-ffffffff817221f4: pm_wakeup_clear (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool reset</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int irq_number</code>
</li>
<li>
<b>Param removed. </b>
<code>bool reset</code>
</li>
</ul>
</details>
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
