# Function: <code>cm_notify_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/charger-manager.c (ffffffff81682820)
Location: drivers/power/charger-manager.c:2049
Inline: False
```
**Symbols:**

```
ffffffff81682820-ffffffff81682a87: cm_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/charger-manager.c (ffffffff816e2510)
Location: drivers/power/charger-manager.c:2028
Inline: False
```
**Symbols:**

```
ffffffff816e2510-ffffffff816e275c: cm_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81712980)
Location: drivers/power/supply/charger-manager.c:2028
Inline: False
```
**Symbols:**

```
ffffffff81712980-ffffffff81712bcc: cm_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8172be70)
Location: drivers/power/supply/charger-manager.c:2021
Inline: True
```
**Symbols:**

```
ffffffff8172be70-ffffffff8172c0bc: cm_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8179d610)
Location: drivers/power/supply/charger-manager.c:2022
Inline: True
```
**Symbols:**

```
ffffffff8179d610-ffffffff8179d865: cm_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff817e4a30)
Location: drivers/power/supply/charger-manager.c:2028
Inline: True
```
**Symbols:**

```
ffffffff817e4a30-ffffffff817e4c86: cm_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81810130)
Location: drivers/power/supply/charger-manager.c:2011
Inline: True
```
**Symbols:**

```
ffffffff81810130-ffffffff81810397: cm_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81850b23)
Location: drivers/power/supply/charger-manager.c:2012
Inline: True
```
**Symbols:**

```
ffffffff81851e09-ffffffff81851e6e: cm_notify_event.cold (STB_LOCAL)
ffffffff81850b00-ffffffff81850d40: cm_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81883573)
Location: drivers/power/supply/charger-manager.c:2012
Inline: True
```
**Symbols:**

```
ffffffff81883f5d-ffffffff81883fca: cm_notify_event.cold (STB_LOCAL)
ffffffff81883550-ffffffff8188378d: cm_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81950ea3)
Location: drivers/power/supply/charger-manager.c:2016
Inline: True
```
**Symbols:**

```
ffffffff8195267f-ffffffff819526c1: cm_notify_event.cold (STB_LOCAL)
ffffffff81950e80-ffffffff81951037: cm_notify_event (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffff800010acfb48)
Location: drivers/power/supply/charger-manager.c:2012
Inline: True
```
**Symbols:**

```
ffff800010acfb48-ffff800010acfe14: cm_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (c0baf60c)
Location: drivers/power/supply/charger-manager.c:2012
Inline: True
```
**Symbols:**

```
c0baf60c-c0baf89c: cm_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (c000000000bb3680)
Location: drivers/power/supply/charger-manager.c:2012
Inline: True
```
**Symbols:**

```
c000000000bb3680-c000000000bb3a5c: cm_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffe0006cc51c)
Location: drivers/power/supply/charger-manager.c:2012
Inline: True
```
**Symbols:**

```
ffffffe0006cc51c-ffffffe0006cc77c: cm_notify_event (STB_GLOBAL)
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
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81878a23)
Location: drivers/power/supply/charger-manager.c:2012
Inline: True
```
**Symbols:**

```
ffffffff8187940d-ffffffff8187947a: cm_notify_event.cold (STB_LOCAL)
ffffffff81878a00-ffffffff81878c3d: cm_notify_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cm_notify_event(struct power_supply *psy, enum cm_event_types type, char *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff818943c3)
Location: drivers/power/supply/charger-manager.c:2012
Inline: True
```
**Symbols:**

```
ffffffff81894dad-ffffffff81894e1a: cm_notify_event.cold (STB_LOCAL)
ffffffff818943a0-ffffffff818945dd: cm_notify_event (STB_GLOBAL)
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
