# Function: <code>net_drop_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81710bd0)
Location: net/core/net_namespace.c:344
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81710bd0-ffffffff81710c07: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81778500)
Location: net/core/net_namespace.c:344
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81778500-ffffffff81778537: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817a5520)
Location: net/core/net_namespace.c:358
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff817a5520-ffffffff817a5557: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817c3780)
Location: net/core/net_namespace.c:380
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff817c3780-ffffffff817c37b7: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8183d240)
Location: net/core/net_namespace.c:381
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff8183d240-ffffffff8183d280: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81887af0)
Location: net/core/net_namespace.c:403
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81887af0-ffffffff81887b2f: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818a8600)
Location: net/core/net_namespace.c:403
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff818a8600-ffffffff818a863f: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818f3bd0)
Location: net/core/net_namespace.c:441
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff818f3bd0-ffffffff818f3c12: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81925b80)
Location: net/core/net_namespace.c:442
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81925b80-ffffffff81925bc2: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f8667)
Location: net/core/net_namespace.c:448
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff819f8110-ffffffff819f8167: net_drop_ns.part.0 (STB_LOCAL)
ffffffff819f9e40-ffffffff819f9e56: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f80f6)
Location: net/core/net_namespace.c:449
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff819f7ee0-ffffffff819f7f37: net_drop_ns.part.0 (STB_LOCAL)
ffffffff819f99c0-ffffffff819f99d6: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net_namespace.c (ffffffff819de65b)
Location: net/core/net_namespace.c:440
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff819dde30-ffffffff819dde87: net_drop_ns.part.0 (STB_LOCAL)
ffffffff819dfba0-ffffffff819dfbb6: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81a8ffa0)
Location: net/core/net_namespace.c:437
Inline: False
```
**Symbols:**

```
ffffffff81a8ffa0-ffffffff81a8ffb6: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81c05db0)
Location: net/core/net_namespace.c:436
Inline: False
```
**Symbols:**

```
ffffffff81c05db0-ffffffff81c05dd2: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81db56a0)
Location: net/core/net_namespace.c:453
Inline: False
```
**Symbols:**

```
ffffffff81db56a0-ffffffff81db56c2: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81e25c70)
Location: net/core/net_namespace.c:454
Inline: False
```
**Symbols:**

```
ffffffff81e25c70-ffffffff81e25c92: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81ee3bd0)
Location: net/core/net_namespace.c:458
Inline: False
```
**Symbols:**

```
ffffffff81ee3bd0-ffffffff81ee3bf2: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net_namespace.c (ffff800010bc1138)
Location: net/core/net_namespace.c:442
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffff800010bc04a8-ffff800010bc0500: net_drop_ns.part.0 (STB_LOCAL)
ffff800010bc1ef8-ffff800010bc1f28: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net_namespace.c (c0cdc230)
Location: net/core/net_namespace.c:442
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
c0cdbf10-c0cdbf54: net_drop_ns.part.0 (STB_LOCAL)
c0cdd404-c0cdd428: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c000000000c9b7d0)
Location: net/core/net_namespace.c:442
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
c000000000c9b7d0-c000000000c9b85c: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffe00074de6a)
Location: net/core/net_namespace.c:442
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffe00074ef1a-ffffffe00074ef5e: net_drop_ns (STB_GLOBAL)
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
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818c5b80)
Location: net/core/net_namespace.c:442
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff818c5b80-ffffffff818c5bc2: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8187fac0)
Location: net/core/net_namespace.c:442
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff8187fac0-ffffffff8187fb02: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81916b80)
Location: net/core/net_namespace.c:442
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81916b80-ffffffff81916bc2: net_drop_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void net_drop_ns(void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81937d90)
Location: net/core/net_namespace.c:442
Inline: False
Direct callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81937d90-ffffffff81937dd2: net_drop_ns (STB_GLOBAL)
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
