# Function: <code>fib_info_hash_move</code>

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
In net/ipv4/fib_semantics.c (ffffffff8179c94d)
Location: net/ipv4/fib_semantics.c:859
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff8180a4da)
Location: net/ipv4/fib_semantics.c:862
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff8183b5ea)
Location: net/ipv4/fib_semantics.c:863
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff8185cefd)
Location: net/ipv4/fib_semantics.c:897
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff818dcf1d)
Location: net/ipv4/fib_semantics.c:933
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff81933ad0)
Location: net/ipv4/fib_semantics.c:935
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff81962fd5)
Location: net/ipv4/fib_semantics.c:935
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff819c90cf)
Location: net/ipv4/fib_semantics.c:1228
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff819ffc8d)
Location: net/ipv4/fib_semantics.c:1228
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fib_info_hash_move(struct hlist_head *new_info_hash, struct hlist_head *new_laddrhash, unsigned int new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aed400)
Location: net/ipv4/fib_semantics.c:1237
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81aed400-ffffffff81aed698: fib_info_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fib_info_hash_move(struct hlist_head *new_info_hash, struct hlist_head *new_laddrhash, unsigned int new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afa1c0)
Location: net/ipv4/fib_semantics.c:1237
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81afa1c0-ffffffff81afa3d5: fib_info_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fib_info_hash_move(struct hlist_head *new_info_hash, struct hlist_head *new_laddrhash, unsigned int new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae5900)
Location: net/ipv4/fib_semantics.c:1238
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81ae5900-ffffffff81ae5b13: fib_info_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fib_info_hash_move(struct hlist_head *new_info_hash, struct hlist_head *new_laddrhash, unsigned int new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ba5310)
Location: net/ipv4/fib_semantics.c:1280
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81ba5310-ffffffff81ba54f4: fib_info_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fib_info_hash_move(struct hlist_head *new_info_hash, struct hlist_head *new_laddrhash, unsigned int new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1266
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81d37cf0-ffffffff81d37f0e: fib_info_hash_move (STB_LOCAL)
ffffffff81f09109-ffffffff81f0914b: fib_info_hash_move.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fib_info_hash_move(struct hlist_head *new_info_hash, struct hlist_head *new_laddrhash, unsigned int new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1272
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81f00150-ffffffff81f0036e: fib_info_hash_move (STB_LOCAL)
ffffffff820b0a13-ffffffff820b0a55: fib_info_hash_move.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fib_info_hash_move(struct hlist_head *new_info_hash, struct hlist_head *new_laddrhash, unsigned int new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1272
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81f5fbd0-ffffffff81f5fdee: fib_info_hash_move (STB_LOCAL)
ffffffff82131c9a-ffffffff82131cdc: fib_info_hash_move.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fib_info_hash_move(struct hlist_head *new_info_hash, struct hlist_head *new_laddrhash, unsigned int new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:1273
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff820261a0-ffffffff820263be: fib_info_hash_move (STB_LOCAL)
ffffffff82213658-ffffffff8221369a: fib_info_hash_move.cold (STB_LOCAL)
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
In net/ipv4/fib_semantics.c (ffff800010cb82bc)
Location: net/ipv4/fib_semantics.c:1228
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (c0dc3668)
Location: net/ipv4/fib_semantics.c:1228
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (c000000000dd0bf4)
Location: net/ipv4/fib_semantics.c:1228
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffe00080f26c)
Location: net/ipv4/fib_semantics.c:1228
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff8199fa2d)
Location: net/ipv4/fib_semantics.c:1228
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff819594ed)
Location: net/ipv4/fib_semantics.c:1228
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff81a0a2cd)
Location: net/ipv4/fib_semantics.c:1228
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff81a14aad)
Location: net/ipv4/fib_semantics.c:1228
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
