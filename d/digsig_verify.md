# Function: <code>digsig_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffffffff81419700)
Location: lib/digsig.c:190
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81419700-ffffffff81419c0d: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffffffff81461470)
Location: lib/digsig.c:196
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81461470-ffffffff814619d5: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffffffff8147ff90)
Location: lib/digsig.c:196
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff8147ff90-ffffffff814804f5: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffffffff81489230)
Location: lib/digsig.c:196
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81489230-ffffffff81489792: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffffffff814c5370)
Location: lib/digsig.c:202
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff814c5370-ffffffff814c58e2: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffffffff814f6250)
Location: lib/digsig.c:202
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff814f6250-ffffffff814f67c8: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffffffff8150a650)
Location: lib/digsig.c:202
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff8150a650-ffffffff8150abd3: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/digsig.c (0)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81539335-ffffffff8153934d: digsig_verify.cold (STB_LOCAL)
ffffffff815391a0-ffffffff81539335: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/digsig.c (0)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff8155a155-ffffffff8155a16d: digsig_verify.cold (STB_LOCAL)
ffffffff81559fc0-ffffffff8155a155: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/digsig.c (0)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff815e3a82-ffffffff815e3a9a: digsig_verify.cold (STB_LOCAL)
ffffffff815e38f0-ffffffff815e3a82: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/digsig.c (0)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81bf48af-ffffffff81bf48c7: digsig_verify.cold (STB_LOCAL)
ffffffff81607d80-ffffffff81607f12: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/digsig.c (0)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81be67a7-ffffffff81be67bf: digsig_verify.cold (STB_LOCAL)
ffffffff815eaa90-ffffffff815eac22: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/digsig.c (0)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81cde5d6-ffffffff81cde5ee: digsig_verify.cold (STB_LOCAL)
ffffffff81656f90-ffffffff81657122: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/digsig.c (0)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81ea4941-ffffffff81ea4959: digsig_verify.cold (STB_LOCAL)
ffffffff8176e7a0-ffffffff8176e96b: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffffffff8189e090)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff8189e090-ffffffff8189e26e: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffffffff818e0650)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff818e0650-ffffffff818e082e: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffffffff81927190)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81927190-ffffffff8192736e: digsig_verify (STB_GLOBAL)
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
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffff8000106667a8)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffff8000106667a8-ffff80001066696c: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/digsig.c (c080f404)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
c080f404-c080f5c4: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/digsig.c (c00000000081c330)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
c00000000081c330-c00000000081c5ac: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/digsig.c (ffffffe00049287a)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffe00049287a-ffffffe000492a38: digsig_verify (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/digsig.c (0)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81552735-ffffffff8155274d: digsig_verify.cold (STB_LOCAL)
ffffffff815525a0-ffffffff81552735: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/digsig.c (0)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81542a15-ffffffff81542a2d: digsig_verify.cold (STB_LOCAL)
ffffffff81542880-ffffffff81542a15: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/digsig.c (0)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff8154e475-ffffffff8154e48d: digsig_verify.cold (STB_LOCAL)
ffffffff8154e2e0-ffffffff8154e475: digsig_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int digsig_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/digsig.c (0)
Location: lib/digsig.c:199
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff815682c5-ffffffff815682dd: digsig_verify.cold (STB_LOCAL)
ffffffff81568130-ffffffff815682c5: digsig_verify (STB_GLOBAL)
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
