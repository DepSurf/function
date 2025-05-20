# Function: <code>fib_create_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8179c830)
Location: net/ipv4/fib_semantics.c:989
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff8179c830-ffffffff8179d865: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8180a3b0)
Location: net/ipv4/fib_semantics.c:994
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff8180a3b0-ffffffff8180b3b4: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8183b4c0)
Location: net/ipv4/fib_semantics.c:995
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff8183b4c0-ffffffff8183c4c2: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8185cd90)
Location: net/ipv4/fib_semantics.c:1029
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff8185cd90-ffffffff8185dc01: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff818dcdb0)
Location: net/ipv4/fib_semantics.c:1065
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff818dcdb0-ffffffff818ddc33: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81933970)
Location: net/ipv4/fib_semantics.c:1028
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81933970-ffffffff81934788: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81962e60)
Location: net/ipv4/fib_semantics.c:1021
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81962e60-ffffffff819640d9: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1337
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff819cb0b4-ffffffff819cb0c7: fib_create_info.cold (STB_LOCAL)
ffffffff819c8dd0-ffffffff819c9c7f: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819ff990)
Location: net/ipv4/fib_semantics.c:1337
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff819ff990-ffffffff81a0083c: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aeef20)
Location: net/ipv4/fib_semantics.c:1346
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81aeef20-ffffffff81aef9a9: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afbea0)
Location: net/ipv4/fib_semantics.c:1346
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81afbea0-ffffffff81afc8ec: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae7620)
Location: net/ipv4/fib_semantics.c:1347
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81ae7620-ffffffff81ae80f0: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1389
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81d3cd7c-ffffffff81d3ce8c: fib_create_info.cold (STB_LOCAL)
ffffffff81ba7460-ffffffff81ba801b: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1374
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81f095ab-ffffffff81f096c1: fib_create_info.cold (STB_LOCAL)
ffffffff81d39e20-ffffffff81d3aa03: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1380
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff820b0e86-ffffffff820b0f9c: fib_create_info.cold (STB_LOCAL)
ffffffff81f02780-ffffffff81f03363: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1380
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff82132110-ffffffff82132227: fib_create_info.cold (STB_LOCAL)
ffffffff81f621e0-ffffffff81f62d4d: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1385
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff82213ace-ffffffff82213be5: fib_create_info.cold (STB_LOCAL)
ffffffff820287b0-ffffffff8202931d: fib_create_info (STB_GLOBAL)
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
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb7f58)
Location: net/ipv4/fib_semantics.c:1337
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffff800010cb7f58-ffff800010cb8e58: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c0dc3314)
Location: net/ipv4/fib_semantics.c:1337
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
c0dc3314-c0dc45a4: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dd07a0)
Location: net/ipv4/fib_semantics.c:1337
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
c000000000dd07a0-c000000000dd1a20: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe00080efb6)
Location: net/ipv4/fib_semantics.c:1337
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffe00080efb6-ffffffe00080fc5e: fib_create_info (STB_GLOBAL)
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
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8199f730)
Location: net/ipv4/fib_semantics.c:1337
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff8199f730-ffffffff819a05dc: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819591f0)
Location: net/ipv4/fib_semantics.c:1337
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff819591f0-ffffffff8195a09c: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a09fd0)
Location: net/ipv4/fib_semantics.c:1337
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81a09fd0-ffffffff81a0ae7c: fib_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fib_info *fib_create_info(struct fib_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a147b0)
Location: net/ipv4/fib_semantics.c:1337
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_insert
```
**Symbols:**

```
ffffffff81a147b0-ffffffff81a1565c: fib_create_info (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
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
