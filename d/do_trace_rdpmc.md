# Function: <code>do_trace_rdpmc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81463ca0)
Location: arch/x86/lib/msr.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff81463ca0-ffffffff81463d07: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81482f40)
Location: arch/x86/lib/msr.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff81482f40-ffffffff81482fa7: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8148c6a0)
Location: arch/x86/lib/msr.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff8148c6a0-ffffffff8148c707: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814c8790)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff814c8790-ffffffff814c8800: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff814f9730)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff814f9730-ffffffff814f97a0: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8150dfd0)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff8150dfd0-ffffffff8150e040: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8153c640)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff8153c640-ffffffff8153c6a9: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8155d450)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff8155d450-ffffffff8155d4b9: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815e7050)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff815e7050-ffffffff815e70b9: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8160c360)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff8160c360-ffffffff8160c3a5: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815ef5e0)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff815ef5e0-ffffffff815ef625: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8165c6f0)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff8165c6f0-ffffffff8165c732: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81775880)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff81775880-ffffffff81775910: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff818a6530)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff818a6530-ffffffff818a65c0: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff818e93a0)
Location: arch/x86/lib/msr.c:137
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff818e93a0-ffffffff818e9430: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81930840)
Location: arch/x86/lib/msr.c:137
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff81930840-ffffffff819308d0: do_trace_rdpmc (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81555a40)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff81555a40-ffffffff81555aa9: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81545c20)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_perf_event_update
  - arch/x86/events/amd/uncore.c:amd_uncore_read
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
```
**Symbols:**

```
ffffffff81545c20-ffffffff81545c89: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff81551780)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff81551780-ffffffff815517e9: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_trace_rdpmc(unsigned int counter, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8156b830)
Location: arch/x86/lib/msr.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_read_pmc
```
**Symbols:**

```
ffffffff8156b830-ffffffff8156b8b0: do_trace_rdpmc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
