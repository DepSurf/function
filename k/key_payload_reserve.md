# Function: <code>key_payload_reserve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8132f3e0)
Location: security/keys/key.c:362
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/user_defined.c:user_revoke
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff8132f3e0-ffffffff8132f497: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813640e0)
Location: security/keys/key.c:367
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff813640e0-ffffffff81364197: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8137a900)
Location: security/keys/key.c:367
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_revoke
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff8137a900-ffffffff8137a9b7: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8138e4f0)
Location: security/keys/key.c:368
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff8138e4f0-ffffffff8138e5a6: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813b39a0)
Location: security/keys/key.c:370
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff813b39a0-ffffffff813b3a59: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813e4940)
Location: security/keys/key.c:370
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff813e4940-ffffffff813e49f9: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813ff150)
Location: security/keys/key.c:371
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff813ff150-ffffffff813ff209: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8142b850)
Location: security/keys/key.c:369
Inline: False
Direct callers:
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff8142b850-ffffffff8142b905: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814455a0)
Location: security/keys/key.c:369
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff814455a0-ffffffff81445655: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814968c0)
Location: security/keys/key.c:370
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_end
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff814968c0-ffffffff81496975: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814b4330)
Location: security/keys/key.c:372
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_end
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff814b4330-ffffffff814b43e5: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814ba160)
Location: security/keys/key.c:372
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_end
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_core.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff814ba160-ffffffff814ba209: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81512990)
Location: security/keys/key.c:372
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_end
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_core.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff81512990-ffffffff81512a39: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff815a4140)
Location: security/keys/key.c:372
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_core.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff815a4140-ffffffff815a4203: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8164de30)
Location: security/keys/key.c:372
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_core.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff8164de30-ffffffff8164def3: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff816865f0)
Location: security/keys/key.c:372
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_core.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff816865f0-ffffffff816866b3: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff816c2a60)
Location: security/keys/key.c:373
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/trusted-keys/trusted_core.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff816c2a60-ffffffff816c2b23: key_payload_reserve (STB_GLOBAL)
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
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffff80001052e348)
Location: security/keys/key.c:369
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffff80001052e348-ffff80001052e46c: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c06e60fc)
Location: security/keys/key.c:369
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
c06e60fc-c06e61d8: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c000000000679c30)
Location: security/keys/key.c:369
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_end
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
c000000000679c30-c000000000679db0: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffe00038fe5c)
Location: security/keys/key.c:369
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffe00038fe5c-ffffffe00038ff54: key_payload_reserve (STB_GLOBAL)
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
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8143db80)
Location: security/keys/key.c:369
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff8143db80-ffffffff8143dc35: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8142e5f0)
Location: security/keys/key.c:369
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff8142e5f0-ffffffff8142e6a5: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81439d20)
Location: security/keys/key.c:369
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff81439d20-ffffffff81439dd5: key_payload_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int key_payload_reserve(struct key *key, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81450560)
Location: security/keys/key.c:369
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_user_key_instantiate
  - security/keys/keyring.c:keyring_revoke
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link_begin
  - security/keys/user_defined.c:user_revoke
  - security/keys/user_defined.c:user_update
  - security/keys/big_key.c:big_key_revoke
  - security/keys/trusted.c:trusted_payload_alloc
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
**Symbols:**

```
ffffffff81450560-ffffffff8145060c: key_payload_reserve (STB_GLOBAL)
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
