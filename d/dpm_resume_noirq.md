# Function: <code>dpm_resume_noirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81559e50)
Location: drivers/base/power/main.c:544
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_resume_start
  - drivers/base/power/main.c:dpm_suspend_noirq
```
**Symbols:**

```
ffffffff81559e50-ffffffff8155a11f: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815abe10)
Location: drivers/base/power/main.c:546
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff815abe10-ffffffff815ac0f2: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815dabb0)
Location: drivers/base/power/main.c:604
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff815dabb0-ffffffff815dae95: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815ef750)
Location: drivers/base/power/main.c:612
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff815ef750-ffffffff815efa38: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81656f00)
Location: drivers/base/power/main.c:703
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81656f00-ffffffff81656f1f: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81692ab0)
Location: drivers/base/power/main.c:774
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81692ab0-ffffffff81692acf: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b3120)
Location: drivers/base/power/main.c:775
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff816b3120-ffffffff816b313f: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816ecf10)
Location: drivers/base/power/main.c:777
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff816ecf10-ffffffff816ecf2f: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81710cb0)
Location: drivers/base/power/main.c:799
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81710cb0-ffffffff81710f60: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817cd88d)
Location: drivers/base/power/main.c:747
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff817ccb40-ffffffff817ccb5f: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817e220d)
Location: drivers/base/power/main.c:746
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff817e1570-ffffffff817e158f: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817c65fc)
Location: drivers/base/power/main.c:747
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff817c5980-ffffffff817c599f: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8185098c)
Location: drivers/base/power/main.c:746
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff8184fd00-ffffffff8184fd1f: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff819963bd)
Location: drivers/base/power/main.c:745
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff81995600-ffffffff81995620: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b0702d)
Location: drivers/base/power/main.c:745
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff81b06150-ffffffff81b06170: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b5507d)
Location: drivers/base/power/main.c:745
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff81b54190-ffffffff81b541b0: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81bad63d)
Location: drivers/base/power/main.c:749
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff81bac8e0-ffffffff81bac900: dpm_resume_noirq (STB_GLOBAL)
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
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff8000109014e0)
Location: drivers/base/power/main.c:799
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffff8000109014e0-ffff8000109017d8: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09eb6ec)
Location: drivers/base/power/main.c:799
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
c09eb6ec-c09eba08: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099f210)
Location: drivers/base/power/main.c:799
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
c00000000099f210-c00000000099f600: dpm_resume_noirq (STB_GLOBAL)
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
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d7030)
Location: drivers/base/power/main.c:799
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff816d7030-ffffffff816d72e0: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b1690)
Location: drivers/base/power/main.c:799
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff816b1690-ffffffff816b1940: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81704970)
Location: drivers/base/power/main.c:799
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81704970-ffffffff81704c20: dpm_resume_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dpm_resume_noirq(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171f1e0)
Location: drivers/base/power/main.c:799
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff8171f1e0-ffffffff8171f4c2: dpm_resume_noirq (STB_GLOBAL)
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
