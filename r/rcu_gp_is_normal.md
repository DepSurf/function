# Function: <code>rcu_gp_is_normal</code>

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
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810e8f60)
Location: kernel/rcu/update.c:127
Inline: False
Direct callers:
  - kernel/rcu/srcu.c:synchronize_srcu
```
**Symbols:**

```
ffffffff810e8f60-ffffffff810e8f76: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810efe20)
Location: kernel/rcu/update.c:128
Inline: False
Direct callers:
  - kernel/rcu/srcu.c:synchronize_srcu
```
**Symbols:**

```
ffffffff810efe20-ffffffff810efe41: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810efde0)
Location: kernel/rcu/update.c:132
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff810efde0-ffffffff810efe01: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f9aa0)
Location: kernel/rcu/update.c:133
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff810f9aa0-ffffffff810f9ac1: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81102010)
Location: kernel/rcu/update.c:133
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff81102010-ffffffff81102031: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8110d9c0)
Location: kernel/rcu/update.c:133
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
```
**Symbols:**

```
ffffffff8110d9c0-ffffffff8110d9e1: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811170d0)
Location: kernel/rcu/update.c:121
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff811170d0-ffffffff811170f1: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811234a0)
Location: kernel/rcu/update.c:137
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff811234a0-ffffffff811234c1: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112faf0)
Location: kernel/rcu/update.c:150
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff8112faf0-ffffffff8112fb11: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112b950)
Location: kernel/rcu/update.c:138
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff8112b950-ffffffff8112b971: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112bc80)
Location: kernel/rcu/update.c:140
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff8112bc80-ffffffff8112bca1: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8114c830)
Location: kernel/rcu/update.c:140
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff8114c830-ffffffff8114c851: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81172330)
Location: kernel/rcu/update.c:140
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff81172330-ffffffff81172357: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811a8aa0)
Location: kernel/rcu/update.c:140
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff811a8aa0-ffffffff811a8ac7: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811ba7c0)
Location: kernel/rcu/update.c:140
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff811ba7c0-ffffffff811ba7e7: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811ca690)
Location: kernel/rcu/update.c:141
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff811ca690-ffffffff811ca6b7: rcu_gp_is_normal (STB_GLOBAL)
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
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffff8000101885b0)
Location: kernel/rcu/update.c:137
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffff8000101885b0-ffff8000101885e8: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (c03d6e80)
Location: kernel/rcu/update.c:137
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
c03d6e80-c03d6ec0: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (c0000000001e25b0)
Location: kernel/rcu/update.c:137
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
c0000000001e25b0-c0000000001e25f8: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffe00011dbae)
Location: kernel/rcu/update.c:137
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffe00011dbae-ffffffe00011dbe2: rcu_gp_is_normal (STB_GLOBAL)
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
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8111ba80)
Location: kernel/rcu/update.c:137
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff8111ba80-ffffffff8111baa1: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8110caf0)
Location: kernel/rcu/update.c:137
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff8110caf0-ffffffff8110cb11: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81119970)
Location: kernel/rcu/update.c:137
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff81119970-ffffffff81119991: rcu_gp_is_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rcu_gp_is_normal();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811250e0)
Location: kernel/rcu/update.c:137
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:synchronize_srcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff811250e0-ffffffff81125101: rcu_gp_is_normal (STB_GLOBAL)
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
