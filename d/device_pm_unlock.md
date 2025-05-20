# Function: <code>device_pm_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8155850a)
Location: drivers/base/power/main.c:115
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
ffffffff81559a60-ffffffff81559a77: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815aa67a)
Location: drivers/base/power/main.c:115
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
ffffffff815abbd0-ffffffff815abbe7: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815d932a)
Location: drivers/base/power/main.c:115
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
ffffffff815da970-ffffffff815da987: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815eedba)
Location: drivers/base/power/main.c:116
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
ffffffff815ef510-ffffffff815ef527: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8165567c)
Location: drivers/base/power/main.c:116
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
ffffffff81656970-ffffffff81656987: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8169114c)
Location: drivers/base/power/main.c:115
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
ffffffff81692530-ffffffff81692547: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b228c)
Location: drivers/base/power/main.c:116
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
ffffffff816b2ba0-ffffffff816b2bb7: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816eb4fc)
Location: drivers/base/power/main.c:116
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
ffffffff816ec9f0-ffffffff816eca07: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8170f5bc)
Location: drivers/base/power/main.c:116
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81710a60-ffffffff81710a77: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817cab1c)
Location: drivers/base/power/main.c:120
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff817cc8c0-ffffffff817cc8d7: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817df5cc)
Location: drivers/base/power/main.c:120
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
ffffffff817e12f0-ffffffff817e1307: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817c39ac)
Location: drivers/base/power/main.c:121
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
ffffffff817c5700-ffffffff817c5717: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8184dd4c)
Location: drivers/base/power/main.c:121
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff8184fa80-ffffffff8184fa97: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff819935cd)
Location: drivers/base/power/main.c:120
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81995340-ffffffff8199535d: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b03ced)
Location: drivers/base/power/main.c:120
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81b05e40-ffffffff81b05e5d: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b51d4d)
Location: drivers/base/power/main.c:120
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81b53e50-ffffffff81b53e6d: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81baa33d)
Location: drivers/base/power/main.c:120
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81bac5a0-ffffffff81bac5bd: device_pm_unlock (STB_GLOBAL)
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
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff8000108ffc4c)
Location: drivers/base/power/main.c:116
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
```
**Symbols:**

```
ffff800010901278-ffff80001090129c: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09eaba8)
Location: drivers/base/power/main.c:116
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
```
**Symbols:**

```
c09eb464-c09eb488: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099d028)
Location: drivers/base/power/main.c:116
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
```
**Symbols:**

```
c00000000099ee30-c00000000099ee6c: device_pm_unlock (STB_GLOBAL)
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
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d52fc)
Location: drivers/base/power/main.c:116
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff816d6de0-ffffffff816d6df7: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816affac)
Location: drivers/base/power/main.c:116
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff816b1440-ffffffff816b1457: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8170327c)
Location: drivers/base/power/main.c:116
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff81704720-ffffffff81704737: device_pm_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void device_pm_unlock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171dafc)
Location: drivers/base/power/main.c:116
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_pm_move_to_tail
  - drivers/base/power/trace.c:late_resume_init
  - drivers/base/power/trace.c:show_trace_dev_match
```
**Symbols:**

```
ffffffff8171ef90-ffffffff8171efa7: device_pm_unlock (STB_GLOBAL)
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
