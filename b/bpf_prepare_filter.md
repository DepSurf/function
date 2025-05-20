# Function: <code>bpf_prepare_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81731d90)
Location: net/core/filter.c:999
Inline: True
Direct callers:
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:sk_attach_filter
```
**Symbols:**

```
ffffffff81731d90-ffffffff81732178: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179dd60)
Location: net/core/filter.c:1027
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff8179dd60-ffffffff8179e13c: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cc7c0)
Location: net/core/filter.c:1029
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff817cc7c0-ffffffff817ccb9c: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ebc10)
Location: net/core/filter.c:1054
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff817ebc10-ffffffff817ebfba: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818679e0)
Location: net/core/filter.c:1075
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff818679e0-ffffffff81867da3: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b7b80)
Location: net/core/filter.c:1287
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff818b7b80-ffffffff818b7f31: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818de400)
Location: net/core/filter.c:1289
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff818de400-ffffffff818de996: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8192c3f0)
Location: net/core/filter.c:1289
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff8192c3f0-ffffffff8192c8a0: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195e6f0)
Location: net/core/filter.c:1289
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff8195e6f0-ffffffff8195eba0: bpf_prepare_filter (STB_LOCAL)
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
In net/core/filter.c (ffffffff81a31523)
Location: net/core/filter.c:1278
Inline: True
Inline callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
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
In net/core/filter.c (ffffffff81a337f3)
Location: net/core/filter.c:1308
Inline: True
Inline callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a1a920)
Location: net/core/filter.c:1308
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff81a1a920-ffffffff81a1ab1b: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acd980)
Location: net/core/filter.c:1309
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff81acd980-ffffffff81acdb7b: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4af60)
Location: net/core/filter.c:1310
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff81c4af60-ffffffff81c4b173: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e002e0)
Location: net/core/filter.c:1312
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff81e002e0-ffffffff81e004f3: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e71db0)
Location: net/core/filter.c:1312
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff81e71db0-ffffffff81e71fc3: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f31500)
Location: net/core/filter.c:1317
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff81f31500-ffffffff81f31713: bpf_prepare_filter (STB_LOCAL)
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
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bff1a0)
Location: net/core/filter.c:1289
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffff800010bff1a0-ffff800010bff5fc: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1abcc)
Location: net/core/filter.c:1289
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
c0d1abcc-c0d1b488: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cea6a0)
Location: net/core/filter.c:1289
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
c000000000cea6a0-c000000000ceb098: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe0007810a4)
Location: net/core/filter.c:1289
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffe0007810a4-ffffffe0007813d2: bpf_prepare_filter (STB_LOCAL)
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
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818fe6c0)
Location: net/core/filter.c:1289
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff818fe6c0-ffffffff818feb70: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b84f0)
Location: net/core/filter.c:1289
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff818b84f0-ffffffff818b89a0: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194f6f0)
Location: net/core/filter.c:1289
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff8194f6f0-ffffffff8194fba0: bpf_prepare_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog *bpf_prepare_filter(struct bpf_prog *fp, bpf_aux_classic_check_t trans);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819710c0)
Location: net/core/filter.c:1289
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
```
**Symbols:**

```
ffffffff819710c0-ffffffff81971570: bpf_prepare_filter (STB_LOCAL)
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
