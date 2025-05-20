# Function: <code>decrypt_pki_encrypted_session_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81307db0)
Location: fs/ecryptfs/keystore.c:1144
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff81307db0-ffffffff81308355: decrypt_pki_encrypted_session_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8133bf60)
Location: fs/ecryptfs/keystore.c:1149
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff8133bf60-ffffffff8133c519: decrypt_pki_encrypted_session_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81351cf0)
Location: fs/ecryptfs/keystore.c:1149
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff81351cf0-ffffffff813522a9: decrypt_pki_encrypted_session_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81366820)
Location: fs/ecryptfs/keystore.c:1149
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff81366820-ffffffff81366dc9: decrypt_pki_encrypted_session_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8138b4a0)
Location: fs/ecryptfs/keystore.c:1139
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff8138b4a0-ffffffff8138ba49: decrypt_pki_encrypted_session_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813ba360)
Location: fs/ecryptfs/keystore.c:1139
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff813ba360-ffffffff813ba911: decrypt_pki_encrypted_session_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813d3930)
Location: fs/ecryptfs/keystore.c:1139
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff813d3930-ffffffff813d3ed8: decrypt_pki_encrypted_session_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1125
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff813fe3d0-ffffffff813fe940: decrypt_pki_encrypted_session_key (STB_LOCAL)
ffffffff81400bec-ffffffff81400c33: decrypt_pki_encrypted_session_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1125
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff814182c0-ffffffff81418830: decrypt_pki_encrypted_session_key (STB_LOCAL)
ffffffff8141aadc-ffffffff8141ab23: decrypt_pki_encrypted_session_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1125
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff814676a0-ffffffff81467881: decrypt_pki_encrypted_session_key (STB_LOCAL)
ffffffff81469756-ffffffff81469794: decrypt_pki_encrypted_session_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1125
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff81482b30-ffffffff81482d11: decrypt_pki_encrypted_session_key (STB_LOCAL)
ffffffff81beece3-ffffffff81beed21: decrypt_pki_encrypted_session_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1126
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff814885a0-ffffffff8148878a: decrypt_pki_encrypted_session_key (STB_LOCAL)
ffffffff81be0d9c-ffffffff81be0ddd: decrypt_pki_encrypted_session_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1126
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff814dfda0-ffffffff814dff8a: decrypt_pki_encrypted_session_key (STB_LOCAL)
ffffffff81cd1539-ffffffff81cd157a: decrypt_pki_encrypted_session_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1126
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff8156e610-ffffffff8156e80d: decrypt_pki_encrypted_session_key (STB_LOCAL)
ffffffff81e8488e-ffffffff81e848ce: decrypt_pki_encrypted_session_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1126
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff81612fc0-ffffffff81613257: decrypt_pki_encrypted_session_key (STB_LOCAL)
ffffffff82072539-ffffffff8207255c: decrypt_pki_encrypted_session_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1126
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff8164ace0-ffffffff8164af6e: decrypt_pki_encrypted_session_key (STB_LOCAL)
ffffffff820f2192-ffffffff820f21b5: decrypt_pki_encrypted_session_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1126
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff816841b0-ffffffff8168443e: decrypt_pki_encrypted_session_key (STB_LOCAL)
ffffffff821cf473-ffffffff821cf496: decrypt_pki_encrypted_session_key.cold (STB_LOCAL)
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
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffff8000104f9c00)
Location: fs/ecryptfs/keystore.c:1125
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffff8000104f9c00-ffff8000104fa090: decrypt_pki_encrypted_session_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c06b73bc)
Location: fs/ecryptfs/keystore.c:1125
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
c06b73bc-c06b77d8: decrypt_pki_encrypted_session_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c00000000063c130)
Location: fs/ecryptfs/keystore.c:1125
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
c00000000063c130-c00000000063c6a0: decrypt_pki_encrypted_session_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffe0003683ba)
Location: fs/ecryptfs/keystore.c:1125
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffe0003683ba-ffffffe000368818: decrypt_pki_encrypted_session_key (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1125
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff814108a0-ffffffff81410e10: decrypt_pki_encrypted_session_key (STB_LOCAL)
ffffffff814130bc-ffffffff81413103: decrypt_pki_encrypted_session_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1125
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff81401320-ffffffff81401890: decrypt_pki_encrypted_session_key (STB_LOCAL)
ffffffff81403b3c-ffffffff81403b83: decrypt_pki_encrypted_session_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1125
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff8140dc20-ffffffff8140e190: decrypt_pki_encrypted_session_key (STB_LOCAL)
ffffffff8141043c-ffffffff81410483: decrypt_pki_encrypted_session_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int decrypt_pki_encrypted_session_key(struct ecryptfs_auth_tok *auth_tok, struct ecryptfs_crypt_stat *crypt_stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:1125
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
```
**Symbols:**

```
ffffffff81423890-ffffffff81423e00: decrypt_pki_encrypted_session_key (STB_LOCAL)
ffffffff814260ac-ffffffff814260f3: decrypt_pki_encrypted_session_key.cold (STB_LOCAL)
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
