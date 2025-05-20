# Function: <code>kgdb_cpu_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8112fc60)
Location: kernel/debug/debug_core.c:467
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_nmicallin
```
**Symbols:**

```
ffffffff8112fc60-ffffffff811301eb: kgdb_cpu_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81137f70)
Location: kernel/debug/debug_core.c:467
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff81137f70-ffffffff811384e2: kgdb_cpu_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81141d00)
Location: kernel/debug/debug_core.c:467
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff81141d00-ffffffff81142280: kgdb_cpu_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81143540)
Location: kernel/debug/debug_core.c:468
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff81143540-ffffffff81143ab7: kgdb_cpu_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811501f0)
Location: kernel/debug/debug_core.c:468
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff811501f0-ffffffff8115076f: kgdb_cpu_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:468
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff8115ed90-ffffffff8115f2f8: kgdb_cpu_enter (STB_LOCAL)
ffffffff8115f8ea-ffffffff8115f8fb: kgdb_cpu_enter.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:525
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff8116bac0-ffffffff8116c03f: kgdb_cpu_enter (STB_LOCAL)
ffffffff8116c65a-ffffffff8116c66b: kgdb_cpu_enter.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:525
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff811788e0-ffffffff81178e65: kgdb_cpu_enter (STB_LOCAL)
ffffffff81179492-ffffffff811794a3: kgdb_cpu_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:525
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff81184730-ffffffff81184cb2: kgdb_cpu_enter (STB_LOCAL)
ffffffff81185322-ffffffff81185333: kgdb_cpu_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:567
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff81198770-ffffffff81198cfd: kgdb_cpu_enter (STB_LOCAL)
ffffffff8119945d-ffffffff81199483: kgdb_cpu_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:586
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff811958d0-ffffffff81195e75: kgdb_cpu_enter (STB_LOCAL)
ffffffff81be4b70-ffffffff81be4b96: kgdb_cpu_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:585
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff81196870-ffffffff81196e4e: kgdb_cpu_enter (STB_LOCAL)
ffffffff81bd69e3-ffffffff81bd6a09: kgdb_cpu_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:582
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff811bfb70-ffffffff811c0635: kgdb_cpu_enter (STB_LOCAL)
ffffffff81cb39d0-ffffffff81cb3a38: kgdb_cpu_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:583
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff811f3060-ffffffff811f3b30: kgdb_cpu_enter (STB_LOCAL)
ffffffff81e64840-ffffffff81e648a7: kgdb_cpu_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81239e00)
Location: kernel/debug/debug_core.c:571
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff81239e00-ffffffff8123a93d: kgdb_cpu_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81250e10)
Location: kernel/debug/debug_core.c:571
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff81250e10-ffffffff8125194d: kgdb_cpu_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8126ac60)
Location: kernel/debug/debug_core.c:571
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
  - kernel/debug/debug_core.c:kgdb_call_nmi_hook
```
**Symbols:**

```
ffffffff8126ac60-ffffffff8126b79d: kgdb_cpu_enter (STB_LOCAL)
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
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffff8000101fa0d8)
Location: kernel/debug/debug_core.c:525
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffff8000101fa0d8-ffff8000101fa794: kgdb_cpu_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c043a15c)
Location: kernel/debug/debug_core.c:525
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
c043a15c-c043a89c: kgdb_cpu_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c000000000271a20)
Location: kernel/debug/debug_core.c:525
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
c000000000271a20-c0000000002721e0: kgdb_cpu_enter (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:525
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff8117cd50-ffffffff8117d2d2: kgdb_cpu_enter (STB_LOCAL)
ffffffff8117d942-ffffffff8117d953: kgdb_cpu_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:525
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff8116fed0-ffffffff81170430: kgdb_cpu_enter (STB_LOCAL)
ffffffff81170a92-ffffffff81170aa3: kgdb_cpu_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:525
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff8117ab20-ffffffff8117b0a2: kgdb_cpu_enter (STB_LOCAL)
ffffffff8117b712-ffffffff8117b723: kgdb_cpu_enter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kgdb_cpu_enter(struct kgdb_state *ks, struct pt_regs *regs, int exception_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:525
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_nmicallin
  - kernel/debug/debug_core.c:kgdb_nmicallback
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff81188450-ffffffff811889ce: kgdb_cpu_enter (STB_LOCAL)
ffffffff81189032-ffffffff81189043: kgdb_cpu_enter.cold (STB_LOCAL)
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
