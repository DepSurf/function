# Function: <code>key_type_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81330330)
Location: security/keys/key.c:659
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
**Symbols:**

```
ffffffff81330330-ffffffff813303a2: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81365080)
Location: security/keys/key.c:678
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:SyS_request_key
```
**Symbols:**

```
ffffffff81365080-ffffffff813650f2: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8137b8a0)
Location: security/keys/key.c:678
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:SyS_request_key
```
**Symbols:**

```
ffffffff8137b8a0-ffffffff8137b912: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8138f440)
Location: security/keys/key.c:680
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:SyS_request_key
```
**Symbols:**

```
ffffffff8138f440-ffffffff8138f4b2: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813b4970)
Location: security/keys/key.c:689
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:SyS_request_key
```
**Symbols:**

```
ffffffff813b4970-ffffffff813b49e2: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813e5150)
Location: security/keys/key.c:689
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff813e5150-ffffffff813e51c2: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813ff920)
Location: security/keys/key.c:690
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff813ff920-ffffffff813ff99b: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8142c030)
Location: security/keys/key.c:697
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff8142c030-ffffffff8142c0ad: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81445d80)
Location: security/keys/key.c:697
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff81445d80-ffffffff81445dfd: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81497128)
Location: security/keys/key.c:700
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
```
**Symbols:**

```
ffffffff814976b0-ffffffff8149772d: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814b4bb2)
Location: security/keys/key.c:703
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
```
**Symbols:**

```
ffffffff814b5160-ffffffff814b51dd: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814baa02)
Location: security/keys/key.c:703
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
```
**Symbols:**

```
ffffffff814bb010-ffffffff814bb08d: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81513232)
Location: security/keys/key.c:703
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
```
**Symbols:**

```
ffffffff81513840-ffffffff815138bd: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff815a5675)
Location: security/keys/key.c:703
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
```
**Symbols:**

```
ffffffff815a5cd0-ffffffff815a5d5b: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8164f475)
Location: security/keys/key.c:703
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
```
**Symbols:**

```
ffffffff8164fb00-ffffffff8164fb8b: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81687cde)
Location: security/keys/key.c:703
Inline: True
Inline callers:
  - security/keys/key.c:__key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
```
**Symbols:**

```
ffffffff816883e0-ffffffff8168846b: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff816c41fe)
Location: security/keys/key.c:701
Inline: True
Inline callers:
  - security/keys/key.c:__key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__do_sys_request_key
```
**Symbols:**

```
ffffffff816c4860-ffffffff816c48eb: key_type_lookup (STB_GLOBAL)
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
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffff80001052efd8)
Location: security/keys/key.c:697
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__arm64_sys_request_key
```
**Symbols:**

```
ffff80001052efd8-ffff80001052f070: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c06e72d0)
Location: security/keys/key.c:697
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__se_sys_request_key
```
**Symbols:**

```
c06e72d0-c06e7350: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c00000000067b9c0)
Location: security/keys/key.c:697
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__se_sys_request_key
```
**Symbols:**

```
c00000000067b9c0-c00000000067bc70: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffe00039084c)
Location: security/keys/key.c:697
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__se_sys_request_key
```
**Symbols:**

```
ffffffe00039084c-ffffffe0003908d8: key_type_lookup (STB_GLOBAL)
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
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8143e360)
Location: security/keys/key.c:697
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff8143e360-ffffffff8143e3dd: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8142edd0)
Location: security/keys/key.c:697
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff8142edd0-ffffffff8142ee4d: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8143a500)
Location: security/keys/key.c:697
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff8143a500-ffffffff8143a57d: key_type_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct key_type *key_type_lookup(const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81451640)
Location: security/keys/key.c:697
Inline: False
Direct callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff81451640-ffffffff814516bd: key_type_lookup (STB_GLOBAL)
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
