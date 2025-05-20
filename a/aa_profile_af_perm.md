# Function: <code>aa_profile_af_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813906d0)
Location: security/apparmor/net.c:161
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_label_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff813906d0-ffffffff813907eb: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813cbc80)
Location: security/apparmor/net.c:161
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff813cbc80-ffffffff813cbd9b: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813e3300)
Location: security/apparmor/net.c:161
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff813e3300-ffffffff813e341b: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813f17b0)
Location: security/apparmor/net.c:159
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_label_sk_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff813f17b0-ffffffff813f1891: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814197d0)
Location: security/apparmor/net.c:159
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_label_sk_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff814197d0-ffffffff814198b1: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8144bc00)
Location: security/apparmor/net.c:163
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_label_sk_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff8144bc00-ffffffff8144bd15: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81468b70)
Location: security/apparmor/net.c:163
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff81468b70-ffffffff81468c85: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81495ba0)
Location: security/apparmor/net.c:159
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff81495ba0-ffffffff81495cc4: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814afad0)
Location: security/apparmor/net.c:159
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff814afad0-ffffffff814afbf4: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8150ef50)
Location: security/apparmor/net.c:160
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff8150ef50-ffffffff8150f070: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8152bd90)
Location: security/apparmor/net.c:162
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff8152bd90-ffffffff8152beb0: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81532030)
Location: security/apparmor/net.c:162
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff81532030-ffffffff81532150: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/net.c (0)
Location: security/apparmor/net.c:162
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff81cd67bb-ffffffff81cd68d4: aa_profile_af_perm.cold (STB_LOCAL)
ffffffff81590530-ffffffff815906ce: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/net.c (0)
Location: security/apparmor/net.c:162
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff81e89723-ffffffff81e89839: aa_profile_af_perm.cold (STB_LOCAL)
ffffffff81631590-ffffffff81631797: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct apparmor_audit_data *ad, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/net.c (0)
Location: security/apparmor/net.c:164
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff82074cde-ffffffff82074df4: aa_profile_af_perm.cold (STB_LOCAL)
ffffffff816e62d0-ffffffff816e64d7: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct apparmor_audit_data *ad, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/net.c (0)
Location: security/apparmor/net.c:164
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff820f48cd-ffffffff820f49a3: aa_profile_af_perm.cold (STB_LOCAL)
ffffffff8171f9d0-ffffffff8171fc0c: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct apparmor_audit_data *ad, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/net.c (0)
Location: security/apparmor/net.c:166
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
ffffffff821d1d61-ffffffff821d1e37: aa_profile_af_perm.cold (STB_LOCAL)
ffffffff8175e400-ffffffff8175e638: aa_profile_af_perm (STB_GLOBAL)
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
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffff8000105a7230)
Location: security/apparmor/net.c:159
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffff8000105a7230-ffff8000105a7378: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (c07571f8)
Location: security/apparmor/net.c:159
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
c07571f8-c075732c: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (c000000000723ab0)
Location: security/apparmor/net.c:159
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
c000000000723ab0-c000000000723c5c: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffe0003f0ad4)
Location: security/apparmor/net.c:159
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffe0003f0ad4-ffffffe0003f0be8: aa_profile_af_perm (STB_GLOBAL)
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
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814a80b0)
Location: security/apparmor/net.c:159
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff814a80b0-ffffffff814a81d4: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81498ad0)
Location: security/apparmor/net.c:159
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff81498ad0-ffffffff81498bf4: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814a4150)
Location: security/apparmor/net.c:159
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff814a4150-ffffffff814a4274: aa_profile_af_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile *profile, struct common_audit_data *sa, u32 request, u16 family, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814bc9e0)
Location: security/apparmor/net.c:159
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff814bc9e0-ffffffff814bcb04: aa_profile_af_perm (STB_GLOBAL)
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
