# Function: <code>device_links_read_unlock</code>

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
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c7880)
Location: drivers/base/core.c:68
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
ffffffff815c7880-ffffffff815c7899: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dc570)
Location: drivers/base/core.c:69
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
ffffffff815dc570-ffffffff815dc589: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816435b0)
Location: drivers/base/core.c:69
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
ffffffff816435b0-ffffffff816435c9: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167eec1)
Location: drivers/base/core.c:66
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
ffffffff8167e960-ffffffff8167e979: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169f301)
Location: drivers/base/core.c:67
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
ffffffff8169ed80-ffffffff8169ed99: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d7943)
Location: drivers/base/core.c:67
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
ffffffff816d7330-ffffffff816d735e: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fba63)
Location: drivers/base/core.c:68
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
ffffffff816fb430-ffffffff816fb45e: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b5283)
Location: drivers/base/core.c:76
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
ffffffff817b4740-ffffffff817b476e: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c9973)
Location: drivers/base/core.c:170
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
ffffffff817c8e50-ffffffff817c8e7e: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ad163)
Location: drivers/base/core.c:188
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
ffffffff817ac460-ffffffff817ac48e: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81836453)
Location: drivers/base/core.c:200
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
ffffffff818356c0-ffffffff818356ee: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81978451)
Location: drivers/base/core.c:201
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
ffffffff819775d0-ffffffff8197760e: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae4cc1)
Location: drivers/base/core.c:269
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
ffffffff81ae3f30-ffffffff81ae3f6e: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b33051)
Location: drivers/base/core.c:255
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
ffffffff81b32220-ffffffff81b3225e: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8a961)
Location: drivers/base/core.c:256
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
ffffffff81b89c60-ffffffff81b89c9e: device_links_read_unlock (STB_GLOBAL)
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
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e6384)
Location: drivers/base/core.c:68
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
ffff8000108e5ba8-ffff8000108e5c04: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d49b8)
Location: drivers/base/core.c:68
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
c09d4234-c09d429c: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097c030)
Location: drivers/base/core.c:68
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
c00000000097b5a0-c00000000097b614: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057ae18)
Location: drivers/base/core.c:68
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
ffffffe00057a760-ffffffe00057a79c: device_links_read_unlock (STB_GLOBAL)
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
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c1253)
Location: drivers/base/core.c:68
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
ffffffff816c0c20-ffffffff816c0c4e: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169c503)
Location: drivers/base/core.c:68
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
ffffffff8169bed0-ffffffff8169befe: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ef723)
Location: drivers/base/core.c:68
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
ffffffff816ef0f0-ffffffff816ef11e: device_links_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void device_links_read_unlock(int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81709f63)
Location: drivers/base/core.c:68
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
ffffffff81709930-ffffffff8170995e: device_links_read_unlock (STB_GLOBAL)
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
