# Function: <code>tpm_buf_append_u8</code>

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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81526026)
Location: drivers/char/tpm/tpm.h:474
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff815797d9)
Location: drivers/char/tpm/tpm.h:455
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a5d06)
Location: drivers/char/tpm/tpm.h:466
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff815ba143)
Location: drivers/char/tpm/tpm.h:481
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81620922)
Location: drivers/char/tpm/tpm.h:474
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81659d4a)
Location: drivers/char/tpm/tpm.h:488
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81677aaa)
Location: drivers/char/tpm/tpm.h:464
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816ad9a3)
Location: drivers/char/tpm/tpm.h:354
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d0683)
Location: drivers/char/tpm/tpm.h:354
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a20ec)
Location: include/linux/tpm.h:373
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814a38f1)
Location: include/linux/tpm.h:373
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff817855ce)
Location: include/linux/tpm.h:373
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814bfab7)
Location: include/linux/tpm.h:373
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c10c3)
Location: include/linux/tpm.h:373
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8179c7ce)
Location: include/linux/tpm.h:373
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c5d17)
Location: include/linux/tpm.h:382
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff814c6d21)
Location: include/linux/tpm.h:382
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8177f29e)
Location: include/linux/tpm.h:382
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151e737)
Location: include/linux/tpm.h:383
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8151f801)
Location: include/linux/tpm.h:383
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8180562e)
Location: include/linux/tpm.h:383
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b1d28)
Location: include/linux/tpm.h:385
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff815b2e91)
Location: include/linux/tpm.h:385
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8194505e)
Location: include/linux/tpm.h:385
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165c87e)
Location: include/linux/tpm.h:385
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff8165db01)
Location: include/linux/tpm.h:385
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa802e)
Location: include/linux/tpm.h:385
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8169519e)
Location: include/linux/tpm.h:389
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff81696441)
Location: include/linux/tpm.h:389
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af385e)
Location: include/linux/tpm.h:389
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d17ce)
Location: include/linux/tpm.h:389
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff816d2ac1)
Location: include/linux/tpm.h:389
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b46e1e)
Location: include/linux/tpm.h:389
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bad5c)
Location: drivers/char/tpm/tpm.h:354
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm2-cmd.c (c09b41bc)
Location: drivers/char/tpm/tpm.h:354
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm2-cmd.c (c00000000095c278)
Location: drivers/char/tpm/tpm.h:354
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056b764)
Location: drivers/char/tpm/tpm.h:354
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816960d3)
Location: drivers/char/tpm/tpm.h:354
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff81673ac3)
Location: drivers/char/tpm/tpm.h:354
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c4343)
Location: drivers/char/tpm/tpm.h:354
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
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
In drivers/char/tpm/tpm2-cmd.c (ffffffff816de8cb)
Location: drivers/char/tpm/tpm.h:354
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
</details>
</li>
</ul>

## Differences
