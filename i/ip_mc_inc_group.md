# Function: <code>ip_mc_inc_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81796c20)
Location: net/ipv4/igmp.c:1314
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81796c20-ffffffff81796ea4: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81805aa0)
Location: net/ipv4/igmp.c:1317
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81805aa0-ffffffff81805d29: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81836870)
Location: net/ipv4/igmp.c:1348
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81836870-ffffffff81836a6c: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81858070)
Location: net/ipv4/igmp.c:1357
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81858070-ffffffff8185824a: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818d7ba0)
Location: net/ipv4/igmp.c:1385
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff818d7ba0-ffffffff818d7d7a: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8192f667)
Location: net/ipv4/igmp.c:1442
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff8192e730-ffffffff8192e742: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8195eb4a)
Location: net/ipv4/igmp.c:1451
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff8195dc60-ffffffff8195dc72: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819c39cf)
Location: net/ipv4/igmp.c:1476
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff819c3000-ffffffff819c3017: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819fa56f)
Location: net/ipv4/igmp.c:1476
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff819f9ba0-ffffffff819f9bb7: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae8e7f)
Location: net/ipv4/igmp.c:1474
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81ae7960-ffffffff81ae7977: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af5d8f)
Location: net/ipv4/igmp.c:1474
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81af4840-ffffffff81af4857: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae14df)
Location: net/ipv4/igmp.c:1481
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81adfe70-ffffffff81adfe87: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ba0bbf)
Location: net/ipv4/igmp.c:1481
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81b9f470-ffffffff81b9f487: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d330af)
Location: net/ipv4/igmp.c:1488
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81d31890-ffffffff81d318b3: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81efb38f)
Location: net/ipv4/igmp.c:1488
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81efa090-ffffffff81efa0b3: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f5ae1f)
Location: net/ipv4/igmp.c:1489
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81f59b30-ffffffff81f59b53: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8202135f)
Location: net/ipv4/igmp.c:1491
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff82020050-ffffffff82020073: ip_mc_inc_group (STB_GLOBAL)
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
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffff800010cb1c80)
Location: net/ipv4/igmp.c:1476
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffff800010cb0f58-ffff800010cb0f94: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c0dbd8ac)
Location: net/ipv4/igmp.c:1476
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
c0dbaf58-c0dbaf7c: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c000000000dc8c7c)
Location: net/ipv4/igmp.c:1476
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
c000000000dc74a0-c000000000dc74bc: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffe00080a632)
Location: net/ipv4/igmp.c:1476
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffe000808582-ffffffe0008085bc: ip_mc_inc_group (STB_GLOBAL)
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
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8199a30f)
Location: net/ipv4/igmp.c:1476
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81999940-ffffffff81999957: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81953dcf)
Location: net/ipv4/igmp.c:1476
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81953400-ffffffff81953417: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a04baf)
Location: net/ipv4/igmp.c:1476
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81a041e0-ffffffff81a041f7: ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ip_mc_inc_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a0f13f)
Location: net/ipv4/igmp.c:1476
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81a0e750-ffffffff81a0e767: ip_mc_inc_group (STB_GLOBAL)
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
