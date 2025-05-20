# Function: <code>device_pm_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815584c6)
Location: drivers/base/power/main.c:107
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_for_each_dev
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81559a40-ffffffff81559a57: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815aa636)
Location: drivers/base/power/main.c:107
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_for_each_dev
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff815abbb0-ffffffff815abbc7: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815d92e6)
Location: drivers/base/power/main.c:107
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_for_each_dev
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff815da950-ffffffff815da967: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815eed76)
Location: drivers/base/power/main.c:108
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff815ef4f0-ffffffff815ef507: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81655636)
Location: drivers/base/power/main.c:108
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:deferred_probe_work_func
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81656950-ffffffff81656967: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81691103)
Location: drivers/base/power/main.c:107
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81692510-ffffffff81692527: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b2243)
Location: drivers/base/power/main.c:108
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff816b2b80-ffffffff816b2b97: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816eb4bf)
Location: drivers/base/power/main.c:108
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff816ec9d0-ffffffff816ec9e7: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8170f57f)
Location: drivers/base/power/main.c:108
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81710a40-ffffffff81710a57: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817caadf)
Location: drivers/base/power/main.c:112
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff817cc8a0-ffffffff817cc8b7: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817df58f)
Location: drivers/base/power/main.c:112
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff817e12d0-ffffffff817e12e7: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817c396f)
Location: drivers/base/power/main.c:113
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff817c56e0-ffffffff817c56f7: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8184dd0f)
Location: drivers/base/power/main.c:113
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff8184fa60-ffffffff8184fa77: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8199358f)
Location: drivers/base/power/main.c:112
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81995320-ffffffff8199533d: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b03caf)
Location: drivers/base/power/main.c:112
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81b05e10-ffffffff81b05e2d: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b51d0f)
Location: drivers/base/power/main.c:112
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81b53e20-ffffffff81b53e3d: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81baa2ff)
Location: drivers/base/power/main.c:112
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81bac570-ffffffff81bac58d: device_pm_lock (STB_GLOBAL)
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
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff8000108ffc04)
Location: drivers/base/power/main.c:108
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
```
**Symbols:**

```
ffff800010901250-ffff800010901274: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09eab6c)
Location: drivers/base/power/main.c:108
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
```
**Symbols:**

```
c09eb440-c09eb464: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099cfc4)
Location: drivers/base/power/main.c:108
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
```
**Symbols:**

```
c00000000099edf0-c00000000099ee2c: device_pm_lock (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d52bf)
Location: drivers/base/power/main.c:108
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff816d6dc0-ffffffff816d6dd7: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816aff6f)
Location: drivers/base/power/main.c:108
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff816b1420-ffffffff816b1437: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8170323f)
Location: drivers/base/power/main.c:108
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81704700-ffffffff81704717: device_pm_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void device_pm_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171dabf)
Location: drivers/base/power/main.c:108
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff8171ef70-ffffffff8171ef87: device_pm_lock (STB_GLOBAL)
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
