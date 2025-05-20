# Function: <code>tpm2_load_cmd</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a629d)
Location: drivers/char/tpm/tpm2-cmd.c:549
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff815ba75d)
Location: drivers/char/tpm/tpm2-cmd.c:588
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81620dfd)
Location: drivers/char/tpm/tpm2-cmd.c:588
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165abbd)
Location: drivers/char/tpm/tpm2-cmd.c:585
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81678b3d)
Location: drivers/char/tpm/tpm2-cmd.c:526
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816aefab)
Location: drivers/char/tpm/tpm2-cmd.c:533
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d1c9b)
Location: drivers/char/tpm/tpm2-cmd.c:533
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm2_load_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 *blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814a34c0)
Location: security/keys/trusted-keys/trusted_tpm2.c:176
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff814a34c0-ffffffff814a36a4: tpm2_load_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm2_load_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 *blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c0c60)
Location: security/keys/trusted-keys/trusted_tpm2.c:183
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff814c0c60-ffffffff814c0e49: tpm2_load_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tpm2_load_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 *blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c6df0)
Location: security/keys/trusted-keys/trusted_tpm2.c:360
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff814c6df0-ffffffff814c707c: tpm2_load_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm2_load_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 *blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8151f8d0)
Location: security/keys/trusted-keys/trusted_tpm2.c:360
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff8151f8d0-ffffffff8151fb5c: tpm2_load_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm2_load_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 *blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff815b2f90)
Location: security/keys/trusted-keys/trusted_tpm2.c:360
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff815b2f90-ffffffff815b324e: tpm2_load_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm2_load_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 *blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8165dc10)
Location: security/keys/trusted-keys/trusted_tpm2.c:360
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff8165dc10-ffffffff8165dece: tpm2_load_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm2_load_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 *blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff81696550)
Location: security/keys/trusted-keys/trusted_tpm2.c:360
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff81696550-ffffffff8169680e: tpm2_load_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm2_load_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 *blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff816d2bd0)
Location: security/keys/trusted-keys/trusted_tpm2.c:360
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff816d2bd0-ffffffff816d2e8e: tpm2_load_cmd (STB_LOCAL)
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
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bc6a0)
Location: drivers/char/tpm/tpm2-cmd.c:533
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (c09b5a04)
Location: drivers/char/tpm/tpm2-cmd.c:533
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (c00000000095e134)
Location: drivers/char/tpm/tpm2-cmd.c:533
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056e3fe)
Location: drivers/char/tpm/tpm2-cmd.c:533
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816976eb)
Location: drivers/char/tpm/tpm2-cmd.c:533
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816750db)
Location: drivers/char/tpm/tpm2-cmd.c:533
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c595b)
Location: drivers/char/tpm/tpm2-cmd.c:533
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816dfe7b)
Location: drivers/char/tpm/tpm2-cmd.c:533
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
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
