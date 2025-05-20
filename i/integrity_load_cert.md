# Function: <code>integrity_load_cert</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff828cf652)
Location: security/integrity/digsig.c:170
Inline: False
```
**Symbols:**

```
ffffffff828cf652-ffffffff828cf69f: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff828e9186)
Location: security/integrity/digsig.c:170
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
```
**Symbols:**

```
ffffffff828e9186-ffffffff828e91d5: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff828f1d73)
Location: security/integrity/digsig.c:195
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
```
**Symbols:**

```
ffffffff828f1d73-ffffffff828f1dc2: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff82d06dca)
Location: security/integrity/digsig.c:193
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
```
**Symbols:**

```
ffffffff82d06dca-ffffffff82d06e19: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff82ff41f7)
Location: security/integrity/digsig.c:195
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
```
**Symbols:**

```
ffffffff82ff41f7-ffffffff82ff4246: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff831fedb8)
Location: security/integrity/digsig.c:197
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
```
**Symbols:**

```
ffffffff831fedb8-ffffffff831fee07: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff832e61aa)
Location: security/integrity/digsig.c:197
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
```
**Symbols:**

```
ffffffff832e61aa-ffffffff832e61f9: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff8349d071)
Location: security/integrity/digsig.c:209
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
  - security/integrity/platform_certs/machine_keyring.c:add_to_machine_keyring
  - security/integrity/platform_certs/machine_keyring.c:add_to_machine_keyring
```
**Symbols:**

```
ffffffff8349d071-ffffffff8349d0dc: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff83ed4ad0)
Location: security/integrity/digsig.c:213
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
  - security/integrity/platform_certs/machine_keyring.c:add_to_machine_keyring
  - security/integrity/platform_certs/machine_keyring.c:add_to_machine_keyring
```
**Symbols:**

```
ffffffff83ed4ad0-ffffffff83ed4b3b: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff836f9c30)
Location: security/integrity/digsig.c:217
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
  - security/integrity/platform_certs/machine_keyring.c:add_to_machine_keyring
  - security/integrity/platform_certs/machine_keyring.c:add_to_machine_keyring
```
**Symbols:**

```
ffffffff836f9c30-ffffffff836f9c9b: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff8392d0e0)
Location: security/integrity/digsig.c:218
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
  - security/integrity/platform_certs/machine_keyring.c:add_to_machine_keyring
  - security/integrity/platform_certs/machine_keyring.c:add_to_machine_keyring
```
**Symbols:**

```
ffffffff8392d0e0-ffffffff8392d14b: integrity_load_cert (STB_GLOBAL)
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
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffff80001146c0c8)
Location: security/integrity/digsig.c:195
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
```
**Symbols:**

```
ffff80001146c0c8-ffff80001146c13c: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (c1544d88)
Location: security/integrity/digsig.c:195
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
```
**Symbols:**

```
c1544d88-c1544dd8: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (c00000000139ae6c)
Location: security/integrity/digsig.c:195
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
```
**Symbols:**

```
c00000000139ae6c-c00000000139aef8: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffe00002703c)
Location: security/integrity/digsig.c:195
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
```
**Symbols:**

```
ffffffe00002703c-ffffffe00002709a: integrity_load_cert (STB_GLOBAL)
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
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff828dac27)
Location: security/integrity/digsig.c:195
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
```
**Symbols:**

```
ffffffff828dac27-ffffffff828dac76: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff828d3343)
Location: security/integrity/digsig.c:195
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
```
**Symbols:**

```
ffffffff828d3343-ffffffff828d3392: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff828ed99b)
Location: security/integrity/digsig.c:195
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
```
**Symbols:**

```
ffffffff828ed99b-ffffffff828ed9ea: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int integrity_load_cert(const unsigned int id, const char *source, const void *data, size_t len, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/digsig.c (ffffffff828f2dbd)
Location: security/integrity/digsig.c:195
Inline: False
Direct callers:
  - security/integrity/platform_certs/platform_keyring.c:add_to_platform_keyring
```
**Symbols:**

```
ffffffff828f2dbd-ffffffff828f2e0c: integrity_load_cert (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
