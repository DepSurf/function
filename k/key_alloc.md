# Function: <code>key_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8132fe70)
Location: security/keys/key.c:224
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff8132fe70-ffffffff813302a9: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, int (*restrict_link)(struct key *, const struct key_type *, const union key_payload *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81364bb0)
Location: security/keys/key.c:225
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff81364bb0-ffffffff81364ff4: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, int (*restrict_link)(struct key *, const struct key_type *, const union key_payload *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8137b3d0)
Location: security/keys/key.c:225
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff8137b3d0-ffffffff8137b814: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8138efc0)
Location: security/keys/key.c:228
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff8138efc0-ffffffff8138f3bf: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813b44a0)
Location: security/keys/key.c:228
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff813b44a0-ffffffff813b48b6: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813e4c10)
Location: security/keys/key.c:228
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff813e4c10-ffffffff813e5091: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813ff420)
Location: security/keys/key.c:228
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff813ff420-ffffffff813ff865: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8142bb30)
Location: security/keys/key.c:224
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff8142bb30-ffffffff8142bfa6: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81445880)
Location: security/keys/key.c:224
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff81445880-ffffffff81445cf6: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81496be0)
Location: security/keys/key.c:225
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff81496be0-ffffffff8149708f: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814b4650)
Location: security/keys/key.c:225
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff814b4650-ffffffff814b4b10: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814ba410)
Location: security/keys/key.c:225
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff814ba410-ffffffff814ba95b: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81512c40)
Location: security/keys/key.c:225
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff81512c40-ffffffff8151318b: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff815a5050)
Location: security/keys/key.c:225
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff815a5050-ffffffff815a55b2: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8164ee40)
Location: security/keys/key.c:225
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff8164ee40-ffffffff8164f3a2: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff816876a0)
Location: security/keys/key.c:225
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:__key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff816876a0-ffffffff81687c0b: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff816c3bb0)
Location: security/keys/key.c:225
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:__key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff816c3bb0-ffffffff816c4129: key_alloc (STB_GLOBAL)
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
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffff80001052e950)
Location: security/keys/key.c:224
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffff80001052e950-ffff80001052eed8: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c06e6d9c)
Location: security/keys/key.c:224
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
c06e6d9c-c06e7240: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c00000000067b180)
Location: security/keys/key.c:224
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
c00000000067b180-c00000000067b86c: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffe00039023c)
Location: security/keys/key.c:224
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffe00039023c-ffffffe000390790: key_alloc (STB_GLOBAL)
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
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8143de60)
Location: security/keys/key.c:224
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff8143de60-ffffffff8143e2d6: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8142e8d0)
Location: security/keys/key.c:224
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff8142e8d0-ffffffff8142ed46: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8143a000)
Location: security/keys/key.c:224
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff8143a000-ffffffff8143a476: key_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct key *key_alloc(struct key_type *type, const char *desc, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81451120)
Location: security/keys/key.c:224
Inline: False
Direct callers:
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key_auth.c:request_key_auth_new
```
**Symbols:**

```
ffffffff81451120-ffffffff814515aa: key_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int (*restrict_link)(struct key *, const struct key_type *, const union key_payload *)</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*restrict_link)(struct key *, const struct key_type *, const union key_payload *)</code> ➡️ <code>struct key_restriction *restrict_link</code>
</li>
</ul>
</details>
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
