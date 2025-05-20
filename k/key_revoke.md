# Function: <code>key_revoke</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8132f4f0)
Location: security/keys/key.c:980
Inline: False
Direct callers:
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key_auth.c:request_key_auth_new
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff8132f4f0-ffffffff8132f567: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813641f0)
Location: security/keys/key.c:1008
Inline: False
Direct callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key_auth.c:request_key_auth_new
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff813641f0-ffffffff81364267: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8137aa10)
Location: security/keys/key.c:1008
Inline: False
Direct callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key_auth.c:request_key_auth_new
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff8137aa10-ffffffff8137aa87: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8138e610)
Location: security/keys/key.c:1008
Inline: False
Direct callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key_auth.c:request_key_auth_new
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff8138e610-ffffffff8138e67e: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813b3ab0)
Location: security/keys/key.c:1023
Inline: False
Direct callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff813b3ab0-ffffffff813b3b20: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813e4170)
Location: security/keys/key.c:1023
Inline: False
Direct callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff813e4170-ffffffff813e41ee: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813fe960)
Location: security/keys/key.c:1024
Inline: False
Direct callers:
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:key_reject_and_link
  - security/keys/key.c:__key_instantiate_and_link
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff813fe960-ffffffff813fe9de: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8142afb0)
Location: security/keys/key.c:1038
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff8142afb0-ffffffff8142b02e: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81444d00)
Location: security/keys/key.c:1038
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff81444d00-ffffffff81444d7e: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81495f60)
Location: security/keys/key.c:1054
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:call_sbin_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff81495f60-ffffffff81496056: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814b39c0)
Location: security/keys/key.c:1058
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:call_sbin_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff814b39c0-ffffffff814b3ab6: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814b97f0)
Location: security/keys/key.c:1058
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:call_sbin_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff814b97f0-ffffffff814b98e6: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81512020)
Location: security/keys/key.c:1058
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:call_sbin_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff81512020-ffffffff81512116: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff815a4490)
Location: security/keys/key.c:1058
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:call_sbin_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff815a4490-ffffffff815a4594: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8164e210)
Location: security/keys/key.c:1058
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:call_sbin_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff8164e210-ffffffff8164e314: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81686a70)
Location: security/keys/key.c:1121
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:call_sbin_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff81686a70-ffffffff81686b74: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff816c2f80)
Location: security/keys/key.c:1117
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:call_sbin_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff816c2f80-ffffffff816c3084: key_revoke (STB_GLOBAL)
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
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffff80001052df08)
Location: security/keys/key.c:1038
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffff80001052df08-ffff80001052dfd8: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c06e638c)
Location: security/keys/key.c:1038
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
c06e638c-c06e6434: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c000000000679e50)
Location: security/keys/key.c:1038
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
c000000000679e50-c000000000679f30: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffe00038f664)
Location: security/keys/key.c:1038
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffe00038f664-ffffffe00038f6dc: key_revoke (STB_GLOBAL)
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
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8143d2e0)
Location: security/keys/key.c:1038
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff8143d2e0-ffffffff8143d35e: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8142dd50)
Location: security/keys/key.c:1038
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff8142dd50-ffffffff8142ddce: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81439480)
Location: security/keys/key.c:1038
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff81439480-ffffffff814394fe: key_revoke (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void key_revoke(struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81450670)
Location: security/keys/key.c:1038
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/request_key.c:complete_request_key
  - net/dns_resolver/dns_key.c:exit_dns_resolver
```
**Symbols:**

```
ffffffff81450670-ffffffff814506ee: key_revoke (STB_GLOBAL)
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
