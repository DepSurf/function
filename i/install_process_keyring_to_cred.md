# Function: <code>install_process_keyring_to_cred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff81333840)
Location: security/keys/process_keys.c:174
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff81333840-ffffffff8133388f: install_process_keyring_to_cred.part.1 (STB_LOCAL)
ffffffff81333a90-ffffffff81333aad: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff8136909a)
Location: security/keys/process_keys.c:177
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff813686d0-ffffffff81368728: install_process_keyring_to_cred.part.1 (STB_LOCAL)
ffffffff81368960-ffffffff8136897d: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff8137f8aa)
Location: security/keys/process_keys.c:177
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff8137eee0-ffffffff8137ef38: install_process_keyring_to_cred.part.1 (STB_LOCAL)
ffffffff8137f170-ffffffff8137f18d: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff8139379f)
Location: security/keys/process_keys.c:183
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff81392e90-ffffffff81392ed8: install_process_keyring_to_cred.part.2 (STB_LOCAL)
ffffffff813930b0-ffffffff813930ca: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff813b8e2c)
Location: security/keys/process_keys.c:185
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff813b84f0-ffffffff813b8538: install_process_keyring_to_cred.part.2 (STB_LOCAL)
ffffffff813b8720-ffffffff813b873a: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff813e9b34)
Location: security/keys/process_keys.c:185
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff813e9260-ffffffff813e92a8: install_process_keyring_to_cred.part.3 (STB_LOCAL)
ffffffff813e94a0-ffffffff813e94ba: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff81404670)
Location: security/keys/process_keys.c:185
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff81403c90-ffffffff81403cd8: install_process_keyring_to_cred.part.3 (STB_LOCAL)
ffffffff81403ed0-ffffffff81403eea: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff8143160b)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff81430900-ffffffff81430948: install_process_keyring_to_cred.part.0 (STB_LOCAL)
ffffffff81430d60-ffffffff81430d7a: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff8144b36b)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff8144a660-ffffffff8144a6a8: install_process_keyring_to_cred.part.0 (STB_LOCAL)
ffffffff8144aac0-ffffffff8144aada: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8149ce32)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff8149c620-ffffffff8149c689: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff814ba8d2)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff814ba0c0-ffffffff814ba129: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff814c074e)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff814bff40-ffffffff814bffa9: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8151916e)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff81518960-ffffffff815189c9: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff815abe12)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff815ab4b0-ffffffff815ab526: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81656292)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff816558c0-ffffffff81655936: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8168ea04)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff8168e0f0-ffffffff8168e166: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff816caf5a)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
```
**Symbols:**

```
ffffffff816ca640-ffffffff816ca6b6: install_process_keyring_to_cred (STB_GLOBAL)
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
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffff800010534f28)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffff800010534318-ffff800010534374: install_process_keyring_to_cred.part.0 (STB_LOCAL)
ffff800010534760-ffff8000105347a4: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (c06ec50c)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
c06eba04-c06eba6c: install_process_keyring_to_cred.part.0 (STB_LOCAL)
c06ebe60-c06ebe90: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (c0000000006832e4)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
c0000000006823b0-c000000000682448: install_process_keyring_to_cred.part.0 (STB_LOCAL)
c000000000682960-c000000000682994: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffe000394ea0)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffe000394538-ffffffe00039458e: install_process_keyring_to_cred.part.0 (STB_LOCAL)
ffffffe0003948e4-ffffffe00039491e: install_process_keyring_to_cred (STB_GLOBAL)
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
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff8144394b)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff81442c40-ffffffff81442c88: install_process_keyring_to_cred.part.0 (STB_LOCAL)
ffffffff814430a0-ffffffff814430ba: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff8143439b)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff81433690-ffffffff814336d8: install_process_keyring_to_cred.part.0 (STB_LOCAL)
ffffffff81433af0-ffffffff81433b0a: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff8143faeb)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff8143ede0-ffffffff8143ee28: install_process_keyring_to_cred.part.0 (STB_LOCAL)
ffffffff8143f240-ffffffff8143f25a: install_process_keyring_to_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int install_process_keyring_to_cred(struct cred *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/process_keys.c (ffffffff81456c96)
Location: security/keys/process_keys.c:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
Direct callers:
  - security/keys/keyctl.c:keyctl_set_reqkey_keyring
  - security/keys/process_keys.c:lookup_user_key
```
**Symbols:**

```
ffffffff81455f90-ffffffff81455fd8: install_process_keyring_to_cred.part.0 (STB_LOCAL)
ffffffff814563f0-ffffffff8145640a: install_process_keyring_to_cred (STB_GLOBAL)
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
