# Function: <code>fullbatt_vchk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/charger-manager.c (ffffffff81681360)
Location: drivers/power/charger-manager.c:515
Inline: False
Direct callers:
  - drivers/power/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81681360-ffffffff81681455: fullbatt_vchk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/charger-manager.c (ffffffff816e2150)
Location: drivers/power/charger-manager.c:515
Inline: False
Direct callers:
  - drivers/power/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff816e2150-ffffffff816e2242: fullbatt_vchk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff817125c0)
Location: drivers/power/supply/charger-manager.c:515
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff817125c0-ffffffff817126b2: fullbatt_vchk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8172a990)
Location: drivers/power/supply/charger-manager.c:515
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff8172a990-ffffffff8172aa82: fullbatt_vchk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8179c130)
Location: drivers/power/supply/charger-manager.c:515
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff8179c130-ffffffff8179c222: fullbatt_vchk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff817e3680)
Location: drivers/power/supply/charger-manager.c:515
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff817e3680-ffffffff817e3772: fullbatt_vchk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8180ef00)
Location: drivers/power/supply/charger-manager.c:515
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff8180ef00-ffffffff8180eff2: fullbatt_vchk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:513
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81850f10-ffffffff81850f90: fullbatt_vchk (STB_LOCAL)
ffffffff81851ea8-ffffffff81851f25: fullbatt_vchk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:513
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81882900-ffffffff81882980: fullbatt_vchk (STB_LOCAL)
ffffffff81883895-ffffffff81883912: fullbatt_vchk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:513
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
```
**Symbols:**

```
ffffffff81951230-ffffffff819512fc: fullbatt_vchk (STB_LOCAL)
ffffffff819526d6-ffffffff81952734: fullbatt_vchk.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffff800010acf228)
Location: drivers/power/supply/charger-manager.c:513
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffff800010acf228-ffff800010acf33c: fullbatt_vchk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (c0bafb1c)
Location: drivers/power/supply/charger-manager.c:513
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
c0bafb1c-c0bafc40: fullbatt_vchk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (c000000000bb2990)
Location: drivers/power/supply/charger-manager.c:513
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
c000000000bb2990-c000000000bb2b10: fullbatt_vchk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffe0006cbcd2)
Location: drivers/power/supply/charger-manager.c:513
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffe0006cbcd2-ffffffe0006cbda6: fullbatt_vchk (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:513
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81877db0-ffffffff81877e30: fullbatt_vchk (STB_LOCAL)
ffffffff81878d45-ffffffff81878dc2: fullbatt_vchk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void fullbatt_vchk(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:513
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81893750-ffffffff818937d0: fullbatt_vchk (STB_LOCAL)
ffffffff818946e5-ffffffff81894762: fullbatt_vchk.cold (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
