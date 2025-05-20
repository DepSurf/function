# Function: <code>hk_should_isolate</code>

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
bool hk_should_isolate(struct irq_data *data, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff8112cbc0)
Location: kernel/irq/cpuhotplug.c:175
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8112cbc0-ffffffff8112cc24: hk_should_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool hk_should_isolate(struct irq_data *data, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff811285f0)
Location: kernel/irq/cpuhotplug.c:175
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff811285f0-ffffffff81128654: hk_should_isolate (STB_LOCAL)
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
In kernel/irq/cpuhotplug.c (ffffffff811289e1)
Location: kernel/irq/cpuhotplug.c:175
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In kernel/irq/cpuhotplug.c (ffffffff81148fc1)
Location: kernel/irq/cpuhotplug.c:175
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In kernel/irq/cpuhotplug.c (ffffffff8116db41)
Location: kernel/irq/cpuhotplug.c:175
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff811a2d71)
Location: kernel/irq/cpuhotplug.c:175
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In kernel/irq/cpuhotplug.c (ffffffff811b4c71)
Location: kernel/irq/cpuhotplug.c:175
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
In kernel/irq/cpuhotplug.c (ffffffff811c4af1)
Location: kernel/irq/cpuhotplug.c:175
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
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
</ul>
