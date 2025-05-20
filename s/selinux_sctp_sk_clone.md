# Function: <code>selinux_sctp_sk_clone</code>

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
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fa540)
Location: security/selinux/hooks.c:5360
Inline: False
```
**Symbols:**

```
ffffffff813fa540-ffffffff813fa5a8: selinux_sctp_sk_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814169d0)
Location: security/selinux/hooks.c:5081
Inline: False
```
**Symbols:**

```
ffffffff814169d0-ffffffff81416a35: selinux_sctp_sk_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81444430)
Location: security/selinux/hooks.c:5280
Inline: False
```
**Symbols:**

```
ffffffff81444430-ffffffff8144448f: selinux_sctp_sk_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145dfa0)
Location: security/selinux/hooks.c:5338
Inline: False
```
**Symbols:**

```
ffffffff8145dfa0-ffffffff8145dfff: selinux_sctp_sk_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b3a70)
Location: security/selinux/hooks.c:5331
Inline: False
```
**Symbols:**

```
ffffffff814b3a70-ffffffff814b3ae2: selinux_sctp_sk_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d0910)
Location: security/selinux/hooks.c:5347
Inline: False
```
**Symbols:**

```
ffffffff814d0910-ffffffff814d0984: selinux_sctp_sk_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d6f10)
Location: security/selinux/hooks.c:5511
Inline: False
```
**Symbols:**

```
ffffffff814d6f10-ffffffff814d6f84: selinux_sctp_sk_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5496
Inline: False
```
**Symbols:**

```
ffffffff8152fcf0-ffffffff8152fdb6: selinux_sctp_sk_clone (STB_LOCAL)
ffffffff81cd379b-ffffffff81cd37bf: selinux_sctp_sk_clone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void selinux_sctp_sk_clone(struct sctp_association *asoc, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5441
Inline: False
```
**Symbols:**

```
ffffffff815c7af0-ffffffff815c7bd5: selinux_sctp_sk_clone (STB_LOCAL)
ffffffff81e8691b-ffffffff81e8693f: selinux_sctp_sk_clone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void selinux_sctp_sk_clone(struct sctp_association *asoc, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5456
Inline: False
```
**Symbols:**

```
ffffffff816749c0-ffffffff81674aa5: selinux_sctp_sk_clone (STB_LOCAL)
ffffffff82073404-ffffffff82073428: selinux_sctp_sk_clone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void selinux_sctp_sk_clone(struct sctp_association *asoc, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5404
Inline: False
```
**Symbols:**

```
ffffffff816ac6c0-ffffffff816ac7a5: selinux_sctp_sk_clone (STB_LOCAL)
ffffffff820f2f9c-ffffffff820f2fc0: selinux_sctp_sk_clone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void selinux_sctp_sk_clone(struct sctp_association *asoc, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5498
Inline: False
```
**Symbols:**

```
ffffffff816e9a30-ffffffff816e9b15: selinux_sctp_sk_clone (STB_LOCAL)
ffffffff821d02b0-ffffffff821d02d4: selinux_sctp_sk_clone.cold (STB_LOCAL)
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
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054b000)
Location: security/selinux/hooks.c:5338
Inline: False
```
**Symbols:**

```
ffff80001054b000-ffff80001054b098: selinux_sctp_sk_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0700f7c)
Location: security/selinux/hooks.c:5338
Inline: False
```
**Symbols:**

```
c0700f7c-c0700ff4: selinux_sctp_sk_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a30f0)
Location: security/selinux/hooks.c:5338
Inline: False
```
**Symbols:**

```
c0000000006a30f0-c0000000006a3174: selinux_sctp_sk_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a5a58)
Location: security/selinux/hooks.c:5338
Inline: False
```
**Symbols:**

```
ffffffe0003a5a58-ffffffe0003a5adc: selinux_sctp_sk_clone (STB_LOCAL)
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
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81456580)
Location: security/selinux/hooks.c:5338
Inline: False
```
**Symbols:**

```
ffffffff81456580-ffffffff814565df: selinux_sctp_sk_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81446fc0)
Location: security/selinux/hooks.c:5338
Inline: False
```
**Symbols:**

```
ffffffff81446fc0-ffffffff8144701f: selinux_sctp_sk_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81452620)
Location: security/selinux/hooks.c:5338
Inline: False
```
**Symbols:**

```
ffffffff81452620-ffffffff8145267f: selinux_sctp_sk_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void selinux_sctp_sk_clone(struct sctp_endpoint *ep, struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81469210)
Location: security/selinux/hooks.c:5338
Inline: False
```
**Symbols:**

```
ffffffff81469210-ffffffff8146926f: selinux_sctp_sk_clone (STB_LOCAL)
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
