# Function: <code>key_read_state</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813b5cd6)
Location: include/linux/key.h:360
Inline: True
```
```
In security/keys/keyctl.c (ffffffff813b733a)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff813b8fc2)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff813b933d)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff813b9fb9)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff813ba52c)
Location: include/linux/key.h:360
Inline: True
```
```
In security/keys/proc.c (ffffffff813badd5)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/big_key.c (ffffffff813bbeda)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In security/keys/trusted.c (ffffffff813bdf0a)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bee40)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff8196a9a1)
Location: include/linux/key.h:360
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813e64c6)
Location: include/linux/key.h:360
Inline: True
```
```
In security/keys/keyctl.c (ffffffff813e7f47)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff813e9d5c)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff813ea0ad)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff813eacc9)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff813eb17c)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff813ebbc7)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/big_key.c (ffffffff813eccca)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In security/keys/trusted.c (ffffffff813eecfa)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813efc10)
Location: include/linux/key.h:360
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff819c41a1)
Location: include/linux/key.h:360
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81400e86)
Location: include/linux/key.h:363
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81402747)
Location: include/linux/key.h:363
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff814047cf)
Location: include/linux/key.h:363
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81404add)
Location: include/linux/key.h:363
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff814056e9)
Location: include/linux/key.h:363
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff81405bbc)
Location: include/linux/key.h:363
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff814067d2)
Location: include/linux/key.h:363
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/big_key.c (ffffffff81407e6a)
Location: include/linux/key.h:363
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In security/keys/trusted.c (ffffffff81409f6a)
Location: include/linux/key.h:363
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140aeb0)
Location: include/linux/key.h:363
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff819fb5e1)
Location: include/linux/key.h:363
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142ced6)
Location: include/linux/key.h:422
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8142f397)
Location: include/linux/key.h:422
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff81431655)
Location: include/linux/key.h:422
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8143199f)
Location: include/linux/key.h:422
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff8143279e)
Location: include/linux/key.h:422
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff81432cdd)
Location: include/linux/key.h:422
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff8143392d)
Location: include/linux/key.h:422
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/big_key.c (ffffffff8143505a)
Location: include/linux/key.h:422
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In security/keys/trusted.c (ffffffff8143705a)
Location: include/linux/key.h:422
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81438960)
Location: include/linux/key.h:422
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81a6aca1)
Location: include/linux/key.h:422
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8134c381)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyring.c (ffffffff81446c26)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyctl.c (ffffffff814490f7)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff8144b3b5)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8144b6ff)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff8144c50e)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff8144ca4d)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff8144d69d)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/big_key.c (ffffffff8144edda)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In security/keys/trusted.c (ffffffff81450dfa)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814527a0)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81aa1691)
Location: include/linux/key.h:434
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81391d61)
Location: include/linux/key.h:443
Inline: True
```
```
In security/keys/keyring.c (ffffffff81498236)
Location: include/linux/key.h:443
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8149a7cf)
Location: include/linux/key.h:443
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff8149cfd7)
Location: include/linux/key.h:443
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8149d6f0)
Location: include/linux/key.h:443
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff8149e56e)
Location: include/linux/key.h:443
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff8149eb7d)
Location: include/linux/key.h:443
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff8149f320)
Location: include/linux/key.h:443
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a2b2e)
Location: include/linux/key.h:443
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a47c4)
Location: include/linux/key.h:443
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81b9d021)
Location: include/linux/key.h:443
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813a3101)
Location: include/linux/key.h:444
Inline: True
```
```
In security/keys/keyring.c (ffffffff814b5ca6)
Location: include/linux/key.h:444
Inline: True
```
```
In security/keys/keyctl.c (ffffffff814b83ff)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff814baa7d)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814bb210)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff814bc05e)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff814bc65d)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff814bcd50)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c04fe)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c1fc4)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81bacd11)
Location: include/linux/key.h:444
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813aa341)
Location: include/linux/key.h:444
Inline: True
```
```
In security/keys/keyring.c (ffffffff814bbb26)
Location: include/linux/key.h:444
Inline: True
```
```
In security/keys/keyctl.c (ffffffff814be26f)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff814c08b4)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814c10d2)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff814c1f2e)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff814c251d)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff814c2bf0)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff814c46d9)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c8444)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81b9bfa1)
Location: include/linux/key.h:444
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff813f9b91)
Location: include/linux/key.h:444
Inline: True
```
```
In security/keys/keyring.c (ffffffff81514386)
Location: include/linux/key.h:444
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81516c8f)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff815192d4)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81519b42)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff8151a91e)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff8151af0d)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff8151b5e0)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff8151d0b9)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81520f34)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81c68f01)
Location: include/linux/key.h:444
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8146ce71)
Location: include/linux/key.h:444
Inline: True
```
```
In security/keys/keyring.c (ffffffff815a6726)
Location: include/linux/key.h:444
Inline: True
```
```
In security/keys/keyctl.c (ffffffff815a95be)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff815abe68)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff815ac7b2)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff815ad75e)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff815ade7d)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff815ae7f7)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff815b0411)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b4740)
Location: include/linux/key.h:444
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81e0c131)
Location: include/linux/key.h:444
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff814fe471)
Location: include/linux/key.h:450
Inline: True
```
```
In security/keys/keyring.c (ffffffff81650686)
Location: include/linux/key.h:450
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8165380e)
Location: include/linux/key.h:450
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff816562e8)
Location: include/linux/key.h:450
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81656c99)
Location: include/linux/key.h:450
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff81657cfe)
Location: include/linux/key.h:450
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff8165846d)
Location: include/linux/key.h:450
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff81658f67)
Location: include/linux/key.h:450
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff8165ad01)
Location: include/linux/key.h:450
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165f910)
Location: include/linux/key.h:450
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81fe2121)
Location: include/linux/key.h:450
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81535ab1)
Location: include/linux/key.h:458
Inline: True
```
```
In security/keys/keyring.c (ffffffff81688f66)
Location: include/linux/key.h:458
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8168c01e)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff8168ebb3)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8168f519)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff8169057e)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff81690ced)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff81691807)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff816935f1)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81698280)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff8205e3c1)
Location: include/linux/key.h:458
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8156aa81)
Location: include/linux/key.h:458
Inline: True
```
```
In security/keys/keyring.c (ffffffff816c53e6)
Location: include/linux/key.h:458
Inline: True
```
```
In security/keys/keyctl.c (ffffffff816c851e)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff816cb109)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff816cbaa9)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff816ccb0e)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff816cd2bd)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff816cdde1)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff816cfbf1)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d46b0)
Location: include/linux/key.h:458
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff821310a1)
Location: include/linux/key.h:458
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffff80001040cf20)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyring.c (ffff80001053007c)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyctl.c (ffff800010532c18)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffff800010535054)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffff800010535500)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffff800010536264)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffff800010536ae4)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffff800010537608)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/big_key.c (ffff8000105398a8)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In security/keys/trusted.c (ffff80001053bfd8)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053ce5c)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffff800010d72e58)
Location: include/linux/key.h:434
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c05d9f48)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyring.c (c06e82a4)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyctl.c (c06ea52c)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (c06ec694)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (c06ed470)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (c06ed93c)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (c06edf00)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (c06ee650)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/big_key.c (c06eff78)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In security/keys/trusted.c (c06f1fdc)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (c06f38f0)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (c0e6fd88)
Location: include/linux/key.h:434
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (c00000000051a30c)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyring.c (c00000000067d0d4)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyctl.c (c00000000068063c)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (c000000000683554)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (c000000000684728)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (c000000000684d30)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (c000000000685574)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (c00000000068677c)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/big_key.c (c000000000688670)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In security/keys/trusted.c (c00000000068b424)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068d90c)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (c000000000eb2078)
Location: include/linux/key.h:434
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffe0002b6708)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyring.c (ffffffe0003916c2)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyctl.c (ffffffe0003933fc)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffe000395032)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffe000395b14)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffe000395f32)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffe000396478)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffe000396a5c)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/big_key.c (ffffffe000397f10)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In security/keys/trusted.c (ffffffe000399cb4)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039adec)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffe0008a3322)
Location: include/linux/key.h:434
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81344961)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyring.c (ffffffff8143f206)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyctl.c (ffffffff814416d7)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff81443995)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81443cdf)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff81444aee)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff8144502d)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff81445c7d)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/big_key.c (ffffffff814473ba)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In security/keys/trusted.c (ffffffff814493da)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144ad80)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81a40a21)
Location: include/linux/key.h:434
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81335641)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyring.c (ffffffff8142fc76)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81432147)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff814343e5)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8143472f)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff8143553e)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff81435a7d)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff814366cd)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/big_key.c (ffffffff81437e0a)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In security/keys/trusted.c (ffffffff81439e2a)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143b7d0)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff819fd611)
Location: include/linux/key.h:434
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81342431)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyring.c (ffffffff8143b3a6)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8143d877)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff8143fb35)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8143ff4f)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff81440b8e)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff814410cd)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff81441d1d)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/big_key.c (ffffffff8144345a)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In security/keys/trusted.c (ffffffff8144547a)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81446e20)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81aac8d1)
Location: include/linux/key.h:434
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81355731)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyring.c (ffffffff814524f6)
Location: include/linux/key.h:434
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81454a07)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_read_key
```
```
In security/keys/process_keys.c (ffffffff81456ce0)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81457024)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In security/keys/request_key_auth.c (ffffffff81457e7e)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff814583dd)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/proc.c (ffffffff81459055)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/big_key.c (ffffffff8145a78a)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In security/keys/trusted.c (ffffffff8145c7aa)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_update
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145e150)
Location: include/linux/key.h:434
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81ab8c41)
Location: include/linux/key.h:434
Inline: True
```
</details>
</li>
</ul>

## Differences
