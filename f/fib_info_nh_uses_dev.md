# Function: <code>fib_info_nh_uses_dev</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8195f9e0)
Location: net/ipv4/fib_frontend.c:318
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff8195f9e0-ffffffff8195fa4d: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819c4820)
Location: net/ipv4/fib_frontend.c:317
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff819c4820-ffffffff819c490b: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819fb3c0)
Location: net/ipv4/fib_frontend.c:318
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff819fb3c0-ffffffff819fb4ab: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81aea130)
Location: net/ipv4/fib_frontend.c:308
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
**Symbols:**

```
ffffffff81aea130-ffffffff81aea211: fib_info_nh_uses_dev.part.0 (STB_LOCAL)
ffffffff81aea220-ffffffff81aea2c4: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81af6f90)
Location: net/ipv4/fib_frontend.c:308
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
**Symbols:**

```
ffffffff81af6f90-ffffffff81af7071: fib_info_nh_uses_dev.part.0 (STB_LOCAL)
ffffffff81af7080-ffffffff81af7124: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ae2700)
Location: net/ipv4/fib_frontend.c:308
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
**Symbols:**

```
ffffffff81ae2700-ffffffff81ae2861: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:308
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fn_trie_dump_leaf
```
**Symbols:**

```
ffffffff81d3c69a-ffffffff81d3c70a: fib_info_nh_uses_dev.cold (STB_LOCAL)
ffffffff81ba1f10-ffffffff81ba20fd: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:309
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fn_trie_dump_leaf
```
**Symbols:**

```
ffffffff81f08edf-ffffffff81f08f4f: fib_info_nh_uses_dev.cold (STB_LOCAL)
ffffffff81d345e0-ffffffff81d347e1: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:309
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fn_trie_dump_leaf
```
**Symbols:**

```
ffffffff820b0838-ffffffff820b08a8: fib_info_nh_uses_dev.cold (STB_LOCAL)
ffffffff81efcad0-ffffffff81efccd1: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:309
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fn_trie_dump_leaf
```
**Symbols:**

```
ffffffff82131abf-ffffffff82131b2f: fib_info_nh_uses_dev.cold (STB_LOCAL)
ffffffff81f5c510-ffffffff81f5c711: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:309
Inline: True
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fn_trie_dump_leaf
```
**Symbols:**

```
ffffffff8221347d-ffffffff822134ed: fib_info_nh_uses_dev.cold (STB_LOCAL)
ffffffff82022a90-ffffffff82022c91: fib_info_nh_uses_dev (STB_GLOBAL)
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
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffff800010cb3260)
Location: net/ipv4/fib_frontend.c:318
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffff800010cb3260-ffff800010cb3380: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c0dbea0c)
Location: net/ipv4/fib_frontend.c:318
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
c0dbea0c-c0dbeb10: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c000000000dca540)
Location: net/ipv4/fib_frontend.c:318
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
c000000000dca540-c000000000dca6b4: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffe00080b51e)
Location: net/ipv4/fib_frontend.c:318
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffe00080b51e-ffffffe00080b5e2: fib_info_nh_uses_dev (STB_GLOBAL)
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
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8199b160)
Location: net/ipv4/fib_frontend.c:318
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff8199b160-ffffffff8199b24b: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81954c20)
Location: net/ipv4/fib_frontend.c:318
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff81954c20-ffffffff81954d0b: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a05a00)
Location: net/ipv4/fib_frontend.c:318
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff81a05a00-ffffffff81a05aeb: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool fib_info_nh_uses_dev(struct fib_info *fi, const struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a0ffd0)
Location: net/ipv4/fib_frontend.c:318
Inline: False
Direct callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/fib_trie.c:fib_table_dump
```
**Symbols:**

```
ffffffff81a0ffd0-ffffffff81a100bb: fib_info_nh_uses_dev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
