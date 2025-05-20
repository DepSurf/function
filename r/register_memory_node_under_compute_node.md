# Function: <code>register_memory_node_under_compute_node</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816f7e50)
Location: drivers/base/node.c:687
Inline: False
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff816f7e50-ffffffff816f7f5a: register_memory_node_under_compute_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8171c2b0)
Location: drivers/base/node.c:693
Inline: False
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff8171c2b0-ffffffff8171c3ba: register_memory_node_under_compute_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff817d83d0)
Location: drivers/base/node.c:696
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff817d83d0-ffffffff817d84d2: register_memory_node_under_compute_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff817ecd90)
Location: drivers/base/node.c:707
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff817ecd90-ffffffff817ecf15: register_memory_node_under_compute_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff817d15e0)
Location: drivers/base/node.c:710
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff817d15e0-ffffffff817d16e1: register_memory_node_under_compute_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8185c120)
Location: drivers/base/node.c:729
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff8185c120-ffffffff8185c27d: register_memory_node_under_compute_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff819a3250)
Location: drivers/base/node.c:733
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff819a3250-ffffffff819a33cf: register_memory_node_under_compute_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81b151b0)
Location: drivers/base/node.c:681
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff81b151b0-ffffffff81b1532f: register_memory_node_under_compute_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81b63f20)
Location: drivers/base/node.c:691
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff81b63f20-ffffffff81b6409f: register_memory_node_under_compute_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81bb7ac0)
Location: drivers/base/node.c:690
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:__hmat_register_target_initiators
```
**Symbols:**

```
ffffffff81bb7ac0-ffffffff81bb7c3f: register_memory_node_under_compute_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffff80001090fe50)
Location: drivers/base/node.c:693
Inline: False
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffff80001090fe50-ffff80001090ffd0: register_memory_node_under_compute_node (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (c0000000009b0990)
Location: drivers/base/node.c:693
Inline: False
```
**Symbols:**

```
c0000000009b0990-c0000000009b0b74: register_memory_node_under_compute_node (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816e25e0)
Location: drivers/base/node.c:693
Inline: False
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff816e25e0-ffffffff816e26ea: register_memory_node_under_compute_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816bcc20)
Location: drivers/base/node.c:693
Inline: False
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff816bcc20-ffffffff816bcd2a: register_memory_node_under_compute_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8170f7e0)
Location: drivers/base/node.c:693
Inline: False
```
**Symbols:**

```
ffffffff8170f7e0-ffffffff8170f8ea: register_memory_node_under_compute_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_memory_node_under_compute_node(unsigned int mem_nid, unsigned int cpu_nid, unsigned int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8172a8d0)
Location: drivers/base/node.c:693
Inline: False
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff8172a8d0-ffffffff8172a9da: register_memory_node_under_compute_node (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
