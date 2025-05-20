# Function: <code>__smp_call_single_queue</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __smp_call_single_queue(int cpu, struct llist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115f39b)
Location: kernel/smp.c:136
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff8115fc40-ffffffff8115fc80: __smp_call_single_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __smp_call_single_queue(int cpu, struct llist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115b33b)
Location: kernel/smp.c:257
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff8115bbe0-ffffffff8115bc20: __smp_call_single_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __smp_call_single_queue(int cpu, struct llist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115ca27)
Location: kernel/smp.c:469
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff8115ce00-ffffffff8115ce40: __smp_call_single_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __smp_call_single_queue(int cpu, struct llist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81181bdf)
Location: kernel/smp.c:469
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811820c0-ffffffff81182139: __smp_call_single_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __smp_call_single_queue(int cpu, struct llist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811b82fe)
Location: kernel/smp.c:472
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811b8860-ffffffff811b88f1: __smp_call_single_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __smp_call_single_queue(int cpu, struct llist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811f960e)
Location: kernel/smp.c:471
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
Direct callers:
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff811f9c10-ffffffff811f9ca1: __smp_call_single_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __smp_call_single_queue(int cpu, struct llist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8120eaa0)
Location: kernel/smp.c:334
Inline: False
Direct callers:
  - kernel/smp.c:generic_exec_single
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff8120eaa0-ffffffff8120ec1e: __smp_call_single_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __smp_call_single_queue(int cpu, struct llist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81226240)
Location: kernel/smp.c:349
Inline: False
Direct callers:
  - kernel/smp.c:generic_exec_single
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffff81226240-ffffffff812263be: __smp_call_single_queue (STB_GLOBAL)
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
