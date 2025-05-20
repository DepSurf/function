# Function: <code>install_thread_keyring_to_cred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81333a40)
Location: security/keys/process_keys.c:131
Inline: False
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff81333a40-ffffffff81333a8f: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81368900)
Location: security/keys/process_keys.c:133
Inline: False
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff81368900-ffffffff81368958: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8137f110)
Location: security/keys/process_keys.c:133
Inline: False
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff8137f110-ffffffff8137f168: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff813937e6)
Location: security/keys/process_keys.c:136
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff81392e40-ffffffff81392e88: install_thread_keyring_to_cred.part.1 (STB_LOCAL)
ffffffff81393090-ffffffff813930aa: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff813b8e77)
Location: security/keys/process_keys.c:138
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff813b84a0-ffffffff813b84e8: install_thread_keyring_to_cred.part.1 (STB_LOCAL)
ffffffff813b8700-ffffffff813b871a: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff813e9b8e)
Location: security/keys/process_keys.c:138
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff813e9210-ffffffff813e9258: install_thread_keyring_to_cred.part.2 (STB_LOCAL)
ffffffff813e9480-ffffffff813e949a: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff814044d0)
Location: security/keys/process_keys.c:138
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff81403c40-ffffffff81403c88: install_thread_keyring_to_cred.part.2 (STB_LOCAL)
ffffffff81403eb0-ffffffff81403eca: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff81431387)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff814308b0-ffffffff814308f8: install_thread_keyring_to_cred.part.0 (STB_LOCAL)
ffffffff81430d40-ffffffff81430d5a: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff8144b0e7)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff8144a610-ffffffff8144a658: install_thread_keyring_to_cred.part.0 (STB_LOCAL)
ffffffff8144aaa0-ffffffff8144aaba: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8149cce5)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff8149c5b0-ffffffff8149c619: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff814ba785)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff814ba050-ffffffff814ba0b9: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff814c0605)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff814bfed0-ffffffff814bff39: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81519025)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff815188f0-ffffffff81518959: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff815abcb0)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff815ab430-ffffffff815ab4a6: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81656130)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff81655830-ffffffff816558a6: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8168eb3c)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff8168e060-ffffffff8168e0d6: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff816cb092)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff816ca5b0-ffffffff816ca626: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffff800010534e90)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffff8000105342b8-ffff800010534314: install_thread_keyring_to_cred.part.0 (STB_LOCAL)
ffff800010534718-ffff80001053475c: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (c06ec5d8)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
c06eb99c-c06eba04: install_thread_keyring_to_cred.part.0 (STB_LOCAL)
c06ebe30-c06ebe60: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (c000000000683404)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
c000000000682310-c0000000006823a8: install_thread_keyring_to_cred.part.0 (STB_LOCAL)
c000000000682920-c000000000682954: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffe000394f46)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffe0003944e2-ffffffe000394538: install_thread_keyring_to_cred.part.0 (STB_LOCAL)
ffffffe0003948aa-ffffffe0003948e4: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff814436c7)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff81442bf0-ffffffff81442c38: install_thread_keyring_to_cred.part.0 (STB_LOCAL)
ffffffff81443080-ffffffff8144309a: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff81434117)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff81433640-ffffffff81433688: install_thread_keyring_to_cred.part.0 (STB_LOCAL)
ffffffff81433ad0-ffffffff81433aea: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff8143f867)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff8143ed90-ffffffff8143edd8: install_thread_keyring_to_cred.part.0 (STB_LOCAL)
ffffffff8143f220-ffffffff8143f23a: install_thread_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_thread_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff81456a07)
Location: security/keys/process_keys.c:221
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - kernel/cred.c:copy_creds
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff81455f40-ffffffff81455f88: install_thread_keyring_to_cred.part.0 (STB_LOCAL)
ffffffff814563d0-ffffffff814563ea: install_thread_keyring_to_cred (STB_GLOBAL)
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
