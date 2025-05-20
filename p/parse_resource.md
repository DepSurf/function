# Function: <code>parse_resource</code>

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
Location: kernel/cgroup/rdma.c:362
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
Location: kernel/cgroup/rdma.c:362
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
In kernel/cgroup/rdma.c (ffffffff811476b9)
Location: kernel/cgroup/rdma.c:362
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
In kernel/cgroup/rdma.c (ffffffff811533e9)
Location: kernel/cgroup/rdma.c:362
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
In kernel/cgroup/rdma.c (ffffffff8115f779)
Location: kernel/cgroup/rdma.c:356
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
In kernel/cgroup/rdma.c (ffffffff8116b3d9)
Location: kernel/cgroup/rdma.c:356
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_resource(char *c, int *intval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8117ca40)
Location: kernel/cgroup/rdma.c:356
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
**Symbols:**

```
ffffffff8117ca40-ffffffff8117cb37: parse_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_resource(char *c, int *intval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff811798a0)
Location: kernel/cgroup/rdma.c:356
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
**Symbols:**

```
ffffffff811798a0-ffffffff81179997: parse_resource (STB_LOCAL)
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
In kernel/cgroup/rdma.c (ffffffff8117a46b)
Location: kernel/cgroup/rdma.c:356
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
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
In kernel/cgroup/rdma.c (ffffffff811a1d94)
Location: kernel/cgroup/rdma.c:356
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
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
In kernel/cgroup/rdma.c (ffffffff811d27d6)
Location: kernel/cgroup/rdma.c:356
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
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
In kernel/cgroup/rdma.c (ffffffff812166d6)
Location: kernel/cgroup/rdma.c:356
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_parse_limits
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_resource(char *c, int *intval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff8122bf90)
Location: kernel/cgroup/rdma.c:358
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
**Symbols:**

```
ffffffff8122bf90-ffffffff8122c09b: parse_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_resource(char *c, int *intval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rdma.c (ffffffff81243fc0)
Location: kernel/cgroup/rdma.c:358
Inline: False
Direct callers:
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
```
**Symbols:**

```
ffffffff81243fc0-ffffffff812440cb: parse_resource (STB_LOCAL)
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
In kernel/cgroup/rdma.c (ffff8000101df680)
Location: kernel/cgroup/rdma.c:356
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
In kernel/cgroup/rdma.c (c0420fb0)
Location: kernel/cgroup/rdma.c:356
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
In kernel/cgroup/rdma.c (c00000000024da8c)
Location: kernel/cgroup/rdma.c:356
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
Location: kernel/cgroup/rdma.c:356
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
In kernel/cgroup/rdma.c (ffffffff811639f9)
Location: kernel/cgroup/rdma.c:356
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
In kernel/cgroup/rdma.c (ffffffff81156c49)
Location: kernel/cgroup/rdma.c:356
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
In kernel/cgroup/rdma.c (ffffffff811617c9)
Location: kernel/cgroup/rdma.c:356
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
In kernel/cgroup/rdma.c (ffffffff8116ec19)
Location: kernel/cgroup/rdma.c:356
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
