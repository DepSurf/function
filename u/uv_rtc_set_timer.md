# Function: <code>uv_rtc_set_timer</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff81099136)
Location: arch/x86/platform/uv/uv_time.c:211
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uv_rtc_set_timer(int cpu, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff8109e750)
Location: arch/x86/platform/uv/uv_time.c:211
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
**Symbols:**

```
ffffffff8109e750-ffffffff8109e830: uv_rtc_set_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uv_rtc_set_timer(int cpu, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a2d0)
Location: arch/x86/platform/uv/uv_time.c:201
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
**Symbols:**

```
ffffffff8109a2d0-ffffffff8109a3b0: uv_rtc_set_timer (STB_LOCAL)
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
In arch/x86/platform/uv/uv_time.c (ffffffff8109aae9)
Location: arch/x86/platform/uv/uv_time.c:201
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
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
In arch/x86/platform/uv/uv_time.c (ffffffff810aacfb)
Location: arch/x86/platform/uv/uv_time.c:201
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
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
In arch/x86/platform/uv/uv_time.c (ffffffff810c0778)
Location: arch/x86/platform/uv/uv_time.c:201
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
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
In arch/x86/platform/uv/uv_time.c (ffffffff810dc728)
Location: arch/x86/platform/uv/uv_time.c:201
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
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
In arch/x86/platform/uv/uv_time.c (ffffffff810e7cfb)
Location: arch/x86/platform/uv/uv_time.c:201
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
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
In arch/x86/platform/uv/uv_time.c (ffffffff810f008b)
Location: arch/x86/platform/uv/uv_time.c:201
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
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
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a606)
Location: arch/x86/platform/uv/uv_time.c:211
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
