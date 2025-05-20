# Function: <code>bpf_get_stackid</code>

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
u64 bpf_get_stackid(u64 r1, u64 r2, u64 flags, u64 r4, u64 r5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811883a0)
Location: kernel/bpf/stackmap.c:119
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
ffffffff811883a0-ffffffff81188626: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81197250)
Location: kernel/bpf/stackmap.c:115
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
ffffffff81197250-ffffffff811974d6: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff8119eea0)
Location: kernel/bpf/stackmap.c:116
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
ffffffff8119eea0-ffffffff8119f109: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811b1e40)
Location: kernel/bpf/stackmap.c:121
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
ffffffff811b1e40-ffffffff811b20b2: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811d10a0)
Location: kernel/bpf/stackmap.c:338
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
ffffffff811d10a0-ffffffff811d14de: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811e0bd0)
Location: kernel/bpf/stackmap.c:350
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
ffffffff811e0bd0-ffffffff811e105b: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811f67d0)
Location: kernel/bpf/stackmap.c:345
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
ffffffff811f67d0-ffffffff811f6c36: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81203790)
Location: kernel/bpf/stackmap.c:346
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
ffffffff81203790-ffffffff81203bf6: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff8122b5f0)
Location: kernel/bpf/stackmap.c:351
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
ffffffff8122b5f0-ffffffff8122ba72: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81233af0)
Location: kernel/bpf/stackmap.c:465
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
```
**Symbols:**

```
ffffffff81233af0-ffffffff81233b85: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff812378b0)
Location: kernel/bpf/stackmap.c:330
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
```
**Symbols:**

```
ffffffff812378b0-ffffffff81237945: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81271e80)
Location: kernel/bpf/stackmap.c:337
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
```
**Symbols:**

```
ffffffff81271e80-ffffffff81271f15: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff812c0fc0)
Location: kernel/bpf/stackmap.c:283
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
```
**Symbols:**

```
ffffffff812c0fc0-ffffffff812c107b: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81324870)
Location: kernel/bpf/stackmap.c:283
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
```
**Symbols:**

```
ffffffff81324870-ffffffff8132492b: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81354ad0)
Location: kernel/bpf/stackmap.c:280
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
```
**Symbols:**

```
ffffffff81354ad0-ffffffff81354b8b: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff8137d440)
Location: kernel/bpf/stackmap.c:280
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
  - kernel/bpf/stackmap.c:bpf_get_stackid_pe
```
**Symbols:**

```
ffffffff8137d440-ffffffff8137d4fb: bpf_get_stackid (STB_GLOBAL)
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffff80001028bf08)
Location: kernel/bpf/stackmap.c:346
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
ffff80001028bf08-ffff80001028c338: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (c04bb5b4)
Location: kernel/bpf/stackmap.c:346
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
c04bb5b4-c04bba1c: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (c000000000338000)
Location: kernel/bpf/stackmap.c:346
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
c000000000338000-c0000000003385a4: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffe0001bf9ca)
Location: kernel/bpf/stackmap.c:346
Inline: False
```
**Symbols:**

```
ffffffe0001bf9ca-ffffffe0001bfd7a: bpf_get_stackid (STB_GLOBAL)
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
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811fbdb0)
Location: kernel/bpf/stackmap.c:346
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
ffffffff811fbdb0-ffffffff811fc216: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811eeb00)
Location: kernel/bpf/stackmap.c:346
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
ffffffff811eeb00-ffffffff811eef66: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811f9b80)
Location: kernel/bpf/stackmap.c:346
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
ffffffff811f9b80-ffffffff811f9fe6: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_get_stackid(u64 regs, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81208640)
Location: kernel/bpf/stackmap.c:346
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stackid_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stackid_tp
```
**Symbols:**

```
ffffffff81208640-ffffffff81208aa6: bpf_get_stackid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 regs</code>
</li>
<li>
<b>Param added. </b>
<code>u64 map</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
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
