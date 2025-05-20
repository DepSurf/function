# Function: <code>fib_info_hash_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8179bf10)
Location: net/ipv4/fib_semantics.c:848
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8179bf10-ffffffff8179bf4d: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81809a90)
Location: net/ipv4/fib_semantics.c:851
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81809a90-ffffffff81809acd: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8183ac10)
Location: net/ipv4/fib_semantics.c:852
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8183ac10-ffffffff8183ac4d: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8185c510)
Location: net/ipv4/fib_semantics.c:886
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8185c510-ffffffff8185c54d: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff818dc400)
Location: net/ipv4/fib_semantics.c:922
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff818dc400-ffffffff818dc43d: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81933030)
Location: net/ipv4/fib_semantics.c:924
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81933030-ffffffff8193306c: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819628c0)
Location: net/ipv4/fib_semantics.c:924
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff819628c0-ffffffff819628fc: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819c7f30)
Location: net/ipv4/fib_semantics.c:1217
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff819c7f30-ffffffff819c7f6c: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819feae0)
Location: net/ipv4/fib_semantics.c:1217
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff819feae0-ffffffff819feb1c: fib_info_hash_free (STB_LOCAL)
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
In net/ipv4/fib_semantics.c (ffffffff81aef4b6)
Location: net/ipv4/fib_semantics.c:1226
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81af9a80)
Location: net/ipv4/fib_semantics.c:1226
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
**Symbols:**

```
ffffffff81af9a80-ffffffff81af9abc: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae5170)
Location: net/ipv4/fib_semantics.c:1227
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
**Symbols:**

```
ffffffff81ae5170-ffffffff81ae51ac: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ba4e40)
Location: net/ipv4/fib_semantics.c:1269
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
```
**Symbols:**

```
ffffffff81ba4e40-ffffffff81ba4e7c: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb6fc8)
Location: net/ipv4/fib_semantics.c:1217
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffff800010cb6fc8-ffff800010cb7034: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c0dc256c)
Location: net/ipv4/fib_semantics.c:1217
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
c0dc256c-c0dc25b0: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dcf350)
Location: net/ipv4/fib_semantics.c:1217
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
c000000000dcf350-c000000000dcf3c8: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe00080e408)
Location: net/ipv4/fib_semantics.c:1217
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffe00080e408-ffffffe00080e4b0: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8199e880)
Location: net/ipv4/fib_semantics.c:1217
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8199e880-ffffffff8199e8bc: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81958340)
Location: net/ipv4/fib_semantics.c:1217
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81958340-ffffffff8195837c: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a09120)
Location: net/ipv4/fib_semantics.c:1217
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81a09120-ffffffff81a0915c: fib_info_hash_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fib_info_hash_free(struct hlist_head *hash, int bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a138d0)
Location: net/ipv4/fib_semantics.c:1217
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81a138d0-ffffffff81a1390c: fib_info_hash_free (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
