# Function: <code>alloc_clustermask</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106061d)
Location: arch/x86/kernel/apic/x2apic_cluster.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810636f4)
Location: arch/x86/kernel/apic/x2apic_cluster.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810693f4)
Location: arch/x86/kernel/apic/x2apic_cluster.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cc44)
Location: arch/x86/kernel/apic/x2apic_cluster.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e3a4)
Location: arch/x86/kernel/apic/x2apic_cluster.c:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int alloc_clustermask(unsigned int cpu, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075660)
Location: arch/x86/kernel/apic/x2apic_cluster.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
**Symbols:**

```
ffffffff81075660-ffffffff810756dc: alloc_clustermask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int alloc_clustermask(unsigned int cpu, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075ca0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:126
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
**Symbols:**

```
ffffffff81075ca0-ffffffff81075d1c: alloc_clustermask (STB_LOCAL)
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076774)
Location: arch/x86/kernel/apic/x2apic_cluster.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083e89)
Location: arch/x86/kernel/apic/x2apic_cluster.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81093ec9)
Location: arch/x86/kernel/apic/x2apic_cluster.c:132
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a9579)
Location: arch/x86/kernel/apic/x2apic_cluster.c:132
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int alloc_clustermask(unsigned int cpu, u32 cluster, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810acbf0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:134
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
**Symbols:**

```
ffffffff810acbf0-ffffffff810ace4c: alloc_clustermask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int alloc_clustermask(unsigned int cpu, u32 cluster, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b37e0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
```
**Symbols:**

```
ffffffff810b37e0-ffffffff810b3a6b: alloc_clustermask (STB_LOCAL)
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d344)
Location: arch/x86/kernel/apic/x2apic_cluster.c:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d6c4)
Location: arch/x86/kernel/apic/x2apic_cluster.c:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d7f4)
Location: arch/x86/kernel/apic/x2apic_cluster.c:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
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
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106fa74)
Location: arch/x86/kernel/apic/x2apic_cluster.c:124
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_prepare_cpu
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
