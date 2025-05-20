# Function: <code>crypto_unregister_template</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8139dd30)
Location: crypto/algapi.c:469
Inline: False
Direct callers:
  - crypto/chainiv.c:chainiv_module_exit
  - crypto/eseqiv.c:eseqiv_module_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
```
**Symbols:**

```
ffffffff8139dd30-ffffffff8139de69: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813dac80)
Location: crypto/algapi.c:468
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
  - crypto/ctr.c:crypto_ctr_module_exit
  - crypto/ctr.c:crypto_ctr_module_exit
```
**Symbols:**

```
ffffffff813dac80-ffffffff813dadbd: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813f25c0)
Location: crypto/algapi.c:469
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
  - crypto/ctr.c:crypto_ctr_module_exit
  - crypto/ctr.c:crypto_ctr_module_exit
```
**Symbols:**

```
ffffffff813f25c0-ffffffff813f26fd: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813fe8b0)
Location: crypto/algapi.c:469
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
  - crypto/ctr.c:crypto_ctr_module_exit
  - crypto/ctr.c:crypto_ctr_module_exit
```
**Symbols:**

```
ffffffff813fe8b0-ffffffff813fe9e7: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81426e70)
Location: crypto/algapi.c:481
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
  - crypto/ctr.c:crypto_ctr_module_exit
  - crypto/ctr.c:crypto_ctr_module_exit
  - crypto/gcm.c:crypto_gcm_module_exit
  - crypto/gcm.c:crypto_gcm_module_exit
  - crypto/gcm.c:crypto_gcm_module_exit
  - crypto/gcm.c:crypto_gcm_module_exit
  - crypto/gcm.c:crypto_gcm_module_init
  - crypto/gcm.c:crypto_gcm_module_init
  - crypto/gcm.c:crypto_gcm_module_init
```
**Symbols:**

```
ffffffff81426e70-ffffffff81426fa7: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8145a5f0)
Location: crypto/algapi.c:488
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
  - crypto/ctr.c:crypto_ctr_module_exit
  - crypto/ctr.c:crypto_ctr_module_exit
  - crypto/ctr.c:crypto_ctr_module_init
  - crypto/gcm.c:crypto_gcm_module_exit
  - crypto/gcm.c:crypto_gcm_module_exit
  - crypto/gcm.c:crypto_gcm_module_exit
  - crypto/gcm.c:crypto_gcm_module_exit
  - crypto/gcm.c:crypto_gcm_module_init
  - crypto/gcm.c:crypto_gcm_module_init
  - crypto/gcm.c:crypto_gcm_module_init
```
**Symbols:**

```
ffffffff8145a5f0-ffffffff8145a72e: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81477b50)
Location: crypto/algapi.c:497
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
  - crypto/ctr.c:crypto_ctr_module_exit
  - crypto/ctr.c:crypto_ctr_module_exit
  - crypto/ctr.c:crypto_ctr_module_init
  - crypto/gcm.c:crypto_gcm_module_exit
  - crypto/gcm.c:crypto_gcm_module_exit
  - crypto/gcm.c:crypto_gcm_module_exit
  - crypto/gcm.c:crypto_gcm_module_exit
  - crypto/gcm.c:crypto_gcm_module_init
  - crypto/gcm.c:crypto_gcm_module_init
  - crypto/gcm.c:crypto_gcm_module_init
```
**Symbols:**

```
ffffffff81477b50-ffffffff81477c8e: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a5800)
Location: crypto/algapi.c:496
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
```
**Symbols:**

```
ffffffff814a5800-ffffffff814a5919: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814c04b0)
Location: crypto/algapi.c:514
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
```
**Symbols:**

```
ffffffff814c04b0-ffffffff814c05c9: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81520600)
Location: crypto/algapi.c:536
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
```
**Symbols:**

```
ffffffff81520600-ffffffff81520724: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8153d490)
Location: crypto/algapi.c:536
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:xts_module_exit
```
**Symbols:**

```
ffffffff8153d490-ffffffff8153d5b4: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81545b70)
Location: crypto/algapi.c:536
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:xts_module_exit
```
**Symbols:**

```
ffffffff81545b70-ffffffff81545c94: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff815a6080)
Location: crypto/algapi.c:536
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:xts_module_exit
```
**Symbols:**

```
ffffffff815a6080-ffffffff815a61a4: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8164d410)
Location: crypto/algapi.c:552
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:xts_module_exit
```
**Symbols:**

```
ffffffff8164d410-ffffffff8164d542: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81706480)
Location: crypto/algapi.c:573
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:xts_module_exit
```
**Symbols:**

```
ffffffff81706480-ffffffff817065b2: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81740670)
Location: crypto/algapi.c:585
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:xts_module_exit
```
**Symbols:**

```
ffffffff81740670-ffffffff817407a2: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81781510)
Location: crypto/algapi.c:586
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:xts_module_exit
```
**Symbols:**

```
ffffffff81781510-ffffffff81781642: crypto_unregister_template (STB_GLOBAL)
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
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffff8000105b9b60)
Location: crypto/algapi.c:514
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
```
**Symbols:**

```
ffff8000105b9b60-ffff8000105b9c94: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c07684a8)
Location: crypto/algapi.c:514
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
```
**Symbols:**

```
c07684a8-c07685f4: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c0000000007400f0)
Location: crypto/algapi.c:514
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
```
**Symbols:**

```
c0000000007400f0-c000000000740290: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffe0003fff6c)
Location: crypto/algapi.c:514
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
```
**Symbols:**

```
ffffffe0003fff6c-ffffffe000400054: crypto_unregister_template (STB_GLOBAL)
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
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b8a90)
Location: crypto/algapi.c:514
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
```
**Symbols:**

```
ffffffff814b8a90-ffffffff814b8ba9: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a94b0)
Location: crypto/algapi.c:514
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
```
**Symbols:**

```
ffffffff814a94b0-ffffffff814a95c9: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b4b20)
Location: crypto/algapi.c:514
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
```
**Symbols:**

```
ffffffff814b4b20-ffffffff814b4c39: crypto_unregister_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void crypto_unregister_template(struct crypto_template *tmpl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814cd5a0)
Location: crypto/algapi.c:514
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_templates
  - crypto/algapi.c:crypto_register_templates
  - crypto/seqiv.c:seqiv_module_exit
  - crypto/rsa.c:rsa_exit
  - crypto/hmac.c:hmac_module_exit
  - crypto/ecb.c:crypto_ecb_module_exit
  - crypto/cbc.c:crypto_cbc_module_exit
  - crypto/cts.c:crypto_cts_module_exit
  - crypto/xts.c:crypto_module_exit
```
**Symbols:**

```
ffffffff814cd5a0-ffffffff814cd6b9: crypto_unregister_template (STB_GLOBAL)
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
