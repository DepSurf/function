# Function: <code>update_cpu_capacity</code>

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
In kernel/sched/fair.c (ffffffff810bc6e0)
Location: kernel/sched/fair.c:6121
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
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
In kernel/sched/fair.c (ffffffff810bfea0)
Location: kernel/sched/fair.c:6582
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
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
In kernel/sched/fair.c (ffffffff810c5e6a)
Location: kernel/sched/fair.c:7127
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
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
In kernel/sched/fair.c (ffffffff810bfa33)
Location: kernel/sched/fair.c:7123
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
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
In kernel/sched/fair.c (ffffffff810c71f1)
Location: kernel/sched/fair.c:7572
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
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
In kernel/sched/fair.c (ffffffff810cf0f8)
Location: kernel/sched/fair.c:7886
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
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
In kernel/sched/fair.c (ffffffff810d8687)
Location: kernel/sched/fair.c:7890
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
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
In kernel/sched/fair.c (ffffffff810df94d)
Location: kernel/sched/fair.c:7785
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
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
In kernel/sched/fair.c (ffffffff810e9fed)
Location: kernel/sched/fair.c:7770
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f463a)
Location: kernel/sched/fair.c:8082
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_cpu_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9950)
Location: kernel/sched/fair.c:8158
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_group_capacity
```
**Symbols:**

```
ffffffff810e9950-ffffffff810e9a17: update_cpu_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f4bb5)
Location: kernel/sched/fair.c:8270
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110e5d6)
Location: kernel/sched/fair.c:8408
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8112a34f)
Location: kernel/sched/fair.c:8382
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_cpu_capacity(struct sched_domain *sd, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811444c0)
Location: kernel/sched/fair.c:8839
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_group_capacity
```
**Symbols:**

```
ffffffff811444c0-ffffffff81144678: update_cpu_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81163e66)
Location: kernel/sched/fair.c:9197
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81170b76)
Location: kernel/sched/fair.c:9521
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff80001014a1ec)
Location: kernel/sched/fair.c:7770
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/topology.c (c0319a94)
Location: arch/arm/kernel/topology.c:164
Inline: True
Inline callers:
  - arch/arm/kernel/topology.c:store_cpu_topology
```
```
In kernel/sched/fair.c (c0397e30)
Location: kernel/sched/fair.c:7770
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019c350)
Location: kernel/sched/fair.c:7770
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f3d3a)
Location: kernel/sched/fair.c:7770
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
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
In kernel/sched/fair.c (ffffffff810e414d)
Location: kernel/sched/fair.c:7770
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d32fd)
Location: kernel/sched/fair.c:7770
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e051d)
Location: kernel/sched/fair.c:7770
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
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
In kernel/sched/fair.c (ffffffff810ec09d)
Location: kernel/sched/fair.c:7770
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
