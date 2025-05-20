# Function: <code>match_to_sk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81391970)
Location: security/apparmor/af_unix.c:127
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81391970-ffffffff813919b4: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813ccf60)
Location: security/apparmor/af_unix.c:127
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff813ccf60-ffffffff813ccfa4: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813e45e0)
Location: security/apparmor/af_unix.c:127
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff813e45e0-ffffffff813e4624: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813f2130)
Location: security/apparmor/af_unix.c:127
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff813f2130-ffffffff813f216d: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8141a1b0)
Location: security/apparmor/af_unix.c:127
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff8141a1b0-ffffffff8141a1ed: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8144c2e0)
Location: security/apparmor/af_unix.c:128
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff8144c2e0-ffffffff8144c31d: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81469240)
Location: security/apparmor/af_unix.c:128
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff81469240-ffffffff8146927d: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81496290)
Location: security/apparmor/af_unix.c:128
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff81496290-ffffffff814962cf: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814b01c0)
Location: security/apparmor/af_unix.c:128
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff814b01c0-ffffffff814b01ff: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81510991)
Location: security/apparmor/af_unix.c:128
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
Direct callers:
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff8150fb00-ffffffff8150fbdc: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8152ce91)
Location: security/apparmor/af_unix.c:128
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
Direct callers:
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff8152c950-ffffffff8152ca2c: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81533b11)
Location: security/apparmor/af_unix.c:128
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
Direct callers:
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff81532c80-ffffffff81532d5c: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81592091)
Location: security/apparmor/af_unix.c:128
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
Direct callers:
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff81591200-ffffffff815912dc: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int match_to_sk(struct aa_dfa *dfa, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81633aa6)
Location: security/apparmor/af_unix.c:137
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
Direct callers:
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff81632cc0-ffffffff81632de3: match_to_sk (STB_LOCAL)
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
In security/apparmor/af_unix.c (ffffffff816e8c86)
Location: security/apparmor/af_unix.c:145
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
In security/apparmor/af_unix.c (ffffffff81722435)
Location: security/apparmor/af_unix.c:145
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
In security/apparmor/af_unix.c (ffffffff81760c55)
Location: security/apparmor/af_unix.c:145
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
```
```
In security/apparmor/af_inet.c (ffffffff8176442d)
Location: security/apparmor/af_inet.c:345
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:aa_inet_file_perm
  - security/apparmor/af_inet.c:inet_label_sock_perm
  - security/apparmor/af_inet.c:aa_inet_opt_perm
  - security/apparmor/af_inet.c:aa_inet_accept_perm
  - security/apparmor/af_inet.c:aa_inet_listen_perm
  - security/apparmor/af_inet.c:aa_inet_bind_perm
  - security/apparmor/af_inet.c:profile_remote_perm
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
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffff8000105a7ab0)
Location: security/apparmor/af_unix.c:128
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffff8000105a7ab0-ffff8000105a7b1c: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c0757940)
Location: security/apparmor/af_unix.c:128
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
c0757940-c0757998: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c000000000724500)
Location: security/apparmor/af_unix.c:128
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
c000000000724500-c000000000724554: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffe0003f1182)
Location: security/apparmor/af_unix.c:128
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffe0003f1182-ffffffe0003f11dc: match_to_sk (STB_LOCAL)
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
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a87a0)
Location: security/apparmor/af_unix.c:128
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff814a87a0-ffffffff814a87df: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814991c0)
Location: security/apparmor/af_unix.c:128
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff814991c0-ffffffff814991ff: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a4840)
Location: security/apparmor/af_unix.c:128
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff814a4840-ffffffff814a487f: match_to_sk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int match_to_sk(struct aa_profile *profile, unsigned int state, struct unix_sock *u, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814bd0d0)
Location: security/apparmor/af_unix.c:128
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
**Symbols:**

```
ffffffff814bd0d0-ffffffff814bd10f: match_to_sk (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aa_dfa *dfa</code>
</li>
<li>
<b>Param removed. </b>
<code>struct aa_profile *profile</code>
</li>
</ul>
</details>
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
