# Function: <code>keyring_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81331540)
Location: security/keys/keyring.c:1300
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff81331540-ffffffff813315b5: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813662d0)
Location: security/keys/keyring.c:1332
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff813662d0-ffffffff81366344: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8137caf0)
Location: security/keys/keyring.c:1332
Inline: True
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff8137caf0-ffffffff8137cb64: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81390640)
Location: security/keys/keyring.c:1445
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff81390640-ffffffff813906b4: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813b5b90)
Location: security/keys/keyring.c:1447
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff813b5b90-ffffffff813b5c04: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813e6380)
Location: security/keys/keyring.c:1440
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff813e6380-ffffffff813e63f4: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81400b60)
Location: security/keys/keyring.c:1438
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff81400b60-ffffffff81400bd4: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142cc50)
Location: security/keys/keyring.c:1646
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff8142cc50-ffffffff8142cccd: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814469a0)
Location: security/keys/keyring.c:1646
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff814469a0-ffffffff81446a1d: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814982d0)
Location: security/keys/keyring.c:1647
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff814982d0-ffffffff814983cc: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814b5d40)
Location: security/keys/keyring.c:1647
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff814b5d40-ffffffff814b5e3c: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814bbbc0)
Location: security/keys/keyring.c:1647
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff814bbbc0-ffffffff814bbcbc: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81514420)
Location: security/keys/keyring.c:1647
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff81514420-ffffffff8151451c: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff815a6a50)
Location: security/keys/keyring.c:1647
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff815a6a50-ffffffff815a6b52: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff816509e0)
Location: security/keys/keyring.c:1647
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff816509e0-ffffffff81650ae2: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff816892c0)
Location: security/keys/keyring.c:1647
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff816892c0-ffffffff816893c2: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff816c57a0)
Location: security/keys/keyring.c:1647
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff816c57a0-ffffffff816c58a2: keyring_clear (STB_GLOBAL)
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
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffff80001052fdd8)
Location: security/keys/keyring.c:1646
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffff80001052fdd8-ffff80001052fe6c: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c06e801c)
Location: security/keys/keyring.c:1646
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
c06e801c-c06e80a4: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c00000000067cf20)
Location: security/keys/keyring.c:1646
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
c00000000067cf20-c00000000067cff8: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffe000391402)
Location: security/keys/keyring.c:1646
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffe000391402-ffffffe00039148a: keyring_clear (STB_GLOBAL)
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
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143ef80)
Location: security/keys/keyring.c:1646
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff8143ef80-ffffffff8143effd: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142f9f0)
Location: security/keys/keyring.c:1646
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff8142f9f0-ffffffff8142fa6d: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143b120)
Location: security/keys/keyring.c:1646
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff8143b120-ffffffff8143b19d: keyring_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int keyring_clear(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81452270)
Location: security/keys/keyring.c:1646
Inline: False
Direct callers:
  - fs/crypto/keyring.c:do_remove_key
  - security/keys/keyctl.c:keyctl_keyring_clear
```
**Symbols:**

```
ffffffff81452270-ffffffff814522ed: keyring_clear (STB_GLOBAL)
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
