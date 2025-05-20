# Function: <code>key_invalidate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8132fc20)
Location: security/keys/key.c:1016
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_invalidate_key
```
**Symbols:**

```
ffffffff8132fc20-ffffffff8132fc5e: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81364970)
Location: security/keys/key.c:1044
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_invalidate_key
```
**Symbols:**

```
ffffffff81364970-ffffffff813649b0: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8137b190)
Location: security/keys/key.c:1044
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_invalidate_key
```
**Symbols:**

```
ffffffff8137b190-ffffffff8137b1d0: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8138ed60)
Location: security/keys/key.c:1044
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_invalidate_key
```
**Symbols:**

```
ffffffff8138ed60-ffffffff8138edac: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813b4230)
Location: security/keys/key.c:1057
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_invalidate_key
```
**Symbols:**

```
ffffffff813b4230-ffffffff813b4282: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813e48e0)
Location: security/keys/key.c:1057
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_invalidate_key
```
**Symbols:**

```
ffffffff813e48e0-ffffffff813e4932: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813ff0f0)
Location: security/keys/key.c:1058
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_invalidate_key
```
**Symbols:**

```
ffffffff813ff0f0-ffffffff813ff142: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (ffffffff8142b6f7)
Location: security/keys/key.c:1072
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8142b2c0-ffffffff8142b306: key_invalidate.part.0 (STB_LOCAL)
ffffffff8142b310-ffffffff8142b32c: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (ffffffff81445447)
Location: security/keys/key.c:1072
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81445010-ffffffff81445056: key_invalidate.part.0 (STB_LOCAL)
ffffffff81445060-ffffffff8144507c: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81496060)
Location: security/keys/key.c:1090
Inline: True
Direct callers:
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81496060-ffffffff81496122: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814b3ac0)
Location: security/keys/key.c:1094
Inline: True
Direct callers:
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff814b3ac0-ffffffff814b3b82: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814b98f0)
Location: security/keys/key.c:1094
Inline: True
Direct callers:
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff814b98f0-ffffffff814b99b2: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81512120)
Location: security/keys/key.c:1094
Inline: True
Direct callers:
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81512120-ffffffff815121e2: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff815a45a0)
Location: security/keys/key.c:1094
Inline: True
Direct callers:
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff815a45a0-ffffffff815a4670: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8164e520)
Location: security/keys/key.c:1094
Inline: False
Direct callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8164e520-ffffffff8164e5f0: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81686d80)
Location: security/keys/key.c:1157
Inline: False
Direct callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81686d80-ffffffff81686e50: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff816c3290)
Location: security/keys/key.c:1153
Inline: False
Direct callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff816c3290-ffffffff816c3360: key_invalidate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (ffff80001052e680)
Location: security/keys/key.c:1072
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffff80001052de28-ffff80001052dec0: key_invalidate.part.0 (STB_LOCAL)
ffff80001052dec0-ffff80001052df04: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (c06e6a8c)
Location: security/keys/key.c:1072
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
c06e65fc-c06e6648: key_invalidate.part.0 (STB_LOCAL)
c06e6648-c06e6670: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (c00000000067ac04)
Location: security/keys/key.c:1072
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
c00000000067a560-c00000000067a608: key_invalidate.part.0 (STB_LOCAL)
c00000000067a610-c00000000067a630: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (ffffffe00038fd0c)
Location: security/keys/key.c:1072
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffe00038f962-ffffffe00038f9ba: key_invalidate.part.0 (STB_LOCAL)
ffffffe00038f9ba-ffffffe00038f9f6: key_invalidate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (ffffffff8143da27)
Location: security/keys/key.c:1072
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8143d5f0-ffffffff8143d636: key_invalidate.part.0 (STB_LOCAL)
ffffffff8143d640-ffffffff8143d65c: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (ffffffff8142e497)
Location: security/keys/key.c:1072
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8142e060-ffffffff8142e0a6: key_invalidate.part.0 (STB_LOCAL)
ffffffff8142e0b0-ffffffff8142e0cc: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (ffffffff81439bc7)
Location: security/keys/key.c:1072
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81439790-ffffffff814397d6: key_invalidate.part.0 (STB_LOCAL)
ffffffff814397e0-ffffffff814397fc: key_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_invalidate(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (ffffffff81450e37)
Location: security/keys/key.c:1072
Inline: True
Inline callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_invalidate_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81450a00-ffffffff81450a46: key_invalidate.part.0 (STB_LOCAL)
ffffffff81450a50-ffffffff81450a6c: key_invalidate (STB_GLOBAL)
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
