# Function: <code>bpf_prog_store_orig_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81731d00)
Location: net/core/filter.c:836
Inline: True
Direct callers:
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:sk_attach_filter
```
**Symbols:**

```
ffffffff81731d00-ffffffff81731d87: bpf_prog_store_orig_filter.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff8179d1a0)
Location: net/core/filter.c:860
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff8179d1a0-ffffffff8179d227: bpf_prog_store_orig_filter.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff817cac50)
Location: net/core/filter.c:862
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff817cac50-ffffffff817cacd7: bpf_prog_store_orig_filter.isra.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff817e9c20)
Location: net/core/filter.c:880
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff817e9c20-ffffffff817e9ca7: bpf_prog_store_orig_filter.isra.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81865290)
Location: net/core/filter.c:899
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff81865290-ffffffff81865317: bpf_prog_store_orig_filter.isra.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff818b2e30)
Location: net/core/filter.c:1108
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff818b2e30-ffffffff818b2eb7: bpf_prog_store_orig_filter.isra.62 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff818d7d10)
Location: net/core/filter.c:1110
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff818d7d10-ffffffff818d7d97: bpf_prog_store_orig_filter.isra.63 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff819257b0)
Location: net/core/filter.c:1110
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff819257b0-ffffffff8192583a: bpf_prog_store_orig_filter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81957be0)
Location: net/core/filter.c:1110
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff81957be0-ffffffff81957c6a: bpf_prog_store_orig_filter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_prog_store_orig_filter(struct bpf_prog *fp, const struct sock_fprog *fprog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a28740)
Location: net/core/filter.c:1099
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff81a28740-ffffffff81a287ca: bpf_prog_store_orig_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_prog_store_orig_filter(struct bpf_prog *fp, const struct sock_fprog *fprog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a29060)
Location: net/core/filter.c:1129
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff81a29060-ffffffff81a290ea: bpf_prog_store_orig_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_prog_store_orig_filter(struct bpf_prog *fp, const struct sock_fprog *fprog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a10350)
Location: net/core/filter.c:1129
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff81a10350-ffffffff81a103da: bpf_prog_store_orig_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_prog_store_orig_filter(struct bpf_prog *fp, const struct sock_fprog *fprog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac23c0)
Location: net/core/filter.c:1130
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff81ac23c0-ffffffff81ac244a: bpf_prog_store_orig_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_prog_store_orig_filter(struct bpf_prog *fp, const struct sock_fprog *fprog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3cdc0)
Location: net/core/filter.c:1131
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff81c3cdc0-ffffffff81c3ce4d: bpf_prog_store_orig_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_prog_store_orig_filter(struct bpf_prog *fp, const struct sock_fprog *fprog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df1140)
Location: net/core/filter.c:1133
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff81df1140-ffffffff81df11cd: bpf_prog_store_orig_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_prog_store_orig_filter(struct bpf_prog *fp, const struct sock_fprog *fprog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e62e60)
Location: net/core/filter.c:1133
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff81e62e60-ffffffff81e62eed: bpf_prog_store_orig_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_prog_store_orig_filter(struct bpf_prog *fp, const struct sock_fprog *fprog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f22270)
Location: net/core/filter.c:1138
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff81f22270-ffffffff81f22327: bpf_prog_store_orig_filter (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffff800010bf9210)
Location: net/core/filter.c:1110
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffff800010bf9210-ffff800010bf92a8: bpf_prog_store_orig_filter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_prog_store_orig_filter(struct bpf_prog *fp, const struct sock_fprog *fprog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d10cb0)
Location: net/core/filter.c:1110
Inline: False
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
c0d10cb0-c0d10d40: bpf_prog_store_orig_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (c000000000ce0570)
Location: net/core/filter.c:1110
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
c000000000ce0570-c000000000ce0648: bpf_prog_store_orig_filter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffe00077b360)
Location: net/core/filter.c:1110
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffe00077b360-ffffffe00077b3f0: bpf_prog_store_orig_filter.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff818f7bb0)
Location: net/core/filter.c:1110
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff818f7bb0-ffffffff818f7c3a: bpf_prog_store_orig_filter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff818b19e0)
Location: net/core/filter.c:1110
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff818b19e0-ffffffff818b1a6a: bpf_prog_store_orig_filter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81948be0)
Location: net/core/filter.c:1110
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff81948be0-ffffffff81948c6a: bpf_prog_store_orig_filter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff8196a4f0)
Location: net/core/filter.c:1110
Inline: True
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff8196a4f0-ffffffff8196a57a: bpf_prog_store_orig_filter.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
