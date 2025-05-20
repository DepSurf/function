# Function: <code>request_key_and_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81334a80)
Location: security/keys/request_key.c:508
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/request_key.c:request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_async
  - security/keys/request_key.c:request_key_async_with_auxdata
```
**Symbols:**

```
ffffffff81334a80-ffffffff8133503e: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81369a30)
Location: security/keys/request_key.c:508
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/request_key.c:request_key_async_with_auxdata
  - security/keys/request_key.c:request_key_async
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
```
**Symbols:**

```
ffffffff81369a30-ffffffff81369fc0: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81380240)
Location: security/keys/request_key.c:508
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/request_key.c:request_key_async_with_auxdata
  - security/keys/request_key.c:request_key_async
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
```
**Symbols:**

```
ffffffff81380240-ffffffff813807d0: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff813940c0)
Location: security/keys/request_key.c:509
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/request_key.c:request_key_async_with_auxdata
  - security/keys/request_key.c:request_key_async
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
```
**Symbols:**

```
ffffffff813940c0-ffffffff8139463e: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff813b9690)
Location: security/keys/request_key.c:537
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/request_key.c:request_key_async_with_auxdata
  - security/keys/request_key.c:request_key_async
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
```
**Symbols:**

```
ffffffff813b9690-ffffffff813b9d97: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff813ea400)
Location: security/keys/request_key.c:537
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/request_key.c:request_key_async_with_auxdata
  - security/keys/request_key.c:request_key_async
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
```
**Symbols:**

```
ffffffff813ea400-ffffffff813eaace: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81404e60)
Location: security/keys/request_key.c:523
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/request_key.c:request_key_async_with_auxdata
  - security/keys/request_key.c:request_key_async
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
```
**Symbols:**

```
ffffffff81404e60-ffffffff814054e8: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814323d0)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff814323d0-ffffffff81432598: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8144c130)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff8144c130-ffffffff8144c2f8: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8149e1e0)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff8149e1e0-ffffffff8149e3a8: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814bbcc0)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff814bbcc0-ffffffff814bbe99: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814c1b90)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff814c1b90-ffffffff814c1d6c: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8151a440)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff8151a440-ffffffff8151a759: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff815ad1c0)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff815ad1c0-ffffffff815ad52f: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff816578c0)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff816578c0-ffffffff81657ac6: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81690140)
Location: security/keys/request_key.c:574
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff81690140-ffffffff81690346: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff816cc6d0)
Location: security/keys/request_key.c:574
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff816cc6d0-ffffffff816cc8d6: request_key_and_link (STB_GLOBAL)
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
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffff800010535e38)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__arm64_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffff800010535e38-ffff800010535fe8: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (c06ed4c0)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
c06ed4c0-c06ed678: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (c0000000006847a0)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
c0000000006847a0-c0000000006849d0: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffe000395b68)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffe000395b68-ffffffe000395d00: request_key_and_link (STB_GLOBAL)
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
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81444710)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff81444710-ffffffff814448d8: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81435160)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff81435160-ffffffff81435328: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814407d0)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff814407d0-ffffffff81440973: request_key_and_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct key *request_key_and_link(struct key_type *type, const char *description, struct key_tag *domain_tag, const void *callout_info, size_t callout_len, void *aux, struct key *dest_keyring, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81457a90)
Location: security/keys/request_key.c:558
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
```
**Symbols:**

```
ffffffff81457a90-ffffffff81457c6e: request_key_and_link (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct key_tag *domain_tag</code>
</li>
<li>
<b>Param reordered. </b>
<code>type, description, callout_info, callout_len, aux, dest_keyring, flags</code> ➡️ <code>type, description, domain_tag, callout_info, callout_len, aux, dest_keyring, flags</code>
</li>
</ul>
</details>
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
