# Function: <code>ima_measure_critical_data</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ima_measure_critical_data(const char *event_label, const char *event_name, const void *buf, size_t buf_len, bool hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8153be40)
Location: security/integrity/ima/ima_main.c:976
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/integrity/ima/ima_init.c:ima_init
```
**Symbols:**

```
ffffffff8153be40-ffffffff8153be84: ima_measure_critical_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ima_measure_critical_data(const char *event_label, const char *event_name, const void *buf, size_t buf_len, bool hash, u8 *digest, size_t digest_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8159a9c0)
Location: security/integrity/ima/ima_main.c:1014
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/md/dm-ima.c:dm_ima_measure_data
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
**Symbols:**

```
ffffffff8159a9c0-ffffffff8159aa0e: ima_measure_critical_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_measure_critical_data(const char *event_label, const char *event_name, const void *buf, size_t buf_len, bool hash, u8 *digest, size_t digest_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8163f740)
Location: security/integrity/ima/ima_main.c:1034
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/md/dm-ima.c:dm_ima_measure_data
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
**Symbols:**

```
ffffffff8163f740-ffffffff8163f7b2: ima_measure_critical_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_measure_critical_data(const char *event_label, const char *event_name, const void *buf, size_t buf_len, bool hash, u8 *digest, size_t digest_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff816f74d0)
Location: security/integrity/ima/ima_main.c:1044
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/md/dm-ima.c:dm_ima_measure_data
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
**Symbols:**

```
ffffffff816f74d0-ffffffff816f7542: ima_measure_critical_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_measure_critical_data(const char *event_label, const char *event_name, const void *buf, size_t buf_len, bool hash, u8 *digest, size_t digest_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81731750)
Location: security/integrity/ima/ima_main.c:1063
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/md/dm-ima.c:dm_ima_measure_data
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
**Symbols:**

```
ffffffff81731750-ffffffff817317c2: ima_measure_critical_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_measure_critical_data(const char *event_label, const char *event_name, const void *buf, size_t buf_len, bool hash, u8 *digest, size_t digest_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81772170)
Location: security/integrity/ima/ima_main.c:1077
Inline: False
Direct callers:
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/selinux/ima.c:selinux_ima_measure_state_locked
  - security/integrity/ima/ima_init.c:ima_init
  - drivers/md/dm-ima.c:dm_ima_measure_data
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
**Symbols:**

```
ffffffff81772170-ffffffff817721e2: ima_measure_critical_data (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
