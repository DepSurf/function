# Function: <code>ipv6_generate_stable_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817c9680)
Location: net/ipv6/addrconf.c:2975
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff817c9680-ffffffff817c98cf: ipv6_generate_stable_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81836820)
Location: net/ipv6/addrconf.c:3056
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81836820-ffffffff81836a6d: ipv6_generate_stable_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81868330)
Location: net/ipv6/addrconf.c:3072
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81868330-ffffffff8186857d: ipv6_generate_stable_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8188c980)
Location: net/ipv6/addrconf.c:3127
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff8188c980-ffffffff8188cbe9: ipv6_generate_stable_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8190dbf0)
Location: net/ipv6/addrconf.c:3113
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff8190dbf0-ffffffff8190de59: ipv6_generate_stable_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3162
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81964ec0-ffffffff8196511b: ipv6_generate_stable_address (STB_LOCAL)
ffffffff8196f389-ffffffff8196f395: ipv6_generate_stable_address.cold.75 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3178
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff8199a340-ffffffff8199a59b: ipv6_generate_stable_address (STB_LOCAL)
ffffffff819a4f39-ffffffff819a4f45: ipv6_generate_stable_address.cold.77 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3216
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81a062c0-ffffffff81a0651b: ipv6_generate_stable_address (STB_LOCAL)
ffffffff81a1123d-ffffffff81a11249: ipv6_generate_stable_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3218
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81a3ce30-ffffffff81a3d08b: ipv6_generate_stable_address (STB_LOCAL)
ffffffff81a47fa8-ffffffff81a47fb4: ipv6_generate_stable_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3179
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81b33aa0-ffffffff81b33cca: ipv6_generate_stable_address (STB_LOCAL)
ffffffff81b3eaaf-ffffffff81b3eabb: ipv6_generate_stable_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3206
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81b423e0-ffffffff81b4260a: ipv6_generate_stable_address (STB_LOCAL)
ffffffff81c32b41-ffffffff81c32b4d: ipv6_generate_stable_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3208
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81b30330-ffffffff81b3055e: ipv6_generate_stable_address (STB_LOCAL)
ffffffff81c24e51-ffffffff81c24e5d: ipv6_generate_stable_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3234
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81bf67d0-ffffffff81bf6a23: ipv6_generate_stable_address (STB_LOCAL)
ffffffff81d3f6db-ffffffff81d3f711: ipv6_generate_stable_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81d8fa60-ffffffff81d8fce6: ipv6_generate_stable_address (STB_LOCAL)
ffffffff81f0c065-ffffffff81f0c09b: ipv6_generate_stable_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3241
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81f5dcc0-ffffffff81f5dfa9: ipv6_generate_stable_address (STB_LOCAL)
ffffffff820b389a-ffffffff820b38d9: ipv6_generate_stable_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3246
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81fbd9c0-ffffffff81fbdca6: ipv6_generate_stable_address (STB_LOCAL)
ffffffff82134993-ffffffff821349d2: ipv6_generate_stable_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3297
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff8208ae10-ffffffff8208b0f6: ipv6_generate_stable_address (STB_LOCAL)
ffffffff82216450-ffffffff8221648f: ipv6_generate_stable_address.cold (STB_LOCAL)
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
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d00b38)
Location: net/ipv6/addrconf.c:3218
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffff800010d00b38-ffff800010d00d88: ipv6_generate_stable_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e062a4)
Location: net/ipv6/addrconf.c:3218
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
c0e062a4-c0e064a8: ipv6_generate_stable_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e269d0)
Location: net/ipv6/addrconf.c:3218
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
c000000000e269d0-c000000000e26d30: ipv6_generate_stable_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084898c)
Location: net/ipv6/addrconf.c:3218
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffe00084898c-ffffffe000848bc6: ipv6_generate_stable_address (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3218
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff819dc4c0-ffffffff819dc71b: ipv6_generate_stable_address (STB_LOCAL)
ffffffff819e7638-ffffffff819e7644: ipv6_generate_stable_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3218
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81999280-ffffffff819994db: ipv6_generate_stable_address (STB_LOCAL)
ffffffff819a43f8-ffffffff819a4404: ipv6_generate_stable_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3218
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81a46f40-ffffffff81a4719b: ipv6_generate_stable_address (STB_LOCAL)
ffffffff81a520b8-ffffffff81a520c4: ipv6_generate_stable_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ipv6_generate_stable_address(struct in6_addr *address, u8 dad_count, const struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3218
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_addr_gen
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_dad_failure
```
**Symbols:**

```
ffffffff81a52ce0-ffffffff81a52f3b: ipv6_generate_stable_address (STB_LOCAL)
ffffffff81a5e008-ffffffff81a5e014: ipv6_generate_stable_address.cold (STB_LOCAL)
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
