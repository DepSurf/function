# Function: <code>within_error_injection_list</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff814f0270)
Location: lib/error-inject.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
```
**Symbols:**

```
ffffffff814f0270-ffffffff814f02c4: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff81504190)
Location: lib/error-inject.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
```
**Symbols:**

```
ffffffff81504190-ffffffff815041e4: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff815322f0)
Location: lib/error-inject.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
```
**Symbols:**

```
ffffffff815322f0-ffffffff8153234b: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff81553130)
Location: lib/error-inject.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
```
**Symbols:**

```
ffffffff81553130-ffffffff8155318b: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff815dc500)
Location: lib/error-inject.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff815dc500-ffffffff815dc55b: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff815fa1a0)
Location: lib/error-inject.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff815fa1a0-ffffffff815fa1fb: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff815dcd80)
Location: lib/error-inject.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff815dcd80-ffffffff815dcddb: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff816486e0)
Location: lib/error-inject.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff816486e0-ffffffff8164873b: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff8175eb00)
Location: lib/error-inject.c:24
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff8175eb00-ffffffff8175eb5d: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff8188c3e0)
Location: lib/error-inject.c:24
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff8188c3e0-ffffffff8188c43d: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff818ce850)
Location: lib/error-inject.c:24
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff818ce850-ffffffff818ce8ad: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff81920630)
Location: lib/error-inject.c:24
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff81920630-ffffffff8192068d: within_error_injection_list (STB_GLOBAL)
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
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffff80001065f438)
Location: lib/error-inject.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
```
**Symbols:**

```
ffff80001065f438-ffff80001065f4c4: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/error-injection.h:15
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (c000000000811f70)
Location: lib/error-inject.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
```
**Symbols:**

```
c000000000811f70-c00000000081203c: within_error_injection_list (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff8154b710)
Location: lib/error-inject.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
```
**Symbols:**

```
ffffffff8154b710-ffffffff8154b76b: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff8153b9f0)
Location: lib/error-inject.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
```
**Symbols:**

```
ffffffff8153b9f0-ffffffff8153ba4b: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff81547450)
Location: lib/error-inject.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
```
**Symbols:**

```
ffffffff81547450-ffffffff815474ab: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool within_error_injection_list(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/error-inject.c (ffffffff815612a0)
Location: lib/error-inject.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
```
**Symbols:**

```
ffffffff815612a0-ffffffff815612fb: within_error_injection_list (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
