# Function: <code>rcutree_online_cpu</code>

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
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ee920)
Location: kernel/rcu/tree.c:3829
Inline: False
```
**Symbols:**

```
ffffffff810ee920-ffffffff810ee98c: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5a10)
Location: kernel/rcu/tree.c:3825
Inline: False
```
**Symbols:**

```
ffffffff810f5a10-ffffffff810f5a7c: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f67b0)
Location: kernel/rcu/tree.c:3823
Inline: False
```
**Symbols:**

```
ffffffff810f67b0-ffffffff810f6808: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811006e0)
Location: kernel/rcu/tree.c:3809
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811006e0-ffffffff811007c1: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81108530)
Location: kernel/rcu/tree.c:3594
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81108530-ffffffff81108612: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113a70)
Location: kernel/rcu/tree.c:3330
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81113a70-ffffffff81113b08: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111d660)
Location: kernel/rcu/tree.c:3017
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff8111d660-ffffffff8111d732: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81129c00)
Location: kernel/rcu/tree.c:3072
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81129c00-ffffffff81129cd2: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811380c0)
Location: kernel/rcu/tree.c:3787
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811380c0-ffffffff81138120: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133920)
Location: kernel/rcu/tree.c:4100
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81133920-ffffffff81133980: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81134500)
Location: kernel/rcu/tree.c:4212
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81134500-ffffffff81134601: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81156b90)
Location: kernel/rcu/tree.c:4183
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81156b90-ffffffff81156cec: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117fc70)
Location: kernel/rcu/tree.c:4310
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff8117fc70-ffffffff8117fcfe: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811ba140)
Location: kernel/rcu/tree.c:4204
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811ba140-ffffffff811ba1ce: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811ccaa0)
Location: kernel/rcu/tree.c:4362
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811ccaa0-ffffffff811ccb2e: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4481
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff821b4285-ffffffff821b4299: rcutree_online_cpu.cold (STB_LOCAL)
ffffffff811e1500-ffffffff811e15d8: rcutree_online_cpu (STB_GLOBAL)
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
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff800010191748)
Location: kernel/rcu/tree.c:3072
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffff800010191748-ffff8000101918cc: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03df3e4)
Location: kernel/rcu/tree.c:3072
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
c03df3e4-c03df50c: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001ecd90)
Location: kernel/rcu/tree.c:3072
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
c0000000001ecd90-c0000000001ecf1c: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000124ae2)
Location: kernel/rcu/tree.c:3072
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffe000124ae2-ffffffe000124bfa: rcutree_online_cpu (STB_GLOBAL)
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
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811221e0)
Location: kernel/rcu/tree.c:3072
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811221e0-ffffffff811222b2: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811148b0)
Location: kernel/rcu/tree.c:3072
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811148b0-ffffffff8111496c: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811200d0)
Location: kernel/rcu/tree.c:3072
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811200d0-ffffffff811201a2: rcutree_online_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rcutree_online_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112c3a0)
Location: kernel/rcu/tree.c:3072
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff8112c3a0-ffffffff8112c3e7: rcutree_online_cpu (STB_GLOBAL)
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
