# Function: <code>mce_log</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mce_log(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044ff0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_inject_log
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log_therm_throt_event
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
```
**Symbols:**

```
ffffffff81044ff0-ffffffff81045174: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mce_log(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045060)
Location: arch/x86/kernel/cpu/mcheck/mce.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log_therm_throt_event
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_inject_log
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
```
**Symbols:**

```
ffffffff81045060-ffffffff810451fc: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mce_log(struct mce *mce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046c30)
Location: arch/x86/kernel/cpu/mcheck/mce.c:159
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_log_therm_throt_event
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_inject_log
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
```
**Symbols:**

```
ffffffff81046c30-ffffffff81046df4: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046720)
Location: arch/x86/kernel/cpu/mcheck/mce.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_inject_log
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
```
**Symbols:**

```
ffffffff81046720-ffffffff81046742: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104a150)
Location: arch/x86/kernel/cpu/mcheck/mce.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_inject_log
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
```
**Symbols:**

```
ffffffff8104a150-ffffffff8104a172: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c800)
Location: arch/x86/kernel/cpu/mcheck/mce.c:139
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_inject_log
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:__log_error
```
**Symbols:**

```
ffffffff8104c800-ffffffff8104c822: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049ef0)
Location: arch/x86/kernel/cpu/mce/core.c:137
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_inject_log
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
**Symbols:**

```
ffffffff81049ef0-ffffffff81049f12: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d040)
Location: arch/x86/kernel/cpu/mce/core.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_inject_log
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
**Symbols:**

```
ffffffff8104d040-ffffffff8104d062: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d9e0)
Location: arch/x86/kernel/cpu/mce/core.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_inject_log
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
**Symbols:**

```
ffffffff8104d9e0-ffffffff8104da02: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810528cc)
Location: arch/x86/kernel/cpu/mce/core.c:156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
**Symbols:**

```
ffffffff81051290-ffffffff810512b2: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051b70)
Location: arch/x86/kernel/cpu/mce/core.c:156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
```
**Symbols:**

```
ffffffff81050560-ffffffff81050582: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81053340)
Location: arch/x86/kernel/cpu/mce/core.c:156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
```
**Symbols:**

```
ffffffff81052080-ffffffff810520a2: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b940)
Location: arch/x86/kernel/cpu/mce/core.c:156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
```
**Symbols:**

```
ffffffff8105a510-ffffffff8105a532: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f16713)
Location: arch/x86/kernel/cpu/mce/core.c:142
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
  - arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error
```
**Symbols:**

```
ffffffff81067830-ffffffff81067862: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bdcd3)
Location: arch/x86/kernel/cpu/mce/core.c:142
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
  - arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error
```
**Symbols:**

```
ffffffff81076cc0-ffffffff81076cf2: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213f750)
Location: arch/x86/kernel/cpu/mce/core.c:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
  - arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error
```
**Symbols:**

```
ffffffff81078f40-ffffffff81078f72: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82221770)
Location: arch/x86/kernel/cpu/mce/core.c:138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
  - arch/x86/kernel/cpu/mce/apei.c:apei_mce_report_mem_error
```
**Symbols:**

```
ffffffff810804f0-ffffffff81080522: mce_log (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104db40)
Location: arch/x86/kernel/cpu/mce/core.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_inject_log
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
**Symbols:**

```
ffffffff8104db40-ffffffff8104db62: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103cff0)
Location: arch/x86/kernel/cpu/mce/core.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_inject_log
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
**Symbols:**

```
ffffffff8103cff0-ffffffff8103d012: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d990)
Location: arch/x86/kernel/cpu/mce/core.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_inject_log
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
**Symbols:**

```
ffffffff8104d990-ffffffff8104d9b2: mce_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mce_log(struct mce *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104edd0)
Location: arch/x86/kernel/cpu/mce/core.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_inject_log
  - arch/x86/kernel/cpu/mce/amd.c:__log_error
```
**Symbols:**

```
ffffffff8104edd0-ffffffff8104edf2: mce_log (STB_GLOBAL)
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
<code>struct mce *m</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mce *mce</code>
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
