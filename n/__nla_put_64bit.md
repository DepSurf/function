# Function: <code>__nla_put_64bit</code>

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
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8145d87a)
Location: lib/nlattr.c:503
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff8145d810-ffffffff8145d835: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8147c33a)
Location: lib/nlattr.c:503
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff8147c2d0-ffffffff8147c2f5: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814855f0)
Location: lib/nlattr.c:506
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff814855f0-ffffffff81485615: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814c1780)
Location: lib/nlattr.c:584
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff814c1780-ffffffff814c17a5: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814f24b0)
Location: lib/nlattr.c:584
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff814f24b0-ffffffff814f24d5: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815061f0)
Location: lib/nlattr.c:759
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff815061f0-ffffffff81506215: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81534bb0)
Location: lib/nlattr.c:791
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff81534bb0-ffffffff81534bd5: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815559e0)
Location: lib/nlattr.c:791
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff815559e0-ffffffff81555a05: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de770)
Location: lib/nlattr.c:943
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff815de770-ffffffff815de795: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815fbe10)
Location: lib/nlattr.c:1009
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff815fbe10-ffffffff815fbe35: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815dea50)
Location: lib/nlattr.c:1009
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff815dea50-ffffffff815dea75: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8164a5d0)
Location: lib/nlattr.c:1009
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff8164a5d0-ffffffff8164a5f5: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81761040)
Location: lib/nlattr.c:1009
Inline: True
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff81761040-ffffffff81761073: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8188f810)
Location: lib/nlattr.c:1024
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff8188f810-ffffffff8188f843: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d1c50)
Location: lib/nlattr.c:1024
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff818d1c50-ffffffff818d1c83: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81923c50)
Location: lib/nlattr.c:1056
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff81923c50-ffffffff81923c83: __nla_put_64bit (STB_GLOBAL)
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
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffff800010661e90)
Location: lib/nlattr.c:791
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffff800010661e90-ffff800010661ec4: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c080af1c)
Location: lib/nlattr.c:791
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
c080af1c-c080af48: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c0000000008160e0)
Location: lib/nlattr.c:791
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
c0000000008160e0-c000000000816134: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffe00048e7d6)
Location: lib/nlattr.c:791
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffe00048e7d6-ffffffe00048e80a: __nla_put_64bit (STB_GLOBAL)
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
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8154dfc0)
Location: lib/nlattr.c:791
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff8154dfc0-ffffffff8154dfe5: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8153e2a0)
Location: lib/nlattr.c:791
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff8153e2a0-ffffffff8153e2c5: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81549d00)
Location: lib/nlattr.c:791
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff81549d00-ffffffff81549d25: __nla_put_64bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __nla_put_64bit(struct sk_buff *skb, int attrtype, int attrlen, const void *data, int padattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81563b50)
Location: lib/nlattr.c:791
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_64bit
```
**Symbols:**

```
ffffffff81563b50-ffffffff81563b75: __nla_put_64bit (STB_GLOBAL)
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
