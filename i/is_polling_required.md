# Function: <code>is_polling_required</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/charger-manager.c (ffffffff81680b30)
Location: drivers/power/charger-manager.c:332
Inline: True
Direct callers:
  - drivers/power/charger-manager.c:_setup_polling
  - drivers/power/charger-manager.c:charger_extcon_notifier
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/power/charger-manager.c:cm_notify_event
```
**Symbols:**

```
ffffffff81680b30-ffffffff81680b92: is_polling_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/charger-manager.c (ffffffff816e1920)
Location: drivers/power/charger-manager.c:332
Inline: True
Direct callers:
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/power/charger-manager.c:charger_extcon_notifier
  - drivers/power/charger-manager.c:_setup_polling
```
**Symbols:**

```
ffffffff816e1920-ffffffff816e1982: is_polling_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81711d90)
Location: drivers/power/supply/charger-manager.c:332
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:_setup_polling
```
**Symbols:**

```
ffffffff81711d90-ffffffff81711df2: is_polling_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8172a160)
Location: drivers/power/supply/charger-manager.c:332
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:_setup_polling
```
**Symbols:**

```
ffffffff8172a160-ffffffff8172a1c1: is_polling_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8179b8f0)
Location: drivers/power/supply/charger-manager.c:332
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:_setup_polling
```
**Symbols:**

```
ffffffff8179b8f0-ffffffff8179b951: is_polling_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff817e2e50)
Location: drivers/power/supply/charger-manager.c:332
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:_setup_polling
```
**Symbols:**

```
ffffffff817e2e50-ffffffff817e2eaf: is_polling_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8180e6a0)
Location: drivers/power/supply/charger-manager.c:332
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:_setup_polling
```
**Symbols:**

```
ffffffff8180e6a0-ffffffff8180e6ff: is_polling_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff818502da)
Location: drivers/power/supply/charger-manager.c:330
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:_setup_polling
```
**Symbols:**

```
ffffffff818502b0-ffffffff818502ee: is_polling_required (STB_LOCAL)
ffffffff81851df2-ffffffff81851e09: is_polling_required.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff818820da)
Location: drivers/power/supply/charger-manager.c:330
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:_setup_polling
```
**Symbols:**

```
ffffffff818820b0-ffffffff818820ee: is_polling_required (STB_LOCAL)
ffffffff8188387e-ffffffff81883895: is_polling_required.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8195110e)
Location: drivers/power/supply/charger-manager.c:330
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:_setup_polling
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_setup_timer
```
**Symbols:**

```
ffffffff81950e30-ffffffff81950e7b: is_polling_required (STB_LOCAL)
ffffffff81952668-ffffffff8195267f: is_polling_required.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81956a1d)
Location: drivers/power/supply/charger-manager.c:343
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:_setup_polling
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8193a671)
Location: drivers/power/supply/charger-manager.c:343
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:_setup_polling
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff819dee11)
Location: drivers/power/supply/charger-manager.c:343
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:_setup_polling
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81b42c5d)
Location: drivers/power/supply/charger-manager.c:343
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:_setup_polling
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81cd9532)
Location: drivers/power/supply/charger-manager.c:343
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:_setup_polling
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81d417a2)
Location: drivers/power/supply/charger-manager.c:343
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:_setup_polling
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81df8152)
Location: drivers/power/supply/charger-manager.c:343
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:_setup_polling
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffff800010ace8a8)
Location: drivers/power/supply/charger-manager.c:330
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:_setup_polling
```
**Symbols:**

```
ffff800010ace8a8-ffff800010ace93c: is_polling_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (c0baef38)
Location: drivers/power/supply/charger-manager.c:330
Inline: False
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:_setup_polling
```
**Symbols:**

```
c0baef38-c0baefa8: is_polling_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (c000000000bb1960)
Location: drivers/power/supply/charger-manager.c:330
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:_setup_polling
```
**Symbols:**

```
c000000000bb1960-c000000000bb19e0: is_polling_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffe0006cb554)
Location: drivers/power/supply/charger-manager.c:330
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:_setup_polling
```
**Symbols:**

```
ffffffe0006cb554-ffffffe0006cb5d0: is_polling_required (STB_LOCAL)
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
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8187758a)
Location: drivers/power/supply/charger-manager.c:330
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:_setup_polling
```
**Symbols:**

```
ffffffff81877560-ffffffff8187759e: is_polling_required (STB_LOCAL)
ffffffff81878d2e-ffffffff81878d45: is_polling_required.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_polling_required(struct charger_manager *cm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81892f2a)
Location: drivers/power/supply/charger-manager.c:330
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:_setup_polling
```
**Symbols:**

```
ffffffff81892f00-ffffffff81892f3e: is_polling_required (STB_LOCAL)
ffffffff818946ce-ffffffff818946e5: is_polling_required.cold (STB_LOCAL)
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
