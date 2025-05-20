# Function: <code>__clocksource_select</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff810f7a60)
Location: kernel/time/clocksource.c:550
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:sysfs_override_clocksource
```
**Symbols:**

```
ffffffff810f7a60-ffffffff810f7b75: __clocksource_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff810febd0)
Location: kernel/time/clocksource.c:580
Inline: False
Direct callers:
  - kernel/time/clocksource.c:sysfs_override_clocksource
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff810febd0-ffffffff810fecf1: __clocksource_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81101a30)
Location: kernel/time/clocksource.c:581
Inline: False
Direct callers:
  - kernel/time/clocksource.c:sysfs_override_clocksource
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff81101a30-ffffffff81101b6d: __clocksource_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81103b60)
Location: kernel/time/clocksource.c:588
Inline: False
Direct callers:
  - kernel/time/clocksource.c:sysfs_override_clocksource
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff81103b60-ffffffff81103cad: __clocksource_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff8110ebf0)
Location: kernel/time/clocksource.c:587
Inline: False
Direct callers:
  - kernel/time/clocksource.c:sysfs_override_clocksource
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff8110ebf0-ffffffff8110ed3d: __clocksource_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:605
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff8111a670-ffffffff8111a78e: __clocksource_select (STB_LOCAL)
ffffffff8111b743-ffffffff8111b7a4: __clocksource_select.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:725
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff81125b70-ffffffff81125c8e: __clocksource_select (STB_LOCAL)
ffffffff81126f33-ffffffff81126f94: __clocksource_select.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:725
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff81130590-ffffffff811306b1: __clocksource_select (STB_LOCAL)
ffffffff811318e5-ffffffff81131945: __clocksource_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:732
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff8113c4d0-ffffffff8113c5f1: __clocksource_select (STB_LOCAL)
ffffffff8113d835-ffffffff8113d895: __clocksource_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:732
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff8114b540-ffffffff8114b661: __clocksource_select (STB_LOCAL)
ffffffff8114c9b5-ffffffff8114ca15: __clocksource_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:730
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff811479a0-ffffffff81147ac1: __clocksource_select (STB_LOCAL)
ffffffff81be38ec-ffffffff81be394c: __clocksource_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:831
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff81148bf0-ffffffff81148d08: __clocksource_select (STB_LOCAL)
ffffffff81bd57bc-ffffffff81bd581c: __clocksource_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:943
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff8116c870-ffffffff8116c988: __clocksource_select (STB_LOCAL)
ffffffff81cb15bf-ffffffff81cb161f: __clocksource_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:949
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff811a0830-ffffffff811a097b: __clocksource_select (STB_LOCAL)
ffffffff81e62bad-ffffffff81e62c11: __clocksource_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811df760)
Location: kernel/time/clocksource.c:968
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff811df760-ffffffff811df922: __clocksource_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff811f3c20)
Location: kernel/time/clocksource.c:979
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff811f3c20-ffffffff811f3e21: __clocksource_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81209d60)
Location: kernel/time/clocksource.c:1002
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff81209d60-ffffffff81209f61: __clocksource_select (STB_LOCAL)
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
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffff8000101a66c8)
Location: kernel/time/clocksource.c:732
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
```
**Symbols:**

```
ffff8000101a66c8-ffff8000101a685c: __clocksource_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (c03f1950)
Location: kernel/time/clocksource.c:732
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
```
**Symbols:**

```
c03f1950-c03f1aec: __clocksource_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (c000000000208b00)
Location: kernel/time/clocksource.c:732
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
```
**Symbols:**

```
c000000000208b00-c000000000208ed8: __clocksource_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clocksource.c (ffffffe00013287e)
Location: kernel/time/clocksource.c:732
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
```
**Symbols:**

```
ffffffe00013287e-ffffffe0001329d0: __clocksource_select (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:732
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff81134c80-ffffffff81134da1: __clocksource_select (STB_LOCAL)
ffffffff81135fe5-ffffffff81136045: __clocksource_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:732
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff811276e0-ffffffff81127801: __clocksource_select (STB_LOCAL)
ffffffff81128a35-ffffffff81128a95: __clocksource_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:732
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff811329a0-ffffffff81132ac1: __clocksource_select (STB_LOCAL)
ffffffff81133d05-ffffffff81133d65: __clocksource_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __clocksource_select(bool skipcur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:732
Inline: False
Direct callers:
  - kernel/time/clocksource.c:current_clocksource_store
  - kernel/time/clocksource.c:clocksource_unbind
  - kernel/time/clocksource.c:clocksource_change_rating
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_done_booting
  - kernel/time/clocksource.c:clocksource_watchdog_kthread
```
**Symbols:**

```
ffffffff8113f3c0-ffffffff8113f4e1: __clocksource_select (STB_LOCAL)
ffffffff81140725-ffffffff81140785: __clocksource_select.cold (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
