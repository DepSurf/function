# Function: <code>cm_setup_timer</code>

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
In drivers/power/charger-manager.c (ffffffff81681494)
Location: drivers/power/charger-manager.c:1062
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:cm_suspend_prepare
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
In drivers/power/charger-manager.c (ffffffff816e2284)
Location: drivers/power/charger-manager.c:1062
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:cm_suspend_prepare
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
In drivers/power/supply/charger-manager.c (ffffffff817126f4)
Location: drivers/power/supply/charger-manager.c:1062
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
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
In drivers/power/supply/charger-manager.c (ffffffff8172aac4)
Location: drivers/power/supply/charger-manager.c:1062
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
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
In drivers/power/supply/charger-manager.c (ffffffff8179c264)
Location: drivers/power/supply/charger-manager.c:1062
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
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
In drivers/power/supply/charger-manager.c (ffffffff817e37b4)
Location: drivers/power/supply/charger-manager.c:1062
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
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
In drivers/power/supply/charger-manager.c (ffffffff8180f034)
Location: drivers/power/supply/charger-manager.c:1062
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
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
In drivers/power/supply/charger-manager.c (ffffffff81850fc1)
Location: drivers/power/supply/charger-manager.c:1060
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
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
In drivers/power/supply/charger-manager.c (ffffffff818829b1)
Location: drivers/power/supply/charger-manager.c:1060
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool cm_setup_timer();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:1060
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81951300-ffffffff81951471: cm_setup_timer (STB_LOCAL)
ffffffff81952734-ffffffff819527ab: cm_setup_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool cm_setup_timer();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:860
Inline: False
```
**Symbols:**

```
ffffffff819569a0-ffffffff81956aee: cm_setup_timer (STB_LOCAL)
ffffffff81c256ff-ffffffff81c2578b: cm_setup_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool cm_setup_timer();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:860
Inline: False
```
**Symbols:**

```
ffffffff8193a5f0-ffffffff8193a742: cm_setup_timer (STB_LOCAL)
ffffffff81c17686-ffffffff81c17712: cm_setup_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool cm_setup_timer();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:860
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff819ded90-ffffffff819deee2: cm_setup_timer (STB_LOCAL)
ffffffff81d266cb-ffffffff81d26757: cm_setup_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool cm_setup_timer();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: drivers/power/supply/charger-manager.c:860
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81b42bd0-ffffffff81b42d2b: cm_setup_timer (STB_LOCAL)
ffffffff81ef23d5-ffffffff81ef2460: cm_setup_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool cm_setup_timer();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81cd94b0)
Location: drivers/power/supply/charger-manager.c:860
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81cd94b0-ffffffff81cd96c4: cm_setup_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool cm_setup_timer();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81d41720)
Location: drivers/power/supply/charger-manager.c:860
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81d41720-ffffffff81d41934: cm_setup_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool cm_setup_timer();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81df80d0)
Location: drivers/power/supply/charger-manager.c:860
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
**Symbols:**

```
ffffffff81df80d0-ffffffff81df82e4: cm_setup_timer (STB_LOCAL)
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
In drivers/power/supply/charger-manager.c (ffff800010acf394)
Location: drivers/power/supply/charger-manager.c:1060
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
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
In drivers/power/supply/charger-manager.c (c0bafc9c)
Location: drivers/power/supply/charger-manager.c:1060
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
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
In drivers/power/supply/charger-manager.c (c000000000bb2b88)
Location: drivers/power/supply/charger-manager.c:1060
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
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
In drivers/power/supply/charger-manager.c (ffffffe0006cbe04)
Location: drivers/power/supply/charger-manager.c:1060
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81877e61)
Location: drivers/power/supply/charger-manager.c:1060
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
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
In drivers/power/supply/charger-manager.c (ffffffff81893801)
Location: drivers/power/supply/charger-manager.c:1060
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
