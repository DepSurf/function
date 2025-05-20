# Function: <code>seg6_hmac_cmpfn</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff818a4840)
Location: net/ipv6/seg6_hmac.c:50
Inline: False
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff818a4840-ffffffff818a485a: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff818cb060)
Location: net/ipv6/seg6_hmac.c:50
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff818cb060-ffffffff818cb07a: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff8194fe00)
Location: net/ipv6/seg6_hmac.c:51
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff8194fe00-ffffffff8194fe1a: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff819aa078)
Location: net/ipv6/seg6_hmac.c:51
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff819a9540-ffffffff819a955a: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff819e0bab)
Location: net/ipv6/seg6_hmac.c:52
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff819e0040-ffffffff819e005a: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a4f86a)
Location: net/ipv6/seg6_hmac.c:47
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81a4ecc0-ffffffff81a4ecda: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a864fa)
Location: net/ipv6/seg6_hmac.c:47
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81a85950-ffffffff81a8596a: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81b80980)
Location: net/ipv6/seg6_hmac.c:46
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81b80980-ffffffff81b8099a: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81b90ed7)
Location: net/ipv6/seg6_hmac.c:45
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81b901f0-ffffffff81b9020a: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81b800d3)
Location: net/ipv6/seg6_hmac.c:45
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81b7f430-ffffffff81b7f44a: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81c4b983)
Location: net/ipv6/seg6_hmac.c:45
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81c4ac90-ffffffff81c4acaa: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81deb362)
Location: net/ipv6/seg6_hmac.c:45
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81dea520-ffffffff81dea544: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81fbef52)
Location: net/ipv6/seg6_hmac.c:45
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81fbde30-ffffffff81fbde54: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff8201fba4)
Location: net/ipv6/seg6_hmac.c:45
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff8201ecc0-ffffffff8201ece4: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff820eecd4)
Location: net/ipv6/seg6_hmac.c:45
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff820eddf0-ffffffff820ede14: seg6_hmac_cmpfn (STB_LOCAL)
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
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffff800010d51a50)
Location: net/ipv6/seg6_hmac.c:47
Inline: False
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffff800010d51a50-ffff800010d51a8c: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (c0e5329c)
Location: net/ipv6/seg6_hmac.c:47
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
**Symbols:**

```
c0e5260c-c0e52638: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (c000000000e89d40)
Location: net/ipv6/seg6_hmac.c:47
Inline: False
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
c000000000e89d40-c000000000e89d68: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffe000889ba4)
Location: net/ipv6/seg6_hmac.c:47
Inline: False
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffe000889ba4-ffffffe000889bd8: seg6_hmac_cmpfn (STB_LOCAL)
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
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a25b8a)
Location: net/ipv6/seg6_hmac.c:47
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81a24fe0-ffffffff81a24ffa: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff819e294a)
Location: net/ipv6/seg6_hmac.c:47
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff819e1da0-ffffffff819e1dba: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a9060a)
Location: net/ipv6/seg6_hmac.c:47
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
```
**Symbols:**

```
ffffffff81a8fa60-ffffffff81a8fa7a: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int seg6_hmac_cmpfn(struct rhashtable_compare_arg *arg, const void *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_hmac.c (ffffffff81a9d780)
Location: net/ipv6/seg6_hmac.c:47
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_push_hmac
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
```
**Symbols:**

```
ffffffff81a9c840-ffffffff81a9c85a: seg6_hmac_cmpfn (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
