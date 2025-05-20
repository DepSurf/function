# Function: <code>match_to_prot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int match_to_prot(struct aa_profile *profile, unsigned int state, int type, int protocol, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813915d0)
Location: security/apparmor/af_unix.c:75
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffff813915d0-ffffffff8139163b: match_to_prot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813ccd95)
Location: security/apparmor/af_unix.c:75
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813e4415)
Location: security/apparmor/af_unix.c:75
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813f1fc0)
Location: security/apparmor/af_unix.c:75
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8141a040)
Location: security/apparmor/af_unix.c:75
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8144c45d)
Location: security/apparmor/af_unix.c:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814695bd)
Location: security/apparmor/af_unix.c:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81496611)
Location: security/apparmor/af_unix.c:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814b0541)
Location: security/apparmor/af_unix.c:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81510425)
Location: security/apparmor/af_unix.c:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8152d0c5)
Location: security/apparmor/af_unix.c:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff815333f5)
Location: security/apparmor/af_unix.c:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81591975)
Location: security/apparmor/af_unix.c:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81633ad2)
Location: security/apparmor/af_unix.c:89
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
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff816e8cae)
Location: security/apparmor/af_unix.c:96
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81722464)
Location: security/apparmor/af_unix.c:96
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
unsigned int match_to_prot(struct aa_dfa *dfa, unsigned int state, int type, int protocol, const char **info);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81760c84)
Location: security/apparmor/af_unix.c:96
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
```
In security/apparmor/af_inet.c (ffffffff81762460)
Location: security/apparmor/af_inet.c:325
Inline: False
Direct callers:
  - security/apparmor/af_inet.c:aa_inet_file_perm
  - security/apparmor/af_inet.c:inet_label_sock_perm
  - security/apparmor/af_inet.c:aa_inet_opt_perm
  - security/apparmor/af_inet.c:aa_inet_accept_perm
  - security/apparmor/af_inet.c:aa_inet_listen_perm
  - security/apparmor/af_inet.c:aa_inet_bind_perm
  - security/apparmor/af_inet.c:aa_inet_create_perm
  - security/apparmor/af_inet.c:profile_remote_perm
```
**Symbols:**

```
ffffffff81762460-ffffffff81762568: match_to_prot (STB_LOCAL)
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
unsigned int match_to_prot(struct aa_profile *profile, unsigned int state, int type, int protocol, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffff8000105a77f8)
Location: security/apparmor/af_unix.c:76
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffff8000105a77f8-ffff8000105a7898: match_to_prot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c0757e94)
Location: security/apparmor/af_unix.c:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c00000000072491c)
Location: security/apparmor/af_unix.c:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int match_to_prot(struct aa_profile *profile, unsigned int state, int type, int protocol, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffe0003f0f84)
Location: security/apparmor/af_unix.c:76
Inline: False
Direct callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
**Symbols:**

```
ffffffe0003f0f84-ffffffe0003f1002: match_to_prot (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a8b21)
Location: security/apparmor/af_unix.c:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81499541)
Location: security/apparmor/af_unix.c:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a4bc1)
Location: security/apparmor/af_unix.c:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814bd451)
Location: security/apparmor/af_unix.c:76
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:match_to_local
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
