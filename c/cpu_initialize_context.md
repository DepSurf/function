# Function: <code>cpu_initialize_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102b74f)
Location: arch/x86/xen/smp.c:382
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102aa5f)
Location: arch/x86/xen/smp.c:389
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102abf1)
Location: arch/x86/xen/smp.c:389
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
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
In arch/x86/xen/smp_pv.c (ffffffff810294b1)
Location: arch/x86/xen/smp_pv.c:273
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
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
In arch/x86/xen/smp_pv.c (ffffffff810296d1)
Location: arch/x86/xen/smp_pv.c:275
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
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
In arch/x86/xen/smp_pv.c (ffffffff8102a151)
Location: arch/x86/xen/smp_pv.c:280
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
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
In arch/x86/xen/smp_pv.c (ffffffff8102a7a1)
Location: arch/x86/xen/smp_pv.c:282
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102c5b8)
Location: arch/x86/xen/smp_pv.c:284
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102ce88)
Location: arch/x86/xen/smp_pv.c:284
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpu_initialize_context(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102ee20)
Location: arch/x86/xen/smp_pv.c:287
Inline: False
```
**Symbols:**

```
ffffffff8102ee20-ffffffff8102f221: cpu_initialize_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpu_initialize_context(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102fc30)
Location: arch/x86/xen/smp_pv.c:277
Inline: False
```
**Symbols:**

```
ffffffff8102fc30-ffffffff81030031: cpu_initialize_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpu_initialize_context(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81030740)
Location: arch/x86/xen/smp_pv.c:277
Inline: False
```
**Symbols:**

```
ffffffff81030740-ffffffff81030b54: cpu_initialize_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpu_initialize_context(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81035610)
Location: arch/x86/xen/smp_pv.c:259
Inline: False
```
**Symbols:**

```
ffffffff81035610-ffffffff81035a8b: cpu_initialize_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpu_initialize_context(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8103b440)
Location: arch/x86/xen/smp_pv.c:251
Inline: False
```
**Symbols:**

```
ffffffff8103b440-ffffffff8103b896: cpu_initialize_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpu_initialize_context(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81043c10)
Location: arch/x86/xen/smp_pv.c:251
Inline: False
```
**Symbols:**

```
ffffffff81043c10-ffffffff81044066: cpu_initialize_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpu_initialize_context(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81043d30)
Location: arch/x86/xen/smp_pv.c:252
Inline: False
```
**Symbols:**

```
ffffffff81043d30-ffffffff8104416e: cpu_initialize_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpu_initialize_context(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8104a230)
Location: arch/x86/xen/smp_pv.c:253
Inline: False
```
**Symbols:**

```
ffffffff8104a230-ffffffff8104a69d: cpu_initialize_context (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102cfe8)
Location: arch/x86/xen/smp_pv.c:284
Inline: True
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102ce48)
Location: arch/x86/xen/smp_pv.c:284
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102dc38)
Location: arch/x86/xen/smp_pv.c:284
Inline: True
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
