# Function: <code>dpm_noirq_suspend_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81657910)
Location: drivers/base/power/main.c:1246
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
```
**Symbols:**

```
ffffffff81657910-ffffffff81657be9: dpm_noirq_suspend_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1382
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
```
**Symbols:**

```
ffffffff81694490-ffffffff816944dd: dpm_noirq_suspend_devices.cold.23 (STB_LOCAL)
ffffffff816934a0-ffffffff816936ff: dpm_noirq_suspend_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1384
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
```
**Symbols:**

```
ffffffff816b4b10-ffffffff816b4b5d: dpm_noirq_suspend_devices.cold.24 (STB_LOCAL)
ffffffff816b3b20-ffffffff816b3d7f: dpm_noirq_suspend_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816ed8b0)
Location: drivers/base/power/main.c:1372
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - drivers/base/power/main.c:dpm_suspend_noirq
```
**Symbols:**

```
ffffffff816ed8b0-ffffffff816edb5a: dpm_noirq_suspend_devices (STB_GLOBAL)
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
In drivers/base/power/main.c (ffffffff817118e4)
Location: drivers/base/power/main.c:1389
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1285
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff817cc1a0-ffffffff817cc3cc: dpm_noirq_suspend_devices (STB_LOCAL)
ffffffff817ce268-ffffffff817ce2b5: dpm_noirq_suspend_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1284
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff817e0c10-ffffffff817e0e18: dpm_noirq_suspend_devices (STB_LOCAL)
ffffffff81c0ee3b-ffffffff81c0ee88: dpm_noirq_suspend_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1285
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff817c4810-ffffffff817c4a18: dpm_noirq_suspend_devices (STB_LOCAL)
ffffffff81c00f89-ffffffff81c00fd6: dpm_noirq_suspend_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1295
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff8184ebf0-ffffffff8184ee25: dpm_noirq_suspend_devices (STB_LOCAL)
ffffffff81d03abb-ffffffff81d03b20: dpm_noirq_suspend_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1292
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff81994c30-ffffffff81994e9c: dpm_noirq_suspend_devices (STB_LOCAL)
ffffffff81ecc36d-ffffffff81ecc3d2: dpm_noirq_suspend_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b05a80)
Location: drivers/base/power/main.c:1292
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff81b05a80-ffffffff81b05d65: dpm_noirq_suspend_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b53a90)
Location: drivers/base/power/main.c:1292
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff81b53a90-ffffffff81b53d75: dpm_noirq_suspend_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dpm_noirq_suspend_devices(pm_message_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81bac1e0)
Location: drivers/base/power/main.c:1291
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend_end
```
**Symbols:**

```
ffffffff81bac1e0-ffffffff81bac4c5: dpm_noirq_suspend_devices (STB_LOCAL)
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
In drivers/base/power/main.c (ffff80001090229c)
Location: drivers/base/power/main.c:1389
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_noirq
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
In drivers/base/power/main.c (c09ec5b0)
Location: drivers/base/power/main.c:1389
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_noirq
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
In drivers/base/power/main.c (c0000000009a03d8)
Location: drivers/base/power/main.c:1389
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_noirq
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
In drivers/base/power/main.c (ffffffff816d7c64)
Location: drivers/base/power/main.c:1389
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b22c4)
Location: drivers/base/power/main.c:1389
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_noirq
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817055a4)
Location: drivers/base/power/main.c:1389
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_noirq
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
In drivers/base/power/main.c (ffffffff8171ff04)
Location: drivers/base/power/main.c:1389
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_noirq
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
