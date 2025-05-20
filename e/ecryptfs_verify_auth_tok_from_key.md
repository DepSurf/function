# Function: <code>ecryptfs_verify_auth_tok_from_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81307ac0)
Location: fs/ecryptfs/keystore.c:464
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
**Symbols:**

```
ffffffff81307ac0-ffffffff81307b73: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8133b970)
Location: fs/ecryptfs/keystore.c:465
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff8133b970-ffffffff8133ba23: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81351700)
Location: fs/ecryptfs/keystore.c:465
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff81351700-ffffffff813517b3: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81366240)
Location: fs/ecryptfs/keystore.c:465
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff81366240-ffffffff813662ef: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8138ae80)
Location: fs/ecryptfs/keystore.c:466
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff8138ae80-ffffffff8138af49: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:466
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff813b9d90-ffffffff813b9e45: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
ffffffff813bcc9c-ffffffff813bccb2: ecryptfs_verify_auth_tok_from_key.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813d33c1)
Location: fs/ecryptfs/keystore.c:466
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff813d3340-ffffffff813d33f5: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
ffffffff813d630c-ffffffff813d6322: ecryptfs_verify_auth_tok_from_key.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff813fdec6)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff813fde40-ffffffff813fdefa: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
ffffffff81400b78-ffffffff81400b8e: ecryptfs_verify_auth_tok_from_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81417db6)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff81417d30-ffffffff81417dea: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
ffffffff8141aa68-ffffffff8141aa7e: ecryptfs_verify_auth_tok_from_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814662fd)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff81466280-ffffffff81466331: ecryptfs_verify_auth_tok_from_key.isra.0 (STB_LOCAL)
ffffffff81469508-ffffffff8146951e: ecryptfs_verify_auth_tok_from_key.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8148178d)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff81481710-ffffffff814817c1: ecryptfs_verify_auth_tok_from_key.isra.0 (STB_LOCAL)
ffffffff81beea95-ffffffff81beeaab: ecryptfs_verify_auth_tok_from_key.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814871ed)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff81487170-ffffffff81487221: ecryptfs_verify_auth_tok_from_key.isra.0 (STB_LOCAL)
ffffffff81be0b5b-ffffffff81be0b71: ecryptfs_verify_auth_tok_from_key.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff814de98d)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff814de910-ffffffff814de9c1: ecryptfs_verify_auth_tok_from_key.isra.0 (STB_LOCAL)
ffffffff81cd12f8-ffffffff81cd130e: ecryptfs_verify_auth_tok_from_key.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (0)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff8156c900-ffffffff8156c9cc: ecryptfs_verify_auth_tok_from_key.isra.0 (STB_LOCAL)
ffffffff81e844c1-ffffffff81e844d7: ecryptfs_verify_auth_tok_from_key.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81610c80)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff81610c80-ffffffff81610d68: ecryptfs_verify_auth_tok_from_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81648b30)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff81648b30-ffffffff81648c18: ecryptfs_verify_auth_tok_from_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81682000)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff81682000-ffffffff816820e8: ecryptfs_verify_auth_tok_from_key.isra.0 (STB_LOCAL)
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
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffff8000104f9540)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffff8000104f9540-ffff8000104f9654: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c06b6ddc)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
c06b6ddc-c06b6ed0: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (c00000000063b910)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
c00000000063b910-c00000000063ba5c: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffe000367c8a)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffe000367c8a-ffffffe000367d7c: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
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
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81410396)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff81410310-ffffffff814103ca: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
ffffffff81413048-ffffffff8141305e: ecryptfs_verify_auth_tok_from_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81400e16)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff81400d90-ffffffff81400e4a: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
ffffffff81403ac8-ffffffff81403ade: ecryptfs_verify_auth_tok_from_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff8140d716)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff8140d690-ffffffff8140d74a: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
ffffffff814103c8-ffffffff814103de: ecryptfs_verify_auth_tok_from_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ecryptfs_verify_auth_tok_from_key(struct key *auth_tok_key, struct ecryptfs_auth_tok **auth_tok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/keystore.c (ffffffff81423386)
Location: fs/ecryptfs/keystore.c:452
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
**Symbols:**

```
ffffffff81423300-ffffffff814233ba: ecryptfs_verify_auth_tok_from_key (STB_LOCAL)
ffffffff81426038-ffffffff8142604e: ecryptfs_verify_auth_tok_from_key.cold (STB_LOCAL)
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
