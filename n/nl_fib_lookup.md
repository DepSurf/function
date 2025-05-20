# Function: <code>nl_fib_lookup</code>

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
In net/ipv4/fib_frontend.c (ffffffff8179a0b4)
Location: net/ipv4/fib_frontend.c:1033
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
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
In net/ipv4/fib_frontend.c (ffffffff81807f85)
Location: net/ipv4/fib_frontend.c:1041
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
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
In net/ipv4/fib_frontend.c (ffffffff81839055)
Location: net/ipv4/fib_frontend.c:1041
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
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
In net/ipv4/fib_frontend.c (ffffffff8185a579)
Location: net/ipv4/fib_frontend.c:1059
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
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
In net/ipv4/fib_frontend.c (ffffffff818da499)
Location: net/ipv4/fib_frontend.c:1083
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
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
In net/ipv4/fib_frontend.c (ffffffff81930f44)
Location: net/ipv4/fib_frontend.c:1119
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
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
In net/ipv4/fib_frontend.c (ffffffff81960841)
Location: net/ipv4/fib_frontend.c:1229
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
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
In net/ipv4/fib_frontend.c (ffffffff819c4dc0)
Location: net/ipv4/fib_frontend.c:1325
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffff819c4dc0-ffffffff819c4ead: nl_fib_lookup.isra.0 (STB_LOCAL)
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
In net/ipv4/fib_frontend.c (ffffffff819fb960)
Location: net/ipv4/fib_frontend.c:1328
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffff819fb960-ffffffff819fba4d: nl_fib_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nl_fib_lookup(struct net *net, struct fib_result_nl *frn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81aea9c0)
Location: net/ipv4/fib_frontend.c:1319
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffff81aea9c0-ffffffff81aeaab4: nl_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nl_fib_lookup(struct net *net, struct fib_result_nl *frn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81af7860)
Location: net/ipv4/fib_frontend.c:1319
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffff81af7860-ffffffff81af7959: nl_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nl_fib_lookup(struct net *net, struct fib_result_nl *frn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ae2f80)
Location: net/ipv4/fib_frontend.c:1321
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffff81ae2f80-ffffffff81ae3079: nl_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void nl_fib_lookup(struct net *net, struct fib_result_nl *frn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ba25b0)
Location: net/ipv4/fib_frontend.c:1319
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffff81ba25b0-ffffffff81ba26a9: nl_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void nl_fib_lookup(struct net *net, struct fib_result_nl *frn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81d34c80)
Location: net/ipv4/fib_frontend.c:1333
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffff81d34c80-ffffffff81d34da8: nl_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nl_fib_lookup(struct net *net, struct fib_result_nl *frn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81efd190)
Location: net/ipv4/fib_frontend.c:1336
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffff81efd190-ffffffff81efd2b8: nl_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nl_fib_lookup(struct net *net, struct fib_result_nl *frn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81f5cbd0)
Location: net/ipv4/fib_frontend.c:1339
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffff81f5cbd0-ffffffff81f5ccff: nl_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nl_fib_lookup(struct net *net, struct fib_result_nl *frn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff82023150)
Location: net/ipv4/fib_frontend.c:1339
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffff82023150-ffffffff82023282: nl_fib_lookup (STB_LOCAL)
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
In net/ipv4/fib_frontend.c (ffff800010cb38b0)
Location: net/ipv4/fib_frontend.c:1328
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffff800010cb38b0-ffff800010cb39c0: nl_fib_lookup.isra.0 (STB_LOCAL)
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
In net/ipv4/fib_frontend.c (c0dbf2fc)
Location: net/ipv4/fib_frontend.c:1328
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nl_fib_lookup(struct net *net, struct fib_result_nl *frn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c000000000dca890)
Location: net/ipv4/fib_frontend.c:1328
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
c000000000dca890-c000000000dcaa0c: nl_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nl_fib_lookup(struct net *net, struct fib_result_nl *frn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffe00080b706)
Location: net/ipv4/fib_frontend.c:1328
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffe00080b706-ffffffe00080b7e8: nl_fib_lookup (STB_LOCAL)
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
In net/ipv4/fib_frontend.c (ffffffff8199b700)
Location: net/ipv4/fib_frontend.c:1328
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffff8199b700-ffffffff8199b7ed: nl_fib_lookup.isra.0 (STB_LOCAL)
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
In net/ipv4/fib_frontend.c (ffffffff819551c0)
Location: net/ipv4/fib_frontend.c:1328
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffff819551c0-ffffffff819552ad: nl_fib_lookup.isra.0 (STB_LOCAL)
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
In net/ipv4/fib_frontend.c (ffffffff81a05fa0)
Location: net/ipv4/fib_frontend.c:1328
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffff81a05fa0-ffffffff81a0608d: nl_fib_lookup.isra.0 (STB_LOCAL)
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
In net/ipv4/fib_frontend.c (ffffffff81a105e0)
Location: net/ipv4/fib_frontend.c:1328
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:nl_fib_input
```
**Symbols:**

```
ffffffff81a105e0-ffffffff81a106f1: nl_fib_lookup.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
