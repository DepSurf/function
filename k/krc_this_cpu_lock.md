# Function: <code>krc_this_cpu_lock</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8113325b)
Location: kernel/rcu/tree.c:3193
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
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
In kernel/rcu/tree.c (ffffffff811332cc)
Location: kernel/rcu/tree.c:3216
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
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
In kernel/rcu/tree.c (ffffffff8115559c)
Location: kernel/rcu/tree.c:3174
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kfree_rcu_cpu *krc_this_cpu_lock(long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81177f60)
Location: kernel/rcu/tree.c:3268
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
```
**Symbols:**

```
ffffffff81177f60-ffffffff81177fa3: krc_this_cpu_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kfree_rcu_cpu *krc_this_cpu_lock(long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811af680)
Location: kernel/rcu/tree.c:2971
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
```
**Symbols:**

```
ffffffff811af680-ffffffff811af6d0: krc_this_cpu_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kfree_rcu_cpu *krc_this_cpu_lock(long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c16f0)
Location: kernel/rcu/tree.c:2879
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
```
**Symbols:**

```
ffffffff811c16f0-ffffffff811c1740: krc_this_cpu_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kfree_rcu_cpu *krc_this_cpu_lock(long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d1bf0)
Location: kernel/rcu/tree.c:2950
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
```
**Symbols:**

```
ffffffff811d1bf0-ffffffff811d1c40: krc_this_cpu_lock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
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
