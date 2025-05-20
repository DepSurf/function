# Function: <code>inet_addr_is_any</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/utils.c (0)
Location: net/core/utils.c:406
Inline: True
```
**Symbols:**

```
ffffffff818ae150-ffffffff818ae166: inet_addr_is_any.cold.4 (STB_LOCAL)
ffffffff818ad8d0-ffffffff818ad958: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/utils.c (ffffffff818d1b78)
Location: net/core/utils.c:406
Inline: True
```
**Symbols:**

```
ffffffff818d23c0-ffffffff818d23d6: inet_addr_is_any.cold.4 (STB_LOCAL)
ffffffff818d1b30-ffffffff818d1bb8: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/utils.c (ffffffff8191ee08)
Location: net/core/utils.c:402
Inline: True
```
**Symbols:**

```
ffffffff8191f651-ffffffff8191f667: inet_addr_is_any.cold (STB_LOCAL)
ffffffff8191edc0-ffffffff8191ee47: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/utils.c (ffffffff81951048)
Location: net/core/utils.c:402
Inline: True
```
**Symbols:**

```
ffffffff81951891-ffffffff819518a7: inet_addr_is_any.cold (STB_LOCAL)
ffffffff81951000-ffffffff81951087: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/utils.c (ffffffff81a21eb8)
Location: net/core/utils.c:402
Inline: True
```
**Symbols:**

```
ffffffff81a22701-ffffffff81a22717: inet_addr_is_any.cold (STB_LOCAL)
ffffffff81a21e70-ffffffff81a21ef7: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/utils.c (ffffffff81a22238)
Location: net/core/utils.c:402
Inline: True
```
**Symbols:**

```
ffffffff81c3171a-ffffffff81c31730: inet_addr_is_any.cold (STB_LOCAL)
ffffffff81a221f0-ffffffff81a22277: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/utils.c (ffffffff81a09578)
Location: net/core/utils.c:402
Inline: True
```
**Symbols:**

```
ffffffff81c23a23-ffffffff81c23a39: inet_addr_is_any.cold (STB_LOCAL)
ffffffff81a09530-ffffffff81a095b7: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/utils.c (ffffffff81abba58)
Location: net/core/utils.c:402
Inline: True
```
**Symbols:**

```
ffffffff81d36f62-ffffffff81d36f78: inet_addr_is_any.cold (STB_LOCAL)
ffffffff81abba10-ffffffff81abba97: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/utils.c (0)
Location: net/core/utils.c:402
Inline: False
```
**Symbols:**

```
ffffffff81f038b4-ffffffff81f038c8: inet_addr_is_any.cold (STB_LOCAL)
ffffffff81c361c0-ffffffff81c36251: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81de9880)
Location: net/core/utils.c:402
Inline: False
```
**Symbols:**

```
ffffffff81de9880-ffffffff81de9919: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81e5b090)
Location: net/core/utils.c:402
Inline: False
```
**Symbols:**

```
ffffffff81e5b090-ffffffff81e5b129: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffff81f1a450)
Location: net/core/utils.c:402
Inline: False
```
**Symbols:**

```
ffffffff81f1a450-ffffffff81f1a4e9: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffff800010bf2cb0)
Location: net/core/utils.c:402
Inline: True
```
**Symbols:**

```
ffff800010bf2cb0-ffff800010bf2d70: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/utils.c (c0d0b4a0)
Location: net/core/utils.c:402
Inline: True
```
**Symbols:**

```
c0d0b4a0-c0d0b560: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/utils.c (c000000000cd7ab0)
Location: net/core/utils.c:402
Inline: True
```
**Symbols:**

```
c000000000cd7ab0-c000000000cd7b90: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/utils.c (ffffffe000774712)
Location: net/core/utils.c:402
Inline: True
```
**Symbols:**

```
ffffffe000774712-ffffffe00077478c: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/utils.c (ffffffff818f1018)
Location: net/core/utils.c:402
Inline: True
```
**Symbols:**

```
ffffffff818f1861-ffffffff818f1877: inet_addr_is_any.cold (STB_LOCAL)
ffffffff818f0fd0-ffffffff818f1057: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/utils.c (ffffffff818aae58)
Location: net/core/utils.c:402
Inline: True
```
**Symbols:**

```
ffffffff818ab6a1-ffffffff818ab6b7: inet_addr_is_any.cold (STB_LOCAL)
ffffffff818aae10-ffffffff818aae97: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/utils.c (ffffffff81942048)
Location: net/core/utils.c:402
Inline: True
```
**Symbols:**

```
ffffffff81942891-ffffffff819428a7: inet_addr_is_any.cold (STB_LOCAL)
ffffffff81942000-ffffffff81942087: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool inet_addr_is_any(struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/utils.c (ffffffff81963948)
Location: net/core/utils.c:402
Inline: True
```
**Symbols:**

```
ffffffff81964191-ffffffff819641a7: inet_addr_is_any.cold (STB_LOCAL)
ffffffff81963900-ffffffff81963987: inet_addr_is_any (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
