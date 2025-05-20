# Function: <code>i8042_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81664a60)
Location: drivers/input/serio/i8042.c:235
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff81664a60-ffffffff81664b11: i8042_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816c4c70)
Location: drivers/input/serio/i8042.c:235
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff816c4c70-ffffffff816c4d21: i8042_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816f2c90)
Location: drivers/input/serio/i8042.c:265
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff816f2c90-ffffffff816f2d41: i8042_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff817085c0)
Location: drivers/input/serio/i8042.c:265
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff817085c0-ffffffff81708671: i8042_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff817797b0)
Location: drivers/input/serio/i8042.c:265
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff817797b0-ffffffff81779861: i8042_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:265
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff817ba4b0-ffffffff817ba53d: i8042_flush (STB_LOCAL)
ffffffff817bb60c-ffffffff817bb637: i8042_flush.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:265
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff817e18d0-ffffffff817e195d: i8042_flush (STB_LOCAL)
ffffffff817e2a7c-ffffffff817e2aa7: i8042_flush.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:261
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff818221d0-ffffffff81822260: i8042_flush (STB_LOCAL)
ffffffff818233fa-ffffffff8182342a: i8042_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:261
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff81853640-ffffffff818536d0: i8042_flush (STB_LOCAL)
ffffffff818548ba-ffffffff818548ea: i8042_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:263
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff81925840-ffffffff819258d0: i8042_flush (STB_LOCAL)
ffffffff81926c03-ffffffff81926c33: i8042_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:283
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff8192d3a0-ffffffff8192d430: i8042_flush (STB_LOCAL)
ffffffff81c22acd-ffffffff81c22afd: i8042_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:283
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff81910800-ffffffff81910890: i8042_flush (STB_LOCAL)
ffffffff81c14d4f-ffffffff81c14d7f: i8042_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:287
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff819b1710-ffffffff819b17ba: i8042_flush (STB_LOCAL)
ffffffff81d223d0-ffffffff81d2241b: i8042_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:287
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff81b10320-ffffffff81b103c8: i8042_flush (STB_LOCAL)
ffffffff81eedf9d-ffffffff81eedfef: i8042_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:287
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff81ca09d0-ffffffff81ca0aae: i8042_flush (STB_LOCAL)
ffffffff820a5f56-ffffffff820a5f71: i8042_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:287
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff81d07d20-ffffffff81d07dfe: i8042_flush (STB_LOCAL)
ffffffff8212735f-ffffffff8212737a: i8042_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:287
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff81dbd950-ffffffff81dbda2e: i8042_flush (STB_LOCAL)
ffffffff82208ce0-ffffffff82208cfb: i8042_flush.cold (STB_LOCAL)
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
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (c000000000b70470)
Location: drivers/input/serio/i8042.c:261
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
c000000000b70470-c000000000b706dc: i8042_flush (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:261
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff81808720-ffffffff818087b0: i8042_flush (STB_LOCAL)
ffffffff818098ca-ffffffff818098fa: i8042_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:261
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff817cfe00-ffffffff817cfe90: i8042_flush (STB_LOCAL)
ffffffff817d106a-ffffffff817d109a: i8042_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:261
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff818477d0-ffffffff81847860: i8042_flush (STB_LOCAL)
ffffffff81848a4a-ffffffff81848a7a: i8042_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int i8042_flush();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:261
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
  - drivers/input/serio/i8042.c:i8042_set_mux_mode
```
**Symbols:**

```
ffffffff81862a10-ffffffff81862aa0: i8042_flush (STB_LOCAL)
ffffffff81863c6a-ffffffff81863c9a: i8042_flush.cold (STB_LOCAL)
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
