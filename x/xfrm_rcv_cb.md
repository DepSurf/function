# Function: <code>xfrm_rcv_cb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff817bbb4f)
Location: net/xfrm/xfrm_input.c:81
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff818289e9)
Location: net/xfrm/xfrm_input.c:81
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8185a3c9)
Location: net/xfrm/xfrm_input.c:81
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8187dd30)
Location: net/xfrm/xfrm_input.c:75
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff8187dd30-ffffffff8187dd68: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff818ff0fb)
Location: net/xfrm/xfrm_input.c:92
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81955cd5)
Location: net/xfrm/xfrm_input.c:99
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8198a7ab)
Location: net/xfrm/xfrm_input.c:97
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff819f45c0)
Location: net/xfrm/xfrm_input.c:99
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff819f45c0-ffffffff819f45fb: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81a2b2d0)
Location: net/xfrm/xfrm_input.c:99
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81a2b2d0-ffffffff81a2b30b: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b1d4e0)
Location: net/xfrm/xfrm_input.c:100
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b1d4e0-ffffffff81b1d51b: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b2bfc0)
Location: net/xfrm/xfrm_input.c:100
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b2bfc0-ffffffff81b2c03f: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b19c20)
Location: net/xfrm/xfrm_input.c:100
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b19c20-ffffffff81b19c9f: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81bddef0)
Location: net/xfrm/xfrm_input.c:100
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81bddef0-ffffffff81bddfaa: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81d74af0)
Location: net/xfrm/xfrm_input.c:100
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81d74af0-ffffffff81d74bb1: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81f41160)
Location: net/xfrm/xfrm_input.c:102
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81f41160-ffffffff81f41221: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81fa09f0)
Location: net/xfrm/xfrm_input.c:102
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81fa09f0-ffffffff81fa0ab1: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8206dd50)
Location: net/xfrm/xfrm_input.c:102
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff8206dd50-ffffffff8206de11: xfrm_rcv_cb (STB_LOCAL)
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
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffff800010ce9af8)
Location: net/xfrm/xfrm_input.c:99
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffff800010ce9af8-ffff800010ce9b7c: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (c0df1c8c)
Location: net/xfrm/xfrm_input.c:99
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
c0df1c8c-c0df1d1c: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (c000000000e0d550)
Location: net/xfrm/xfrm_input.c:99
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
c000000000e0d550-c000000000e0d5d8: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffe0008379ec)
Location: net/xfrm/xfrm_input.c:99
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffe0008379ec-ffffffe000837a5c: xfrm_rcv_cb (STB_LOCAL)
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
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff819ca960)
Location: net/xfrm/xfrm_input.c:99
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff819ca960-ffffffff819ca99b: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81987750)
Location: net/xfrm/xfrm_input.c:99
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81987750-ffffffff8198778b: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81a353e0)
Location: net/xfrm/xfrm_input.c:99
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81a353e0-ffffffff81a3541b: xfrm_rcv_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xfrm_rcv_cb(struct sk_buff *skb, unsigned int family, u8 protocol, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81a40e20)
Location: net/xfrm/xfrm_input.c:99
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81a40e20-ffffffff81a40e9a: xfrm_rcv_cb (STB_LOCAL)
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
