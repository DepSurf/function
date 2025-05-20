# Function: <code>key_is_positive</code>

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
Location: include/linux/key.h:373
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff813b9fb9)
Location: include/linux/key.h:373
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff813ba52c)
Location: include/linux/key.h:373
Inline: True
```
```
In security/keys/big_key.c (ffffffff813bbeda)
Location: include/linux/key.h:373
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In net/dns_resolver/dns_key.c (ffffffff8196a9a1)
Location: include/linux/key.h:373
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
Location: include/linux/key.h:373
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff813eacc9)
Location: include/linux/key.h:373
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff813eb17c)
Location: include/linux/key.h:373
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/big_key.c (ffffffff813eccca)
Location: include/linux/key.h:373
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In net/dns_resolver/dns_key.c (ffffffff819c41a1)
Location: include/linux/key.h:373
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
Location: include/linux/key.h:376
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff814056e9)
Location: include/linux/key.h:376
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff81405bbc)
Location: include/linux/key.h:376
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/big_key.c (ffffffff81407e6a)
Location: include/linux/key.h:376
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In net/dns_resolver/dns_key.c (ffffffff819fb5e1)
Location: include/linux/key.h:376
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
Location: include/linux/key.h:435
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff8143279e)
Location: include/linux/key.h:435
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff81432cdd)
Location: include/linux/key.h:435
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/big_key.c (ffffffff8143505a)
Location: include/linux/key.h:435
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In net/dns_resolver/dns_key.c (ffffffff81a6aca1)
Location: include/linux/key.h:435
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
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/keyring.c (ffffffff81446c26)
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff8144c50e)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff8144ca4d)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/big_key.c (ffffffff8144edda)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In net/dns_resolver/dns_key.c (ffffffff81aa1691)
Location: include/linux/key.h:447
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
Location: include/linux/key.h:456
Inline: True
```
```
In security/keys/keyring.c (ffffffff81498236)
Location: include/linux/key.h:456
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff8149e56e)
Location: include/linux/key.h:456
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff8149eb7d)
Location: include/linux/key.h:456
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81b9d021)
Location: include/linux/key.h:456
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
Location: include/linux/key.h:457
Inline: True
```
```
In security/keys/keyring.c (ffffffff814b5ca6)
Location: include/linux/key.h:457
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff814bc05e)
Location: include/linux/key.h:457
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff814bc65d)
Location: include/linux/key.h:457
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81bacd11)
Location: include/linux/key.h:457
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
Location: include/linux/key.h:457
Inline: True
```
```
In security/keys/keyring.c (ffffffff814bbb26)
Location: include/linux/key.h:457
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff814c1f2e)
Location: include/linux/key.h:457
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff814c251d)
Location: include/linux/key.h:457
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81b9bfa1)
Location: include/linux/key.h:457
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
Location: include/linux/key.h:457
Inline: True
```
```
In security/keys/keyring.c (ffffffff81514386)
Location: include/linux/key.h:457
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff8151a91e)
Location: include/linux/key.h:457
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff8151af0d)
Location: include/linux/key.h:457
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81c68f01)
Location: include/linux/key.h:457
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
Location: include/linux/key.h:457
Inline: True
```
```
In security/keys/keyring.c (ffffffff815a6726)
Location: include/linux/key.h:457
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff815ad75e)
Location: include/linux/key.h:457
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff815ade7d)
Location: include/linux/key.h:457
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81e0c131)
Location: include/linux/key.h:457
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
Location: include/linux/key.h:463
Inline: True
```
```
In security/keys/keyring.c (ffffffff81650686)
Location: include/linux/key.h:463
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff81657cfe)
Location: include/linux/key.h:463
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff8165846d)
Location: include/linux/key.h:463
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In net/dns_resolver/dns_key.c (ffffffff81fe2121)
Location: include/linux/key.h:463
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
Location: include/linux/key.h:471
Inline: True
```
```
In security/keys/keyring.c (ffffffff81688f66)
Location: include/linux/key.h:471
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff8169057e)
Location: include/linux/key.h:471
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff81690ced)
Location: include/linux/key.h:471
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In net/dns_resolver/dns_key.c (ffffffff8205e3c1)
Location: include/linux/key.h:471
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
Location: include/linux/key.h:471
Inline: True
```
```
In security/keys/keyring.c (ffffffff816c53e6)
Location: include/linux/key.h:471
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff816ccb0e)
Location: include/linux/key.h:471
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff816cd2bd)
Location: include/linux/key.h:471
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In net/dns_resolver/dns_key.c (ffffffff821310a1)
Location: include/linux/key.h:471
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
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/keyring.c (ffff80001053007c)
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/request_key_auth.c (ffff800010536264)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffff800010536ae4)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/big_key.c (ffff8000105398a8)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In net/dns_resolver/dns_key.c (ffff800010d72e58)
Location: include/linux/key.h:447
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
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/keyring.c (c06e82a4)
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/request_key_auth.c (c06ed93c)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (c06edf00)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/big_key.c (c06eff78)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In net/dns_resolver/dns_key.c (c0e6fd88)
Location: include/linux/key.h:447
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
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/keyring.c (c00000000067d0d4)
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/request_key_auth.c (c000000000684d30)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (c000000000685574)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/big_key.c (c000000000688670)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In net/dns_resolver/dns_key.c (c000000000eb2078)
Location: include/linux/key.h:447
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
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/keyring.c (ffffffe0003916c2)
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffe000395f32)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffe000396478)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/big_key.c (ffffffe000397f10)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In net/dns_resolver/dns_key.c (ffffffe0008a3322)
Location: include/linux/key.h:447
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
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/keyring.c (ffffffff8143f206)
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff81444aee)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff8144502d)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/big_key.c (ffffffff814473ba)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In net/dns_resolver/dns_key.c (ffffffff81a40a21)
Location: include/linux/key.h:447
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
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/keyring.c (ffffffff8142fc76)
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff8143553e)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff81435a7d)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/big_key.c (ffffffff81437e0a)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In net/dns_resolver/dns_key.c (ffffffff819fd611)
Location: include/linux/key.h:447
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
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/keyring.c (ffffffff8143b3a6)
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff81440b8e)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff814410cd)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/big_key.c (ffffffff8144345a)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In net/dns_resolver/dns_key.c (ffffffff81aac8d1)
Location: include/linux/key.h:447
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
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/keyring.c (ffffffff814524f6)
Location: include/linux/key.h:447
Inline: True
```
```
In security/keys/request_key_auth.c (ffffffff81457e7e)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_describe
```
```
In security/keys/user_defined.c (ffffffff814583dd)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_update
```
```
In security/keys/big_key.c (ffffffff8145a78a)
Location: include/linux/key.h:447
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_describe
  - security/keys/big_key.c:big_key_revoke
```
```
In net/dns_resolver/dns_key.c (ffffffff81ab8c41)
Location: include/linux/key.h:447
Inline: True
```
</details>
</li>
</ul>

## Differences
