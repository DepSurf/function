# Function: <code>integrity_audit_message</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void integrity_audit_message(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff81531070)
Location: security/integrity/integrity_audit.c:36
Inline: False
Direct callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_queue_keys.c:ima_alloc_key_entry
  - security/integrity/ima/ima_queue_keys.c:ima_alloc_key_entry
```
**Symbols:**

```
ffffffff81531070-ffffffff8153121b: integrity_audit_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void integrity_audit_message(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff815394a0)
Location: security/integrity/integrity_audit.c:36
Inline: False
Direct callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
```
**Symbols:**

```
ffffffff815394a0-ffffffff81539645: integrity_audit_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void integrity_audit_message(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff81597ce0)
Location: security/integrity/integrity_audit.c:36
Inline: False
Direct callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
```
**Symbols:**

```
ffffffff81597ce0-ffffffff81597e89: integrity_audit_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void integrity_audit_message(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff8163c4c0)
Location: security/integrity/integrity_audit.c:36
Inline: False
Direct callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
```
**Symbols:**

```
ffffffff8163c4c0-ffffffff8163c688: integrity_audit_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void integrity_audit_message(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff816f3d10)
Location: security/integrity/integrity_audit.c:36
Inline: False
Direct callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
```
**Symbols:**

```
ffffffff816f3d10-ffffffff816f3ed8: integrity_audit_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void integrity_audit_message(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff8172de40)
Location: security/integrity/integrity_audit.c:36
Inline: False
Direct callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
```
**Symbols:**

```
ffffffff8172de40-ffffffff8172e008: integrity_audit_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void integrity_audit_message(int audit_msgno, struct inode *inode, const unsigned char *fname, const char *op, const char *cause, int result, int audit_info, int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/integrity_audit.c (ffffffff8176e7a0)
Location: security/integrity/integrity_audit.c:36
Inline: False
Direct callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
```
**Symbols:**

```
ffffffff8176e7a0-ffffffff8176e968: integrity_audit_message (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
