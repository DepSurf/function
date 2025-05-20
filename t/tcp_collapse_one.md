# Function: <code>tcp_collapse_one</code>

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
In net/ipv4/tcp_input.c (ffffffff8176e56e)
Location: net/ipv4/tcp_input.c:4653
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
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
In net/ipv4/tcp_input.c (ffffffff817da6d0)
Location: net/ipv4/tcp_input.c:4716
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81808590)
Location: net/ipv4/tcp_input.c:4757
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff81808590-ffffffff81808626: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81828ba0)
Location: net/ipv4/tcp_input.c:4717
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff81828ba0-ffffffff81828c36: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a80a0)
Location: net/ipv4/tcp_input.c:4676
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff818a80a0-ffffffff818a8136: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818fd390)
Location: net/ipv4/tcp_input.c:4785
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff818fd390-ffffffff818fd41d: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192b270)
Location: net/ipv4/tcp_input.c:4809
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff8192b270-ffffffff8192b2fd: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8198e440)
Location: net/ipv4/tcp_input.c:4816
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff8198e440-ffffffff8198e4cd: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819c5130)
Location: net/ipv4/tcp_input.c:4867
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff819c5130-ffffffff819c51bd: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab06c0)
Location: net/ipv4/tcp_input.c:4908
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff81ab06c0-ffffffff81ab0752: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81abb6a0)
Location: net/ipv4/tcp_input.c:5047
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff81abb6a0-ffffffff81abb732: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aa6650)
Location: net/ipv4/tcp_input.c:5055
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff81aa6650-ffffffff81aa66df: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b62a40)
Location: net/ipv4/tcp_input.c:5089
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff81b62a40-ffffffff81b62acf: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf1220)
Location: net/ipv4/tcp_input.c:5119
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff81cf1220-ffffffff81cf12bb: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81eb5560)
Location: net/ipv4/tcp_input.c:5132
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff81eb5560-ffffffff81eb55fb: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f13990)
Location: net/ipv4/tcp_input.c:5137
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff81f13990-ffffffff81f13a2b: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fd7e70)
Location: net/ipv4/tcp_input.c:5275
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff81fd7e70-ffffffff81fd7f0b: tcp_collapse_one (STB_LOCAL)
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
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c785f8)
Location: net/ipv4/tcp_input.c:4867
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffff800010c785f8-ffff800010c786ac: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d863ac)
Location: net/ipv4/tcp_input.c:4867
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
c0d863ac-c0d86460: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d80310)
Location: net/ipv4/tcp_input.c:4867
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
c000000000d80310-c000000000d80410: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007da9a8)
Location: net/ipv4/tcp_input.c:4867
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffe0007da9a8-ffffffe0007daa60: tcp_collapse_one (STB_LOCAL)
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
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81964fa0)
Location: net/ipv4/tcp_input.c:4867
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff81964fa0-ffffffff8196502d: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8191ea90)
Location: net/ipv4/tcp_input.c:4867
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff8191ea90-ffffffff8191eb1d: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819cf770)
Location: net/ipv4/tcp_input.c:4867
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff819cf770-ffffffff819cf7fd: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *tcp_collapse_one(struct sock *sk, struct sk_buff *skb, struct sk_buff_head *list, struct rb_root *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d9300)
Location: net/ipv4/tcp_input.c:4867
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
```
**Symbols:**

```
ffffffff819d9300-ffffffff819d938d: tcp_collapse_one (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
