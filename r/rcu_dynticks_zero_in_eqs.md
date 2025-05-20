# Function: <code>rcu_dynticks_zero_in_eqs</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rcu_dynticks_zero_in_eqs(int cpu, int *vp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81137cb0)
Location: kernel/rcu/tree.c:353
Inline: False
```
**Symbols:**

```
ffffffff81137cb0-ffffffff81137cf1: rcu_dynticks_zero_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rcu_dynticks_zero_in_eqs(int cpu, int *vp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133550)
Location: kernel/rcu/tree.c:366
Inline: False
```
**Symbols:**

```
ffffffff81133550-ffffffff81133591: rcu_dynticks_zero_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rcu_dynticks_zero_in_eqs(int cpu, int *vp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81134070)
Location: kernel/rcu/tree.c:372
Inline: False
```
**Symbols:**

```
ffffffff81134070-ffffffff811340b1: rcu_dynticks_zero_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool rcu_dynticks_zero_in_eqs(int cpu, int *vp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81156640)
Location: kernel/rcu/tree.c:374
Inline: False
```
**Symbols:**

```
ffffffff81156640-ffffffff811566a7: rcu_dynticks_zero_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool rcu_dynticks_zero_in_eqs(int cpu, int *vp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117f640)
Location: kernel/rcu/tree.c:385
Inline: False
```
**Symbols:**

```
ffffffff8117f640-ffffffff8117f6b0: rcu_dynticks_zero_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool rcu_dynticks_zero_in_eqs(int cpu, int *vp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b98d0)
Location: kernel/rcu/tree.c:318
Inline: False
```
**Symbols:**

```
ffffffff811b98d0-ffffffff811b9963: rcu_dynticks_zero_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool rcu_dynticks_zero_in_eqs(int cpu, int *vp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811cc1e0)
Location: kernel/rcu/tree.c:299
Inline: False
```
**Symbols:**

```
ffffffff811cc1e0-ffffffff811cc273: rcu_dynticks_zero_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool rcu_dynticks_zero_in_eqs(int cpu, int *vp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811e0d50)
Location: kernel/rcu/tree.c:300
Inline: False
```
**Symbols:**

```
ffffffff811e0d50-ffffffff811e0de4: rcu_dynticks_zero_in_eqs (STB_GLOBAL)
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
