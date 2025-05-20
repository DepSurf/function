# Function: <code>do_perms</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81391640)
Location: security/apparmor/af_unix.c:177
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81391640-ffffffff813916ee: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813ccbc0)
Location: security/apparmor/af_unix.c:177
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff813ccbc0-ffffffff813ccc6e: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813e4240)
Location: security/apparmor/af_unix.c:177
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff813e4240-ffffffff813e42ee: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813f1e30)
Location: security/apparmor/af_unix.c:177
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff813f1e30-ffffffff813f1eae: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81419eb0)
Location: security/apparmor/af_unix.c:177
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff81419eb0-ffffffff81419f2e: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8144c150)
Location: security/apparmor/af_unix.c:178
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff8144c150-ffffffff8144c1ce: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814690b0)
Location: security/apparmor/af_unix.c:178
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff814690b0-ffffffff8146912e: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81496100)
Location: security/apparmor/af_unix.c:178
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff81496100-ffffffff81496180: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814b0030)
Location: security/apparmor/af_unix.c:178
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff814b0030-ffffffff814b00b0: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff815109c0)
Location: security/apparmor/af_unix.c:178
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8152cec0)
Location: security/apparmor/af_unix.c:178
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81533b40)
Location: security/apparmor/af_unix.c:178
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff815920c0)
Location: security/apparmor/af_unix.c:178
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, struct aa_ruleset *rule, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff816328d0)
Location: security/apparmor/af_unix.c:187
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff816328d0-ffffffff816329de: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, struct aa_ruleset *rule, unsigned int state, u32 request, struct apparmor_audit_data *ad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff816e76e0)
Location: security/apparmor/af_unix.c:195
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff816e76e0-ffffffff816e77ee: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81721090)
Location: security/apparmor/af_unix.c:195
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff81721090-ffffffff8172119e: do_perms.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int do_perms(struct aa_profile *profile, struct aa_ruleset *rule, unsigned int state, u32 request, struct apparmor_audit_data *ad);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8175fbb0)
Location: security/apparmor/af_unix.c:195
Inline: True
Direct callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
```
In security/apparmor/af_inet.c (ffffffff81761e80)
Location: security/apparmor/af_inet.c:244
Inline: False
Direct callers:
  - security/apparmor/af_inet.c:aa_inet_file_perm
  - security/apparmor/af_inet.c:inet_label_sock_perm
  - security/apparmor/af_inet.c:aa_inet_opt_perm
  - security/apparmor/af_inet.c:aa_inet_accept_perm
  - security/apparmor/af_inet.c:aa_inet_listen_perm
  - security/apparmor/af_inet.c:aa_inet_bind_perm
  - security/apparmor/af_inet.c:aa_inet_create_perm
  - security/apparmor/af_inet.c:profile_remote_perm
```
**Symbols:**

```
ffffffff8175fbb0-ffffffff8175fcbe: do_perms.isra.0 (STB_LOCAL)
ffffffff81761e80-ffffffff81761fb1: do_perms (STB_LOCAL)
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
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffff8000105a7898)
Location: security/apparmor/af_unix.c:178
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffff8000105a7898-ffff8000105a7934: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c0757778)
Location: security/apparmor/af_unix.c:178
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
c0757778-c075780c: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c000000000724260)
Location: security/apparmor/af_unix.c:178
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
c000000000724260-c000000000724310: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffe0003f1002)
Location: security/apparmor/af_unix.c:178
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffe0003f1002-ffffffe0003f106c: do_perms (STB_LOCAL)
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
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a8610)
Location: security/apparmor/af_unix.c:178
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff814a8610-ffffffff814a8690: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81499030)
Location: security/apparmor/af_unix.c:178
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff81499030-ffffffff814990b0: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a46b0)
Location: security/apparmor/af_unix.c:178
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff814a46b0-ffffffff814a4730: do_perms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_perms(struct aa_profile *profile, unsigned int state, u32 request, struct common_audit_data *sa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814bcf40)
Location: security/apparmor/af_unix.c:178
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff814bcf40-ffffffff814bcfc0: do_perms (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct apparmor_audit_data *ad</code>
</li>
<li>
<b>Param removed. </b>
<code>struct common_audit_data *sa</code>
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
