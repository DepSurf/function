# Function: <code>match_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81391890)
Location: security/apparmor/af_unix.c:89
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81391890-ffffffff813918e4: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813cce40)
Location: security/apparmor/af_unix.c:89
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffff813cce40-ffffffff813cce94: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813e44c0)
Location: security/apparmor/af_unix.c:89
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffff813e44c0-ffffffff813e4514: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813f2020)
Location: security/apparmor/af_unix.c:89
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffff813f2020-ffffffff813f206d: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8141a0a0)
Location: security/apparmor/af_unix.c:89
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffff8141a0a0-ffffffff8141a0ed: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8144c1d0)
Location: security/apparmor/af_unix.c:90
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffff8144c1d0-ffffffff8144c21b: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81469130)
Location: security/apparmor/af_unix.c:90
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffff81469130-ffffffff8146917b: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81496180)
Location: security/apparmor/af_unix.c:90
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffff81496180-ffffffff814961cd: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814b00b0)
Location: security/apparmor/af_unix.c:90
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffff814b00b0-ffffffff814b00fd: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8150f760)
Location: security/apparmor/af_unix.c:90
Inline: False
```
**Symbols:**

```
ffffffff8150f760-ffffffff8150f7b0: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8152c5a0)
Location: security/apparmor/af_unix.c:90
Inline: False
```
**Symbols:**

```
ffffffff8152c5a0-ffffffff8152c5f0: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff815328e0)
Location: security/apparmor/af_unix.c:90
Inline: False
```
**Symbols:**

```
ffffffff815328e0-ffffffff81532930: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81590e60)
Location: security/apparmor/af_unix.c:90
Inline: False
```
**Symbols:**

```
ffffffff81590e60-ffffffff81590eb0: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81633ae6)
Location: security/apparmor/af_unix.c:102
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff816e8cc2)
Location: security/apparmor/af_unix.c:110
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81722478)
Location: security/apparmor/af_unix.c:110
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81760c98)
Location: security/apparmor/af_unix.c:110
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
```
```
In security/apparmor/af_inet.c (ffffffff817621d0)
Location: security/apparmor/af_inet.c:261
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:match_addr_label
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
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffff8000105a7938)
Location: security/apparmor/af_unix.c:90
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffff8000105a7938-ffff8000105a79cc: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c075780c)
Location: security/apparmor/af_unix.c:90
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
c075780c-c0757858: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c000000000724310)
Location: security/apparmor/af_unix.c:90
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
c000000000724310-c0000000007243bc: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffe0003f106c)
Location: security/apparmor/af_unix.c:90
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffe0003f106c-ffffffe0003f10e2: match_addr (STB_LOCAL)
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
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a8690)
Location: security/apparmor/af_unix.c:90
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffff814a8690-ffffffff814a86dd: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814990b0)
Location: security/apparmor/af_unix.c:90
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffff814990b0-ffffffff814990fd: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a4730)
Location: security/apparmor/af_unix.c:90
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffff814a4730-ffffffff814a477d: match_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int match_addr(struct aa_profile *profile, unsigned int state, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814bcfc0)
Location: security/apparmor/af_unix.c:90
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffff814bcfc0-ffffffff814bd00d: match_addr (STB_LOCAL)
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
