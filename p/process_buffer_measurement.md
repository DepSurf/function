# Function: <code>process_buffer_measurement</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8149b9c0)
Location: security/integrity/ima/ima_main.c:618
Inline: True
Direct callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
```
**Symbols:**

```
ffffffff8149b9c0-ffffffff8149bb38: process_buffer_measurement.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void process_buffer_measurement(const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:638
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff814b6e71-ffffffff814b6e9a: process_buffer_measurement.cold (STB_LOCAL)
ffffffff814b6be0-ffffffff814b6def: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void process_buffer_measurement(const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr, const char *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:738
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff81516674-ffffffff8151669d: process_buffer_measurement.cold (STB_LOCAL)
ffffffff815163c0-ffffffff815165e6: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void process_buffer_measurement(struct inode *inode, const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr, const char *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81533530)
Location: security/integrity/ima/ima_main.c:823
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff81533530-ffffffff815337a9: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void process_buffer_measurement(struct user_namespace *mnt_userns, struct inode *inode, const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr, const char *func_data, bool buf_hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:839
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_measure_critical_data
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff81be3c1a-ffffffff81be3c26: process_buffer_measurement.cold (STB_LOCAL)
ffffffff8153ba70-ffffffff8153bda4: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int process_buffer_measurement(struct user_namespace *mnt_userns, struct inode *inode, const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr, const char *func_data, bool buf_hash, u8 *digest, size_t digest_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:862
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_measure_critical_data
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff81cd6e6f-ffffffff81cd6e7b: process_buffer_measurement.cold (STB_LOCAL)
ffffffff8159a500-ffffffff8159a9bb: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int process_buffer_measurement(struct user_namespace *mnt_userns, struct inode *inode, const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr, const char *func_data, bool buf_hash, u8 *digest, size_t digest_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:885
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_measure_critical_data
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff81e8a097-ffffffff81e8a0a3: process_buffer_measurement.cold (STB_LOCAL)
ffffffff8163f250-ffffffff8163f737: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int process_buffer_measurement(struct user_namespace *mnt_userns, struct inode *inode, const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr, const char *func_data, bool buf_hash, u8 *digest, size_t digest_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff816f6fc0)
Location: security/integrity/ima/ima_main.c:895
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_measure_critical_data
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff816f6fc0-ffffffff816f74b3: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int process_buffer_measurement(struct mnt_idmap *idmap, struct inode *inode, const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr, const char *func_data, bool buf_hash, u8 *digest, size_t digest_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81731240)
Location: security/integrity/ima/ima_main.c:914
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_measure_critical_data
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff81731240-ffffffff81731733: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int process_buffer_measurement(struct mnt_idmap *idmap, struct inode *inode, const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr, const char *func_data, bool buf_hash, u8 *digest, size_t digest_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81771ca0)
Location: security/integrity/ima/ima_main.c:928
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_measure_critical_data
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
  - security/integrity/ima/ima_asymmetric_keys.c:ima_post_key_create_or_update
```
**Symbols:**

```
ffffffff81771ca0-ffffffff8177215b: process_buffer_measurement (STB_GLOBAL)
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
void process_buffer_measurement(const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffff8000105aef20)
Location: security/integrity/ima/ima_main.c:638
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffff8000105aef20-ffff8000105af114: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void process_buffer_measurement(const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (c075e61c)
Location: security/integrity/ima/ima_main.c:638
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
c075e61c-c075e83c: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void process_buffer_measurement(const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (c00000000072e130)
Location: security/integrity/ima/ima_main.c:638
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
c00000000072e130-c00000000072e3a8: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void process_buffer_measurement(const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffe0003f6eb6)
Location: security/integrity/ima/ima_main.c:638
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffe0003f6eb6-ffffffe0003f709c: process_buffer_measurement (STB_GLOBAL)
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
void process_buffer_measurement(const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:638
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff814af451-ffffffff814af47a: process_buffer_measurement.cold (STB_LOCAL)
ffffffff814af1c0-ffffffff814af3cf: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void process_buffer_measurement(const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:638
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff8149fe71-ffffffff8149fe9a: process_buffer_measurement.cold (STB_LOCAL)
ffffffff8149fbe0-ffffffff8149fdef: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void process_buffer_measurement(const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:638
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff814ab4e1-ffffffff814ab50a: process_buffer_measurement.cold (STB_LOCAL)
ffffffff814ab250-ffffffff814ab45f: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void process_buffer_measurement(const void *buf, int size, const char *eventname, enum ima_hooks func, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: security/integrity/ima/ima_main.c:638
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_appraise.c:ima_check_blacklist
```
**Symbols:**

```
ffffffff814c3f31-ffffffff814c3f5a: process_buffer_measurement.cold (STB_LOCAL)
ffffffff814c3ca0-ffffffff814c3eaf: process_buffer_measurement (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *keyring</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>buf, size, eventname, func, pcr, keyring</code> ➡️ <code>inode, buf, size, eventname, func, pcr, keyring</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param added. </b>
<code>const char *func_data</code>
</li>
<li>
<b>Param added. </b>
<code>bool buf_hash</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *keyring</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, buf, size, eventname, func, pcr, keyring</code> ➡️ <code>mnt_userns, inode, buf, size, eventname, func, pcr, func_data, buf_hash</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *digest</code>
</li>
<li>
<b>Param added. </b>
<code>size_t digest_len</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
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
