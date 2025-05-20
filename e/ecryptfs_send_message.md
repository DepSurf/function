# Function: <code>ecryptfs_send_message</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/messaging.c (ffffffff8130b7f0)
Location: fs/ecryptfs/messaging.c:318
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
```
**Symbols:**

```
ffffffff8130b7f0-ffffffff8130b9a3: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/messaging.c (ffffffff8133fa60)
Location: fs/ecryptfs/messaging.c:318
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8133fa60-ffffffff8133fc24: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/messaging.c (ffffffff813557f0)
Location: fs/ecryptfs/messaging.c:318
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff813557f0-ffffffff813559b4: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/messaging.c (ffffffff8136a3f0)
Location: fs/ecryptfs/messaging.c:318
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8136a3f0-ffffffff8136a5b6: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/messaging.c (ffffffff8138ef90)
Location: fs/ecryptfs/messaging.c:314
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8138ef90-ffffffff8138f156: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/messaging.c (0)
Location: fs/ecryptfs/messaging.c:314
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff813be3df-ffffffff813be417: ecryptfs_send_message.cold.8 (STB_LOCAL)
ffffffff813bdf60-ffffffff813be0f8: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/messaging.c (0)
Location: fs/ecryptfs/messaging.c:314
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff813d7a1f-ffffffff813d7a57: ecryptfs_send_message.cold.7 (STB_LOCAL)
ffffffff813d75a0-ffffffff813d7738: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/messaging.c (0)
Location: fs/ecryptfs/messaging.c:301
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8140237f-ffffffff814023b7: ecryptfs_send_message.cold (STB_LOCAL)
ffffffff81401ef0-ffffffff8140208a: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/messaging.c (0)
Location: fs/ecryptfs/messaging.c:301
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8141c26f-ffffffff8141c2a7: ecryptfs_send_message.cold (STB_LOCAL)
ffffffff8141bde0-ffffffff8141bf7a: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/messaging.c (ffffffff8146aa80)
Location: fs/ecryptfs/messaging.c:301
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8146aa80-ffffffff8146aacc: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/messaging.c (ffffffff814854f0)
Location: fs/ecryptfs/messaging.c:301
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff814854f0-ffffffff8148553c: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/messaging.c (0)
Location: fs/ecryptfs/messaging.c:303
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81be15af-ffffffff81be15e7: ecryptfs_send_message.cold (STB_LOCAL)
ffffffff8148ae10-ffffffff8148afac: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/messaging.c (0)
Location: fs/ecryptfs/messaging.c:303
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81cd1d8e-ffffffff81cd1dc6: ecryptfs_send_message.cold (STB_LOCAL)
ffffffff814e2650-ffffffff814e27ec: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/messaging.c (0)
Location: fs/ecryptfs/messaging.c:303
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81e84ebe-ffffffff81e84ef6: ecryptfs_send_message.cold (STB_LOCAL)
ffffffff815708f0-ffffffff81570aa2: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/messaging.c (ffffffff81615960)
Location: fs/ecryptfs/messaging.c:303
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81615960-ffffffff81615b47: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/messaging.c (ffffffff8164d9f0)
Location: fs/ecryptfs/messaging.c:303
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8164d9f0-ffffffff8164dbd7: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/messaging.c (ffffffff81686f50)
Location: fs/ecryptfs/messaging.c:303
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81686f50-ffffffff81687137: ecryptfs_send_message (STB_GLOBAL)
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
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/messaging.c (ffff8000104fd398)
Location: fs/ecryptfs/messaging.c:301
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffff8000104fd398-ffff8000104fd57c: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/messaging.c (c06ba99c)
Location: fs/ecryptfs/messaging.c:301
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
c06ba99c-c06bab80: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/messaging.c (c0000000006406c0)
Location: fs/ecryptfs/messaging.c:301
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
c0000000006406c0-c000000000640950: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/messaging.c (ffffffe00036ba3a)
Location: fs/ecryptfs/messaging.c:301
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffe00036ba3a-ffffffe00036bbcc: ecryptfs_send_message (STB_GLOBAL)
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
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/messaging.c (0)
Location: fs/ecryptfs/messaging.c:301
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8141484f-ffffffff81414887: ecryptfs_send_message.cold (STB_LOCAL)
ffffffff814143c0-ffffffff8141455a: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/messaging.c (0)
Location: fs/ecryptfs/messaging.c:301
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff814052cf-ffffffff81405307: ecryptfs_send_message.cold (STB_LOCAL)
ffffffff81404e40-ffffffff81404fda: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/messaging.c (0)
Location: fs/ecryptfs/messaging.c:301
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff81411bcf-ffffffff81411c07: ecryptfs_send_message.cold (STB_LOCAL)
ffffffff81411740-ffffffff814118da: ecryptfs_send_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_send_message(char *data, int data_len, struct ecryptfs_msg_ctx **msg_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/messaging.c (0)
Location: fs/ecryptfs/messaging.c:301
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:decrypt_pki_encrypted_session_key
```
**Symbols:**

```
ffffffff8142783f-ffffffff81427877: ecryptfs_send_message.cold (STB_LOCAL)
ffffffff814273b0-ffffffff8142754a: ecryptfs_send_message (STB_GLOBAL)
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
