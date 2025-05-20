# Function: <code>device_links_read_lock</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c7860)
Location: drivers/base/core.c:63
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_for_suppliers
```
**Symbols:**

```
ffffffff815c7860-ffffffff815c7877: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dc550)
Location: drivers/base/core.c:64
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_for_suppliers
```
**Symbols:**

```
ffffffff815dc550-ffffffff815dc567: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81643590)
Location: drivers/base/core.c:64
Inline: False
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_for_suppliers
```
**Symbols:**

```
ffffffff81643590-ffffffff816435a7: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167ee95)
Location: drivers/base/core.c:61
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_for_suppliers
```
**Symbols:**

```
ffffffff8167e940-ffffffff8167e957: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169f2d5)
Location: drivers/base/core.c:62
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_for_suppliers
```
**Symbols:**

```
ffffffff8169ed60-ffffffff8169ed77: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d7915)
Location: drivers/base/core.c:62
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
  - drivers/base/power/main.c:dpm_wait_for_suppliers
```
**Symbols:**

```
ffffffff816d7310-ffffffff816d7327: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fba35)
Location: drivers/base/core.c:63
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
ffffffff816fb410-ffffffff816fb427: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b5255)
Location: drivers/base/core.c:71
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
ffffffff817b4720-ffffffff817b4737: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c9945)
Location: drivers/base/core.c:165
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
ffffffff817c8e30-ffffffff817c8e47: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ad135)
Location: drivers/base/core.c:183
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
ffffffff817ac440-ffffffff817ac457: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81836425)
Location: drivers/base/core.c:195
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
ffffffff818356a0-ffffffff818356b7: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81978425)
Location: drivers/base/core.c:196
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
ffffffff819775b0-ffffffff819775cd: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae4c95)
Location: drivers/base/core.c:264
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
ffffffff81ae3f00-ffffffff81ae3f1d: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b33025)
Location: drivers/base/core.c:250
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
ffffffff81b321f0-ffffffff81b3220d: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8a935)
Location: drivers/base/core.c:251
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
ffffffff81b89c30-ffffffff81b89c4d: device_links_read_lock (STB_GLOBAL)
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
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e6364)
Location: drivers/base/core.c:63
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
ffff8000108e5b80-ffff8000108e5ba4: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d4990)
Location: drivers/base/core.c:63
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
c09d4210-c09d4234: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097bff8)
Location: drivers/base/core.c:63
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
c00000000097b560-c00000000097b59c: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057adfa)
Location: drivers/base/core.c:63
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
```
**Symbols:**

```
ffffffe00057a736-ffffffe00057a760: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c1225)
Location: drivers/base/core.c:63
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
ffffffff816c0c00-ffffffff816c0c17: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169c4d5)
Location: drivers/base/core.c:63
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
ffffffff8169beb0-ffffffff8169bec7: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ef6f5)
Location: drivers/base/core.c:63
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
ffffffff816ef0d0-ffffffff816ef0e7: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int device_links_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81709f35)
Location: drivers/base/core.c:63
Inline: True
Inline callers:
  - drivers/base/core.c:device_pm_move_to_tail
Direct callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_noirq
  - drivers/base/power/main.c:dpm_wait_for_subordinate
```
**Symbols:**

```
ffffffff81709910-ffffffff81709927: device_links_read_lock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
