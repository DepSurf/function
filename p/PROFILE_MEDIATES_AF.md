# Function: <code>PROFILE_MEDIATES_AF</code>

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
In security/apparmor/file.c (ffffffff8138834a)
Location: security/apparmor/include/policy.h:206
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff8139179d)
Location: security/apparmor/include/policy.h:206
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
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
In security/apparmor/file.c (ffffffff813c2eaa)
Location: security/apparmor/include/policy.h:223
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff813ceeb3)
Location: security/apparmor/include/policy.h:223
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff813da3ba)
Location: security/apparmor/include/policy.h:223
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff813e652e)
Location: security/apparmor/include/policy.h:223
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff813eb4f5)
Location: security/apparmor/include/policy.h:226
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff813f2382)
Location: security/apparmor/include/policy.h:226
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff81412e35)
Location: security/apparmor/include/policy.h:226
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff8141acd2)
Location: security/apparmor/include/policy.h:226
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff8144524b)
Location: security/apparmor/include/policy.h:230
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff8144da25)
Location: security/apparmor/include/policy.h:230
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff8146213b)
Location: security/apparmor/include/policy.h:230
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff8146a9e8)
Location: security/apparmor/include/policy.h:230
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff8148f3f3)
Location: security/apparmor/include/policy.h:225
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff814979f8)
Location: security/apparmor/include/policy.h:225
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff814a92b3)
Location: security/apparmor/include/policy.h:225
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff814b1928)
Location: security/apparmor/include/policy.h:225
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff815069b1)
Location: security/apparmor/include/policy.h:228
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff815108ea)
Location: security/apparmor/include/policy.h:228
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff81523aa1)
Location: security/apparmor/include/policy.h:228
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff8152cdea)
Location: security/apparmor/include/policy.h:228
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff81529c78)
Location: security/apparmor/include/policy.h:228
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff81533a6a)
Location: security/apparmor/include/policy.h:228
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff81588018)
Location: security/apparmor/include/policy.h:228
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff81591fea)
Location: security/apparmor/include/policy.h:228
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In security/apparmor/file.c (ffff80001059fc34)
Location: security/apparmor/include/policy.h:225
Inline: True
```
```
In security/apparmor/af_unix.c (ffff8000105a9220)
Location: security/apparmor/include/policy.h:225
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (c07508cc)
Location: security/apparmor/include/policy.h:225
Inline: True
```
```
In security/apparmor/af_unix.c (c0759328)
Location: security/apparmor/include/policy.h:225
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (c000000000719b9c)
Location: security/apparmor/include/policy.h:225
Inline: True
```
```
In security/apparmor/af_unix.c (c000000000726660)
Location: security/apparmor/include/policy.h:225
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffe0003ead7a)
Location: security/apparmor/include/policy.h:225
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffe0003f26b6)
Location: security/apparmor/include/policy.h:225
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff814a1893)
Location: security/apparmor/include/policy.h:225
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff814a9f08)
Location: security/apparmor/include/policy.h:225
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff814922b3)
Location: security/apparmor/include/policy.h:225
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff8149a928)
Location: security/apparmor/include/policy.h:225
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff8149d933)
Location: security/apparmor/include/policy.h:225
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff814a5fa8)
Location: security/apparmor/include/policy.h:225
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff814b5ed3)
Location: security/apparmor/include/policy.h:225
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff814be858)
Location: security/apparmor/include/policy.h:225
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
</details>
</li>
</ul>

## Differences
