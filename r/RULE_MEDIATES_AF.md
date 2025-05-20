# Function: <code>RULE_MEDIATES_AF</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81628635)
Location: security/apparmor/include/policy.h:286
Inline: True
Inline callers:
  - security/apparmor/file.c:__aa_path_perm
```
```
In security/apparmor/af_unix.c (ffffffff816339e3)
Location: security/apparmor/include/policy.h:286
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff816dcd9a)
Location: security/apparmor/include/policy.h:292
Inline: True
Inline callers:
  - security/apparmor/file.c:__aa_path_perm
```
```
In security/apparmor/af_unix.c (ffffffff816e8bca)
Location: security/apparmor/include/policy.h:292
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff81716393)
Location: security/apparmor/include/policy.h:323
Inline: True
Inline callers:
  - security/apparmor/file.c:__aa_path_perm
```
```
In security/apparmor/af_unix.c (ffffffff81722376)
Location: security/apparmor/include/policy.h:323
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/file.c (ffffffff81754e46)
Location: security/apparmor/include/policy.h:320
Inline: True
Inline callers:
  - security/apparmor/file.c:__aa_path_perm
```
```
In security/apparmor/af_unix.c (ffffffff81760b96)
Location: security/apparmor/include/policy.h:320
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
```
In security/apparmor/af_inet.c (ffffffff817643e0)
Location: security/apparmor/include/policy.h:320
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:aa_inet_file_perm
  - security/apparmor/af_inet.c:inet_label_sock_perm
  - security/apparmor/af_inet.c:aa_inet_opt_perm
  - security/apparmor/af_inet.c:aa_inet_accept_perm
  - security/apparmor/af_inet.c:aa_inet_listen_perm
  - security/apparmor/af_inet.c:aa_inet_bind_perm
  - security/apparmor/af_inet.c:aa_inet_create_perm
  - security/apparmor/af_inet.c:profile_remote_perm
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
