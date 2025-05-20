# Function: <code>_rcu_barrier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void _rcu_barrier(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e4ae0)
Location: kernel/rcu/tree.c:4021
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_barrier_bh
  - kernel/rcu/tree.c:rcu_barrier
```
**Symbols:**

```
ffffffff810e4ae0-ffffffff810e4c89: _rcu_barrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void _rcu_barrier(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eaed0)
Location: kernel/rcu/tree.c:3615
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_bh
```
**Symbols:**

```
ffffffff810eaed0-ffffffff810eb02c: _rcu_barrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void _rcu_barrier(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2880)
Location: kernel/rcu/tree.c:3613
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_bh
```
**Symbols:**

```
ffffffff810f2880-ffffffff810f29e8: _rcu_barrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _rcu_barrier(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f44c0)
Location: kernel/rcu/tree.c:3602
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_bh
```
**Symbols:**

```
ffffffff810f44c0-ffffffff810f4650: _rcu_barrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _rcu_barrier(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fe390)
Location: kernel/rcu/tree.c:3587
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_bh
```
**Symbols:**

```
ffffffff810fe390-ffffffff810fe51a: _rcu_barrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _rcu_barrier(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811052b0)
Location: kernel/rcu/tree.c:3376
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_bh
```
**Symbols:**

```
ffffffff811052b0-ffffffff81105446: _rcu_barrier (STB_LOCAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
</ul>
