# Function: <code>__nla_reserve_nohdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81415ae0)
Location: lib/nlattr.c:367
Inline: False
Direct callers:
  - lib/nlattr.c:nla_reserve_nohdr
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff81415ae0-ffffffff81415b0c: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8145d910)
Location: lib/nlattr.c:391
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff8145d910-ffffffff8145d93c: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8147c3d0)
Location: lib/nlattr.c:391
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff8147c3d0-ffffffff8147c3fc: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814856e9)
Location: lib/nlattr.c:399
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff814857e0-ffffffff81485801: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814c1879)
Location: lib/nlattr.c:477
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff814c1970-ffffffff814c1991: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814f25a0)
Location: lib/nlattr.c:477
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff814f2860-ffffffff814f2881: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815062d0)
Location: lib/nlattr.c:652
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff81506b90-ffffffff81506bb1: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81534ca0)
Location: lib/nlattr.c:684
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff81534d90-ffffffff81534db1: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81555ad0)
Location: lib/nlattr.c:684
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff81555bc0-ffffffff81555be1: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de860)
Location: lib/nlattr.c:836
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff815de950-ffffffff815de974: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815fbf00)
Location: lib/nlattr.c:902
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff815fbff0-ffffffff815fc014: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815deb40)
Location: lib/nlattr.c:902
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff815dec30-ffffffff815dec54: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8164a6c0)
Location: lib/nlattr.c:902
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff8164a7b0-ffffffff8164a7d4: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81760de0)
Location: lib/nlattr.c:902
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff81760f90-ffffffff81760fc0: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8188fb40)
Location: lib/nlattr.c:917
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff8188fc80-ffffffff8188fcb0: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d1fb0)
Location: lib/nlattr.c:917
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff818d20f0-ffffffff818d2120: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81923f80)
Location: lib/nlattr.c:949
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff819240c0-ffffffff819240f0: __nla_reserve_nohdr (STB_GLOBAL)
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
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffff800010661f98)
Location: lib/nlattr.c:684
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffff8000106620d8-ffff800010662114: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c080b024)
Location: lib/nlattr.c:684
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
c080b134-c080b168: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c0000000008162a0)
Location: lib/nlattr.c:684
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
c000000000816470-c0000000008164cc: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffe00048e8ca)
Location: lib/nlattr.c:684
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffe00048e8ca-ffffffe00048e904: __nla_reserve_nohdr (STB_GLOBAL)
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
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8154e0b0)
Location: lib/nlattr.c:684
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff8154e1a0-ffffffff8154e1c1: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8153e390)
Location: lib/nlattr.c:684
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff8153e480-ffffffff8153e4a1: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81549df0)
Location: lib/nlattr.c:684
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff81549ee0-ffffffff81549f01: __nla_reserve_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *__nla_reserve_nohdr(struct sk_buff *skb, int attrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81563c40)
Location: lib/nlattr.c:684
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
**Symbols:**

```
ffffffff81563d30-ffffffff81563d51: __nla_reserve_nohdr (STB_GLOBAL)
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
