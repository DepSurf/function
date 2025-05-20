# Function: <code>ip6mr_hash_cmp</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8199c420)
Location: net/ipv6/ip6mr.c:333
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff8199c420-ffffffff8199c46d: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d2d90)
Location: net/ipv6/ip6mr.c:343
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff819d2d90-ffffffff819d2ddd: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a41bf0)
Location: net/ipv6/ip6mr.c:338
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a41bf0-ffffffff81a41c42: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a78850)
Location: net/ipv6/ip6mr.c:338
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a78850-ffffffff81a788a2: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b73200)
Location: net/ipv6/ip6mr.c:342
Inline: False
```
**Symbols:**

```
ffffffff81b73200-ffffffff81b73252: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b81f30)
Location: net/ipv6/ip6mr.c:342
Inline: False
```
**Symbols:**

```
ffffffff81b81f30-ffffffff81b81f82: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b70b50)
Location: net/ipv6/ip6mr.c:342
Inline: False
```
**Symbols:**

```
ffffffff81b70b50-ffffffff81b70ba2: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81c3aeb0)
Location: net/ipv6/ip6mr.c:344
Inline: False
```
**Symbols:**

```
ffffffff81c3aeb0-ffffffff81c3af02: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81dd8e60)
Location: net/ipv6/ip6mr.c:337
Inline: True
```
**Symbols:**

```
ffffffff81dd8e60-ffffffff81dd8ebb: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81faa970)
Location: net/ipv6/ip6mr.c:344
Inline: True
```
**Symbols:**

```
ffffffff81faa970-ffffffff81faa9cb: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8200b100)
Location: net/ipv6/ip6mr.c:344
Inline: True
```
**Symbols:**

```
ffffffff8200b100-ffffffff8200b15b: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff820da100)
Location: net/ipv6/ip6mr.c:344
Inline: True
```
**Symbols:**

```
ffffffff820da100-ffffffff820da15b: ip6mr_hash_cmp (STB_LOCAL)
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
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffff800010d41f50)
Location: net/ipv6/ip6mr.c:338
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffff800010d41f50-ffff800010d41fc4: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c0e4486c)
Location: net/ipv6/ip6mr.c:338
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
c0e4486c-c0e44914: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c000000000e76ce0)
Location: net/ipv6/ip6mr.c:338
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
c000000000e76ce0-c000000000e76d48: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffe00087d592)
Location: net/ipv6/ip6mr.c:338
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffe00087d592-ffffffe00087d62e: ip6mr_hash_cmp (STB_LOCAL)
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
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a17ee0)
Location: net/ipv6/ip6mr.c:338
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a17ee0-ffffffff81a17f32: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d4ca0)
Location: net/ipv6/ip6mr.c:338
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff819d4ca0-ffffffff819d4cf2: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a82960)
Location: net/ipv6/ip6mr.c:338
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a82960-ffffffff81a829b2: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6mr_hash_cmp(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a8f230)
Location: net/ipv6/ip6mr.c:338
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a8f230-ffffffff81a8f282: ip6mr_hash_cmp (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
