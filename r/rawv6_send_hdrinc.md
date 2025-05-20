# Function: <code>rawv6_send_hdrinc</code>

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
In net/ipv6/raw.c (ffffffff817e6069)
Location: net/ipv6/raw.c:612
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff818544da)
Location: net/ipv6/raw.c:612
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff818861fc)
Location: net/ipv6/raw.c:618
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff818ac7e9)
Location: net/ipv6/raw.c:618
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff8192f19c)
Location: net/ipv6/raw.c:621
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff81987b7a)
Location: net/ipv6/raw.c:621
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv6/raw.c (ffffffff819be4aa)
Location: net/ipv6/raw.c:620
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a2ce90)
Location: net/ipv6/raw.c:618
Inline: True
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81a2ce90-ffffffff81a2d353: rawv6_send_hdrinc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a639d0)
Location: net/ipv6/raw.c:618
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81a639d0-ffffffff81a63eb6: rawv6_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b5c460)
Location: net/ipv6/raw.c:618
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81b5c460-ffffffff81b5c933: rawv6_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b6aca0)
Location: net/ipv6/raw.c:618
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81b6aca0-ffffffff81b6b18b: rawv6_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b58fb0)
Location: net/ipv6/raw.c:618
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81b58fb0-ffffffff81b594d0: rawv6_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/raw.c (0)
Location: net/ipv6/raw.c:618
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81c20580-ffffffff81c20af0: rawv6_send_hdrinc (STB_LOCAL)
ffffffff81d4084c-ffffffff81d40890: rawv6_send_hdrinc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/raw.c (0)
Location: net/ipv6/raw.c:584
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81dbd2f0-ffffffff81dbd855: rawv6_send_hdrinc (STB_LOCAL)
ffffffff81f0d252-ffffffff81f0d288: rawv6_send_hdrinc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/raw.c (0)
Location: net/ipv6/raw.c:588
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81f8d830-ffffffff81f8dd95: rawv6_send_hdrinc (STB_LOCAL)
ffffffff820b46c4-ffffffff820b46fa: rawv6_send_hdrinc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/raw.c (0)
Location: net/ipv6/raw.c:587
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81fee010-ffffffff81fee57f: rawv6_send_hdrinc (STB_LOCAL)
ffffffff82135762-ffffffff82135791: rawv6_send_hdrinc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff820bbc30)
Location: net/ipv6/raw.c:587
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff820bbc30-ffffffff820bc166: rawv6_send_hdrinc (STB_LOCAL)
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
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffff800010d29ac0)
Location: net/ipv6/raw.c:618
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffff800010d29ac0-ffff800010d29f68: rawv6_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (c0e2d860)
Location: net/ipv6/raw.c:618
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
c0e2d860-c0e2dec0: rawv6_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (c000000000e5a870)
Location: net/ipv6/raw.c:618
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
c000000000e5a870-c000000000e5aec0: rawv6_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffe00086a31e)
Location: net/ipv6/raw.c:618
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffe00086a31e-ffffffe00086a774: rawv6_send_hdrinc (STB_LOCAL)
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
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a03060)
Location: net/ipv6/raw.c:618
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81a03060-ffffffff81a03546: rawv6_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff819bfe20)
Location: net/ipv6/raw.c:618
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff819bfe20-ffffffff819c0306: rawv6_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a6dae0)
Location: net/ipv6/raw.c:618
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81a6dae0-ffffffff81a6dfc6: rawv6_send_hdrinc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rawv6_send_hdrinc(struct sock *sk, struct msghdr *msg, int length, struct flowi6 *fl6, struct dst_entry **dstp, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81a7a100)
Location: net/ipv6/raw.c:618
Inline: False
Direct callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81a7a100-ffffffff81a7a608: rawv6_send_hdrinc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
