# Function: <code>security_perf_event_open</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_perf_event_open(struct perf_event_attr *attr, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aca70)
Location: security/security.c:2992
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/p4.c:p4_hw_config
  - kernel/trace/trace_event_perf.c:perf_trace_event_perm
  - kernel/trace/trace_event_perf.c:perf_trace_event_perm
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff814aca70-ffffffff814acab4: security_perf_event_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_perf_event_open(struct perf_event_attr *attr, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ca070)
Location: security/security.c:3010
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/p4.c:p4_hw_config
  - kernel/trace/trace_event_perf.c:perf_trace_event_perm
  - kernel/trace/trace_event_perf.c:perf_trace_event_perm
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff814ca070-ffffffff814ca0b4: security_perf_event_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_perf_event_open(struct perf_event_attr *attr, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814d06a0)
Location: security/security.c:3073
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/p4.c:p4_hw_config
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff814d06a0-ffffffff814d06e4: security_perf_event_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_perf_event_open(struct perf_event_attr *attr, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815293d0)
Location: security/security.c:3081
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/p4.c:p4_hw_config
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff815293d0-ffffffff81529414: security_perf_event_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_perf_event_open(struct perf_event_attr *attr, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bea50)
Location: security/security.c:3159
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/p4.c:p4_hw_config
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff815bea50-ffffffff815beaad: security_perf_event_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_perf_event_open(struct perf_event_attr *attr, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8166ad40)
Location: security/security.c:3139
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/p4.c:p4_hw_config
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff8166ad40-ffffffff8166ad9d: security_perf_event_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_perf_event_open(struct perf_event_attr *attr, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a34a0)
Location: security/security.c:5611
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/p4.c:p4_hw_config
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff816a34a0-ffffffff816a34fd: security_perf_event_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_perf_event_open(struct perf_event_attr *attr, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dff20)
Location: security/security.c:5752
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/p4.c:p4_hw_config
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff816dff20-ffffffff816dff7d: security_perf_event_open (STB_GLOBAL)
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
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
