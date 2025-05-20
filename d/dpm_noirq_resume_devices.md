# Function: <code>dpm_noirq_resume_devices</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81656bf0)
Location: drivers/base/power/main.c:640
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff81656bf0-ffffffff81656ed1: dpm_noirq_resume_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816927b0)
Location: drivers/base/power/main.c:711
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff816927b0-ffffffff81692a8e: dpm_noirq_resume_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b2e20)
Location: drivers/base/power/main.c:712
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff816b2e20-ffffffff816b30fe: dpm_noirq_resume_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816ecc40)
Location: drivers/base/power/main.c:719
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff816ecc40-ffffffff816ecee6: dpm_noirq_resume_devices (STB_GLOBAL)
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
In drivers/base/power/main.c (ffffffff81710cb5)
Location: drivers/base/power/main.c:748
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_resume_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817cc580)
Location: drivers/base/power/main.c:696
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff817cc580-ffffffff817cc82e: dpm_noirq_resume_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817e0fd0)
Location: drivers/base/power/main.c:695
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff817e0fd0-ffffffff817e125a: dpm_noirq_resume_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817c4c60)
Location: drivers/base/power/main.c:696
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff817c4c60-ffffffff817c4eea: dpm_noirq_resume_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:693
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff8184f040-ffffffff8184f2be: dpm_noirq_resume_devices (STB_LOCAL)
ffffffff81d03ba6-ffffffff81d03c0b: dpm_noirq_resume_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:692
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81994ff0-ffffffff81995291: dpm_noirq_resume_devices (STB_LOCAL)
ffffffff81ecc4e3-ffffffff81ecc543: dpm_noirq_resume_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b057b0)
Location: drivers/base/power/main.c:692
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81b057b0-ffffffff81b05a6f: dpm_noirq_resume_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b537c0)
Location: drivers/base/power/main.c:692
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81b537c0-ffffffff81b53a7f: dpm_noirq_resume_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dpm_noirq_resume_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81babfe0)
Location: drivers/base/power/main.c:704
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81babfe0-ffffffff81bac1c3: dpm_noirq_resume_devices (STB_LOCAL)
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
In drivers/base/power/main.c (ffff800010901504)
Location: drivers/base/power/main.c:748
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_resume_noirq
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
In drivers/base/power/main.c (c09eb704)
Location: drivers/base/power/main.c:748
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_resume_noirq
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
In drivers/base/power/main.c (c00000000099f25c)
Location: drivers/base/power/main.c:748
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_resume_noirq
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d7035)
Location: drivers/base/power/main.c:748
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_resume_noirq
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
In drivers/base/power/main.c (ffffffff816b1695)
Location: drivers/base/power/main.c:748
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_resume_noirq
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
In drivers/base/power/main.c (ffffffff81704975)
Location: drivers/base/power/main.c:748
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_resume_noirq
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
In drivers/base/power/main.c (ffffffff8171f1e5)
Location: drivers/base/power/main.c:748
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_resume_noirq
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
