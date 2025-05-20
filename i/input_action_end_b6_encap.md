# Function: <code>input_action_end_b6_encap</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff8194f3d0)
Location: net/ipv6/seg6_local.c:419
Inline: True
```
**Symbols:**

```
ffffffff8194f3d0-ffffffff8194f436: input_action_end_b6_encap.part.10 (STB_LOCAL)
ffffffff8194f580-ffffffff8194f64e: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff819a90a0)
Location: net/ipv6/seg6_local.c:429
Inline: True
```
**Symbols:**

```
ffffffff819a90a0-ffffffff819a9106: input_action_end_b6_encap.part.16 (STB_LOCAL)
ffffffff819a9170-ffffffff819a9228: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff819df990)
Location: net/ipv6/seg6_local.c:429
Inline: True
```
**Symbols:**

```
ffffffff819df990-ffffffff819df9f3: input_action_end_b6_encap.part.17 (STB_LOCAL)
ffffffff819dfa60-ffffffff819dfb18: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a4e510)
Location: net/ipv6/seg6_local.c:424
Inline: True
```
**Symbols:**

```
ffffffff81a4e510-ffffffff81a4e635: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a85180)
Location: net/ipv6/seg6_local.c:437
Inline: True
```
**Symbols:**

```
ffffffff81a85180-ffffffff81a852a5: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b80480)
Location: net/ipv6/seg6_local.c:451
Inline: False
```
**Symbols:**

```
ffffffff81b80480-ffffffff81b805c2: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b8fd00)
Location: net/ipv6/seg6_local.c:768
Inline: False
```
**Symbols:**

```
ffffffff81b8fd00-ffffffff81b8fe42: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b7ecf0)
Location: net/ipv6/seg6_local.c:797
Inline: False
```
**Symbols:**

```
ffffffff81b7ecf0-ffffffff81b7ee59: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81c4a490)
Location: net/ipv6/seg6_local.c:840
Inline: False
```
**Symbols:**

```
ffffffff81c4a490-ffffffff81c4a5f9: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81de9d90)
Location: net/ipv6/seg6_local.c:841
Inline: False
```
**Symbols:**

```
ffffffff81de9d90-ffffffff81de9ee2: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81fbd4f0)
Location: net/ipv6/seg6_local.c:966
Inline: False
```
**Symbols:**

```
ffffffff81fbd4f0-ffffffff81fbd642: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff8201e290)
Location: net/ipv6/seg6_local.c:1293
Inline: False
```
**Symbols:**

```
ffffffff8201e290-ffffffff8201e3e2: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff820ed270)
Location: net/ipv6/seg6_local.c:1353
Inline: False
```
**Symbols:**

```
ffffffff820ed270-ffffffff820ed3c2: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (ffff800010d51208)
Location: net/ipv6/seg6_local.c:437
Inline: True
```
**Symbols:**

```
ffff800010d51208-ffff800010d5127c: input_action_end_b6_encap.part.0 (STB_LOCAL)
ffff800010d512f8-ffff800010d513bc: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (c0e51dc8)
Location: net/ipv6/seg6_local.c:437
Inline: False
```
**Symbols:**

```
c0e51dc8-c0e51ecc: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (c000000000e891f0)
Location: net/ipv6/seg6_local.c:437
Inline: True
```
**Symbols:**

```
c000000000e891f0-c000000000e89358: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffe00088947a)
Location: net/ipv6/seg6_local.c:437
Inline: True
```
**Symbols:**

```
ffffffe00088947a-ffffffe0008894e0: input_action_end_b6_encap.part.0 (STB_LOCAL)
ffffffe00088954c-ffffffe000889604: input_action_end_b6_encap (STB_LOCAL)
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
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a24810)
Location: net/ipv6/seg6_local.c:437
Inline: True
```
**Symbols:**

```
ffffffff81a24810-ffffffff81a24935: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff819e15d0)
Location: net/ipv6/seg6_local.c:437
Inline: True
```
**Symbols:**

```
ffffffff819e15d0-ffffffff819e16f5: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a8f290)
Location: net/ipv6/seg6_local.c:437
Inline: True
```
**Symbols:**

```
ffffffff81a8f290-ffffffff81a8f3b5: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int input_action_end_b6_encap(struct sk_buff *skb, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81a9c010)
Location: net/ipv6/seg6_local.c:437
Inline: True
```
**Symbols:**

```
ffffffff81a9c010-ffffffff81a9c135: input_action_end_b6_encap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
