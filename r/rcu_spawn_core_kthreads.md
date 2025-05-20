# Function: <code>rcu_spawn_core_kthreads</code>

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
int rcu_spawn_core_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff828c6df2)
Location: kernel/rcu/tree.c:2419
Inline: False
```
**Symbols:**

```
ffffffff828c6df2-ffffffff828c6e70: rcu_spawn_core_kthreads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rcu_spawn_core_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff828cf407)
Location: kernel/rcu/tree.c:2483
Inline: False
```
**Symbols:**

```
ffffffff828cf407-ffffffff828cf485: rcu_spawn_core_kthreads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rcu_spawn_core_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff82cf0628)
Location: kernel/rcu/tree.c:2746
Inline: False
```
**Symbols:**

```
ffffffff82cf0628-ffffffff82cf06a6: rcu_spawn_core_kthreads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rcu_spawn_core_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff82fdcfe4)
Location: kernel/rcu/tree.c:2883
Inline: False
```
**Symbols:**

```
ffffffff82fdcfe4-ffffffff82fdd062: rcu_spawn_core_kthreads (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff831e8372)
Location: kernel/rcu/tree.c:2902
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
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
In kernel/rcu/tree.c (ffffffff832cc6c9)
Location: kernel/rcu/tree.c:2853
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
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
In kernel/rcu/tree.c (ffffffff8348007a)
Location: kernel/rcu/tree.c:2954
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2622
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:2515
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
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
In kernel/rcu/tree.c (ffffffff83903496)
Location: kernel/rcu/tree.c:2581
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
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
int rcu_spawn_core_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff800011446b28)
Location: kernel/rcu/tree.c:2483
Inline: False
```
**Symbols:**

```
ffff800011446b28-ffff800011446bdc: rcu_spawn_core_kthreads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rcu_spawn_core_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c15211b8)
Location: kernel/rcu/tree.c:2483
Inline: False
```
**Symbols:**

```
c15211b8-c1521288: rcu_spawn_core_kthreads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rcu_spawn_core_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c00000000136ba80)
Location: kernel/rcu/tree.c:2483
Inline: False
```
**Symbols:**

```
c00000000136ba80-c00000000136bb84: rcu_spawn_core_kthreads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rcu_spawn_core_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe0000085c6)
Location: kernel/rcu/tree.c:2483
Inline: False
```
**Symbols:**

```
ffffffe0000085c6-ffffffe000008686: rcu_spawn_core_kthreads (STB_LOCAL)
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
int rcu_spawn_core_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff828b80ff)
Location: kernel/rcu/tree.c:2483
Inline: False
```
**Symbols:**

```
ffffffff828b80ff-ffffffff828b817d: rcu_spawn_core_kthreads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rcu_spawn_core_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff828b0393)
Location: kernel/rcu/tree.c:2483
Inline: False
```
**Symbols:**

```
ffffffff828b0393-ffffffff828b0411: rcu_spawn_core_kthreads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rcu_spawn_core_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff828cb03b)
Location: kernel/rcu/tree.c:2483
Inline: False
```
**Symbols:**

```
ffffffff828cb03b-ffffffff828cb0b9: rcu_spawn_core_kthreads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rcu_spawn_core_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff828d0434)
Location: kernel/rcu/tree.c:2483
Inline: False
```
**Symbols:**

```
ffffffff828d0434-ffffffff828d04b2: rcu_spawn_core_kthreads (STB_LOCAL)
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
