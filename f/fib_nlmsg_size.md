# Function: <code>fib_nlmsg_size</code>

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
In net/ipv4/fib_semantics.c (ffffffff8179dd31)
Location: net/ipv4/fib_semantics.c:358
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (ffffffff8180b871)
Location: net/ipv4/fib_semantics.c:358
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (ffffffff8183c991)
Location: net/ipv4/fib_semantics.c:359
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (ffffffff8185e0e3)
Location: net/ipv4/fib_semantics.c:364
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (ffffffff818de123)
Location: net/ipv4/fib_semantics.c:365
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (ffffffff81934c8c)
Location: net/ipv4/fib_semantics.c:365
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (ffffffff819645dc)
Location: net/ipv4/fib_semantics.c:363
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (ffffffff819ca17c)
Location: net/ipv4/fib_semantics.c:455
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (ffffffff81a00d4c)
Location: net/ipv4/fib_semantics.c:455
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aefdaf)
Location: net/ipv4/fib_semantics.c:455
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afccef)
Location: net/ipv4/fib_semantics.c:455
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t fib_nlmsg_size(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae6850)
Location: net/ipv4/fib_semantics.c:455
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
**Symbols:**

```
ffffffff81ae6850-ffffffff81ae6993: fib_nlmsg_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t fib_nlmsg_size(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:460
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
**Symbols:**

```
ffffffff81d3cb88-ffffffff81d3cc4a: fib_nlmsg_size.cold (STB_LOCAL)
ffffffff81ba6400-ffffffff81ba65f0: fib_nlmsg_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t fib_nlmsg_size(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:462
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
**Symbols:**

```
ffffffff81f093ea-ffffffff81f094ac: fib_nlmsg_size.cold (STB_LOCAL)
ffffffff81d38dd0-ffffffff81d38fd7: fib_nlmsg_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t fib_nlmsg_size(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:464
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
**Symbols:**

```
ffffffff820b0cc6-ffffffff820b0d88: fib_nlmsg_size.cold (STB_LOCAL)
ffffffff81f01680-ffffffff81f01887: fib_nlmsg_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t fib_nlmsg_size(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:464
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
**Symbols:**

```
ffffffff82131f4d-ffffffff82132012: fib_nlmsg_size.cold (STB_LOCAL)
ffffffff81f610f0-ffffffff81f612ea: fib_nlmsg_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t fib_nlmsg_size(struct fib_info *fi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:465
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
  - net/ipv4/fib_trie.c:fib_alias_hw_flags_set
```
**Symbols:**

```
ffffffff8221390b-ffffffff822139d0: fib_nlmsg_size.cold (STB_LOCAL)
ffffffff820276c0-ffffffff820278ba: fib_nlmsg_size (STB_GLOBAL)
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
In net/ipv4/fib_semantics.c (ffff800010cb9348)
Location: net/ipv4/fib_semantics.c:455
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (c0dc4ae8)
Location: net/ipv4/fib_semantics.c:455
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (c000000000dd20c0)
Location: net/ipv4/fib_semantics.c:455
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (ffffffe000810052)
Location: net/ipv4/fib_semantics.c:455
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (ffffffff819a0aec)
Location: net/ipv4/fib_semantics.c:455
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (ffffffff8195a5ac)
Location: net/ipv4/fib_semantics.c:455
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (ffffffff81a0b38c)
Location: net/ipv4/fib_semantics.c:455
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
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
In net/ipv4/fib_semantics.c (ffffffff81a15b6c)
Location: net/ipv4/fib_semantics.c:455
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:rtmsg_fib
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
