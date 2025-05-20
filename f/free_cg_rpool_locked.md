# Function: <code>free_cg_rpool_locked</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_cg_rpool_locked(struct rdmacg_resource_pool *rpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8112ba10)
Location: kernel/cgroup/rdma.c:106
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
**Symbols:**

```
ffffffff8112ba10-ffffffff8112ba62: free_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_cg_rpool_locked(struct rdmacg_resource_pool *rpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff81138810)
Location: kernel/cgroup/rdma.c:106
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
**Symbols:**

```
ffffffff81138810-ffffffff81138862: free_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_cg_rpool_locked(struct rdmacg_resource_pool *rpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff81147130)
Location: kernel/cgroup/rdma.c:106
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
**Symbols:**

```
ffffffff81147130-ffffffff81147182: free_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_cg_rpool_locked(struct rdmacg_resource_pool *rpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff81152cb0)
Location: kernel/cgroup/rdma.c:106
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
**Symbols:**

```
ffffffff81152cb0-ffffffff81152d02: free_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_cg_rpool_locked(struct rdmacg_resource_pool *rpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8115f300)
Location: kernel/cgroup/rdma.c:103
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
**Symbols:**

```
ffffffff8115f300-ffffffff8115f352: free_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_cg_rpool_locked(struct rdmacg_resource_pool *rpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8116af60)
Location: kernel/cgroup/rdma.c:103
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
**Symbols:**

```
ffffffff8116af60-ffffffff8116afb2: free_cg_rpool_locked (STB_LOCAL)
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
In kernel/cgroup/rdma.c (ffffffff8117cfdf)
Location: kernel/cgroup/rdma.c:103
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff81179e3f)
Location: kernel/cgroup/rdma.c:103
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
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
In kernel/cgroup/rdma.c (ffffffff8117a9ab)
Location: kernel/cgroup/rdma.c:103
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
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
In kernel/cgroup/rdma.c (ffffffff811a233b)
Location: kernel/cgroup/rdma.c:103
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
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
In kernel/cgroup/rdma.c (ffffffff811d2d60)
Location: kernel/cgroup/rdma.c:103
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
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
In kernel/cgroup/rdma.c (ffffffff81216c78)
Location: kernel/cgroup/rdma.c:103
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
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
In kernel/cgroup/rdma.c (ffffffff8122c5c4)
Location: kernel/cgroup/rdma.c:103
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
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
In kernel/cgroup/rdma.c (ffffffff81244653)
Location: kernel/cgroup/rdma.c:103
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
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
void free_cg_rpool_locked(struct rdmacg_resource_pool *rpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffff8000101df140)
Location: kernel/cgroup/rdma.c:103
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
**Symbols:**

```
ffff8000101df140-ffff8000101df19c: free_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_cg_rpool_locked(struct rdmacg_resource_pool *rpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (c0420ac8)
Location: kernel/cgroup/rdma.c:103
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
**Symbols:**

```
c0420ac8-c0420b1c: free_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_cg_rpool_locked(struct rdmacg_resource_pool *rpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (c00000000024d3c0)
Location: kernel/cgroup/rdma.c:103
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
**Symbols:**

```
c00000000024d3c0-c00000000024d44c: free_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_cg_rpool_locked(struct rdmacg_resource_pool *rpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffe000156244)
Location: kernel/cgroup/rdma.c:103
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
**Symbols:**

```
ffffffe000156244-ffffffe00015628e: free_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void free_cg_rpool_locked(struct rdmacg_resource_pool *rpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff81163580)
Location: kernel/cgroup/rdma.c:103
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
**Symbols:**

```
ffffffff81163580-ffffffff811635d2: free_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_cg_rpool_locked(struct rdmacg_resource_pool *rpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff811567d0)
Location: kernel/cgroup/rdma.c:103
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
**Symbols:**

```
ffffffff811567d0-ffffffff81156822: free_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_cg_rpool_locked(struct rdmacg_resource_pool *rpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff81161350)
Location: kernel/cgroup/rdma.c:103
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
**Symbols:**

```
ffffffff81161350-ffffffff811613a2: free_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_cg_rpool_locked(struct rdmacg_resource_pool *rpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8116e7a0)
Location: kernel/cgroup/rdma.c:103
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_unregister_device
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
**Symbols:**

```
ffffffff8116e7a0-ffffffff8116e7f2: free_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
