# Function: <code>key_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813315c0)
Location: security/keys/keyring.c:1259
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff813315c0-ffffffff81331653: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81366350)
Location: security/keys/keyring.c:1291
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff81366350-ffffffff813663e3: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8137cb70)
Location: security/keys/keyring.c:1291
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff8137cb70-ffffffff8137cc03: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813906c0)
Location: security/keys/keyring.c:1404
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff813906c0-ffffffff81390753: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813b5c10)
Location: security/keys/keyring.c:1406
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff813b5c10-ffffffff813b5ca3: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813e6400)
Location: security/keys/keyring.c:1399
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff813e6400-ffffffff813e6493: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81400dc0)
Location: security/keys/keyring.c:1397
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff81400dc0-ffffffff81400e53: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142cf40)
Location: security/keys/keyring.c:1544
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff8142cf40-ffffffff8142cfe5: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81446c90)
Location: security/keys/keyring.c:1544
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff81446c90-ffffffff81446d35: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814983d0)
Location: security/keys/keyring.c:1545
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff814983d0-ffffffff81498505: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814b5e40)
Location: security/keys/keyring.c:1545
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff814b5e40-ffffffff814b5f75: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814bbcc0)
Location: security/keys/keyring.c:1545
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff814bbcc0-ffffffff814bbdf5: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81514520)
Location: security/keys/keyring.c:1545
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff81514520-ffffffff81514655: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff815a6b60)
Location: security/keys/keyring.c:1545
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff815a6b60-ffffffff815a6c9e: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81650b00)
Location: security/keys/keyring.c:1545
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff81650b00-ffffffff81650c3e: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff816893e0)
Location: security/keys/keyring.c:1545
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff816893e0-ffffffff8168950a: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff816c58c0)
Location: security/keys/keyring.c:1545
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff816c58c0-ffffffff816c59ea: key_unlink (STB_GLOBAL)
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
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffff8000105301e8)
Location: security/keys/keyring.c:1544
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffff8000105301e8-ffff8000105302a0: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c06e8300)
Location: security/keys/keyring.c:1544
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
c06e8300-c06e83a8: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c00000000067d430)
Location: security/keys/keyring.c:1544
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
c00000000067d430-c00000000067d560: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffe00039173e)
Location: security/keys/keyring.c:1544
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffe00039173e-ffffffe0003917de: key_unlink (STB_GLOBAL)
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
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143f270)
Location: security/keys/keyring.c:1544
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff8143f270-ffffffff8143f315: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142fce0)
Location: security/keys/keyring.c:1544
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff8142fce0-ffffffff8142fd85: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143b410)
Location: security/keys/keyring.c:1544
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff8143b410-ffffffff8143b4b5: key_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int key_unlink(struct key *keyring, struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81452560)
Location: security/keys/keyring.c:1544
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
```
**Symbols:**

```
ffffffff81452560-ffffffff81452605: key_unlink (STB_GLOBAL)
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
