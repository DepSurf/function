# Function: <code>inflate</code>

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
In net/ipv4/fib_trie.c (ffffffff8179fdd2)
Location: net/ipv4/fib_trie.c:510
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
In net/ipv4/fib_trie.c (ffffffff8180d984)
Location: net/ipv4/fib_trie.c:508
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
In net/ipv4/fib_trie.c (ffffffff8183eef5)
Location: net/ipv4/fib_trie.c:635
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
In net/ipv4/fib_trie.c (ffffffff8186046a)
Location: net/ipv4/fib_trie.c:540
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
In net/ipv4/fib_trie.c (ffffffff818e04ea)
Location: net/ipv4/fib_trie.c:541
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
In net/ipv4/fib_trie.c (ffffffff81936bac)
Location: net/ipv4/fib_trie.c:542
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
In net/ipv4/fib_trie.c (ffffffff8196659c)
Location: net/ipv4/fib_trie.c:542
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
In net/ipv4/fib_trie.c (ffffffff819cc643)
Location: net/ipv4/fib_trie.c:538
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
In net/ipv4/fib_trie.c (ffffffff81a031a3)
Location: net/ipv4/fib_trie.c:538
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
struct key_vector *inflate(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af2740)
Location: net/ipv4/fib_trie.c:535
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81af2740-ffffffff81af29d5: inflate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct key_vector *inflate(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aff650)
Location: net/ipv4/fib_trie.c:535
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81aff650-ffffffff81aff8e5: inflate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct key_vector *inflate(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aeace0)
Location: net/ipv4/fib_trie.c:535
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81aeace0-ffffffff81aeaf75: inflate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct key_vector *inflate(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:535
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81baab10-ffffffff81baadcd: inflate (STB_LOCAL)
ffffffff81d3d657-ffffffff81d3d6da: inflate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct key_vector *inflate(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:536
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81d3d800-ffffffff81d3db39: inflate (STB_LOCAL)
ffffffff81f09ee8-ffffffff81f09f96: inflate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct key_vector *inflate(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:536
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81f06ab0-ffffffff81f06de9: inflate (STB_LOCAL)
ffffffff820b17ef-ffffffff820b189d: inflate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct key_vector *inflate(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:536
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff81f66570-ffffffff81f668a2: inflate (STB_LOCAL)
ffffffff82132a4f-ffffffff82132afd: inflate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct key_vector *inflate(struct trie *t, struct key_vector *oldtnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (0)
Location: net/ipv4/fib_trie.c:537
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:resize
```
**Symbols:**

```
ffffffff8202cb40-ffffffff8202ce72: inflate (STB_LOCAL)
ffffffff8221440d-ffffffff822144bb: inflate.cold (STB_LOCAL)
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
In net/ipv4/fib_trie.c (ffff800010cbbc08)
Location: net/ipv4/fib_trie.c:538
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
In net/ipv4/fib_trie.c (c0dc7408)
Location: net/ipv4/fib_trie.c:538
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
In net/ipv4/fib_trie.c (c000000000dd5798)
Location: net/ipv4/fib_trie.c:538
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
In net/ipv4/fib_trie.c (ffffffe000812228)
Location: net/ipv4/fib_trie.c:538
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
In net/ipv4/fib_trie.c (ffffffff819a2f43)
Location: net/ipv4/fib_trie.c:538
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
In net/ipv4/fib_trie.c (ffffffff8195ca03)
Location: net/ipv4/fib_trie.c:538
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
In net/ipv4/fib_trie.c (ffffffff81a0d7e3)
Location: net/ipv4/fib_trie.c:538
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
In net/ipv4/fib_trie.c (ffffffff81a17ff3)
Location: net/ipv4/fib_trie.c:538
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
