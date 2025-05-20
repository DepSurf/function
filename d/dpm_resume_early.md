# Function: <code>dpm_resume_early</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8155a120)
Location: drivers/base/power/main.c:667
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_resume_start
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff8155a120-ffffffff8155a3e0: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815ac100)
Location: drivers/base/power/main.c:669
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff815ac100-ffffffff815ac3d3: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815daea0)
Location: drivers/base/power/main.c:727
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff815daea0-ffffffff815db176: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815efa40)
Location: drivers/base/power/main.c:735
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff815efa40-ffffffff815efd19: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81656f20)
Location: drivers/base/power/main.c:780
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81656f20-ffffffff81657201: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81692ad0)
Location: drivers/base/power/main.c:868
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81692ad0-ffffffff81692dae: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b3140)
Location: drivers/base/power/main.c:869
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff816b3140-ffffffff816b341e: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816ecf30)
Location: drivers/base/power/main.c:871
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff816ecf30-ffffffff816ed1d6: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81710f60)
Location: drivers/base/power/main.c:898
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81710f60-ffffffff81711206: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817ccb60)
Location: drivers/base/power/main.c:837
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff817ccb60-ffffffff817cce0e: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817e1590)
Location: drivers/base/power/main.c:836
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff817e1590-ffffffff817e181a: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817c59a0)
Location: drivers/base/power/main.c:837
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff817c59a0-ffffffff817c5c2a: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:836
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81d03cc1-ffffffff81d03d26: dpm_resume_early.cold (STB_LOCAL)
ffffffff8184fd20-ffffffff8184ff9e: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:833
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81ecc543-ffffffff81ecc5a3: dpm_resume_early.cold (STB_LOCAL)
ffffffff81995620-ffffffff819958c1: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b06180)
Location: drivers/base/power/main.c:833
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81b06180-ffffffff81b0643f: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b541c0)
Location: drivers/base/power/main.c:833
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81b541c0-ffffffff81b5447f: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81bac910)
Location: drivers/base/power/main.c:839
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81bac910-ffffffff81bacaf3: dpm_resume_early (STB_GLOBAL)
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
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff8000109017d8)
Location: drivers/base/power/main.c:898
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffff8000109017d8-ffff800010901af4: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09eba08)
Location: drivers/base/power/main.c:898
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
c09eba08-c09ebd24: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099f600)
Location: drivers/base/power/main.c:898
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
c00000000099f600-c00000000099f9f4: dpm_resume_early (STB_GLOBAL)
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
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d72e0)
Location: drivers/base/power/main.c:898
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff816d72e0-ffffffff816d7586: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b1940)
Location: drivers/base/power/main.c:898
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff816b1940-ffffffff816b1be6: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81704c20)
Location: drivers/base/power/main.c:898
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff81704c20-ffffffff81704ec6: dpm_resume_early (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dpm_resume_early(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171f4d0)
Location: drivers/base/power/main.c:898
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_end
  - drivers/base/power/main.c:dpm_suspend_late
  - drivers/base/power/main.c:dpm_resume_start
```
**Symbols:**

```
ffffffff8171f4d0-ffffffff8171f7a2: dpm_resume_early (STB_GLOBAL)
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
