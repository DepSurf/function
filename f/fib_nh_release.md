# Function: <code>fib_nh_release</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819c7d4a)
Location: net/ipv4/fib_semantics.c:221
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffff819c7fc0-ffffffff819c7fe4: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819fe8fa)
Location: net/ipv4/fib_semantics.c:221
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffff819feb70-ffffffff819feb94: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aed72d)
Location: net/ipv4/fib_semantics.c:221
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffff81aee0c0-ffffffff81aee0e4: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afa5fd)
Location: net/ipv4/fib_semantics.c:221
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffff81afb020-ffffffff81afb044: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae5bfd)
Location: net/ipv4/fib_semantics.c:221
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffff81ae65c0-ffffffff81ae65e4: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ba578a)
Location: net/ipv4/fib_semantics.c:220
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffff81ba6130-ffffffff81ba6154: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81d38136)
Location: net/ipv4/fib_semantics.c:222
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
  - net/ipv4/nexthop.c:nh_create_ipv4
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffff81d38b10-ffffffff81d38b40: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81f00996)
Location: net/ipv4/fib_semantics.c:223
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
  - net/ipv4/nexthop.c:nh_create_ipv4
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffff81f01380-ffffffff81f013b0: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81f60416)
Location: net/ipv4/fib_semantics.c:223
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
  - net/ipv4/nexthop.c:nh_create_ipv4
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffff81f60df0-ffffffff81f60e20: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff820269e6)
Location: net/ipv4/fib_semantics.c:223
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nh_create_ipv4
  - net/ipv4/nexthop.c:nh_create_ipv4
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffff820273c0-ffffffff820273f0: fib_nh_release (STB_GLOBAL)
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
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb6a54)
Location: net/ipv4/fib_semantics.c:221
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffff800010cb7038-ffff800010cb707c: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c0dc22c4)
Location: net/ipv4/fib_semantics.c:221
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nexthop_create
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
c0dc25f4-c0dc2628: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dceaf0)
Location: net/ipv4/fib_semantics.c:221
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
c000000000dcf450-c000000000dcf480: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe00080e1a2)
Location: net/ipv4/fib_semantics.c:221
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffe00080e4b0-ffffffe00080e4ee: fib_nh_release (STB_GLOBAL)
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
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8199e69a)
Location: net/ipv4/fib_semantics.c:221
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffff8199e910-ffffffff8199e934: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8195815a)
Location: net/ipv4/fib_semantics.c:221
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffff819583d0-ffffffff819583f4: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a08f3a)
Location: net/ipv4/fib_semantics.c:221
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffff81a091b0-ffffffff81a091d4: fib_nh_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fib_nh_release(struct net *net, struct fib_nh *fib_nh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a136ea)
Location: net/ipv4/fib_semantics.c:221
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
Direct callers:
  - net/ipv4/nexthop.c:nexthop_free_rcu
```
**Symbols:**

```
ffffffff81a13960-ffffffff81a13984: fib_nh_release (STB_GLOBAL)
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
