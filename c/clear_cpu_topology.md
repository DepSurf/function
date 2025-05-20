# Function: <code>clear_cpu_topology</code>

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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void clear_cpu_topology(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/arch_topology.c (ffff80001091fff0)
Location: drivers/base/arch_topology.c:479
Inline: False
Direct callers:
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:reset_cpu_topology
```
**Symbols:**

```
ffff80001091fff0-ffff8000109200bc: clear_cpu_topology (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clear_cpu_topology(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/arch_topology.c (c0a05044)
Location: drivers/base/arch_topology.c:479
Inline: False
Direct callers:
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:reset_cpu_topology
```
**Symbols:**

```
c0a05044-c0a050ac: clear_cpu_topology (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void clear_cpu_topology(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/arch_topology.c (ffffffe00059ed34)
Location: drivers/base/arch_topology.c:479
Inline: False
Direct callers:
  - drivers/base/arch_topology.c:remove_cpu_topology
  - drivers/base/arch_topology.c:reset_cpu_topology
```
**Symbols:**

```
ffffffe00059ed34-ffffffe00059edae: clear_cpu_topology (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
