# Function: <code>tpm2_unseal_cmd</code>

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
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a6412)
Location: drivers/char/tpm/tpm2-cmd.c:641
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff815ba934)
Location: drivers/char/tpm/tpm2-cmd.c:654
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81620fe2)
Location: drivers/char/tpm/tpm2-cmd.c:654
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165ad3c)
Location: drivers/char/tpm/tpm2-cmd.c:651
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81678cbc)
Location: drivers/char/tpm/tpm2-cmd.c:592
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816af11e)
Location: drivers/char/tpm/tpm2-cmd.c:597
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d1e0e)
Location: drivers/char/tpm/tpm2-cmd.c:597
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
int tpm2_unseal_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814a3310)
Location: security/keys/trusted-keys/trusted_tpm2.c:240
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff814a3310-ffffffff814a34b5: tpm2_unseal_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm2_unseal_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c0ab0)
Location: security/keys/trusted-keys/trusted_tpm2.c:247
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff814c0ab0-ffffffff814c0c5e: tpm2_unseal_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tpm2_unseal_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c7080)
Location: security/keys/trusted-keys/trusted_tpm2.c:458
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff814c7080-ffffffff814c7281: tpm2_unseal_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tpm2_unseal_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8151fb60)
Location: security/keys/trusted-keys/trusted_tpm2.c:458
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff8151fb60-ffffffff8151fd61: tpm2_unseal_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm2_unseal_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff815b3250)
Location: security/keys/trusted-keys/trusted_tpm2.c:458
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff815b3250-ffffffff815b3465: tpm2_unseal_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm2_unseal_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8165dee0)
Location: security/keys/trusted-keys/trusted_tpm2.c:458
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff8165dee0-ffffffff8165e0f5: tpm2_unseal_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm2_unseal_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff81696820)
Location: security/keys/trusted-keys/trusted_tpm2.c:458
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff81696820-ffffffff81696a43: tpm2_unseal_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm2_unseal_cmd(struct tpm_chip *chip, struct trusted_key_payload *payload, struct trusted_key_options *options, u32 blob_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff816d2ea0)
Location: security/keys/trusted-keys/trusted_tpm2.c:458
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
```
**Symbols:**

```
ffffffff816d2ea0-ffffffff816d30c3: tpm2_unseal_cmd (STB_LOCAL)
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
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bc820)
Location: drivers/char/tpm/tpm2-cmd.c:597
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
In drivers/char/tpm/tpm2-cmd.c (c09b5b90)
Location: drivers/char/tpm/tpm2-cmd.c:597
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
In drivers/char/tpm/tpm2-cmd.c (c00000000095e30c)
Location: drivers/char/tpm/tpm2-cmd.c:597
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
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056e6c0)
Location: drivers/char/tpm/tpm2-cmd.c:597
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff8169785e)
Location: drivers/char/tpm/tpm2-cmd.c:597
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff8167524e)
Location: drivers/char/tpm/tpm2-cmd.c:597
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c5ace)
Location: drivers/char/tpm/tpm2-cmd.c:597
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816dffeb)
Location: drivers/char/tpm/tpm2-cmd.c:597
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
