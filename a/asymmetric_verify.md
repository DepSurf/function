# Function: <code>asymmetric_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff81396790)
Location: security/integrity/digsig_asymmetric.c:67
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81396790-ffffffff813969f6: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff813d2520)
Location: security/integrity/digsig_asymmetric.c:82
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff813d2520-ffffffff813d27bd: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff813e9c40)
Location: security/integrity/digsig_asymmetric.c:82
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff813e9c40-ffffffff813e9ea1: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff813f6040)
Location: security/integrity/digsig_asymmetric.c:82
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff813f6040-ffffffff813f626c: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff8141e140)
Location: security/integrity/digsig_asymmetric.c:82
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff8141e140-ffffffff8141e36c: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig_asymmetric.c (0)
Location: security/integrity/digsig_asymmetric.c:82
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff8145060f-ffffffff81450628: asymmetric_verify.cold.0 (STB_LOCAL)
ffffffff814503f0-ffffffff8145060f: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig_asymmetric.c (0)
Location: security/integrity/digsig_asymmetric.c:82
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff8146d5ec-ffffffff8146d605: asymmetric_verify.cold.0 (STB_LOCAL)
ffffffff8146d390-ffffffff8146d5b8: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig_asymmetric.c (0)
Location: security/integrity/digsig_asymmetric.c:78
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff8149ad0c-ffffffff8149ad25: asymmetric_verify.cold (STB_LOCAL)
ffffffff8149aa80-ffffffff8149acda: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig_asymmetric.c (0)
Location: security/integrity/digsig_asymmetric.c:78
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff814b4f5c-ffffffff814b4f75: asymmetric_verify.cold (STB_LOCAL)
ffffffff814b4cd0-ffffffff814b4f2a: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff81514360)
Location: security/integrity/digsig_asymmetric.c:76
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81514360-ffffffff815144a5: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff815314e0)
Location: security/integrity/digsig_asymmetric.c:82
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff815314e0-ffffffff81531645: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff81539910)
Location: security/integrity/digsig_asymmetric.c:82
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81539910-ffffffff81539ad7: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff81598260)
Location: security/integrity/digsig_asymmetric.c:82
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff81598260-ffffffff8159844f: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff8163cad0)
Location: security/integrity/digsig_asymmetric.c:82
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff8163cad0-ffffffff8163cce2: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff816f43c0)
Location: security/integrity/digsig_asymmetric.c:82
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff816f43c0-ffffffff816f45d2: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff8172e4f0)
Location: security/integrity/digsig_asymmetric.c:82
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff8172e4f0-ffffffff8172e6f9: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffff8176ee50)
Location: security/integrity/digsig_asymmetric.c:82
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff8176ee50-ffffffff8176f059: asymmetric_verify (STB_GLOBAL)
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
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffff8000105ace90)
Location: security/integrity/digsig_asymmetric.c:78
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffff8000105ace90-ffff8000105ad118: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (c075c704)
Location: security/integrity/digsig_asymmetric.c:78
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
c075c704-c075c990: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (c00000000072b440)
Location: security/integrity/digsig_asymmetric.c:78
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
c00000000072b440-c00000000072b774: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig_asymmetric.c (ffffffe0003f5482)
Location: security/integrity/digsig_asymmetric.c:78
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffe0003f5482-ffffffe0003f571a: asymmetric_verify (STB_GLOBAL)
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
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig_asymmetric.c (0)
Location: security/integrity/digsig_asymmetric.c:78
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff814ad53c-ffffffff814ad555: asymmetric_verify.cold (STB_LOCAL)
ffffffff814ad2b0-ffffffff814ad50a: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig_asymmetric.c (0)
Location: security/integrity/digsig_asymmetric.c:78
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff8149df5c-ffffffff8149df75: asymmetric_verify.cold (STB_LOCAL)
ffffffff8149dcd0-ffffffff8149df2a: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig_asymmetric.c (0)
Location: security/integrity/digsig_asymmetric.c:78
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff814a95dc-ffffffff814a95f5: asymmetric_verify.cold (STB_LOCAL)
ffffffff814a9350-ffffffff814a95aa: asymmetric_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int asymmetric_verify(struct key *keyring, const char *sig, int siglen, const char *data, int datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/digsig_asymmetric.c (0)
Location: security/integrity/digsig_asymmetric.c:78
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
**Symbols:**

```
ffffffff814c1fec-ffffffff814c2005: asymmetric_verify.cold (STB_LOCAL)
ffffffff814c1d60-ffffffff814c1fba: asymmetric_verify (STB_GLOBAL)
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
