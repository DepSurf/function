# Function: <code>selinux_sctp_assoc_request</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fd080)
Location: security/selinux/hooks.c:5215
Inline: False
```
**Symbols:**

```
ffffffff813fd080-ffffffff813fd233: selinux_sctp_assoc_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814192f0)
Location: security/selinux/hooks.c:4930
Inline: False
```
**Symbols:**

```
ffffffff814192f0-ffffffff8141947f: selinux_sctp_assoc_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81446cb0)
Location: security/selinux/hooks.c:5129
Inline: False
```
**Symbols:**

```
ffffffff81446cb0-ffffffff81446e43: selinux_sctp_assoc_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81460840)
Location: security/selinux/hooks.c:5187
Inline: False
```
**Symbols:**

```
ffffffff81460840-ffffffff814609d3: selinux_sctp_assoc_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b3e10)
Location: security/selinux/hooks.c:5180
Inline: False
```
**Symbols:**

```
ffffffff814b3e10-ffffffff814b3fb3: selinux_sctp_assoc_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d14f0)
Location: security/selinux/hooks.c:5196
Inline: False
```
**Symbols:**

```
ffffffff814d14f0-ffffffff814d1697: selinux_sctp_assoc_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d79e0)
Location: security/selinux/hooks.c:5360
Inline: False
```
**Symbols:**

```
ffffffff814d79e0-ffffffff814d7b87: selinux_sctp_assoc_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5345
Inline: False
```
**Symbols:**

```
ffffffff815307e0-ffffffff815309c9: selinux_sctp_assoc_request (STB_LOCAL)
ffffffff81cd37bf-ffffffff81cd3803: selinux_sctp_assoc_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int selinux_sctp_assoc_request(struct sctp_association *asoc, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5309
Inline: False
```
**Symbols:**

```
ffffffff815c8130-ffffffff815c8208: selinux_sctp_assoc_request (STB_LOCAL)
ffffffff81e86975-ffffffff81e8698a: selinux_sctp_assoc_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int selinux_sctp_assoc_request(struct sctp_association *asoc, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5324
Inline: False
```
**Symbols:**

```
ffffffff81675230-ffffffff81675308: selinux_sctp_assoc_request (STB_LOCAL)
ffffffff8207345e-ffffffff82073473: selinux_sctp_assoc_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int selinux_sctp_assoc_request(struct sctp_association *asoc, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5272
Inline: False
```
**Symbols:**

```
ffffffff816ad420-ffffffff816ad4ef: selinux_sctp_assoc_request (STB_LOCAL)
ffffffff820f3067-ffffffff820f307c: selinux_sctp_assoc_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int selinux_sctp_assoc_request(struct sctp_association *asoc, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5366
Inline: False
```
**Symbols:**

```
ffffffff816e9090-ffffffff816e915f: selinux_sctp_assoc_request (STB_LOCAL)
ffffffff821d029b-ffffffff821d02b0: selinux_sctp_assoc_request.cold (STB_LOCAL)
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
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054e200)
Location: security/selinux/hooks.c:5187
Inline: False
```
**Symbols:**

```
ffff80001054e200-ffff80001054e374: selinux_sctp_assoc_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c07076f0)
Location: security/selinux/hooks.c:5187
Inline: False
```
**Symbols:**

```
c07076f0-c0707880: selinux_sctp_assoc_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006ae140)
Location: security/selinux/hooks.c:5187
Inline: False
```
**Symbols:**

```
c0000000006ae140-c0000000006ae350: selinux_sctp_assoc_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a80b2)
Location: security/selinux/hooks.c:5187
Inline: False
```
**Symbols:**

```
ffffffe0003a80b2-ffffffe0003a81ea: selinux_sctp_assoc_request (STB_LOCAL)
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
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81458e20)
Location: security/selinux/hooks.c:5187
Inline: False
```
**Symbols:**

```
ffffffff81458e20-ffffffff81458fb3: selinux_sctp_assoc_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81449850)
Location: security/selinux/hooks.c:5187
Inline: False
```
**Symbols:**

```
ffffffff81449850-ffffffff814499e3: selinux_sctp_assoc_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81454ec0)
Location: security/selinux/hooks.c:5187
Inline: False
```
**Symbols:**

```
ffffffff81454ec0-ffffffff81455053: selinux_sctp_assoc_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int selinux_sctp_assoc_request(struct sctp_endpoint *ep, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146fe70)
Location: security/selinux/hooks.c:5187
Inline: False
```
**Symbols:**

```
ffffffff8146fe70-ffffffff81470003: selinux_sctp_assoc_request (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sctp_association *asoc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sctp_endpoint *ep</code>
</li>
</ul>
</details>
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
