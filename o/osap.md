# Function: <code>osap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81337c2f)
Location: security/keys/trusted.c:394
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff8136d2b8)
Location: security/keys/trusted.c:394
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81383ad8)
Location: security/keys/trusted.c:394
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81398168)
Location: security/keys/trusted.c:394
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813bd978)
Location: security/keys/trusted.c:394
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813ee788)
Location: security/keys/trusted.c:393
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff814099b3)
Location: security/keys/trusted.c:396
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81436aa0)
Location: security/keys/trusted.c:398
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81450840)
Location: security/keys/trusted.c:398
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int osap(struct tpm_buf *tb, struct osapsess *s, const unsigned char *key, uint16_t type, uint32_t handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a1c80)
Location: security/keys/trusted-keys/trusted_tpm1.c:398
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff814a1c80-ffffffff814a1e7b: osap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int osap(struct tpm_buf *tb, struct osapsess *s, const unsigned char *key, uint16_t type, uint32_t handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814bf640)
Location: security/keys/trusted-keys/trusted_tpm1.c:398
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff814bf640-ffffffff814bf83b: osap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int osap(struct tpm_buf *tb, struct osapsess *s, const unsigned char *key, uint16_t type, uint32_t handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c58a0)
Location: security/keys/trusted-keys/trusted_tpm1.c:391
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff814c58a0-ffffffff814c5a9b: osap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int osap(struct tpm_buf *tb, struct osapsess *s, const unsigned char *key, uint16_t type, uint32_t handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151e2c0)
Location: security/keys/trusted-keys/trusted_tpm1.c:391
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff8151e2c0-ffffffff8151e4bb: osap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int osap(struct tpm_buf *tb, struct osapsess *s, const unsigned char *key, uint16_t type, uint32_t handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b17f0)
Location: security/keys/trusted-keys/trusted_tpm1.c:391
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff815b17f0-ffffffff815b1a2b: osap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int osap(struct tpm_buf *tb, struct osapsess *s, const unsigned char *key, uint16_t type, uint32_t handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165c330)
Location: security/keys/trusted-keys/trusted_tpm1.c:391
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff8165c330-ffffffff8165c56b: osap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int osap(struct tpm_buf *tb, struct osapsess *s, const unsigned char *key, uint16_t type, uint32_t handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff81694c50)
Location: security/keys/trusted-keys/trusted_tpm1.c:391
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff81694c50-ffffffff81694e8b: osap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int osap(struct tpm_buf *tb, struct osapsess *s, const unsigned char *key, uint16_t type, uint32_t handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d1280)
Location: security/keys/trusted-keys/trusted_tpm1.c:391
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
**Symbols:**

```
ffffffff816d1280-ffffffff816d14bb: osap (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffff80001053ba48)
Location: security/keys/trusted.c:398
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c06f19a0)
Location: security/keys/trusted.c:398
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c00000000068acdc)
Location: security/keys/trusted.c:398
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffe0003996ac)
Location: security/keys/trusted.c:398
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_seal
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81448e20)
Location: security/keys/trusted.c:398
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81439870)
Location: security/keys/trusted.c:398
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81444ec0)
Location: security/keys/trusted.c:398
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff8145c1f0)
Location: security/keys/trusted.c:398
Inline: True
Inline callers:
  - security/keys/trusted.c:tpm_seal
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
