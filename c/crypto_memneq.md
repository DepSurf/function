# Function: <code>crypto_memneq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff8139accf)
Location: include/crypto/algapi.h:380
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/asymmetric_keys/rsa.c (ffffffff813ac8f9)
Location: include/crypto/algapi.h:380
Inline: True
Inline callers:
  - crypto/asymmetric_keys/rsa.c:RSA_verify_signature
  - crypto/asymmetric_keys/rsa.c:RSA_verify_signature
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
In security/integrity/evm/evm_main.c (ffffffff813d7afd)
Location: include/crypto/algapi.h:438
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_main.c (ffffffff813ef7bd)
Location: include/crypto/algapi.h:373
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/xts.c (ffffffff81401347)
Location: include/crypto/algapi.h:373
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff8139a203)
Location: include/crypto/algapi.h:389
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff813fbd9d)
Location: include/crypto/algapi.h:389
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81405f9f)
Location: include/crypto/algapi.h:389
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff8140e63b)
Location: include/crypto/algapi.h:389
Inline: True
Inline callers:
  - crypto/xts.c:setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bf893)
Location: include/crypto/algapi.h:408
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff8142426d)
Location: include/crypto/algapi.h:408
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8142e8bf)
Location: include/crypto/algapi.h:408
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff81437105)
Location: include/crypto/algapi.h:408
Inline: True
Inline callers:
  - crypto/xts.c:setkey
