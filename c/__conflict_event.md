# Function: <code>__conflict_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool __conflict_event(struct perf_event *a, struct perf_event *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100da60)
Location: arch/x86/events/intel/cqm.c:379
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
**Symbols:**

```
ffffffff8100da60-ffffffff8100db5b: __conflict_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool __conflict_event(struct perf_event *a, struct perf_event *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100e430)
Location: arch/x86/events/intel/cqm.c:379
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
**Symbols:**

```
ffffffff8100e430-ffffffff8100e5a0: __conflict_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool __conflict_event(struct perf_event *a, struct perf_event *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/cqm.c (ffffffff8100e4f0)
Location: arch/x86/events/intel/cqm.c:360
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
**Symbols:**

```
ffffffff8100e4f0-ffffffff8100e660: __conflict_event (STB_LOCAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
