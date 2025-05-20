# Function: <code>__ip_options_compile</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff819181e0)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff819181e0-ffffffff81918891: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81979690)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff81979690-ffffffff81979d4c: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff819afff0)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff819afff0-ffffffff819b06ac: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81a99ee0)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/ip_options.c:ip_options_get
  - net/ipv4/ip_options.c:ip_options_get_from_user
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff81a99ee0-ffffffff81a9a5ab: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81aa3e40)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/ip_options.c:ip_options_get
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff81aa3e40-ffffffff81aa450b: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81a8ef20)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/ip_options.c:ip_options_get
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff81a8ef20-ffffffff81a8f5e3: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81b4a160)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/ip_options.c:ip_options_get
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff81b4a160-ffffffff81b4a823: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81cd7970)
Location: net/ipv4/ip_options.c:241
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/ip_options.c:ip_options_get
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff81cd7970-ffffffff81cd803f: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81e98000)
Location: net/ipv4/ip_options.c:241
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/ip_options.c:ip_options_get
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff81e98000-ffffffff81e986cf: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81ef6870)
Location: net/ipv4/ip_options.c:241
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/ip_options.c:ip_options_get
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff81ef6870-ffffffff81ef6f1b: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81fba800)
Location: net/ipv4/ip_options.c:241
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_send_dest_unreach
  - net/ipv4/ip_options.c:ip_options_get
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff81fba800-ffffffff81fbaeab: __ip_options_compile (STB_GLOBAL)
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
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffff800010c606d8)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffff800010c606d8-ffff800010c60c34: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (c0d6fffc)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
c0d6fffc-c0d70644: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (c000000000d636f0)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/ip_options.c:ip_options_get_finish
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
c000000000d636f0-c000000000d63e7c: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffe0007c893a)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/ip_options.c:ip_options_get_finish
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffe0007c893a-ffffffe0007c8ea0: __ip_options_compile (STB_GLOBAL)
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
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff8194fe60)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff8194fe60-ffffffff8195051c: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff81909950)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff81909950-ffffffff8190a00c: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff819ba630)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff819ba630-ffffffff819bacec: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ip_options_compile(struct net *net, struct ip_options *opt, struct sk_buff *skb, __be32 *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_options.c (ffffffff819c3f30)
Location: net/ipv4/ip_options.c:254
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/cipso_ipv4.c:cipso_v4_error
```
**Symbols:**

```
ffffffff819c3f30-ffffffff819c45ec: __ip_options_compile (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
