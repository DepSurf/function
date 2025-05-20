# Function: <code>netlbl_af6list_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff8180d240)
Location: net/netlabel/netlabel_addrlist.c:293
Inline: False
Direct callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff8180d240-ffffffff8180d279: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff8187f630)
Location: net/netlabel/netlabel_addrlist.c:293
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff8187f630-ffffffff8187f669: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff818b3ee0)
Location: net/netlabel/netlabel_addrlist.c:293
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff818b3ee0-ffffffff818b3f19: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff818da880)
Location: net/netlabel/netlabel_addrlist.c:293
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff818da880-ffffffff818da8b9: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff81960460)
Location: net/netlabel/netlabel_addrlist.c:293
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81960460-ffffffff81960499: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff819b9c30)
Location: net/netlabel/netlabel_addrlist.c:293
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff819b9c30-ffffffff819b9c69: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff819f0f00)
Location: net/netlabel/netlabel_addrlist.c:293
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff819f0f00-ffffffff819f0f39: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff81a601c0)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81a601c0-ffffffff81a601f9: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff81a96df0)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81a96df0-ffffffff81a96e29: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff81b925c0)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
```
**Symbols:**

```
ffffffff81b925c0-ffffffff81b925f9: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff81ba2230)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove_addr6
```
**Symbols:**

```
ffffffff81ba2230-ffffffff81ba2269: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff81b91310)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81b91310-ffffffff81b91349: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff81c5dab0)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81c5dab0-ffffffff81c5dae9: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff81dffb70)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81dffb70-ffffffff81dffbb5: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff81fd4930)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81fd4930-ffffffff81fd4975: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff82050580)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff82050580-ffffffff820505c5: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff82122c30)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff82122c30-ffffffff82122c75: netlbl_af6list_remove (STB_GLOBAL)
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
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffff800010d66328)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffff800010d66328-ffff800010d6638c: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (c0e64bac)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
c0e64bac-c0e64bf0: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (c000000000ea2410)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
c000000000ea2410-c000000000ea2478: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffe000899e02)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffe000899e02-ffffffe000899e50: netlbl_af6list_remove (STB_GLOBAL)
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
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff81a36180)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81a36180-ffffffff81a361b9: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff819f2da0)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff819f2da0-ffffffff819f2dd9: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff81aa2030)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81aa2030-ffffffff81aa2069: netlbl_af6list_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct netlbl_af6list *netlbl_af6list_remove(const struct in6_addr *addr, const struct in6_addr *mask, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff81aae3a0)
Location: net/netlabel/netlabel_addrlist.c:279
Inline: False
Direct callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_remove_af6
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove
```
**Symbols:**

```
ffffffff81aae3a0-ffffffff81aae3d9: netlbl_af6list_remove (STB_GLOBAL)
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
