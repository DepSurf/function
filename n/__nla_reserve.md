# Function: <code>__nla_reserve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814159f0)
Location: lib/nlattr.c:343
Inline: False
Direct callers:
  - lib/nlattr.c:nla_reserve
  - lib/nlattr.c:__nla_put
```
**Symbols:**

```
ffffffff814159f0-ffffffff81415a3d: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8145d740)
Location: lib/nlattr.c:343
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff8145d740-ffffffff8145d78d: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8147c200)
Location: lib/nlattr.c:343
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff8147c200-ffffffff8147c24d: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81485520)
Location: lib/nlattr.c:351
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff81485520-ffffffff8148556d: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814c16b0)
Location: lib/nlattr.c:429
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff814c16b0-ffffffff814c16fd: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814f23e0)
Location: lib/nlattr.c:429
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
**Symbols:**

```
ffffffff814f23e0-ffffffff814f242d: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81506120)
Location: lib/nlattr.c:604
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
**Symbols:**

```
ffffffff81506120-ffffffff8150616d: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81534ae0)
Location: lib/nlattr.c:636
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff81534ae0-ffffffff81534b2d: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81555910)
Location: lib/nlattr.c:636
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff81555910-ffffffff8155595d: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de690)
Location: lib/nlattr.c:788
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
**Symbols:**

```
ffffffff815de690-ffffffff815de6e1: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815fbd30)
Location: lib/nlattr.c:855
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
**Symbols:**

```
ffffffff815fbd30-ffffffff815fbd81: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de980)
Location: lib/nlattr.c:855
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
**Symbols:**

```
ffffffff815de980-ffffffff815de9cd: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8164a500)
Location: lib/nlattr.c:855
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
**Symbols:**

```
ffffffff8164a500-ffffffff8164a54d: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81760cc0)
Location: lib/nlattr.c:855
Inline: False
Direct callers:
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
**Symbols:**

```
ffffffff81760cc0-ffffffff81760d17: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8188f6b0)
Location: lib/nlattr.c:870
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
**Symbols:**

```
ffffffff8188f6b0-ffffffff8188f707: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d1af0)
Location: lib/nlattr.c:870
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
**Symbols:**

```
ffffffff818d1af0-ffffffff818d1b47: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81923af0)
Location: lib/nlattr.c:902
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
  - lib/nlattr.c:nla_reserve
```
**Symbols:**

```
ffffffff81923af0-ffffffff81923b47: __nla_reserve (STB_GLOBAL)
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
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffff800010661d88)
Location: lib/nlattr.c:636
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffff800010661d88-ffff800010661dec: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c080ae34)
Location: lib/nlattr.c:636
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
c080ae34-c080ae80: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c000000000815fa0)
Location: lib/nlattr.c:636
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
c000000000815fa0-c000000000816028: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffe00048e6a0)
Location: lib/nlattr.c:636
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:__nla_reserve_64bit
  - lib/nlattr.c:__nla_reserve_64bit
```
**Symbols:**

```
ffffffe00048e6a0-ffffffe00048e6fa: __nla_reserve (STB_GLOBAL)
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
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8154def0)
Location: lib/nlattr.c:636
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff8154def0-ffffffff8154df3d: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8153e1d0)
Location: lib/nlattr.c:636
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff8153e1d0-ffffffff8153e21d: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81549c30)
Location: lib/nlattr.c:636
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff81549c30-ffffffff81549c7d: __nla_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct nlattr *__nla_reserve(struct sk_buff *skb, int attrtype, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81563a80)
Location: lib/nlattr.c:636
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:__nla_put
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff81563a80-ffffffff81563acd: __nla_reserve (STB_GLOBAL)
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
