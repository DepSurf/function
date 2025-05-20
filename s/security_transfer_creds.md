# Function: <code>security_transfer_creds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133e2d0)
Location: security/security.c:882
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff8133e2d0-ffffffff8133e310: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373930)
Location: security/security.c:904
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff81373930-ffffffff81373970: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138a260)
Location: security/security.c:925
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff8138a260-ffffffff8138a2a0: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139f750)
Location: security/security.c:1562
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff8139f750-ffffffff8139f790: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5300)
Location: security/security.c:1524
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff813c5300-ffffffff813c5346: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5410)
Location: security/security.c:1021
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff813f5410-ffffffff813f544e: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814109f0)
Location: security/security.c:1612
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff814109f0-ffffffff81410a78: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/security.c (0)
Location: security/security.c:1631
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff81440116-ffffffff81440129: security_transfer_creds.cold (STB_LOCAL)
ffffffff8143e190-ffffffff8143e215: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81457c30)
Location: security/security.c:1670
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff81457c30-ffffffff81457cb8: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814aaaa0)
Location: security/security.c:1839
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff814aaaa0-ffffffff814aaade: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c80a0)
Location: security/security.c:1841
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff814c80a0-ffffffff814c80de: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ce6e0)
Location: security/security.c:1891
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff814ce6e0-ffffffff814ce71e: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815273a0)
Location: security/security.c:1899
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff815273a0-ffffffff815273de: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bc110)
Location: security/security.c:1904
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff815bc110-ffffffff815bc158: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81668020)
Location: security/security.c:1951
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff81668020-ffffffff81668068: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a0640)
Location: security/security.c:3101
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff816a0640-ffffffff816a0688: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dd060)
Location: security/security.c:3167
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff816dd060-ffffffff816dd0a8: security_transfer_creds (STB_GLOBAL)
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
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105438f8)
Location: security/security.c:1670
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffff8000105438f8-ffff800010543994: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f9860)
Location: security/security.c:1670
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
c06f9860-c06f98f8: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000697bd0)
Location: security/security.c:1670
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
c000000000697bd0-c000000000697cd0: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039fd86)
Location: security/security.c:1670
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffe00039fd86-ffffffe00039fe04: security_transfer_creds (STB_GLOBAL)
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
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450210)
Location: security/security.c:1670
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff81450210-ffffffff81450298: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81440c60)
Location: security/security.c:1670
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff81440c60-ffffffff81440ce8: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144c2b0)
Location: security/security.c:1670
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff8144c2b0-ffffffff8144c338: security_transfer_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_transfer_creds(struct cred *new, const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463680)
Location: security/security.c:1670
Inline: False
Direct callers:
  - security/keys/process_keys.c:key_change_session_keyring
```
**Symbols:**

```
ffffffff81463680-ffffffff81463708: security_transfer_creds (STB_GLOBAL)
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
