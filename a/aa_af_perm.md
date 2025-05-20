# Function: <code>aa_af_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/net.c (ffffffff81390bd0)
Location: security/apparmor/net.c:183
Inline: True
Direct callers:
  - security/apparmor/net.c:aa_sock_create_perm
```
**Symbols:**

```
ffffffff81390bd0-ffffffff81390cf5: aa_af_perm.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/net.c (ffffffff813cc1c0)
Location: security/apparmor/net.c:183
Inline: True
Direct callers:
  - security/apparmor/net.c:aa_sock_create_perm
```
**Symbols:**

```
ffffffff813cc1c0-ffffffff813cc2e5: aa_af_perm.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/net.c (ffffffff813e3840)
Location: security/apparmor/net.c:183
Inline: True
Direct callers:
  - security/apparmor/net.c:aa_sock_create_perm
```
**Symbols:**

```
ffffffff813e3840-ffffffff813e3965: aa_af_perm.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813f19e0)
Location: security/apparmor/net.c:181
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_create_perm
```
**Symbols:**

```
ffffffff813f19e0-ffffffff813f1b09: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81419a00)
Location: security/apparmor/net.c:181
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_create_perm
```
**Symbols:**

```
ffffffff81419a00-ffffffff81419b29: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8144be60)
Location: security/apparmor/net.c:201
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff8144be60-ffffffff8144bf89: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81468de0)
Location: security/apparmor/net.c:201
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff81468de0-ffffffff81468f09: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81495e30)
Location: security/apparmor/net.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff81495e30-ffffffff81495f56: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814afd60)
Location: security/apparmor/net.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff814afd60-ffffffff814afe86: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8150f1d0)
Location: security/apparmor/net.c:198
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff8150f1d0-ffffffff8150f2f6: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8152c010)
Location: security/apparmor/net.c:200
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff8152c010-ffffffff8152c136: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff815322b0)
Location: security/apparmor/net.c:200
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff815322b0-ffffffff815323d6: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81590830)
Location: security/apparmor/net.c:200
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff81590830-ffffffff81590956: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81631910)
Location: security/apparmor/net.c:200
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff81631910-ffffffff81631a57: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_af_perm(const struct cred *subj_cred, struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff816e6670)
Location: security/apparmor/net.c:202
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff816e6670-ffffffff816e67a2: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_af_perm(const struct cred *subj_cred, struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8171fda0)
Location: security/apparmor/net.c:202
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff8171fda0-ffffffff8171fed2: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_af_perm(const struct cred *subj_cred, struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8175e7d0)
Location: security/apparmor/net.c:205
Inline: False
```
**Symbols:**

```
ffffffff8175e7d0-ffffffff8175e902: aa_af_perm (STB_GLOBAL)
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
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffff8000105a74b8)
Location: security/apparmor/net.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffff8000105a74b8-ffff8000105a75e0: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (c0757480)
Location: security/apparmor/net.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
c0757480-c07575b0: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (c000000000723e10)
Location: security/apparmor/net.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
c000000000723e10-c000000000723f98: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffe0003f0cfa)
Location: security/apparmor/net.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffe0003f0cfa-ffffffe0003f0df8: aa_af_perm (STB_GLOBAL)
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
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814a8340)
Location: security/apparmor/net.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff814a8340-ffffffff814a8466: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81498d60)
Location: security/apparmor/net.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff81498d60-ffffffff81498e86: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814a43e0)
Location: security/apparmor/net.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff814a43e0-ffffffff814a4506: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_af_perm(struct aa_label *label, const char *op, u32 request, u16 family, int type, int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814bcc70)
Location: security/apparmor/net.c:197
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_create
```
**Symbols:**

```
ffffffff814bcc70-ffffffff814bcd96: aa_af_perm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>label, op, request, family, type, protocol</code> ➡️ <code>subj_cred, label, op, request, family, type, protocol</code>
</li>
</ul>
</details>
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
