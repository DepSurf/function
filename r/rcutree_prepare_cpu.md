# Function: <code>rcutree_prepare_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81fa8959)
Location: kernel/rcu/tree.c:3809
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff810ee8d0-ffffffff810ee920: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81fe47e1)
Location: kernel/rcu/tree.c:3805
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff810f59c0-ffffffff810f5a10: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff820c5463)
Location: kernel/rcu/tree.c:3796
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff810f6760-ffffffff810f67b0: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff826cdb05)
Location: kernel/rcu/tree.c:3782
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81100690-ffffffff811006e0: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff826f7c7b)
Location: kernel/rcu/tree.c:3567
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811084e0-ffffffff81108530: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113970)
Location: kernel/rcu/tree.c:3276
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81113970-ffffffff81113a67: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111d560)
Location: kernel/rcu/tree.c:2963
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff8111d560-ffffffff8111d657: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81129af0)
Location: kernel/rcu/tree.c:3018
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81129af0-ffffffff81129bf2: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81137fb0)
Location: kernel/rcu/tree.c:3733
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81137fb0-ffffffff811380b1: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811337f0)
Location: kernel/rcu/tree.c:4044
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811337f0-ffffffff8113391e: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811343d0)
Location: kernel/rcu/tree.c:4152
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811343d0-ffffffff81134500: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81156a30)
Location: kernel/rcu/tree.c:4123
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81156a30-ffffffff81156b82: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117fb20)
Location: kernel/rcu/tree.c:4251
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff8117fb20-ffffffff8117fc61: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b9fc0)
Location: kernel/rcu/tree.c:4144
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811b9fc0-ffffffff811ba130: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811cc8b0)
Location: kernel/rcu/tree.c:4293
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811cc8b0-ffffffff811cca1c: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811e1300)
Location: kernel/rcu/tree.c:4412
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811e1300-ffffffff811e147b: rcutree_prepare_cpu (STB_GLOBAL)
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
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff800010191578)
Location: kernel/rcu/tree.c:3018
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffff800010191578-ffff800010191748: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03df2c8)
Location: kernel/rcu/tree.c:3018
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
c03df2c8-c03df3e4: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001ecbe0)
Location: kernel/rcu/tree.c:3018
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
c0000000001ecbe0-c0000000001ecd90: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe0001249b6)
Location: kernel/rcu/tree.c:3018
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffe0001249b6-ffffffe000124ae2: rcutree_prepare_cpu (STB_GLOBAL)
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
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811220d0)
Location: kernel/rcu/tree.c:3018
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811220d0-ffffffff811221d2: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81114780)
Location: kernel/rcu/tree.c:3018
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81114780-ffffffff811148a6: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111ffc0)
Location: kernel/rcu/tree.c:3018
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff8111ffc0-ffffffff811200c2: rcutree_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rcutree_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112c2a0)
Location: kernel/rcu/tree.c:3018
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff8112c2a0-ffffffff8112c39f: rcutree_prepare_cpu (STB_GLOBAL)
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
