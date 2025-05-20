# Function: <code>rcu_bh_qs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void rcu_bh_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e7b80)
Location: kernel/rcu/tree.c:269
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff810e7b80-ffffffff810e7ba0: rcu_bh_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_bh_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ee107)
Location: kernel/rcu/tree.c:262
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff810edd90-ffffffff810eddb0: rcu_bh_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void rcu_bh_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f51e7)
Location: kernel/rcu/tree.c:263
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff810f4e70-ffffffff810f4e90: rcu_bh_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void rcu_bh_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5f67)
Location: kernel/rcu/tree.c:249
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff810f5bb0-ffffffff810f5bd0: rcu_bh_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_bh_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ffe07)
Location: kernel/rcu/tree.c:246
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff810ff9b0-ffffffff810ff9d0: rcu_bh_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rcu_bh_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81108126)
Location: kernel/rcu/tree.c:246
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
Direct callers:
  - kernel/softirq.c:__do_softirq
```
**Symbols:**

```
ffffffff81107ce0-ffffffff81107d00: rcu_bh_qs (STB_GLOBAL)
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
