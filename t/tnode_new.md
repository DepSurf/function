# Function: <code>tnode_new</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8179fb50)
Location: net/ipv4/fib_trie.c:350
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:fib_insert_alias
```
**Symbols:**

```
ffffffff8179fb50-ffffffff8179fc46: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8180d710)
Location: net/ipv4/fib_trie.c:348
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff8180d710-ffffffff8180d813: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8183eb80)
Location: net/ipv4/fib_trie.c:475
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff8183eb80-ffffffff8183ec83: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff818600d0)
Location: net/ipv4/fib_trie.c:380
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff818600d0-ffffffff818601d2: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff818e0150)
Location: net/ipv4/fib_trie.c:381
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff818e0150-ffffffff818e0252: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81936990)
Location: net/ipv4/fib_trie.c:382
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81936990-ffffffff81936aa0: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81966380)
Location: net/ipv4/fib_trie.c:382
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81966380-ffffffff81966490: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819cc420)
Location: net/ipv4/fib_trie.c:378
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff819cc420-ffffffff819cc52a: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a02f80)
Location: net/ipv4/fib_trie.c:378
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81a02f80-ffffffff81a0308a: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af16c0)
Location: net/ipv4/fib_trie.c:375
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_node
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
```
**Symbols:**

```
ffffffff81af16c0-ffffffff81af17d6: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81afe740)
Location: net/ipv4/fib_trie.c:375
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_node
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
```
**Symbols:**

```
ffffffff81afe740-ffffffff81afe856: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81ae9c40)
Location: net/ipv4/fib_trie.c:375
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
```
**Symbols:**

```
ffffffff81ae9c40-ffffffff81ae9d53: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:375
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
```
**Symbols:**

```
ffffffff81ba9dd0-ffffffff81ba9efc: tnode_new (STB_LOCAL)
ffffffff81d3d358-ffffffff81d3d3ae: tnode_new.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:376
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
```
**Symbols:**

```
ffffffff81d3c990-ffffffff81d3cadd: tnode_new (STB_LOCAL)
ffffffff81f09b6f-ffffffff81f09be1: tnode_new.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:376
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
```
**Symbols:**

```
ffffffff81f05440-ffffffff81f05590: tnode_new (STB_LOCAL)
ffffffff820b144a-ffffffff820b14bc: tnode_new.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:376
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
```
**Symbols:**

```
ffffffff81f64e90-ffffffff81f64fe0: tnode_new (STB_LOCAL)
ffffffff821326ca-ffffffff82132720: tnode_new.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:377
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:halve
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
  - net/ipv4/fib_trie.c:inflate
```
**Symbols:**

```
ffffffff8202b460-ffffffff8202b5b0: tnode_new (STB_LOCAL)
ffffffff82214088-ffffffff822140de: tnode_new.cold (STB_LOCAL)
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
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffff800010cbb980)
Location: net/ipv4/fib_trie.c:378
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffff800010cbb980-ffff800010cbba98: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c0dc71b0)
Location: net/ipv4/fib_trie.c:378
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
c0dc71b0-c0dc72b0: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c000000000dd5360)
Location: net/ipv4/fib_trie.c:378
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
c000000000dd5360-c000000000dd54ec: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffe000811f8a)
Location: net/ipv4/fib_trie.c:378
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffe000811f8a-ffffffe000812082: tnode_new (STB_LOCAL)
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
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819a2d20)
Location: net/ipv4/fib_trie.c:378
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff819a2d20-ffffffff819a2e2a: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8195c7e0)
Location: net/ipv4/fib_trie.c:378
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff8195c7e0-ffffffff8195c8ea: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a0d5c0)
Location: net/ipv4/fib_trie.c:378
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81a0d5c0-ffffffff81a0d6ca: tnode_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct key_vector *tnode_new(t_key key, int pos, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a17dd0)
Location: net/ipv4/fib_trie.c:378
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81a17dd0-ffffffff81a17eda: tnode_new (STB_LOCAL)
```
</details>
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
