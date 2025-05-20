# Function: <code>fib_lookup_good_nhc</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool fib_lookup_good_nhc(const struct fib_nh_common *nhc, int fib_flags, const struct flowi4 *flp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af38c0)
Location: net/ipv4/fib_trie.c:1374
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
**Symbols:**

```
ffffffff81af38c0-ffffffff81af3914: fib_lookup_good_nhc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool fib_lookup_good_nhc(const struct fib_nh_common *nhc, int fib_flags, const struct flowi4 *flp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81b007d0)
Location: net/ipv4/fib_trie.c:1374
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
**Symbols:**

```
ffffffff81b007d0-ffffffff81b00844: fib_lookup_good_nhc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool fib_lookup_good_nhc(const struct fib_nh_common *nhc, int fib_flags, const struct flowi4 *flp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81aebe50)
Location: net/ipv4/fib_trie.c:1411
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
**Symbols:**

```
ffffffff81aebe50-ffffffff81aebed4: fib_lookup_good_nhc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool fib_lookup_good_nhc(const struct fib_nh_common *nhc, int fib_flags, const struct flowi4 *flp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81bac070)
Location: net/ipv4/fib_trie.c:1415
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
**Symbols:**

```
ffffffff81bac070-ffffffff81bac0f4: fib_lookup_good_nhc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool fib_lookup_good_nhc(const struct fib_nh_common *nhc, int fib_flags, const struct flowi4 *flp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81d3eec0)
Location: net/ipv4/fib_trie.c:1424
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
**Symbols:**

```
ffffffff81d3eec0-ffffffff81d3ef52: fib_lookup_good_nhc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fib_lookup_good_nhc(const struct fib_nh_common *nhc, int fib_flags, const struct flowi4 *flp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f07aa0)
Location: net/ipv4/fib_trie.c:1426
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
**Symbols:**

```
ffffffff81f07aa0-ffffffff81f07b32: fib_lookup_good_nhc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fib_lookup_good_nhc(const struct fib_nh_common *nhc, int fib_flags, const struct flowi4 *flp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81f67580)
Location: net/ipv4/fib_trie.c:1426
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
**Symbols:**

```
ffffffff81f67580-ffffffff81f67612: fib_lookup_good_nhc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fib_lookup_good_nhc(const struct fib_nh_common *nhc, int fib_flags, const struct flowi4 *flp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff8202db60)
Location: net/ipv4/fib_trie.c:1427
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
  - net/ipv4/fib_trie.c:fib_table_lookup
```
**Symbols:**

```
ffffffff8202db60-ffffffff8202dbf2: fib_lookup_good_nhc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
