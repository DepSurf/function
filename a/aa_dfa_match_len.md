# Function: <code>aa_dfa_match_len</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81379550)
Location: security/apparmor/match.c:327
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/af_unix.c:match_to_prot
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
```
**Symbols:**

```
ffffffff81379550-ffffffff8137961f: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813b22d0)
Location: security/apparmor/match.c:331
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff813b22d0-ffffffff813b23a5: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813c9490)
Location: security/apparmor/match.c:331
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff813c9490-ffffffff813c9565: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813deb70)
Location: security/apparmor/match.c:331
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff813deb70-ffffffff813dec39: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81405510)
Location: security/apparmor/match.c:331
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff81405510-ffffffff814055d9: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81436670)
Location: security/apparmor/match.c:404
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff81436670-ffffffff81436740: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814532d0)
Location: security/apparmor/match.c:404
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff814532d0-ffffffff814533a0: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81480c30)
Location: security/apparmor/match.c:400
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff81480c30-ffffffff81480d0c: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8149a930)
Location: security/apparmor/match.c:415
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff8149a930-ffffffff8149aa0c: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814f3220)
Location: security/apparmor/match.c:439
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff814f3220-ffffffff814f32fc: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff815103f0)
Location: security/apparmor/match.c:439
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff815103f0-ffffffff815104cc: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81516da0)
Location: security/apparmor/match.c:439
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff81516da0-ffffffff81516e7f: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81574da0)
Location: security/apparmor/match.c:439
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff81574da0-ffffffff81574e7f: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81612760)
Location: security/apparmor/match.c:439
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/file.c:__aa_path_perm
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff81612760-ffffffff81612870: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816c5310)
Location: security/apparmor/match.c:439
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/file.c:__aa_path_perm
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
**Symbols:**

```
ffffffff816c5310-ffffffff816c5420: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816fdf10)
Location: security/apparmor/match.c:395
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/file.c:__aa_path_perm
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/notify.c:notification_match
```
**Symbols:**

```
ffffffff816fdf10-ffffffff816fe020: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8173b4a0)
Location: security/apparmor/match.c:395
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/capability.c:profile_capable
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_components_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/domain.c:label_compound_match
  - security/apparmor/file.c:__aa_path_perm
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_components_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/label.c:label_compound_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_inet.c:aa_inet_file_perm
  - security/apparmor/af_inet.c:inet_label_sock_perm
  - security/apparmor/af_inet.c:aa_inet_opt_perm
  - security/apparmor/af_inet.c:aa_inet_opt_perm
  - security/apparmor/af_inet.c:aa_inet_opt_perm
  - security/apparmor/af_inet.c:aa_inet_opt_perm
  - security/apparmor/af_inet.c:aa_inet_accept_perm
  - security/apparmor/af_inet.c:aa_inet_listen_perm
  - security/apparmor/af_inet.c:aa_inet_listen_perm
  - security/apparmor/af_inet.c:aa_inet_listen_perm
  - security/apparmor/af_inet.c:aa_inet_bind_perm
  - security/apparmor/af_inet.c:aa_inet_create_perm
  - security/apparmor/af_inet.c:profile_remote_perm
  - security/apparmor/af_inet.c:profile_remote_perm
  - security/apparmor/af_inet.c:match_to_prot
  - security/apparmor/af_inet.c:match_to_prot
  - security/apparmor/af_inet.c:match_addr_label
  - security/apparmor/af_inet.c:match_addr_label
  - security/apparmor/af_inet.c:match_addr_label
  - security/apparmor/af_inet.c:match_addr_label
  - security/apparmor/notify.c:notification_match
```
**Symbols:**

```
ffffffff8173b4a0-ffffffff8173b5b0: aa_dfa_match_len (STB_GLOBAL)
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
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffff800010590a78)
Location: security/apparmor/match.c:415
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_to_prot
```
**Symbols:**

```
ffff800010590a78-ffff800010590b70: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c07417a4)
Location: security/apparmor/match.c:415
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
c07417a4-c07418a8: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c0000000007042d0)
Location: security/apparmor/match.c:415
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
c0000000007042d0-c00000000070443c: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffe0003de502)
Location: security/apparmor/match.c:415
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_to_prot
```
**Symbols:**

```
ffffffe0003de502-ffffffe0003de604: aa_dfa_match_len (STB_GLOBAL)
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
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81492f10)
Location: security/apparmor/match.c:415
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff81492f10-ffffffff81492fec: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81483930)
Location: security/apparmor/match.c:415
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff81483930-ffffffff81483a0c: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8148efb0)
Location: security/apparmor/match.c:415
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff8148efb0-ffffffff8148f08c: aa_dfa_match_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int aa_dfa_match_len(struct aa_dfa *dfa, unsigned int start, const char *str, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814a6ec0)
Location: security/apparmor/match.c:415
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/apparmorfs.c:profile_query_cb
  - security/apparmor/domain.c:aa_xattrs_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/label.c:aa_label_match
  - security/apparmor/net.c:aa_profile_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
  - security/apparmor/af_unix.c:match_addr
  - security/apparmor/af_unix.c:match_addr
```
**Symbols:**

```
ffffffff814a6ec0-ffffffff814a6f9c: aa_dfa_match_len (STB_GLOBAL)
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
