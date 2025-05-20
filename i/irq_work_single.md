# Function: <code>irq_work_single</code>

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
void irq_work_single(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f74f0)
Location: kernel/irq_work.c:133
Inline: False
Direct callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff811f74f0-ffffffff811f7534: irq_work_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_work_single(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f6060)
Location: kernel/irq_work.c:133
Inline: False
Direct callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff811f6060-ffffffff811f609f: irq_work_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_work_single(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f6f50)
Location: kernel/irq_work.c:135
Inline: False
Direct callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
**Symbols:**

```
ffffffff811f6f50-ffffffff811f6f8f: irq_work_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_work_single(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81228520)
Location: kernel/irq_work.c:135
Inline: False
Direct callers:
  - kernel/smp.c:flush_smp_call_function_queue
  - kernel/irq_work.c:irq_work_run_list
```
**Symbols:**

```
ffffffff81228520-ffffffff8122855f: irq_work_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_work_single(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812695a0)
Location: kernel/irq_work.c:191
Inline: False
Direct callers:
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/irq_work.c:irq_work_run_list
```
**Symbols:**

```
ffffffff812695a0-ffffffff8126960f: irq_work_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_work_single(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812be440)
Location: kernel/irq_work.c:191
Inline: False
Direct callers:
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/irq_work.c:irq_work_run_list
```
**Symbols:**

```
ffffffff812be440-ffffffff812be4af: irq_work_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_work_single(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812e5080)
Location: kernel/irq_work.c:201
Inline: False
Direct callers:
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/irq_work.c:irq_work_run_list
```
**Symbols:**

```
ffffffff812e5080-ffffffff812e50ef: irq_work_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_work_single(void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81303130)
Location: kernel/irq_work.c:201
Inline: False
Direct callers:
  - kernel/smp.c:__flush_smp_call_function_queue
  - kernel/irq_work.c:irq_work_run_list
```
**Symbols:**

```
ffffffff81303130-ffffffff8130319f: irq_work_single (STB_GLOBAL)
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
