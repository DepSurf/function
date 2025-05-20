# Function: <code>key_serial</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/gc.c (0)
Location: include/linux/key.h:302
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/key.h:302
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/linux/key.h:302
Inline: True
```
```
In security/keys/request_key.c (0)
Location: include/linux/key.h:302
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffff81396999)
Location: include/linux/key.h:302
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/linux/key.h:302
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_trust.c (0)
Location: include/linux/key.h:302
Inline: True
```
```
In net/dns_resolver/dns_key.c (ffffffff81fbef69)
Location: include/linux/key.h:302
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff813d2672)
Location: include/linux/key.h:326
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In net/dns_resolver/dns_key.c (ffffffff81feceb4)
Location: include/linux/key.h:326
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff813e9dd2)
Location: include/linux/key.h:326
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In net/dns_resolver/dns_key.c (ffffffff8202b941)
Location: include/linux/key.h:326
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff813f613b)
Location: include/linux/key.h:336
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In net/dns_resolver/dns_key.c (ffffffff8210f0e9)
Location: include/linux/key.h:336
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff8141e23b)
Location: include/linux/key.h:342
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In net/dns_resolver/dns_key.c (ffffffff827194da)
Location: include/linux/key.h:342
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/integrity/digsig_asymmetric.c (ffffffff814505aa)
Location: include/linux/key.h:342
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In net/dns_resolver/dns_key.c (ffffffff82743c5f)
Location: include/linux/key.h:342
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/integrity/digsig_asymmetric.c (ffffffff8146d553)
Location: include/linux/key.h:342
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In drivers/nvdimm/security.c (ffffffff817047ba)
Location: include/linux/key.h:342
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_overwrite
  - drivers/nvdimm/security.c:nvdimm_security_erase
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_disable
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In net/dns_resolver/dns_key.c (ffffffff828fdf7d)
Location: include/linux/key.h:342
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/integrity/digsig_asymmetric.c (ffffffff8149ac7e)
Location: include/linux/key.h:400
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In drivers/nvdimm/security.c (ffffffff8173e5c6)
Location: include/linux/key.h:400
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_overwrite
  - drivers/nvdimm/security.c:nvdimm_security_erase
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_update
  - drivers/nvdimm/security.c:nvdimm_security_disable
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In net/dns_resolver/dns_key.c (ffffffff8291ab70)
Location: include/linux/key.h:400
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/integrity/digsig_asymmetric.c (ffffffff814b4ece)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In drivers/nvdimm/security.c (ffffffff817627e5)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In net/dns_resolver/dns_key.c (ffffffff829249df)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/keys/key.c (ffffffff81495fcc)
Location: include/linux/key.h:432
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff81498347)
Location: include/linux/key.h:432
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff8149bb85)
Location: include/linux/key.h:432
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff81514327)
Location: include/linux/key.h:432
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In drivers/nvdimm/security.c (ffffffff818217c2)
Location: include/linux/key.h:432
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
```
In net/dns_resolver/dns_key.c (ffffffff82d30c1e)
Location: include/linux/key.h:432
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/keys/key.c (ffffffff814b3a2c)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff814b5db7)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff814b9625)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff81531468)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In drivers/nvdimm/security.c (ffffffff818304d2)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
```
In net/dns_resolver/dns_key.c (ffffffff8301f7ee)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/keys/key.c (ffffffff814b985c)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff814bbc37)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff814bf46e)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff81539898)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In drivers/nvdimm/security.c (ffffffff8181464f)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
```
In net/dns_resolver/dns_key.c (ffffffff8322a912)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/keys/key.c (ffffffff8151208c)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff81514497)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff81517e8e)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff815981e2)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In drivers/nvdimm/security.c (ffffffff8189ed7d)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
```
In net/dns_resolver/dns_key.c (ffffffff83315010)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/keys/key.c (ffffffff815a450a)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff815a6ac9)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff815aa934)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8163ca70)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In drivers/nvdimm/security.c (ffffffff819e88f9)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
```
```
In net/dns_resolver/dns_key.c (ffffffff834cf598)
Location: include/linux/key.h:433
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/keys/key.c (ffffffff8164e5a5)
Location: include/linux/key.h:439
Inline: True
Inline callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff81650a59)
Location: include/linux/key.h:439
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff81654c54)
Location: include/linux/key.h:439
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff816f42bd)
Location: include/linux/key.h:439
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In drivers/nvdimm/security.c (ffffffff81b63adb)
Location: include/linux/key.h:439
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
```
```
In net/dns_resolver/dns_key.c (ffffffff83f12e0b)
Location: include/linux/key.h:439
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/keys/key.c (ffffffff81686e05)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff81689339)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff8168d494)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8172e475)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In drivers/nvdimm/security.c (ffffffff81bb7095)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
```
```
In net/dns_resolver/dns_key.c (ffffffff837394bb)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/keys/key.c (ffffffff816c3315)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff816c5819)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff816c99be)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8176edd5)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In drivers/nvdimm/security.c (ffffffff81c0b6e5)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
```
```
In net/dns_resolver/dns_key.c (ffffffff8396dc9d)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/integrity/digsig_asymmetric.c (ffff8000105ad0a0)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In drivers/nvdimm/security.c (ffff8000109625d0)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In net/dns_resolver/dns_key.c (ffff8000114b5be4)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/integrity/digsig_asymmetric.c (c075c914)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In net/dns_resolver/dns_key.c (c15baf00)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/integrity/digsig_asymmetric.c (c00000000072b6b0)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In drivers/nvdimm/security.c (c000000000a186e4)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In net/dns_resolver/dns_key.c (c0000000013c7fcc)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/integrity/digsig_asymmetric.c (ffffffe0003f56ca)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In drivers/nvdimm/security.c (ffffffe0005cfd50)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In net/dns_resolver/dns_key.c (ffffffe0000449ae)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/integrity/digsig_asymmetric.c (ffffffff814ad4ae)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In drivers/nvdimm/security.c (ffffffff81716ed5)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In net/dns_resolver/dns_key.c (ffffffff829096e3)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/integrity/digsig_asymmetric.c (ffffffff8149dece)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In drivers/nvdimm/security.c (ffffffff816ea955)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In net/dns_resolver/dns_key.c (ffffffff82901a31)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/integrity/digsig_asymmetric.c (ffffffff814a954e)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In drivers/nvdimm/security.c (ffffffff81755ca5)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In net/dns_resolver/dns_key.c (ffffffff8291f02d)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In security/integrity/digsig_asymmetric.c (ffffffff814c1f5e)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In drivers/nvdimm/security.c (ffffffff81771115)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In net/dns_resolver/dns_key.c (ffffffff82925a51)
Location: include/linux/key.h:412
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
</details>
</li>
</ul>

## Differences
