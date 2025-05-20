# Function: <code>__cpuhp_kick_ap</code>

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
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108bb10)
Location: kernel/cpu.c:385
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffffffff8108bb10-ffffffff8108bb5c: __cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108f3d0)
Location: kernel/cpu.c:461
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffffffff8108f3d0-ffffffff8108f41b: __cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810976d0)
Location: kernel/cpu.c:468
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffffffff810976d0-ffffffff8109771b: __cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109bc40)
Location: kernel/cpu.c:478
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffffffff8109bc40-ffffffff8109bc8c: __cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a21c0)
Location: kernel/cpu.c:488
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffffffff810a21c0-ffffffff810a220c: __cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81bc0b6a)
Location: kernel/cpu.c:489
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_invoke_ap_callback
  - kernel/cpu.c:cpuhp_invoke_ap_callback
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81c39bfa)
Location: kernel/cpu.c:489
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_invoke_ap_callback
  - kernel/cpu.c:cpuhp_invoke_ap_callback
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff810a6817)
Location: kernel/cpu.c:516
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:527
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
```
**Symbols:**

```
ffffffff810b7380-ffffffff810b73ee: __cpuhp_kick_ap (STB_LOCAL)
ffffffff81ca3db2-ffffffff81ca3ddc: __cpuhp_kick_ap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:529
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffffffff810cdb40-ffffffff810cdbb8: __cpuhp_kick_ap (STB_LOCAL)
ffffffff81e535dd-ffffffff81e53607: __cpuhp_kick_ap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:529
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffffffff810ebd60-ffffffff810ebdd8: __cpuhp_kick_ap (STB_LOCAL)
ffffffff82055afc-ffffffff82055b26: __cpuhp_kick_ap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:723
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffffffff810f7a40-ffffffff810f7ab8: __cpuhp_kick_ap (STB_LOCAL)
ffffffff820d40e2-ffffffff820d410c: __cpuhp_kick_ap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:751
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffffffff81100e30-ffffffff81100ea8: __cpuhp_kick_ap (STB_LOCAL)
ffffffff821aefb6-ffffffff821aefe0: __cpuhp_kick_ap.cold (STB_LOCAL)
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
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f7160)
Location: kernel/cpu.c:488
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffff8000100f7160-ffff8000100f71c8: __cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c03555fc)
Location: kernel/cpu.c:488
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
c03555fc-c0355660: __cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013d710)
Location: kernel/cpu.c:488
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
c00000000013d710-c00000000013d7a8: __cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c2d02)
Location: kernel/cpu.c:488
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffffffe0000c2d02-ffffffe0000c2d60: __cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109bae0)
Location: kernel/cpu.c:488
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffffffff8109bae0-ffffffff8109bb2c: __cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108a510)
Location: kernel/cpu.c:488
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffffffff8108a510-ffffffff8108a55c: __cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109ba90)
Location: kernel/cpu.c:488
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffffffff8109ba90-ffffffff8109badc: __cpuhp_kick_ap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __cpuhp_kick_ap(struct cpuhp_cpu_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3700)
Location: kernel/cpu.c:488
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
```
**Symbols:**

```
ffffffff810a3700-ffffffff810a374c: __cpuhp_kick_ap (STB_LOCAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
