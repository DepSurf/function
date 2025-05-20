# Function: <code>rcu_sched_qs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_sched_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e6420)
Location: kernel/rcu/tree.c:247
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_check_callbacks
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_check_callbacks
```
**Symbols:**

```
ffffffff810e6420-ffffffff810e647e: rcu_sched_qs.part.62 (STB_LOCAL)
ffffffff810e7b40-ffffffff810e7b71: rcu_sched_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_sched_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ee131)
Location: kernel/rcu/tree.c:247
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_all_qs
  - kernel/rcu/tree.c:rcu_note_context_switch
Direct callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_all_qs
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff810ec560-ffffffff810ec594: rcu_sched_qs.part.65 (STB_LOCAL)
ffffffff810edd50-ffffffff810edd82: rcu_sched_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_sched_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5211)
Location: kernel/rcu/tree.c:248
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_all_qs
  - kernel/rcu/tree.c:rcu_note_context_switch
Direct callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_all_qs
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff810f2d70-ffffffff810f2dab: rcu_sched_qs.part.67 (STB_LOCAL)
ffffffff810f4e30-ffffffff810f4e62: rcu_sched_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_sched_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5fa0)
Location: kernel/rcu/tree.c:233
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_note_context_switch
Direct callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff810f37c0-ffffffff810f37fb: rcu_sched_qs.part.61 (STB_LOCAL)
ffffffff810f5b70-ffffffff810f5ba2: rcu_sched_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_sched_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ffe40)
Location: kernel/rcu/tree.c:230
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_note_context_switch
Direct callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff810fd210-ffffffff810fd24b: rcu_sched_qs.part.61 (STB_LOCAL)
ffffffff810ff970-ffffffff810ff9a2: rcu_sched_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_sched_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8110815e)
Location: kernel/rcu/tree.c:230
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_note_context_switch
Direct callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff81105620-ffffffff8110565b: rcu_sched_qs.part.61 (STB_LOCAL)
ffffffff81107ca0-ffffffff81107cd2: rcu_sched_qs (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
