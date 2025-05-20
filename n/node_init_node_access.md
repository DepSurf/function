# Function: <code>node_init_node_access</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816f7890)
Location: drivers/base/node.c:120
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
```
**Symbols:**

```
ffffffff816f7890-ffffffff816f799c: node_init_node_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8171bcf0)
Location: drivers/base/node.c:120
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
```
**Symbols:**

```
ffffffff8171bcf0-ffffffff8171bdfc: node_init_node_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff817d7e40)
Location: drivers/base/node.c:120
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
```
**Symbols:**

```
ffffffff817d7e40-ffffffff817d7f4c: node_init_node_access (STB_LOCAL)
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
In drivers/base/node.c (ffffffff817ecddd)
Location: drivers/base/node.c:124
Inline: True
Inline callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
```
**Symbols:**

```
ffffffff817ec850-ffffffff817ec91f: node_init_node_access.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff817d1030)
Location: drivers/base/node.c:124
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
```
**Symbols:**

```
ffffffff817d1030-ffffffff817d113c: node_init_node_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8185b9f0)
Location: drivers/base/node.c:128
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
```
**Symbols:**

```
ffffffff8185b9f0-ffffffff8185bafc: node_init_node_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff819a2a40)
Location: drivers/base/node.c:128
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
```
**Symbols:**

```
ffffffff819a2a40-ffffffff819a2b69: node_init_node_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81b14ac0)
Location: drivers/base/node.c:129
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
```
**Symbols:**

```
ffffffff81b14ac0-ffffffff81b14be9: node_init_node_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81b63830)
Location: drivers/base/node.c:129
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
```
**Symbols:**

```
ffffffff81b63830-ffffffff81b63959: node_init_node_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81bb7340)
Location: drivers/base/node.c:128
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
```
**Symbols:**

```
ffffffff81bb7340-ffffffff81bb7498: node_init_node_access (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffff80001090f710)
Location: drivers/base/node.c:120
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
```
**Symbols:**

```
ffff80001090f710-ffff80001090f838: node_init_node_access (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (c0000000009b05d0)
Location: drivers/base/node.c:120
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
c0000000009b05d0-c0000000009b075c: node_init_node_access (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816e2020)
Location: drivers/base/node.c:120
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
```
**Symbols:**

```
ffffffff816e2020-ffffffff816e212c: node_init_node_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816bc660)
Location: drivers/base/node.c:120
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
```
**Symbols:**

```
ffffffff816bc660-ffffffff816bc76c: node_init_node_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8170f550)
Location: drivers/base/node.c:120
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
```
**Symbols:**

```
ffffffff8170f550-ffffffff8170f65c: node_init_node_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct node_access_nodes *node_init_node_access(struct node *node, unsigned int access);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8172a310)
Location: drivers/base/node.c:120
Inline: True
Direct callers:
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_set_perf_attrs
```
**Symbols:**

```
ffffffff8172a310-ffffffff8172a41c: node_init_node_access (STB_LOCAL)
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
