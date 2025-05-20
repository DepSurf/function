# Function: <code>get_cg_rpool_locked</code>

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
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8112bd90)
Location: kernel/cgroup/rdma.c:132
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff8112bd90-ffffffff8112be87: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff81138ba0)
Location: kernel/cgroup/rdma.c:132
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff81138ba0-ffffffff81138c97: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff811474e0)
Location: kernel/cgroup/rdma.c:132
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff811474e0-ffffffff811475d7: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff81152da0)
Location: kernel/cgroup/rdma.c:132
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff81152da0-ffffffff81152e97: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8115f3f0)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff8115f3f0-ffffffff8115f4d4: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8116b050)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff8116b050-ffffffff8116b134: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8117ccb0)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff8117ccb0-ffffffff8117cd94: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff81179b10)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff81179b10-ffffffff81179bf4: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8117a6a0)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff8117a6a0-ffffffff8117a784: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff811a1ff0)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff811a1ff0-ffffffff811a20d4: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff811d2a30)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff811d2a30-ffffffff811d2b38: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff81216950)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff81216950-ffffffff81216a58: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8122c240)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff8122c240-ffffffff8122c348: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff81244270)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff81244270-ffffffff812443a7: get_cg_rpool_locked (STB_LOCAL)
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
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffff8000101df260)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffff8000101df260-ffff8000101df374: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (c0420bb4)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
c0420bb4-c0420cb0: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (c00000000024d7c0)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
c00000000024d7c0-c00000000024d928: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffe00015639a)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffe00015639a-ffffffe00015647e: get_cg_rpool_locked (STB_LOCAL)
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
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff81163670)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff81163670-ffffffff81163754: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff811568c0)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff811568c0-ffffffff811569a4: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff81161440)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff81161440-ffffffff81161524: get_cg_rpool_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rdmacg_resource_pool *get_cg_rpool_locked(struct rdma_cgroup *cg, struct rdmacg_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8116e890)
Location: kernel/cgroup/rdma.c:129
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:rdmacg_try_charge
```
**Symbols:**

```
ffffffff8116e890-ffffffff8116e974: get_cg_rpool_locked (STB_LOCAL)
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
