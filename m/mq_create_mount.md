# Function: <code>mq_create_mount</code>

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
struct vfsmount *mq_create_mount(struct ipc_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81427ae0)
Location: ipc/mqueue.c:395
Inline: False
Direct callers:
  - ipc/mqueue.c:init_mqueue_fs
```
**Symbols:**

```
ffffffff81427ae0-ffffffff81427b8c: mq_create_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vfsmount *mq_create_mount(struct ipc_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81441810)
Location: ipc/mqueue.c:394
Inline: False
Direct callers:
  - ipc/mqueue.c:init_mqueue_fs
```
**Symbols:**

```
ffffffff81441810-ffffffff814418bc: mq_create_mount (STB_LOCAL)
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
In ipc/mqueue.c (ffffffff81494cbf)
Location: ipc/mqueue.c:454
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
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
In ipc/mqueue.c (ffffffff814b261f)
Location: ipc/mqueue.c:454
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
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
In ipc/mqueue.c (ffffffff814b848f)
Location: ipc/mqueue.c:454
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
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
In ipc/mqueue.c (ffffffff81510cbf)
Location: ipc/mqueue.c:457
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
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
In ipc/mqueue.c (ffffffff815a2ebf)
Location: ipc/mqueue.c:468
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
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
In ipc/mqueue.c (ffffffff8164ca1f)
Location: ipc/mqueue.c:468
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
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
In ipc/mqueue.c (ffffffff8168517f)
Location: ipc/mqueue.c:468
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
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
In ipc/mqueue.c (ffffffff816c159f)
Location: ipc/mqueue.c:468
Inline: True
Inline callers:
  - ipc/mqueue.c:mq_init_ns
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
struct vfsmount *mq_create_mount(struct ipc_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffff80001052a228)
Location: ipc/mqueue.c:394
Inline: False
Direct callers:
  - ipc/mqueue.c:init_mqueue_fs
```
**Symbols:**

```
ffff80001052a228-ffff80001052a330: mq_create_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vfsmount *mq_create_mount(struct ipc_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c06e45f4)
Location: ipc/mqueue.c:394
Inline: False
Direct callers:
  - ipc/mqueue.c:init_mqueue_fs
```
**Symbols:**

```
c06e45f4-c06e46d8: mq_create_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vfsmount *mq_create_mount(struct ipc_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c000000000678140)
Location: ipc/mqueue.c:394
Inline: False
Direct callers:
  - ipc/mqueue.c:init_mqueue_fs
```
**Symbols:**

```
c000000000678140-c00000000067826c: mq_create_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vfsmount *mq_create_mount(struct ipc_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffe00038c88a)
Location: ipc/mqueue.c:394
Inline: False
Direct callers:
  - ipc/mqueue.c:init_mqueue_fs
```
**Symbols:**

```
ffffffe00038c88a-ffffffe00038c93c: mq_create_mount (STB_LOCAL)
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
struct vfsmount *mq_create_mount(struct ipc_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81439df0)
Location: ipc/mqueue.c:394
Inline: False
Direct callers:
  - ipc/mqueue.c:init_mqueue_fs
```
**Symbols:**

```
ffffffff81439df0-ffffffff81439e9c: mq_create_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vfsmount *mq_create_mount(struct ipc_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8142a860)
Location: ipc/mqueue.c:394
Inline: False
Direct callers:
  - ipc/mqueue.c:init_mqueue_fs
```
**Symbols:**

```
ffffffff8142a860-ffffffff8142a90c: mq_create_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vfsmount *mq_create_mount(struct ipc_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81435f90)
Location: ipc/mqueue.c:394
Inline: False
Direct callers:
  - ipc/mqueue.c:init_mqueue_fs
```
**Symbols:**

```
ffffffff81435f90-ffffffff8143603c: mq_create_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vfsmount *mq_create_mount(struct ipc_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8144f460)
Location: ipc/mqueue.c:394
Inline: False
Direct callers:
  - ipc/mqueue.c:init_mqueue_fs
```
**Symbols:**

```
ffffffff8144f460-ffffffff8144f50c: mq_create_mount (STB_LOCAL)
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
