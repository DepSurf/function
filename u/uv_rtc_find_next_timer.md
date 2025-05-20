# Function: <code>uv_rtc_find_next_timer</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head *head, int pnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff81098e40)
Location: arch/x86/platform/uv/uv_time.c:181
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
```
**Symbols:**

```
ffffffff81098e40-ffffffff81098fa8: uv_rtc_find_next_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head *head, int pnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff8109e4a0)
Location: arch/x86/platform/uv/uv_time.c:181
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_set_timer
```
**Symbols:**

```
ffffffff8109e4a0-ffffffff8109e60b: uv_rtc_find_next_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head *head, int pnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a020)
Location: arch/x86/platform/uv/uv_time.c:171
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_set_timer
```
**Symbols:**

```
ffffffff8109a020-ffffffff8109a183: uv_rtc_find_next_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head *head, int pnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a7f0)
Location: arch/x86/platform/uv/uv_time.c:171
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
```
**Symbols:**

```
ffffffff8109a7f0-ffffffff8109a953: uv_rtc_find_next_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head *head, int pnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff810aa988)
Location: arch/x86/platform/uv/uv_time.c:171
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
```
**Symbols:**

```
ffffffff810aa910-ffffffff810aaac6: uv_rtc_find_next_timer (STB_LOCAL)
ffffffff81ca2a4a-ffffffff81ca2aba: uv_rtc_find_next_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head *head, int pnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff810c03b2)
Location: arch/x86/platform/uv/uv_time.c:171
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
```
**Symbols:**

```
ffffffff810c0320-ffffffff810c0510: uv_rtc_find_next_timer (STB_LOCAL)
ffffffff81e522ac-ffffffff81e5231c: uv_rtc_find_next_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head *head, int pnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff810dc322)
Location: arch/x86/platform/uv/uv_time.c:171
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
```
**Symbols:**

```
ffffffff810dc290-ffffffff810dc480: uv_rtc_find_next_timer (STB_LOCAL)
ffffffff8205575a-ffffffff820557ca: uv_rtc_find_next_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head *head, int pnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff810e78f2)
Location: arch/x86/platform/uv/uv_time.c:171
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
```
**Symbols:**

```
ffffffff810e7860-ffffffff810e7a50: uv_rtc_find_next_timer (STB_LOCAL)
ffffffff820d3d55-ffffffff820d3dc5: uv_rtc_find_next_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head *head, int pnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff810efc82)
Location: arch/x86/platform/uv/uv_time.c:171
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
```
**Symbols:**

```
ffffffff810efbf0-ffffffff810efddf: uv_rtc_find_next_timer (STB_LOCAL)
ffffffff821aeba7-ffffffff821aec17: uv_rtc_find_next_timer.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head *head, int pnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a310)
Location: arch/x86/platform/uv/uv_time.c:181
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
```
**Symbols:**

```
ffffffff8109a310-ffffffff8109a478: uv_rtc_find_next_timer (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