```
```
In crypto/gcm.c (ffffffff8143928e)
Location: include/crypto/algapi.h:408
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/encrypted-keys/encrypted.c (ffffffff813f0661)
Location: include/crypto/algapi.h:415
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff8145693a)
Location: include/crypto/algapi.h:415
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8146148c)
Location: include/crypto/algapi.h:415
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff81469b33)
Location: include/crypto/algapi.h:415
Inline: True
```
```
In crypto/gcm.c (ffffffff8146bc17)
Location: include/crypto/algapi.h:415
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff81311163)
Location: include/crypto/algapi.h:417
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:find_or_insert_master_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140b941)
Location: include/crypto/algapi.h:417
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff81473dae)
Location: include/crypto/algapi.h:417
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8147f0db)
Location: include/crypto/algapi.h:417
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff81487a03)
Location: include/crypto/algapi.h:417
Inline: True
```
```
In crypto/gcm.c (ffffffff81489177)
Location: include/crypto/algapi.h:417
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff813384e5)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:find_or_insert_master_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814386a2)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff814a1ad1)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814ad08d)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff814b5717)
Location: include/crypto/algapi.h:405
Inline: True
```
```
In crypto/gcm.c (ffffffff814b6e17)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff8134e2f5)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814524d0)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff814bc7a1)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c7d3d)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff814ce917)
Location: include/crypto/algapi.h:405
Inline: True
```
```
In crypto/gcm.c (ffffffff814d0037)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
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
In fs/crypto/keysetup_v1.c (ffffffff813943cc)
Location: include/crypto/algapi.h:264
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a5140)
Location: include/crypto/algapi.h:264
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff8151d041)
Location: include/crypto/algapi.h:264
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8152712b)
Location: include/crypto/algapi.h:264
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff8152dbc4)
Location: include/crypto/algapi.h:264
Inline: True
```
```
In crypto/gcm.c (ffffffff8152f217)
Location: include/crypto/algapi.h:264
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
```
In net/mptcp/subflow.c (ffffffff81baf0aa)
Location: include/crypto/algapi.h:264
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In fs/crypto/keysetup_v1.c (ffffffff813a58ad)
Location: include/crypto/algapi.h:275
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c2910)
Location: include/crypto/algapi.h:275
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff81539ee1)
Location: include/crypto/algapi.h:275
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815440a8)
Location: include/crypto/algapi.h:275
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff8154ab94)
Location: include/crypto/algapi.h:275
Inline: True
```
```
In crypto/gcm.c (ffffffff8154c197)
Location: include/crypto/algapi.h:275
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
```
In net/mptcp/subflow.c (ffffffff81bc1c7c)
Location: include/crypto/algapi.h:275
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In fs/crypto/keysetup_v1.c (ffffffff813ac90d)
Location: include/crypto/algapi.h:236
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c86c6)
Location: include/crypto/algapi.h:236
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff81542594)
Location: include/crypto/algapi.h:236
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8154c71c)
Location: include/crypto/algapi.h:236
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff815531b4)
Location: include/crypto/algapi.h:236
Inline: True
```
```
In crypto/gcm.c (ffffffff81554787)
Location: include/crypto/algapi.h:236
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
```
In net/mptcp/subflow.c (ffffffff81bb2587)
Location: include/crypto/algapi.h:236
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In fs/crypto/keysetup_v1.c (ffffffff813fc28e)
Location: include/crypto/algapi.h:244
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815211b6)
Location: include/crypto/algapi.h:244
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff815a2696)
Location: include/crypto/algapi.h:244
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff815acefc)
Location: include/crypto/algapi.h:244
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff815b41e4)
Location: include/crypto/algapi.h:244
Inline: True
```
```
In crypto/gcm.c (ffffffff815b57b7)
Location: include/crypto/algapi.h:244
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
```
In net/mptcp/subflow.c (ffffffff81c8083d)
Location: include/crypto/algapi.h:244
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In fs/crypto/keysetup_v1.c (ffffffff8146f707)
Location: include/crypto/algapi.h:253
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b4a26)
Location: include/crypto/algapi.h:253
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff81648d33)
Location: include/crypto/algapi.h:253
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8165530f)
Location: include/crypto/algapi.h:253
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff8165d04d)
Location: include/crypto/algapi.h:253
Inline: True
```
```
In crypto/gcm.c (ffffffff8165e967)
Location: include/crypto/algapi.h:253
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
```
In net/mptcp/subflow.c (ffffffff81e264ab)
Location: include/crypto/algapi.h:253
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In fs/crypto/keysetup_v1.c (ffffffff81500ee9)
Location: include/crypto/algapi.h:290
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165f536)
Location: include/crypto/algapi.h:290
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff81701b0c)
Location: include/crypto/algapi.h:290
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8170f52f)
Location: include/crypto/algapi.h:290
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff81716b2d)
Location: include/crypto/algapi.h:290
Inline: True
```
```
In crypto/gcm.c (ffffffff817186f7)
Location: include/crypto/algapi.h:290
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
```
In net/mptcp/subflow.c (ffffffff81fff5cd)
Location: include/crypto/algapi.h:290
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In fs/crypto/keysetup_v1.c (ffffffff81538579)
Location: include/crypto/utils.h:68
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81697eb6)
Location: include/crypto/utils.h:68
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff8173bbb6)
Location: include/crypto/utils.h:68
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81749e8f)
Location: include/crypto/utils.h:68
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff817523e0)
Location: include/crypto/utils.h:68
Inline: True
```
```
In crypto/gcm.c (ffffffff81754067)
Location: include/crypto/utils.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
```
In net/mptcp/subflow.c (ffffffff8207b6dd)
Location: include/crypto/utils.h:68
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
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
In fs/crypto/keysetup_v1.c (ffffffff8156d6c9)
Location: include/crypto/utils.h:68
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d49e6)
Location: include/crypto/utils.h:68
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff8177cac6)
Location: include/crypto/utils.h:68
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178bd2f)
Location: include/crypto/utils.h:68
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff81794270)
Location: include/crypto/utils.h:68
Inline: True
```
```
In crypto/gcm.c (ffffffff817959d7)
Location: include/crypto/utils.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
```
In net/mptcp/subflow.c (ffffffff82150cae)
Location: include/crypto/utils.h:68
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffff80001040f810)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053d294)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffff8000105b5308)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffff8000105c36f0)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffff8000105cab3c)
Location: include/crypto/algapi.h:405
Inline: True
```
```
In crypto/gcm.c (ffff8000105cc4ec)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (c05dc0c4)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (c06f3630)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (c07644a0)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (c0770998)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (c077871c)
Location: include/crypto/algapi.h:405
Inline: True
```
```
In crypto/gcm.c (c077a418)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (c00000000051ceac)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068d2f8)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (c000000000738990)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (c00000000074c214)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (c0000000007554d0)
Location: include/crypto/algapi.h:405
Inline: True
```
```
In crypto/gcm.c (c000000000757864)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffe0002b828c)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039b27c)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffe0003fc28e)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffe000407f50)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffe00040ed20)
Location: include/crypto/algapi.h:405
Inline: True
```
```
In crypto/gcm.c (ffffffe000410226)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813468d5)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144aab0)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff814b4d81)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814c031d)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff814c6ef7)
Location: include/crypto/algapi.h:405
Inline: True
```
```
In crypto/gcm.c (ffffffff814c8617)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813375b5)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143b500)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff814a57a1)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814b0d3d)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff814b7917)
Location: include/crypto/algapi.h:405
Inline: True
```
```
In crypto/gcm.c (ffffffff814b9037)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff813443a5)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81446b50)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff814b0e11)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814bc3ad)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff814c2f87)
Location: include/crypto/algapi.h:405
Inline: True
```
```
In crypto/gcm.c (ffffffff814c46a7)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup_v1.c (ffffffff81357685)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145de80)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In security/integrity/evm/evm_main.c (ffffffff814c9891)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
```
In crypto/rsa-pkcs1pad.c (ffffffff814d4e7d)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
```
```
In crypto/xts.c (ffffffff814dba57)
Location: include/crypto/algapi.h:405
Inline: True
```
```
In crypto/gcm.c (ffffffff814dd177)
Location: include/crypto/algapi.h:405
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
```
</details>
</li>
</ul>

## Differences
