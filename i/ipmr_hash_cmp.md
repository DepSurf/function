# Function: <code>ipmr_hash_cmp</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81868160)
Location: net/ipv4/ipmr.c:303
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_cache_find_parent
  - net/ipv4/ipmr.c:ipmr_cache_find_any
  - net/ipv4/ipmr.c:ipmr_cache_find_any_parent
```
**Symbols:**

```
ffffffff81868160-ffffffff81868184: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818e81e0)
Location: net/ipv4/ipmr.c:336
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_cache_find_parent
  - net/ipv4/ipmr.c:ipmr_cache_find_any
  - net/ipv4/ipmr.c:ipmr_cache_find_any_parent
```
**Symbols:**

```
ffffffff818e81e0-ffffffff818e8204: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8193ecb0)
Location: net/ipv4/ipmr.c:359
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff8193ecb0-ffffffff8193ecd4: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196eb60)
Location: net/ipv4/ipmr.c:362
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff8196eb60-ffffffff8196eb84: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819d8360)
Location: net/ipv4/ipmr.c:356
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff819d8360-ffffffff819d8384: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a0ef10)
Location: net/ipv4/ipmr.c:356
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81a0ef10-ffffffff81a0ef34: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81affee0)
Location: net/ipv4/ipmr.c:360
Inline: False
```
**Symbols:**

```
ffffffff81affee0-ffffffff81afff04: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b0df20)
Location: net/ipv4/ipmr.c:360
Inline: False
```
**Symbols:**

```
ffffffff81b0df20-ffffffff81b0df44: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81afbd20)
Location: net/ipv4/ipmr.c:360
Inline: False
```
**Symbols:**

```
ffffffff81afbd20-ffffffff81afbd44: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81bbd1c0)
Location: net/ipv4/ipmr.c:362
Inline: False
```
**Symbols:**

```
ffffffff81bbd1c0-ffffffff81bbd1e4: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81d518f0)
Location: net/ipv4/ipmr.c:355
Inline: True
```
**Symbols:**

```
ffffffff81d518f0-ffffffff81d5192c: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f1b820)
Location: net/ipv4/ipmr.c:360
Inline: True
```
**Symbols:**

```
ffffffff81f1b820-ffffffff81f1b85c: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f7b2e0)
Location: net/ipv4/ipmr.c:360
Inline: True
```
**Symbols:**

```
ffffffff81f7b2e0-ffffffff81f7b31c: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff820419d0)
Location: net/ipv4/ipmr.c:360
Inline: True
```
**Symbols:**

```
ffffffff820419d0-ffffffff82041a0c: ipmr_hash_cmp (STB_LOCAL)
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
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010cc8df0)
Location: net/ipv4/ipmr.c:356
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffff800010cc8df0-ffff800010cc8e20: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd4208)
Location: net/ipv4/ipmr.c:356
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
c0dd4208-c0dd4244: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000de6320)
Location: net/ipv4/ipmr.c:356
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
c000000000de6320-c000000000de635c: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe00081d034)
Location: net/ipv4/ipmr.c:356
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffe00081d034-ffffffe00081d05a: ipmr_hash_cmp (STB_LOCAL)
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
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819aebf0)
Location: net/ipv4/ipmr.c:356
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff819aebf0-ffffffff819aec14: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196b220)
Location: net/ipv4/ipmr.c:356
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff8196b220-ffffffff8196b244: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a19490)
Location: net/ipv4/ipmr.c:356
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81a19490-ffffffff81a194b4: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipmr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a23fb0)
Location: net/ipv4/ipmr.c:356
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
**Symbols:**

```
ffffffff81a23fb0-ffffffff81a23fd4: ipmr_hash_cmp (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
