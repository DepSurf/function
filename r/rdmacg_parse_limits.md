# Function: <code>rdmacg_parse_limits</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8112c09f)
Location: kernel/cgroup/rdma.c:398
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (ffffffff81138eaf)
Location: kernel/cgroup/rdma.c:398
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (ffffffff8114767d)
Location: kernel/cgroup/rdma.c:395
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (ffffffff811533ad)
Location: kernel/cgroup/rdma.c:395
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (ffffffff8115f73d)
Location: kernel/cgroup/rdma.c:389
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (ffffffff8116b39d)
Location: kernel/cgroup/rdma.c:389
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (ffffffff8117ce3b)
Location: kernel/cgroup/rdma.c:389
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (ffffffff81179c9b)
Location: kernel/cgroup/rdma.c:389
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rdmacg_parse_limits(char *options, int *new_limits, long unsigned int *enables);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8117a400)
Location: kernel/cgroup/rdma.c:389
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
**Symbols:**

```
ffffffff8117a400-ffffffff8117a529: rdmacg_parse_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rdmacg_parse_limits(char *options, int *new_limits, long unsigned int *enables);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/rdma.c (0)
Location: kernel/cgroup/rdma.c:389
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
**Symbols:**

```
ffffffff811a1d20-ffffffff811a1e62: rdmacg_parse_limits (STB_LOCAL)
ffffffff81cb322f-ffffffff81cb3245: rdmacg_parse_limits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rdmacg_parse_limits(char *options, int *new_limits, long unsigned int *enables);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/rdma.c (0)
Location: kernel/cgroup/rdma.c:389
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
**Symbols:**

```
ffffffff811d2750-ffffffff811d28b0: rdmacg_parse_limits (STB_LOCAL)
ffffffff81e64034-ffffffff81e6404a: rdmacg_parse_limits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rdmacg_parse_limits(char *options, int *new_limits, long unsigned int *enables);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/rdma.c (0)
Location: kernel/cgroup/rdma.c:389
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
**Symbols:**

```
ffffffff81216650-ffffffff812167b0: rdmacg_parse_limits (STB_LOCAL)
ffffffff8205c42a-ffffffff8205c440: rdmacg_parse_limits.cold (STB_LOCAL)
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
In kernel/cgroup/rdma.c (ffffffff8122c3e8)
Location: kernel/cgroup/rdma.c:391
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (ffffffff81244477)
Location: kernel/cgroup/rdma.c:391
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (ffff8000101df648)
Location: kernel/cgroup/rdma.c:389
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (c0420f74)
Location: kernel/cgroup/rdma.c:389
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (c00000000024d9fc)
Location: kernel/cgroup/rdma.c:389
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (ffffffe0001566da)
Location: kernel/cgroup/rdma.c:389
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (ffffffff811639bd)
Location: kernel/cgroup/rdma.c:389
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (ffffffff81156c0d)
Location: kernel/cgroup/rdma.c:389
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (ffffffff8116178d)
Location: kernel/cgroup/rdma.c:389
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
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
In kernel/cgroup/rdma.c (ffffffff8116ebdd)
Location: kernel/cgroup/rdma.c:389
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
