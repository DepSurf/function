# Function: <code>netlink_compare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81749e10)
Location: net/netlink/af_netlink.c:1028
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff81749e10-ffffffff81749e39: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817b6d20)
Location: net/netlink/af_netlink.c:414
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
```
**Symbols:**

```
ffffffff817b6d20-ffffffff817b6d47: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817e67a0)
Location: net/netlink/af_netlink.c:421
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff817e67a0-ffffffff817e67c7: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818081a8)
Location: net/netlink/af_netlink.c:452
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
Direct callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff81806560-ffffffff81806589: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81886ff0)
Location: net/netlink/af_netlink.c:454
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
Direct callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff818852a0-ffffffff818852c9: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818db129)
Location: net/netlink/af_netlink.c:488
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
Direct callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff818d8c80-ffffffff818d8ca3: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81907a3b)
Location: net/netlink/af_netlink.c:488
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
Direct callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff81905470-ffffffff81905493: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81968c8a)
Location: net/netlink/af_netlink.c:479
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
Direct callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff81966600-ffffffff81966623: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199f72a)
Location: net/netlink/af_netlink.c:479
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
Direct callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff8199d090-ffffffff8199d0b3: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a762d0)
Location: net/netlink/af_netlink.c:479
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff81a762d0-ffffffff81a762f3: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a81a34)
Location: net/netlink/af_netlink.c:480
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff81a7f040-ffffffff81a7f063: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6ab2c)
Location: net/netlink/af_netlink.c:490
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff81a67ee0-ffffffff81a67f03: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b2412c)
Location: net/netlink/af_netlink.c:490
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff81b21400-ffffffff81b21423: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ca97e0)
Location: net/netlink/af_netlink.c:494
Inline: True
```
**Symbols:**

```
ffffffff81ca97e0-ffffffff81ca981b: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e66750)
Location: net/netlink/af_netlink.c:494
Inline: True
```
**Symbols:**

```
ffffffff81e66750-ffffffff81e6678b: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec2510)
Location: net/netlink/af_netlink.c:494
Inline: True
```
**Symbols:**

```
ffffffff81ec2510-ffffffff81ec254b: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f85860)
Location: net/netlink/af_netlink.c:492
Inline: True
```
**Symbols:**

```
ffffffff81f85860-ffffffff81f8589b: netlink_compare (STB_LOCAL)
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
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4a5d0)
Location: net/netlink/af_netlink.c:479
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffff800010c4a5d0-ffff800010c4a600: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d5dbbc)
Location: net/netlink/af_netlink.c:479
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
```
**Symbols:**

```
c0d5b0d0-c0d5b10c: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d481f0)
Location: net/netlink/af_netlink.c:479
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
c000000000d481f0-c000000000d48228: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007b784e)
Location: net/netlink/af_netlink.c:479
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffe0007b784e-ffffffe0007b7872: netlink_compare (STB_LOCAL)
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
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193f59a)
Location: net/netlink/af_netlink.c:479
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
Direct callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff8193cf00-ffffffff8193cf23: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f909a)
Location: net/netlink/af_netlink.c:479
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
Direct callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff818f6a00-ffffffff818f6a23: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199072a)
Location: net/netlink/af_netlink.c:479
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
Direct callers:
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff8198e090-ffffffff8198e0b3: netlink_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int netlink_compare(struct rhashtable_compare_arg *arg, const void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b2ff6)
Location: net/netlink/af_netlink.c:479
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
Direct callers:
  - net/netlink/af_netlink.c:netlink_lookup
```
**Symbols:**

```
ffffffff819b0930-ffffffff819b0953: netlink_compare (STB_LOCAL)
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
