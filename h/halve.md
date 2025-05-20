# Function: <code>halve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff817a0088)
Location: net/ipv4/fib_trie.c:606
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8180dc7a)
Location: net/ipv4/fib_trie.c:604
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8183eda9)
Location: net/ipv4/fib_trie.c:731
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff818602ed)
Location: net/ipv4/fib_trie.c:636
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff818e036d)
Location: net/ipv4/fib_trie.c:637
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81936e39)
Location: net/ipv4/fib_trie.c:638
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81966829)
Location: net/ipv4/fib_trie.c:638
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819cc904)
Location: net/ipv4/fib_trie.c:634
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a03464)
Location: net/ipv4/fib_trie.c:634
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct key_vector *halve(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af29e0)
Location: net/ipv4/fib_trie.c:631
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81af29e0-ffffffff81af2b44: halve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct key_vector *halve(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aff8f0)
Location: net/ipv4/fib_trie.c:631
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81aff8f0-ffffffff81affa54: halve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct key_vector *halve(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aeaf80)
Location: net/ipv4/fib_trie.c:631
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81aeaf80-ffffffff81aeb0e1: halve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct key_vector *halve(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:631
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81baadd0-ffffffff81baaf38: halve (STB_LOCAL)
ffffffff81d3d6da-ffffffff81d3d6f9: halve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct key_vector *halve(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:632
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81d3db40-ffffffff81d3dcc1: halve (STB_LOCAL)
ffffffff81f09f96-ffffffff81f09fb5: halve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct key_vector *halve(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:632
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81f06e00-ffffffff81f06f81: halve (STB_LOCAL)
ffffffff820b189d-ffffffff820b18bc: halve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct key_vector *halve(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:632
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81f668c0-ffffffff81f66a41: halve (STB_LOCAL)
ffffffff82132afd-ffffffff82132b1c: halve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct key_vector *halve(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:633
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff8202ce90-ffffffff8202d011: halve (STB_LOCAL)
ffffffff822144bb-ffffffff822144da: halve.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffff800010cbbf74)
Location: net/ipv4/fib_trie.c:634
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c0dc7758)
Location: net/ipv4/fib_trie.c:634
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (c000000000dd5aac)
Location: net/ipv4/fib_trie.c:634
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffe000812146)
Location: net/ipv4/fib_trie.c:634
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819a3204)
Location: net/ipv4/fib_trie.c:634
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8195ccc4)
Location: net/ipv4/fib_trie.c:634
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a0daa4)
Location: net/ipv4/fib_trie.c:634
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81a182b4)
Location: net/ipv4/fib_trie.c:634
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:resize
```
</details>
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
