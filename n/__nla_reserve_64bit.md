# Function: <code>__nla_reserve_64bit</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8145d87a)
Location: lib/nlattr.c:371
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff8145d7c0-ffffffff8145d7cb: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8147c33a)
Location: lib/nlattr.c:371
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff8147c280-ffffffff8147c28b: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814855fc)
Location: lib/nlattr.c:379
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff814855a0-ffffffff814855ab: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814c178c)
Location: lib/nlattr.c:457
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff814c1730-ffffffff814c173b: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814f24b0)
Location: lib/nlattr.c:457
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff814f2460-ffffffff814f246b: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815061f0)
Location: lib/nlattr.c:632
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff815061a0-ffffffff815061ab: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81534bb0)
Location: lib/nlattr.c:664
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff81534b60-ffffffff81534b6b: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815559e0)
Location: lib/nlattr.c:664
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff81555990-ffffffff8155599b: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de770)
Location: lib/nlattr.c:816
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff815de720-ffffffff815de72b: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815fbe10)
Location: lib/nlattr.c:883
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff815fbdc0-ffffffff815fbdcb: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815dea50)
Location: lib/nlattr.c:883
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff815dea00-ffffffff815dea0b: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8164a5d0)
Location: lib/nlattr.c:883
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff8164a580-ffffffff8164a58b: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81760db3)
Location: lib/nlattr.c:883
Inline: True
Inline callers:
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff81760d70-ffffffff81760d85: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8188f810)
Location: lib/nlattr.c:898
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff8188f780-ffffffff8188f795: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d1c50)
Location: lib/nlattr.c:898
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff818d1bc0-ffffffff818d1bd5: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81923c50)
Location: lib/nlattr.c:930
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff81923bc0-ffffffff81923bd5: __nla_reserve_64bit (STB_GLOBAL)
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
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffff800010661e90)
Location: lib/nlattr.c:664
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffff800010661e30-ffff800010661e44: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c080af28)
Location: lib/nlattr.c:664
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
c080aec4-c080aed8: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c0000000008160fc)
Location: lib/nlattr.c:664
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
c000000000816080-c00000000081608c: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffe00048e732)
Location: lib/nlattr.c:664
Inline: False
Direct callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffe00048e732-ffffffe00048e78e: __nla_reserve_64bit (STB_GLOBAL)
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
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8154dfc0)
Location: lib/nlattr.c:664
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff8154df70-ffffffff8154df7b: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8153e2a0)
Location: lib/nlattr.c:664
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff8153e250-ffffffff8153e25b: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81549d00)
Location: lib/nlattr.c:664
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff81549cb0-ffffffff81549cbb: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *__nla_reserve_64bit(struct sk_buff *skb, int attrtype, int attrlen, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81563b50)
Location: lib/nlattr.c:664
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_64bit
  - lib/nlattr.c:nla_reserve_64bit
```
**Symbols:**

```
ffffffff81563b00-ffffffff81563b0b: __nla_reserve_64bit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
