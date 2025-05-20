# Function: <code>i8042_controller_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int i8042_controller_resume(bool force_reset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81665790)
Location: drivers/input/serio/i8042.c:1113
Inline: True
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff81665790-ffffffff816658de: i8042_controller_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int i8042_controller_resume(bool force_reset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816c5a00)
Location: drivers/input/serio/i8042.c:1113
Inline: True
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff816c5a00-ffffffff816c5b4f: i8042_controller_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816f3a20)
Location: drivers/input/serio/i8042.c:1145
Inline: True
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff816f3a20-ffffffff816f3b6a: i8042_controller_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81709570)
Location: drivers/input/serio/i8042.c:1153
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff81709570-ffffffff817096bd: i8042_controller_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8177a720)
Location: drivers/input/serio/i8042.c:1153
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff8177a720-ffffffff8177a86d: i8042_controller_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1153
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff817bb010-ffffffff817bb100: i8042_controller_resume (STB_LOCAL)
ffffffff817bb9c5-ffffffff817bba31: i8042_controller_resume.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1156
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff817e2480-ffffffff817e2570: i8042_controller_resume (STB_LOCAL)
ffffffff817e2e20-ffffffff817e2e8c: i8042_controller_resume.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1149
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff81822e10-ffffffff81822f08: i8042_controller_resume (STB_LOCAL)
ffffffff81823800-ffffffff8182386e: i8042_controller_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1166
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff818542b0-ffffffff818543a8: i8042_controller_resume (STB_LOCAL)
ffffffff81854cbc-ffffffff81854d2a: i8042_controller_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81926bb5)
Location: drivers/input/serio/i8042.c:1168
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff819269a0-ffffffff81926aec: i8042_controller_resume.part.0 (STB_LOCAL)
ffffffff8192718a-ffffffff81927212: i8042_controller_resume.part.0.cold (STB_LOCAL)
ffffffff81926af0-ffffffff81926b33: i8042_controller_resume (STB_LOCAL)
ffffffff81927212-ffffffff81927228: i8042_controller_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8192e725)
Location: drivers/input/serio/i8042.c:1191
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff8192e510-ffffffff8192e65c: i8042_controller_resume.part.0 (STB_LOCAL)
ffffffff81c230a3-ffffffff81c2312b: i8042_controller_resume.part.0.cold (STB_LOCAL)
ffffffff8192e660-ffffffff8192e6a3: i8042_controller_resume (STB_LOCAL)
ffffffff81c2312b-ffffffff81c23141: i8042_controller_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8191194d)
Location: drivers/input/serio/i8042.c:1191
Inline: True
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff81911900-ffffffff81911a43: i8042_controller_resume (STB_LOCAL)
ffffffff81c151cc-ffffffff81c1524d: i8042_controller_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff819b3355)
Location: drivers/input/serio/i8042.c:1195
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff819b30e0-ffffffff819b3256: i8042_controller_resume.part.0 (STB_LOCAL)
ffffffff81d22ceb-ffffffff81d22db6: i8042_controller_resume.part.0.cold (STB_LOCAL)
ffffffff819b3260-ffffffff819b32a3: i8042_controller_resume (STB_LOCAL)
ffffffff81d22db6-ffffffff81d22dcc: i8042_controller_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81b12495)
Location: drivers/input/serio/i8042.c:1195
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff81b120e0-ffffffff81b1238d: i8042_controller_resume.part.0 (STB_LOCAL)
ffffffff81eee9c5-ffffffff81eeeaf2: i8042_controller_resume.part.0.cold (STB_LOCAL)
ffffffff81b12390-ffffffff81b123d9: i8042_controller_resume (STB_LOCAL)
ffffffff81eeeaf2-ffffffff81eeeb08: i8042_controller_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81ca2f55)
Location: drivers/input/serio/i8042.c:1195
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff81ca2b40-ffffffff81ca2e06: i8042_controller_resume.part.0 (STB_LOCAL)
ffffffff820a6432-ffffffff820a64c5: i8042_controller_resume.part.0.cold (STB_LOCAL)
ffffffff81ca2e20-ffffffff81ca2e78: i8042_controller_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81d0a615)
Location: drivers/input/serio/i8042.c:1195
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff81d0a200-ffffffff81d0a4c6: i8042_controller_resume.part.0 (STB_LOCAL)
ffffffff82127839-ffffffff821278cc: i8042_controller_resume.part.0.cold (STB_LOCAL)
ffffffff81d0a4e0-ffffffff81d0a538: i8042_controller_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81dc02a5)
Location: drivers/input/serio/i8042.c:1195
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff81dbfe90-ffffffff81dc0156: i8042_controller_resume.part.0 (STB_LOCAL)
ffffffff822091ba-ffffffff8220924d: i8042_controller_resume.part.0.cold (STB_LOCAL)
ffffffff81dc0170-ffffffff81dc01c8: i8042_controller_resume (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (c000000000b720b0)
Location: drivers/input/serio/i8042.c:1166
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
c000000000b720b0-c000000000b72284: i8042_controller_resume (STB_LOCAL)
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
In drivers/input/serio/i8042.c (ffffffff81809275)
Location: drivers/input/serio/i8042.c:1166
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1166
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff817d0a70-ffffffff817d0b68: i8042_controller_resume (STB_LOCAL)
ffffffff817d146c-ffffffff817d14da: i8042_controller_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1166
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff81848440-ffffffff81848538: i8042_controller_resume (STB_LOCAL)
ffffffff81848e4c-ffffffff81848eba: i8042_controller_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int i8042_controller_resume(bool s2r_wants_reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1166
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_resume
```
**Symbols:**

```
ffffffff818636c0-ffffffff818637b8: i8042_controller_resume (STB_LOCAL)
ffffffff8186406c-ffffffff818640da: i8042_controller_resume.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool s2r_wants_reset</code>
</li>
<li>
<b>Param removed. </b>
<code>bool force_reset</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
