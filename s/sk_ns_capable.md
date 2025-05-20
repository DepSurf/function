# Function: <code>sk_ns_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81700580)
Location: net/core/sock.c:159
Inline: False
Direct callers:
  - net/core/sock.c:sk_capable
  - net/core/sock.c:sk_net_capable
```
**Symbols:**

```
ffffffff81700580-ffffffff817005b6: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81767070)
Location: net/core/sock.c:160
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
```
**Symbols:**

```
ffffffff81767070-ffffffff817670ac: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817940f0)
Location: net/core/sock.c:160
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
```
**Symbols:**

```
ffffffff817940f0-ffffffff8179412c: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b24b0)
Location: net/core/sock.c:158
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
```
**Symbols:**

```
ffffffff817b24b0-ffffffff817b24ec: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182a660)
Location: net/core/sock.c:158
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/rtnetlink.c:get_target_net
```
**Symbols:**

```
ffffffff8182a660-ffffffff8182a69c: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818747b0)
Location: net/core/sock.c:160
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/rtnetlink.c:get_target_net
```
**Symbols:**

```
ffffffff818747b0-ffffffff818747f3: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81895080)
Location: net/core/sock.c:161
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff81895080-ffffffff818950bb: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818df540)
Location: net/core/sock.c:156
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff818df540-ffffffff818df57e: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81911710)
Location: net/core/sock.c:156
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff81911710-ffffffff8191174e: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e52da)
Location: net/core/sock.c:156
Inline: True
Inline callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff819e3560-ffffffff819e359e: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4aba)
Location: net/core/sock.c:157
Inline: True
Inline callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff819e30d0-ffffffff819e310e: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819caf4a)
Location: net/core/sock.c:157
Inline: True
Inline callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff819c90f0-ffffffff819c912e: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7a56a)
Location: net/core/sock.c:159
Inline: True
Inline callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff81a78490-ffffffff81a784ce: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bedfb8)
Location: net/core/sock.c:162
Inline: True
Inline callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff81bebb70-ffffffff81bebbbf: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9a998)
Location: net/core/sock.c:162
Inline: True
Inline callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff81d98680-ffffffff81d986cf: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e091c8)
Location: net/core/sock.c:166
Inline: True
Inline callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff81e06cf0-ffffffff81e06d3f: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec5bb8)
Location: net/core/sock.c:167
Inline: True
Inline callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
Direct callers:
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff81ec35e0-ffffffff81ec362f: sk_ns_capable (STB_GLOBAL)
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
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010ba9390)
Location: net/core/sock.c:156
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffff800010ba9390-ffff800010ba9400: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc7a70)
Location: net/core/sock.c:156
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
c0cc7a70-c0cc7ab0: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7e280)
Location: net/core/sock.c:156
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
c000000000c7e280-c000000000c7e308: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073c734)
Location: net/core/sock.c:156
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffe00073c734-ffffffe00073c78e: sk_ns_capable (STB_GLOBAL)
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
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b1710)
Location: net/core/sock.c:156
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff818b1710-ffffffff818b174e: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186b660)
Location: net/core/sock.c:156
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff8186b660-ffffffff8186b69e: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81902710)
Location: net/core/sock.c:156
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff81902710-ffffffff8190274e: sk_ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool sk_ns_capable(const struct sock *sk, struct user_namespace *user_ns, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819236b0)
Location: net/core/sock.c:156
Inline: False
Direct callers:
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
**Symbols:**

```
ffffffff819236b0-ffffffff819236ee: sk_ns_capable (STB_GLOBAL)
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
