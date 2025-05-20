# Function: <code>uv_setup_intr</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
int uv_setup_intr(int cpu, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff81098ab0)
Location: arch/x86/platform/uv/uv_time.c:98
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
**Symbols:**

```
ffffffff81098ab0-ffffffff81098e3d: uv_setup_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uv_setup_intr(int cpu, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff8109e1a0)
Location: arch/x86/platform/uv/uv_time.c:98
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_set_timer
```
**Symbols:**

```
ffffffff8109e1a0-ffffffff8109e49e: uv_setup_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uv_setup_intr(int cpu, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff81099d60)
Location: arch/x86/platform/uv/uv_time.c:93
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_set_timer
```
**Symbols:**

```
ffffffff81099d60-ffffffff8109a01f: uv_setup_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uv_setup_intr(int cpu, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a550)
Location: arch/x86/platform/uv/uv_time.c:93
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
**Symbols:**

```
ffffffff8109a550-ffffffff8109a7e4: uv_setup_intr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int uv_setup_intr(int cpu, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/platform/uv/uv_time.c:93
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
**Symbols:**

```
ffffffff810aa5d0-ffffffff810aa909: uv_setup_intr (STB_LOCAL)
ffffffff81ca2990-ffffffff81ca2a4a: uv_setup_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int uv_setup_intr(int cpu, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/platform/uv/uv_time.c:93
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
**Symbols:**

```
ffffffff810c0020-ffffffff810c031c: uv_setup_intr (STB_LOCAL)
ffffffff81e521f2-ffffffff81e522ac: uv_setup_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int uv_setup_intr(int cpu, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/platform/uv/uv_time.c:93
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
**Symbols:**

```
ffffffff810dbf80-ffffffff810dc27c: uv_setup_intr (STB_LOCAL)
ffffffff820556a0-ffffffff8205575a: uv_setup_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int uv_setup_intr(int cpu, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/platform/uv/uv_time.c:93
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
**Symbols:**

```
ffffffff810e7550-ffffffff810e784c: uv_setup_intr (STB_LOCAL)
ffffffff820d3c9b-ffffffff820d3d55: uv_setup_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int uv_setup_intr(int cpu, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/platform/uv/uv_time.c:93
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
**Symbols:**

```
ffffffff810ef8e0-ffffffff810efbdb: uv_setup_intr (STB_LOCAL)
ffffffff821aeaed-ffffffff821aeba7: uv_setup_intr.cold (STB_LOCAL)
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
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uv_setup_intr(int cpu, u64 expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff81099f80)
Location: arch/x86/platform/uv/uv_time.c:98
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
```
**Symbols:**

```
ffffffff81099f80-ffffffff8109a30d: uv_setup_intr (STB_LOCAL)
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
