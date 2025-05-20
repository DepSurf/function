# Function: <code>score_nearby_nodes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b3d50)
Location: kernel/sched/fair.c:946
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_fault
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810b3d50-ffffffff810b3e8f: score_nearby_nodes.part.71 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810be682)
Location: kernel/sched/fair.c:1093
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810b67c0-ffffffff810b68f7: score_nearby_nodes.part.73 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bdfc4)
Location: kernel/sched/fair.c:1217
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810bbf50-ffffffff810bc091: score_nearby_nodes.part.80 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b8f26)
Location: kernel/sched/fair.c:1214
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810b6b10-ffffffff810b6c52: score_nearby_nodes.part.87 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c0d86)
Location: kernel/sched/fair.c:1255
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810bdd00-ffffffff810bde42: score_nearby_nodes.part.90 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c638f)
Location: kernel/sched/fair.c:1283
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810c5b80-ffffffff810c5cbf: score_nearby_nodes.part.94 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d66bf)
Location: kernel/sched/fair.c:1279
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810ce4d0-ffffffff810ce60f: score_nearby_nodes.part.98 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d8884)
Location: kernel/sched/fair.c:1341
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810d68b0-ffffffff810d69f9: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e3184)
Location: kernel/sched/fair.c:1299
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810e0f30-ffffffff810e1079: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ec74f)
Location: kernel/sched/fair.c:1310
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff810e9480-ffffffff810e95be: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ea25f)
Location: kernel/sched/fair.c:1317
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff810e7230-ffffffff810e736e: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ebb4e)
Location: kernel/sched/fair.c:1314
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff810e9120-ffffffff810e925e: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff811036ce)
Location: kernel/sched/fair.c:1303
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff811009b0-ffffffff81100aee: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff81125502)
Location: kernel/sched/fair.c:1305
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
Direct callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff8111bb00-ffffffff8111bcc4: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff8114e78b)
Location: kernel/sched/fair.c:1344
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
Direct callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff81143560-ffffffff81143716: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115fd7b)
Location: kernel/sched/fair.c:1361
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
Direct callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff811533e0-ffffffff81153596: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116a1ab)
Location: kernel/sched/fair.c:1602
Inline: True
Inline callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
Direct callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff8115f480-ffffffff8115f636: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffff800010147f2c)
Location: kernel/sched/fair.c:1299
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffff800010140f38-ffff8000101410c0: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (c0000000001940f4)
Location: kernel/sched/fair.c:1299
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
c000000000191df0-c000000000192038: score_nearby_nodes.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dd334)
Location: kernel/sched/fair.c:1299
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810db0e0-ffffffff810db229: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cc344)
Location: kernel/sched/fair.c:1299
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810ca0f0-ffffffff810ca239: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d96b4)
Location: kernel/sched/fair.c:1299
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810d7460-ffffffff810d75a9: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e50e4)
Location: kernel/sched/fair.c:1299
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810e2e10-ffffffff810e2f59: score_nearby_nodes.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
