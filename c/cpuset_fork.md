# Function: <code>cpuset_fork</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff81123000)
Location: kernel/cpuset.c:2088
Inline: False
```
**Symbols:**

```
ffffffff81123000-ffffffff8112304e: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8112aeb0)
Location: kernel/cpuset.c:2088
Inline: False
```
**Symbols:**

```
ffffffff8112aeb0-ffffffff8112afe3: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8112c990)
Location: kernel/cgroup/cpuset.c:2077
Inline: True
```
**Symbols:**

```
ffffffff8112c990-ffffffff8112cac3: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81139840)
Location: kernel/cgroup/cpuset.c:2087
Inline: True
```
**Symbols:**

```
ffffffff81139840-ffffffff81139973: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81148020)
Location: kernel/cgroup/cpuset.c:2088
Inline: True
```
**Symbols:**

```
ffffffff81148020-ffffffff81148152: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81153c00)
Location: kernel/cgroup/cpuset.c:2813
Inline: True
```
**Symbols:**

```
ffffffff81153c00-ffffffff81153d32: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81160160)
Location: kernel/cgroup/cpuset.c:2774
Inline: True
```
**Symbols:**

```
ffffffff81160160-ffffffff81160292: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116be30)
Location: kernel/cgroup/cpuset.c:2860
Inline: True
```
**Symbols:**

```
ffffffff8116be30-ffffffff8116bf62: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117d850)
Location: kernel/cgroup/cpuset.c:2862
Inline: True
```
**Symbols:**

```
ffffffff8117d850-ffffffff8117d982: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117a6a0)
Location: kernel/cgroup/cpuset.c:2885
Inline: True
```
**Symbols:**

```
ffffffff8117a6a0-ffffffff8117a7d2: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117b220)
Location: kernel/cgroup/cpuset.c:2885
Inline: True
```
**Symbols:**

```
ffffffff8117b220-ffffffff8117b352: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811a2d70)
Location: kernel/cgroup/cpuset.c:2942
Inline: True
```
**Symbols:**

```
ffffffff811a2d70-ffffffff811a2ea2: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811d3c60)
Location: kernel/cgroup/cpuset.c:2982
Inline: True
```
**Symbols:**

```
ffffffff811d3c60-ffffffff811d3daa: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81217a00)
Location: kernel/cgroup/cpuset.c:3255
Inline: True
```
**Symbols:**

```
ffffffff81217a00-ffffffff81217b4a: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81230490)
Location: kernel/cgroup/cpuset.c:3422
Inline: False
```
**Symbols:**

```
ffffffff81230490-ffffffff8123068d: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81248f20)
Location: kernel/cgroup/cpuset.c:4247
Inline: False
```
**Symbols:**

```
ffffffff81248f20-ffffffff8124911d: cpuset_fork (STB_LOCAL)
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
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e0310)
Location: kernel/cgroup/cpuset.c:2860
Inline: True
```
**Symbols:**

```
ffff8000101e0310-ffff8000101e0364: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c0421c90)
Location: kernel/cgroup/cpuset.c:2860
Inline: True
```
**Symbols:**

```
c0421c90-c0421cf8: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c00000000024ef60)
Location: kernel/cgroup/cpuset.c:2860
Inline: True
```
**Symbols:**

```
c00000000024ef60-c00000000024efec: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe0001571c2)
Location: kernel/cgroup/cpuset.c:2860
Inline: True
```
**Symbols:**

```
ffffffe0001571c2-ffffffe00015721a: cpuset_fork (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81164450)
Location: kernel/cgroup/cpuset.c:2860
Inline: True
```
**Symbols:**

```
ffffffff81164450-ffffffff81164582: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811576a0)
Location: kernel/cgroup/cpuset.c:2860
Inline: True
```
**Symbols:**

```
ffffffff811576a0-ffffffff811577d2: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81162220)
Location: kernel/cgroup/cpuset.c:2860
Inline: True
```
**Symbols:**

```
ffffffff81162220-ffffffff81162352: cpuset_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cpuset_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116f7a0)
Location: kernel/cgroup/cpuset.c:2860
Inline: True
```
**Symbols:**

```
ffffffff8116f7a0-ffffffff8116f8d2: cpuset_fork (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
