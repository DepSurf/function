# Function: <code>keyctl_change_reqkey_auth</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81331ca0)
Location: security/keys/keyctl.c:980
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_reject_key
```
**Symbols:**

```
ffffffff81331ca0-ffffffff81331ce7: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81366a60)
Location: security/keys/keyctl.c:1008
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81366a60-ffffffff81366aa7: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8137d280)
Location: security/keys/keyctl.c:1008
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff8137d280-ffffffff8137d2c7: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81391070)
Location: security/keys/keyctl.c:1013
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81391070-ffffffff813910b7: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff813b6740)
Location: security/keys/keyctl.c:1017
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff813b6740-ffffffff813b678d: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff813e72f0)
Location: security/keys/keyctl.c:1017
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff813e72f0-ffffffff813e733d: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81401af0)
Location: security/keys/keyctl.c:1017
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81401af0-ffffffff81401b3d: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8142e600)
Location: security/keys/keyctl.c:1073
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff8142e600-ffffffff8142e64c: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814483b0)
Location: security/keys/keyctl.c:1073
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff814483b0-ffffffff814483fc: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8149b286)
Location: security/keys/keyctl.c:1144
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff814998a0-ffffffff81499915: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814b8d16)
Location: security/keys/keyctl.c:1144
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff814b7330-ffffffff814b73a5: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814beb6d)
Location: security/keys/keyctl.c:1144
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff814bd190-ffffffff814bd205: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8151758d)
Location: security/keys/keyctl.c:1144
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81515c10-ffffffff81515c85: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff815a9f9b)
Location: security/keys/keyctl.c:1144
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff815a8420-ffffffff815a84a0: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8165423b)
Location: security/keys/keyctl.c:1144
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81652540-ffffffff816525c0: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8168ca7b)
Location: security/keys/keyctl.c:1149
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff8168ad60-ffffffff8168ade0: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816c8f6b)
Location: security/keys/keyctl.c:1149
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff816c7260-ffffffff816c72e0: keyctl_change_reqkey_auth (STB_LOCAL)
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
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffff8000105318a8)
Location: security/keys/keyctl.c:1073
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffff8000105318a8-ffff800010531900: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (c06e9558)
Location: security/keys/keyctl.c:1073
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
c06e9558-c06e95ac: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (c00000000067f000)
Location: security/keys/keyctl.c:1073
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
c00000000067f000-c00000000067f08c: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffe000392766)
Location: security/keys/keyctl.c:1073
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffe000392766-ffffffe0003927bc: keyctl_change_reqkey_auth (STB_LOCAL)
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
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81440990)
Location: security/keys/keyctl.c:1073
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81440990-ffffffff814409dc: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81431400)
Location: security/keys/keyctl.c:1073
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81431400-ffffffff8143144c: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8143cb30)
Location: security/keys/keyctl.c:1073
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff8143cb30-ffffffff8143cb7c: keyctl_change_reqkey_auth (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int keyctl_change_reqkey_auth(struct key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81453cc0)
Location: security/keys/keyctl.c:1073
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
```
**Symbols:**

```
ffffffff81453cc0-ffffffff81453d0c: keyctl_change_reqkey_auth (STB_LOCAL)
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
