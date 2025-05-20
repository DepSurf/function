# Function: <code>notify_key</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void notify_key(struct key *key, enum key_notification_subtype subtype, u32 aux);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81495fbe)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81498339)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff8149b439)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff81495cd0-ffffffff81495d4f: notify_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void notify_key(struct key *key, enum key_notification_subtype subtype, u32 aux);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814b3a1e)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff814b5da9)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff814b8ec9)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff814b3730-ffffffff814b37af: notify_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void notify_key(struct key *key, enum key_notification_subtype subtype, u32 aux);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814b984e)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff814bbc29)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff814bed19)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff814b9560-ffffffff814b95df: notify_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void notify_key(struct key *key, enum key_notification_subtype subtype, u32 aux);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8151207e)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81514489)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff81517739)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff81511d90-ffffffff81511e0f: notify_key (STB_LOCAL)
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
In security/keys/key.c (ffffffff815a44fc)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
```
```
In security/keys/keyring.c (ffffffff815a6abb)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff815aa172)
Location: security/keys/internal.h:187
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
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
In security/keys/key.c (ffffffff8164e597)
Location: security/keys/internal.h:185
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
In security/keys/keyring.c (ffffffff81650a4b)
Location: security/keys/internal.h:185
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff81654442)
Location: security/keys/internal.h:185
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void notify_key(struct key *key, enum key_notification_subtype subtype, u32 aux);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81686df7)
Location: security/keys/internal.h:185
Inline: True
Inline callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - security/keys/key.c:__key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8168932b)
Location: security/keys/internal.h:185
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff8168cc82)
Location: security/keys/internal.h:185
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff816866d0-ffffffff8168675d: notify_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void notify_key(struct key *key, enum key_notification_subtype subtype, u32 aux);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff816c3307)
Location: security/keys/internal.h:179
Inline: True
Inline callers:
  - security/keys/key.c:key_invalidate
  - security/keys/key.c:key_revoke
  - security/keys/key.c:key_update
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - security/keys/key.c:__key_create_or_update
```
```
In security/keys/keyring.c (ffffffff816c580b)
Location: security/keys/internal.h:179
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_clear
  - security/keys/keyring.c:key_move
  - security/keys/keyring.c:key_unlink
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff816c9172)
Location: security/keys/internal.h:179
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff816c2b40-ffffffff816c2bcd: notify_key (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
