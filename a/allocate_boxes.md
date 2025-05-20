# Function: <code>allocate_boxes</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101562b)
Location: arch/x86/events/intel/uncore.c:1117
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81013b1f)
Location: arch/x86/events/intel/uncore.c:1117
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81014453)
Location: arch/x86/events/intel/uncore.c:1125
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81014fe3)
Location: arch/x86/events/intel/uncore.c:1186
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810155e3)
Location: arch/x86/events/intel/uncore.c:1187
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int allocate_boxes(struct intel_uncore_type **types, unsigned int die, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81015fb0)
Location: arch/x86/events/intel/uncore.c:1208
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
**Symbols:**

```
ffffffff81015fb0-ffffffff810161b9: allocate_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int allocate_boxes(struct intel_uncore_type **types, unsigned int die, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016960)
Location: arch/x86/events/intel/uncore.c:1240
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
**Symbols:**

```
ffffffff81016960-ffffffff81016b69: allocate_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int allocate_boxes(struct intel_uncore_type **types, unsigned int die, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810180f0)
Location: arch/x86/events/intel/uncore.c:1240
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
**Symbols:**

```
ffffffff810180f0-ffffffff810182fc: allocate_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int allocate_boxes(struct intel_uncore_type **types, unsigned int die, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810187c0)
Location: arch/x86/events/intel/uncore.c:1400
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
**Symbols:**

```
ffffffff810187c0-ffffffff810189cf: allocate_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int allocate_boxes(struct intel_uncore_type **types, unsigned int die, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81019ae0)
Location: arch/x86/events/intel/uncore.c:1511
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
**Symbols:**

```
ffffffff81019ae0-ffffffff81019cee: allocate_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int allocate_boxes(struct intel_uncore_type **types, unsigned int die, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101c230)
Location: arch/x86/events/intel/uncore.c:1518
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
**Symbols:**

```
ffffffff8101c230-ffffffff8101c465: allocate_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int allocate_boxes(struct intel_uncore_type **types, unsigned int die, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101ea00)
Location: arch/x86/events/intel/uncore.c:1518
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
**Symbols:**

```
ffffffff8101ea00-ffffffff8101ec41: allocate_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int allocate_boxes(struct intel_uncore_type **types, unsigned int die, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81022f90)
Location: arch/x86/events/intel/uncore.c:1518
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
**Symbols:**

```
ffffffff81022f90-ffffffff810231d1: allocate_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int allocate_boxes(struct intel_uncore_type **types, unsigned int die, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81022c90)
Location: arch/x86/events/intel/uncore.c:1539
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
**Symbols:**

```
ffffffff81022c90-ffffffff81022ed1: allocate_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int allocate_boxes(struct intel_uncore_type **types, unsigned int die, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81028dc0)
Location: arch/x86/events/intel/uncore.c:1539
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
**Symbols:**

```
ffffffff81028dc0-ffffffff81029001: allocate_boxes (STB_LOCAL)
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
int allocate_boxes(struct intel_uncore_type **types, unsigned int die, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016960)
Location: arch/x86/events/intel/uncore.c:1240
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
**Symbols:**

```
ffffffff81016960-ffffffff81016b69: allocate_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int allocate_boxes(struct intel_uncore_type **types, unsigned int die, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81015d90)
Location: arch/x86/events/intel/uncore.c:1240
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
**Symbols:**

```
ffffffff81015d90-ffffffff81015f99: allocate_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int allocate_boxes(struct intel_uncore_type **types, unsigned int die, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016920)
Location: arch/x86/events/intel/uncore.c:1240
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
**Symbols:**

```
ffffffff81016920-ffffffff81016b29: allocate_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int allocate_boxes(struct intel_uncore_type **types, unsigned int die, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016b60)
Location: arch/x86/events/intel/uncore.c:1240
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_online
```
**Symbols:**

```
ffffffff81016b60-ffffffff81016d69: allocate_boxes (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
