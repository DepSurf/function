# Function: <code>initcall_debug_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ktime_t initcall_debug_start(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815585b0)
Location: drivers/base/power/main.c:191
Inline: False
Direct callers:
  - drivers/base/power/main.c:legacy_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff815585b0-ffffffff81558614: initcall_debug_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ktime_t initcall_debug_start(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815aa860)
Location: drivers/base/power/main.c:193
Inline: False
Direct callers:
  - drivers/base/power/main.c:legacy_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff815aa860-ffffffff815aa8c4: initcall_debug_start (STB_LOCAL)
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
In drivers/base/power/main.c (ffffffff817861ea)
Location: drivers/base/power/main.c:195
Inline: True
Inline callers:
  - drivers/base/power/main.c:legacy_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:legacy_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff815d9790-ffffffff815d97e8: initcall_debug_start.part.8 (STB_LOCAL)
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
In drivers/base/power/main.c (ffffffff815eedf1)
Location: drivers/base/power/main.c:196
Inline: True
Inline callers:
  - drivers/base/power/main.c:legacy_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:legacy_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff815ee180-ffffffff815ee1d8: initcall_debug_start.part.8 (STB_LOCAL)
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
In drivers/base/power/main.c (ffffffff816565ea)
Location: drivers/base/power/main.c:196
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff81655560-ffffffff816555b8: initcall_debug_start.part.9 (STB_LOCAL)
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
In drivers/base/power/main.c (ffffffff816921e6)
Location: drivers/base/power/main.c:195
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff816910a0-ffffffff816910ec: initcall_debug_start.part.13 (STB_LOCAL)
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
In drivers/base/power/main.c (ffffffff816b2856)
Location: drivers/base/power/main.c:196
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff816b1700-ffffffff816b174c: initcall_debug_start.part.14 (STB_LOCAL)
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
In drivers/base/power/main.c (ffffffff816ec667)
Location: drivers/base/power/main.c:203
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff816ee918-ffffffff816ee962: initcall_debug_start.part.0 (STB_LOCAL)
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
In drivers/base/power/main.c (ffffffff817106d7)
Location: drivers/base/power/main.c:203
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff817128f8-ffffffff81712942: initcall_debug_start.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff817cab62)
Location: drivers/base/power/main.c:207
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff817ce13f-ffffffff817ce189: initcall_debug_start.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff817df60d)
Location: drivers/base/power/main.c:207
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff81c0ed13-ffffffff81c0ed5d: initcall_debug_start.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff817c39ed)
Location: drivers/base/power/main.c:208
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff81c00e8c-ffffffff81c00ed6: initcall_debug_start.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff8184dd91)
Location: drivers/base/power/main.c:208
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff81d03946-ffffffff81d03990: initcall_debug_start.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff81993630)
Location: drivers/base/power/main.c:207
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff81ecc1ff-ffffffff81ecc258: initcall_debug_start.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
ktime_t initcall_debug_start(struct device *dev, void *cb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b03c20)
Location: drivers/base/power/main.c:207
Inline: True
Direct callers:
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff81b03bf0-ffffffff81b03c77: initcall_debug_start (STB_LOCAL)
ffffffff820988ca-ffffffff820988e7: initcall_debug_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
ktime_t initcall_debug_start(struct device *dev, void *cb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b51c80)
Location: drivers/base/power/main.c:207
Inline: True
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff81b51c50-ffffffff81b51cd7: initcall_debug_start (STB_LOCAL)
ffffffff821198c6-ffffffff821198e3: initcall_debug_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ktime_t initcall_debug_start(struct device *dev, void *cb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff81baa270)
Location: drivers/base/power/main.c:207
Inline: True
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff81baa240-ffffffff81baa2c7: initcall_debug_start (STB_LOCAL)
ffffffff821f7888-ffffffff821f78a5: initcall_debug_start.cold (STB_LOCAL)
```
</details>
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
In drivers/base/power/main.c (ffff800010900e4c)
Location: drivers/base/power/main.c:203
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffff8000109035dc-ffff800010903644: initcall_debug_start.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (c09eb048)
Location: drivers/base/power/main.c:203
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
c09ed8e0-c09ed94c: initcall_debug_start.part.0 (STB_LOCAL)
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
In drivers/base/power/main.c (c00000000099e898)
Location: drivers/base/power/main.c:203
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
c0000000009a1ce8-c0000000009a1d5c: initcall_debug_start.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d6a7d)
Location: drivers/base/power/main.c:203
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff816d8c78-ffffffff816d8cc2: initcall_debug_start.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b10bb)
Location: drivers/base/power/main.c:203
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff816b32b8-ffffffff816b3302: initcall_debug_start.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (ffffffff81704397)
Location: drivers/base/power/main.c:203
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff817065b8-ffffffff81706602: initcall_debug_start.part.0 (STB_LOCAL)
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
In drivers/base/power/main.c (ffffffff8171e485)
Location: drivers/base/power/main.c:203
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
Direct callers:
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:dpm_run_callback
```
**Symbols:**

```
ffffffff81720fc8-ffffffff81721012: initcall_debug_start.part.0 (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
