# Function: <code>aa_profile_af_sk_perm</code>

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
In security/apparmor/net.c (ffffffff81390915)
Location: security/apparmor/include/net.h:93
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_label_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81391ac1)
Location: security/apparmor/include/net.h:93
Inline: True
Inline callers:
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
In security/apparmor/net.c (ffffffff813cbeb1)
Location: security/apparmor/include/net.h:93
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_label_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813cede9)
Location: security/apparmor/include/net.h:93
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff813e3531)
Location: security/apparmor/include/net.h:93
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_label_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813e6469)
Location: security/apparmor/include/net.h:93
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff813f199a)
Location: security/apparmor/include/net.h:103
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_label_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813f23a1)
Location: security/apparmor/include/net.h:103
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff814199ba)
Location: security/apparmor/include/net.h:103
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_label_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8141acf1)
Location: security/apparmor/include/net.h:103
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff8144be1a)
Location: security/apparmor/include/net.h:108
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_label_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff8144dc02)
Location: security/apparmor/include/net.h:108
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff81468d71)
Location: security/apparmor/include/net.h:112
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff8146ab25)
Location: security/apparmor/include/net.h:112
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff81495db4)
Location: security/apparmor/include/net.h:108
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff81497bf3)
Location: security/apparmor/include/net.h:108
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff814afce4)
Location: security/apparmor/include/net.h:108
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff814b1b23)
Location: security/apparmor/include/net.h:108
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff8150f154)
Location: security/apparmor/include/net.h:115
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff8151092c)
Location: security/apparmor/include/net.h:115
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff8152bf94)
Location: security/apparmor/include/net.h:115
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff8152ce2c)
Location: security/apparmor/include/net.h:115
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff81532234)
Location: security/apparmor/include/net.h:115
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff81533aac)
Location: security/apparmor/include/net.h:115
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff815907b4)
Location: security/apparmor/include/net.h:115
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff8159202c)
Location: security/apparmor/include/net.h:115
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff81631890)
Location: security/apparmor/include/net.h:116
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff81633a1d)
Location: security/apparmor/include/net.h:116
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff816e65cf)
Location: security/apparmor/include/net.h:118
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff816e8c04)
Location: security/apparmor/include/net.h:118
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
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
In security/apparmor/net.c (ffffffff8171fcff)
Location: security/apparmor/include/net.h:118
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff817223b6)
Location: security/apparmor/include/net.h:118
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
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
In security/apparmor/net.c (ffffffff8175e72f)
Location: security/apparmor/include/net.h:128
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff81760bd6)
Location: security/apparmor/include/net.h:128
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
```
```
In security/apparmor/af_inet.c (ffffffff81764385)
Location: security/apparmor/include/net.h:128
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:aa_inet_file_perm
  - security/apparmor/af_inet.c:inet_label_sock_perm
  - security/apparmor/af_inet.c:aa_inet_opt_perm
  - security/apparmor/af_inet.c:aa_inet_accept_perm
  - security/apparmor/af_inet.c:aa_inet_listen_perm
  - security/apparmor/af_inet.c:aa_inet_bind_perm
  - security/apparmor/af_inet.c:profile_remote_perm
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
In security/apparmor/net.c (ffff8000105a7448)
Location: security/apparmor/include/net.h:108
Inline: True
```
```
In security/apparmor/af_unix.c (ffff8000105a93cc)
Location: security/apparmor/include/net.h:108
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (c075740c)
Location: security/apparmor/include/net.h:108
Inline: True
```
```
In security/apparmor/af_unix.c (c07594f0)
Location: security/apparmor/include/net.h:108
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (c000000000723d70)
Location: security/apparmor/include/net.h:108
Inline: True
```
```
In security/apparmor/af_unix.c (c000000000726880)
Location: security/apparmor/include/net.h:108
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffe0003f0cae)
Location: security/apparmor/include/net.h:108
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffe0003f2814)
Location: security/apparmor/include/net.h:108
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff814a82c4)
Location: security/apparmor/include/net.h:108
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff814aa103)
Location: security/apparmor/include/net.h:108
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff81498ce4)
Location: security/apparmor/include/net.h:108
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff8149ab23)
Location: security/apparmor/include/net.h:108
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff814a4364)
Location: security/apparmor/include/net.h:108
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff814a61a3)
Location: security/apparmor/include/net.h:108
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
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
In security/apparmor/net.c (ffffffff814bcbf4)
Location: security/apparmor/include/net.h:108
Inline: True
```
```
In security/apparmor/af_unix.c (ffffffff814bea53)
Location: security/apparmor/include/net.h:108
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_sk_perm
```
</details>
</li>
</ul>

## Differences
