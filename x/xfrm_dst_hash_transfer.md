# Function: <code>xfrm_dst_hash_transfer</code>

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
In net/xfrm/xfrm_policy.c (ffffffff817b1d79)
Location: net/xfrm/xfrm_policy.c:409
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
In net/xfrm/xfrm_policy.c (ffffffff8181ec9e)
Location: net/xfrm/xfrm_policy.c:409
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
In net/xfrm/xfrm_policy.c (ffffffff8185052b)
Location: net/xfrm/xfrm_policy.c:418
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
In net/xfrm/xfrm_policy.c (ffffffff818741f9)
Location: net/xfrm/xfrm_policy.c:413
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
In net/xfrm/xfrm_policy.c (ffffffff818f4769)
Location: net/xfrm/xfrm_policy.c:384
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
In net/xfrm/xfrm_policy.c (ffffffff8194b1f9)
Location: net/xfrm/xfrm_policy.c:384
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
In net/xfrm/xfrm_policy.c (ffffffff8197dab9)
Location: net/xfrm/xfrm_policy.c:508
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
In net/xfrm/xfrm_policy.c (ffffffff819e6ff0)
Location: net/xfrm/xfrm_policy.c:513
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
In net/xfrm/xfrm_policy.c (ffffffff81a1dfe0)
Location: net/xfrm/xfrm_policy.c:515
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xfrm_dst_hash_transfer(struct net *net, struct hlist_head *list, struct hlist_head *ndsttable, unsigned int nhashmask, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b100e0)
Location: net/xfrm/xfrm_policy.c:518
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
**Symbols:**

```
ffffffff81b100e0-ffffffff81b105ae: xfrm_dst_hash_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xfrm_dst_hash_transfer(struct net *net, struct hlist_head *list, struct hlist_head *ndsttable, unsigned int nhashmask, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1e3d0)
Location: net/xfrm/xfrm_policy.c:518
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
**Symbols:**

```
ffffffff81b1e3d0-ffffffff81b1e89e: xfrm_dst_hash_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xfrm_dst_hash_transfer(struct net *net, struct hlist_head *list, struct hlist_head *ndsttable, unsigned int nhashmask, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0c090)
Location: net/xfrm/xfrm_policy.c:517
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
**Symbols:**

```
ffffffff81b0c090-ffffffff81b0c528: xfrm_dst_hash_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xfrm_dst_hash_transfer(struct net *net, struct hlist_head *list, struct hlist_head *ndsttable, unsigned int nhashmask, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bcf0b0)
Location: net/xfrm/xfrm_policy.c:519
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
**Symbols:**

```
ffffffff81bcf0b0-ffffffff81bcf613: xfrm_dst_hash_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xfrm_dst_hash_transfer(struct net *net, struct hlist_head *list, struct hlist_head *ndsttable, unsigned int nhashmask, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d65090)
Location: net/xfrm/xfrm_policy.c:519
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
**Symbols:**

```
ffffffff81d65090-ffffffff81d65622: xfrm_dst_hash_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xfrm_dst_hash_transfer(struct net *net, struct hlist_head *list, struct hlist_head *ndsttable, unsigned int nhashmask, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f2ffe0)
Location: net/xfrm/xfrm_policy.c:520
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
**Symbols:**

```
ffffffff81f2ffe0-ffffffff81f30590: xfrm_dst_hash_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xfrm_dst_hash_transfer(struct net *net, struct hlist_head *list, struct hlist_head *ndsttable, unsigned int nhashmask, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f8e840)
Location: net/xfrm/xfrm_policy.c:520
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
**Symbols:**

```
ffffffff81f8e840-ffffffff81f8ee81: xfrm_dst_hash_transfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xfrm_dst_hash_transfer(struct net *net, struct hlist_head *list, struct hlist_head *ndsttable, unsigned int nhashmask, int dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205c550)
Location: net/xfrm/xfrm_policy.c:535
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
**Symbols:**

```
ffffffff8205c550-ffffffff8205cb91: xfrm_dst_hash_transfer (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffff800010cdea70)
Location: net/xfrm/xfrm_policy.c:515
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
In net/xfrm/xfrm_policy.c (c0de4210)
Location: net/xfrm/xfrm_policy.c:515
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
In net/xfrm/xfrm_policy.c (c000000000dfb5d0)
Location: net/xfrm/xfrm_policy.c:515
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
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
In net/xfrm/xfrm_policy.c (ffffffe00082b642)
Location: net/xfrm/xfrm_policy.c:515
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
In net/xfrm/xfrm_policy.c (ffffffff819bd670)
Location: net/xfrm/xfrm_policy.c:515
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
In net/xfrm/xfrm_policy.c (ffffffff8197a460)
Location: net/xfrm/xfrm_policy.c:515
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
In net/xfrm/xfrm_policy.c (ffffffff81a280f0)
Location: net/xfrm/xfrm_policy.c:515
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
In net/xfrm/xfrm_policy.c (ffffffff81a33720)
Location: net/xfrm/xfrm_policy.c:515
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
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
