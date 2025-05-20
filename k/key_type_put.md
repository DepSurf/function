# Function: <code>key_type_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81330472)
Location: security/keys/key.c:702
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:keyctl_keyring_search
```
**Symbols:**

```
ffffffff81330810-ffffffff81330827: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813651c8)
Location: security/keys/key.c:721
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:SyS_request_key
```
**Symbols:**

```
ffffffff81365570-ffffffff81365587: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8137b9e8)
Location: security/keys/key.c:721
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:SyS_request_key
```
**Symbols:**

```
ffffffff8137bd90-ffffffff8137bda7: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8138f585)
Location: security/keys/key.c:723
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:SyS_request_key
```
**Symbols:**

```
ffffffff8138f920-ffffffff8138f937: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813b4ab5)
Location: security/keys/key.c:729
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:SyS_request_key
```
**Symbols:**

```
ffffffff813b4ea0-ffffffff813b4eb7: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813e529b)
Location: security/keys/key.c:729
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff813e5690-ffffffff813e56a7: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813ffa6b)
Location: security/keys/key.c:730
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff813ffe60-ffffffff813ffe77: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8142c19b)
Location: security/keys/key.c:737
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff8142c550-ffffffff8142c567: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81445eeb)
Location: security/keys/key.c:737
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff814462a0-ffffffff814462b7: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814971c9)
Location: security/keys/key.c:740
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
ffffffff81497730-ffffffff81497747: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814b4c56)
Location: security/keys/key.c:743
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
ffffffff814b51e0-ffffffff814b51f7: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814baaa6)
Location: security/keys/key.c:743
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
ffffffff814bb090-ffffffff814bb0a7: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff815132d6)
Location: security/keys/key.c:743
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
ffffffff815138c0-ffffffff815138d7: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff815a571e)
Location: security/keys/key.c:743
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
ffffffff815a5d60-ffffffff815a5d7d: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8164f51e)
Location: security/keys/key.c:743
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
ffffffff8164fba0-ffffffff8164fbbd: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81687d87)
Location: security/keys/key.c:743
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
ffffffff81688480-ffffffff8168849d: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff816c42a7)
Location: security/keys/key.c:739
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
ffffffff816c4900-ffffffff816c491d: key_type_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffff80001052f12c)
Location: security/keys/key.c:737
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__arm64_sys_request_key
```
**Symbols:**

```
ffff80001052f430-ffff80001052f454: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c06e7410)
Location: security/keys/key.c:737
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__se_sys_request_key
```
**Symbols:**

```
c06e7780-c06e77a4: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c00000000067bd74)
Location: security/keys/key.c:737
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__se_sys_request_key
```
**Symbols:**

```
c00000000067c1a0-c00000000067c1dc: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffe00039096e)
Location: security/keys/key.c:737
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__se_sys_request_key
```
**Symbols:**

```
ffffffe000390c22-ffffffe000390c4c: key_type_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8143e4cb)
Location: security/keys/key.c:737
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff8143e880-ffffffff8143e897: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8142ef3b)
Location: security/keys/key.c:737
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff8142f2f0-ffffffff8142f307: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8143a66b)
Location: security/keys/key.c:737
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff8143aa20-ffffffff8143aa37: key_type_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void key_type_put(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814517ab)
Location: security/keys/key.c:737
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
Direct callers:
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff81451b60-ffffffff81451b77: key_type_put (STB_GLOBAL)
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
