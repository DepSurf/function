# Function: <code>check_init_srcu_struct</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void check_init_srcu_struct(struct srcu_struct *sp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f1450)
Location: kernel/rcu/srcutree.c:204
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff810f1450-ffffffff810f14b5: check_init_srcu_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void check_init_srcu_struct(struct srcu_struct *sp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fb1b0)
Location: kernel/rcu/srcutree.c:205
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff810fb1b0-ffffffff810fb21a: check_init_srcu_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void check_init_srcu_struct(struct srcu_struct *sp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81103640)
Location: kernel/rcu/srcutree.c:232
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81103640-ffffffff811036aa: check_init_srcu_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff828ae3c2)
Location: kernel/rcu/srcutree.c:238
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8110eff0-ffffffff8110f03b: check_init_srcu_struct.part.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff828c6da2)
Location: kernel/rcu/srcutree.c:227
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff811187a0-ffffffff811187ef: check_init_srcu_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff828cf3b7)
Location: kernel/rcu/srcutree.c:227
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81124b70-ffffffff81124bbf: check_init_srcu_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void check_init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811322d0)
Location: kernel/rcu/srcutree.c:240
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff811322d0-ffffffff8113232b: check_init_srcu_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void check_init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112daa0)
Location: kernel/rcu/srcutree.c:229
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_might_be_idle
```
**Symbols:**

```
ffffffff8112daa0-ffffffff8112dafb: check_init_srcu_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void check_init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e0d0)
Location: kernel/rcu/srcutree.c:232
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff8112e0d0-ffffffff8112e12b: check_init_srcu_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void check_init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114f580)
Location: kernel/rcu/srcutree.c:224
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff8114f580-ffffffff8114f5db: check_init_srcu_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void check_init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811768a0)
Location: kernel/rcu/srcutree.c:392
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__synchronize_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff811768a0-ffffffff81176908: check_init_srcu_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void check_init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ae2f0)
Location: kernel/rcu/srcutree.c:392
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__synchronize_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff811ae2f0-ffffffff811ae358: check_init_srcu_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void check_init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811c02d0)
Location: kernel/rcu/srcutree.c:401
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__synchronize_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff811c02d0-ffffffff811c0342: check_init_srcu_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void check_init_srcu_struct(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811d0770)
Location: kernel/rcu/srcutree.c:403
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__synchronize_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff811d0770-ffffffff811d07e2: check_init_srcu_struct (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffff800011446ad0)
Location: kernel/rcu/srcutree.c:227
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffff80001018a3f0-ffff80001018a4a4: check_init_srcu_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (c1521174)
Location: kernel/rcu/srcutree.c:227
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
c03d8b34-c03d8b84: check_init_srcu_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (c00000000136ba14)
Location: kernel/rcu/srcutree.c:227
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
c0000000001e4a40-c0000000001e4ac8: check_init_srcu_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00000857e)
Location: kernel/rcu/srcutree.c:227
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffe00011f1da-ffffffe00011f230: check_init_srcu_struct.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff828b80af)
Location: kernel/rcu/srcutree.c:227
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8111d150-ffffffff8111d19f: check_init_srcu_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff828b032f)
Location: kernel/rcu/srcutree.c:227
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8110e210-ffffffff8110e25f: check_init_srcu_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff828cafeb)
Location: kernel/rcu/srcutree.c:227
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8111b040-ffffffff8111b08f: check_init_srcu_struct.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff828d03e4)
Location: kernel/rcu/srcutree.c:227
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
Direct callers:
  - kernel/rcu/srcutree.c:srcu_init
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81126920-ffffffff8112696f: check_init_srcu_struct.part.0 (STB_LOCAL)
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
