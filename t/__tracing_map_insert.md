# Function: <code>__tracing_map_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811603f7)
Location: kernel/trace/tracing_map.c:411
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
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
In kernel/trace/tracing_map.c (ffffffff8116ae57)
Location: kernel/trace/tracing_map.c:411
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
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
In kernel/trace/tracing_map.c (ffffffff8116dde7)
Location: kernel/trace/tracing_map.c:414
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
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
In kernel/trace/tracing_map.c (ffffffff8117aea4)
Location: kernel/trace/tracing_map.c:414
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
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
In kernel/trace/tracing_map.c (ffffffff81189ff0)
Location: kernel/trace/tracing_map.c:522
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
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
In kernel/trace/tracing_map.c (ffffffff81197900)
Location: kernel/trace/tracing_map.c:513
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
  - kernel/trace/tracing_map.c:tracing_map_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a4fe0)
Location: kernel/trace/tracing_map.c:513
Inline: True
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff811a4fe0-ffffffff811a53a0: __tracing_map_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811b0810)
Location: kernel/trace/tracing_map.c:513
Inline: True
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff811b0810-ffffffff811b0bd0: __tracing_map_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c8e40)
Location: kernel/trace/tracing_map.c:513
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff811c8e40-ffffffff811c9031: __tracing_map_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c6500)
Location: kernel/trace/tracing_map.c:513
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff811c6500-ffffffff811c66f1: __tracing_map_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c7550)
Location: kernel/trace/tracing_map.c:513
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff811c7550-ffffffff811c770c: __tracing_map_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:516
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff811f2c60-ffffffff811f2e8a: __tracing_map_insert (STB_LOCAL)
ffffffff81cb59cf-ffffffff81cb5a85: __tracing_map_insert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:516
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff8122c210-ffffffff8122c457: __tracing_map_insert (STB_LOCAL)
ffffffff81e669dc-ffffffff81e66aa2: __tracing_map_insert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:516
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff81277d40-ffffffff81277f87: __tracing_map_insert (STB_LOCAL)
ffffffff8205da9a-ffffffff8205db60: __tracing_map_insert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:516
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff8128f780-ffffffff8128f9c7: __tracing_map_insert (STB_LOCAL)
ffffffff820dc3b7-ffffffff820dc47d: __tracing_map_insert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:516
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff812aace0-ffffffff812aaf27: __tracing_map_insert (STB_LOCAL)
ffffffff821b81e5-ffffffff821b82ab: __tracing_map_insert.cold (STB_LOCAL)
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
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffff80001022e918)
Location: kernel/trace/tracing_map.c:513
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffff80001022dfa8-ffff80001022e450: __tracing_map_insert (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (c0000000002b7efc)
Location: kernel/trace/tracing_map.c:513
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_lookup
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
c0000000002b71d0-c0000000002b77a8: __tracing_map_insert (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a8e30)
Location: kernel/trace/tracing_map.c:513
Inline: True
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff811a8e30-ffffffff811a91f0: __tracing_map_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8119bdb0)
Location: kernel/trace/tracing_map.c:513
Inline: True
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff8119bdb0-ffffffff8119c170: __tracing_map_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a6c00)
Location: kernel/trace/tracing_map.c:513
Inline: True
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff811a6c00-ffffffff811a6fc0: __tracing_map_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct tracing_map_elt *__tracing_map_insert(struct tracing_map *map, void *key, bool lookup_only);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811b49a0)
Location: kernel/trace/tracing_map.c:513
Inline: True
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff811b49a0-ffffffff811b4d60: __tracing_map_insert (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
