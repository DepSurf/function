# Function: <code>uevent_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/charger-manager.c (ffffffff81681250)
Location: drivers/power/charger-manager.c:463
Inline: True
Direct callers:
  - drivers/power/charger-manager.c:fullbatt_vchk
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_notify_event
```
**Symbols:**

```
ffffffff81681250-ffffffff81681353: uevent_notify.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/charger-manager.c (ffffffff816e2040)
Location: drivers/power/charger-manager.c:463
Inline: True
Direct callers:
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
ffffffff816e2040-ffffffff816e2143: uevent_notify.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff817124b0)
Location: drivers/power/supply/charger-manager.c:463
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
ffffffff817124b0-ffffffff817125b3: uevent_notify.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8172a880)
Location: drivers/power/supply/charger-manager.c:463
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
ffffffff8172a880-ffffffff8172a983: uevent_notify.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8179c020)
Location: drivers/power/supply/charger-manager.c:463
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
ffffffff8179c020-ffffffff8179c123: uevent_notify.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff817e3570)
Location: drivers/power/supply/charger-manager.c:463
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
ffffffff817e3570-ffffffff817e3672: uevent_notify.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8180edf0)
Location: drivers/power/supply/charger-manager.c:463
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
ffffffff8180edf0-ffffffff8180eef2: uevent_notify.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81850a00)
Location: drivers/power/supply/charger-manager.c:461
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
ffffffff81850a00-ffffffff81850af5: uevent_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81882800)
Location: drivers/power/supply/charger-manager.c:461
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
ffffffff81882800-ffffffff818828f5: uevent_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uevent_notify(struct charger_manager *cm, const char *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81950560)
Location: drivers/power/supply/charger-manager.c:461
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:fullbatt_handler
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:_cm_monitor
  - drivers/power/supply/charger-manager.c:check_charging_duration
  - drivers/power/supply/charger-manager.c:check_charging_duration
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
ffffffff81950560-ffffffff8195065a: uevent_notify (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffff800010acf110)
Location: drivers/power/supply/charger-manager.c:461
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
ffff800010acf110-ffff800010acf228: uevent_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void uevent_notify(struct charger_manager *cm, const char *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (c0baf50c)
Location: drivers/power/supply/charger-manager.c:461
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
c0baf50c-c0baf60c: uevent_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (c000000000bb25b0)
Location: drivers/power/supply/charger-manager.c:461
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
c000000000bb25b0-c000000000bb2984: uevent_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffe0006cbbac)
Location: drivers/power/supply/charger-manager.c:461
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
ffffffe0006cbbac-ffffffe0006cbcd2: uevent_notify.isra.0 (STB_LOCAL)
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

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81877cb0)
Location: drivers/power/supply/charger-manager.c:461
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
ffffffff81877cb0-ffffffff81877da5: uevent_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81893650)
Location: drivers/power/supply/charger-manager.c:461
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:fullbatt_vchk
```
**Symbols:**

```
ffffffff81893650-ffffffff81893745: uevent_notify.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
