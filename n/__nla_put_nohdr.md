# Function: <code>__nla_put_nohdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81415b40)
Location: lib/nlattr.c:447
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff81415b40-ffffffff81415b64: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8145d9d7)
Location: lib/nlattr.c:522
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff8145d970-ffffffff8145d994: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8147c497)
Location: lib/nlattr.c:522
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff8147c430-ffffffff8147c454: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814856e0)
Location: lib/nlattr.c:525
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff814856e0-ffffffff8148571d: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814c1870)
Location: lib/nlattr.c:603
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff814c1870-ffffffff814c18ad: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814f25a0)
Location: lib/nlattr.c:603
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff814f25a0-ffffffff814f25dd: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815062d0)
Location: lib/nlattr.c:778
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff815062d0-ffffffff8150630d: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81534ca0)
Location: lib/nlattr.c:810
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff81534ca0-ffffffff81534ce0: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81555ad0)
Location: lib/nlattr.c:810
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff81555ad0-ffffffff81555b10: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de860)
Location: lib/nlattr.c:962
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff815de860-ffffffff815de8a0: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815fbf00)
Location: lib/nlattr.c:1028
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff815fbf00-ffffffff815fbf40: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815deb40)
Location: lib/nlattr.c:1028
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff815deb40-ffffffff815deb80: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8164a6c0)
Location: lib/nlattr.c:1028
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff8164a6c0-ffffffff8164a700: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81760de0)
Location: lib/nlattr.c:1028
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff81760de0-ffffffff81760e2c: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8188fb40)
Location: lib/nlattr.c:1043
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff8188fb40-ffffffff8188fb8c: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d1fb0)
Location: lib/nlattr.c:1043
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff818d1fb0-ffffffff818d1ffc: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81923f80)
Location: lib/nlattr.c:1075
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff81923f80-ffffffff81923fcc: __nla_put_nohdr (STB_GLOBAL)
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
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffff800010661f98)
Location: lib/nlattr.c:810
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffff800010661f98-ffff800010661ff0: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c080b018)
Location: lib/nlattr.c:810
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
c080b018-c080b060: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c000000000816280)
Location: lib/nlattr.c:810
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
c000000000816280-c000000000816304: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffe00048e998)
Location: lib/nlattr.c:810
Inline: True
Inline callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffe00048e93c-ffffffe00048e96c: __nla_put_nohdr (STB_GLOBAL)
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
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8154e0b0)
Location: lib/nlattr.c:810
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff8154e0b0-ffffffff8154e0f0: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8153e390)
Location: lib/nlattr.c:810
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff8153e390-ffffffff8153e3d0: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81549df0)
Location: lib/nlattr.c:810
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff81549df0-ffffffff81549e30: __nla_put_nohdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __nla_put_nohdr(struct sk_buff *skb, int attrlen, const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81563c40)
Location: lib/nlattr.c:810
Inline: False
Direct callers:
  - lib/nlattr.c:nla_put_nohdr
```
**Symbols:**

```
ffffffff81563c40-ffffffff81563c80: __nla_put_nohdr (STB_GLOBAL)
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
