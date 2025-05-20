# Function: <code>inet_register_protosw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81792ea0)
Location: net/ipv4/af_inet.c:1032
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
```
**Symbols:**

```
ffffffff81792ea0-ffffffff81792f4f: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81800660)
Location: net/ipv4/af_inet.c:1037
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
```
**Symbols:**

```
ffffffff81800660-ffffffff81800719: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818315b0)
Location: net/ipv4/af_inet.c:1043
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
```
**Symbols:**

```
ffffffff818315b0-ffffffff81831669: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81852b60)
Location: net/ipv4/af_inet.c:1061
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
```
**Symbols:**

```
ffffffff81852b60-ffffffff81852c18: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818d2970)
Location: net/ipv4/af_inet.c:1065
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
```
**Symbols:**

```
ffffffff818d2970-ffffffff818d2a28: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1120
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
```
**Symbols:**

```
ffffffff8192b606-ffffffff8192b62e: inet_register_protosw.cold.23 (STB_LOCAL)
ffffffff81928f30-ffffffff81928fd9: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1120
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
```
**Symbols:**

```
ffffffff8195aa96-ffffffff8195aabe: inet_register_protosw.cold.28 (STB_LOCAL)
ffffffff81958220-ffffffff819582c9: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1126
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
```
**Symbols:**

```
ffffffff819bf685-ffffffff819bf6ad: inet_register_protosw.cold (STB_LOCAL)
ffffffff819bcd40-ffffffff819bcddc: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1126
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
```
**Symbols:**

```
ffffffff819f62c5-ffffffff819f62ed: inet_register_protosw.cold (STB_LOCAL)
ffffffff819f3950-ffffffff819f39ec: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1158
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81ae47a5-ffffffff81ae47cd: inet_register_protosw.cold (STB_LOCAL)
ffffffff81ae1c10-ffffffff81ae1cac: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1156
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81c328d3-ffffffff81c328fb: inet_register_protosw.cold (STB_LOCAL)
ffffffff81aeea90-ffffffff81aeeb2c: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1160
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81c24ba7-ffffffff81c24bcf: inet_register_protosw.cold (STB_LOCAL)
ffffffff81ada1c0-ffffffff81ada25c: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1162
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81d3c36d-ffffffff81d3c397: inet_register_protosw.cold (STB_LOCAL)
ffffffff81b99350-ffffffff81b9949c: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1157
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81f08ba5-ffffffff81f08bcf: inet_register_protosw.cold (STB_LOCAL)
ffffffff81d2b190-ffffffff81d2b2e8: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ef2d80)
Location: net/ipv4/af_inet.c:1170
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81ef2d80-ffffffff81ef2eff: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81f52830)
Location: net/ipv4/af_inet.c:1169
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81f52830-ffffffff81f529af: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff82018b10)
Location: net/ipv4/af_inet.c:1189
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff82018b10-ffffffff82018c8f: inet_register_protosw (STB_GLOBAL)
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
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffff800010cabbf8)
Location: net/ipv4/af_inet.c:1126
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
```
**Symbols:**

```
ffff800010cabbf8-ffff800010cabd44: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c0db63a8)
Location: net/ipv4/af_inet.c:1126
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
```
**Symbols:**

```
c0db63a8-c0db6484: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c000000000dbf200)
Location: net/ipv4/af_inet.c:1126
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
```
**Symbols:**

```
c000000000dbf200-c000000000dbf324: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffe00080471c)
Location: net/ipv4/af_inet.c:1126
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
```
**Symbols:**

```
ffffffe00080471c-ffffffe0008047ea: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1126
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
```
**Symbols:**

```
ffffffff81996065-ffffffff8199608d: inet_register_protosw.cold (STB_LOCAL)
ffffffff819936f0-ffffffff8199378c: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1126
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
```
**Symbols:**

```
ffffffff8194fb25-ffffffff8194fb4d: inet_register_protosw.cold (STB_LOCAL)
ffffffff8194d1b0-ffffffff8194d24c: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1126
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
```
**Symbols:**

```
ffffffff81a00905-ffffffff81a0092d: inet_register_protosw.cold (STB_LOCAL)
ffffffff819fdf90-ffffffff819fe02c: inet_register_protosw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void inet_register_protosw(struct inet_protosw *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:1126
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
```
**Symbols:**

```
ffffffff81a0ade5-ffffffff81a0ae0d: inet_register_protosw.cold (STB_LOCAL)
ffffffff81a08320-ffffffff81a083bc: inet_register_protosw (STB_GLOBAL)
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
