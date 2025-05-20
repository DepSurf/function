# Function: <code>__do_sys_add_key</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff813e7118)
Location: security/keys/keyctl.c:62
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
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
In security/keys/keyctl.c (ffffffff81401918)
Location: security/keys/keyctl.c:62
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
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
In security/keys/keyctl.c (ffffffff8142e438)
Location: security/keys/keyctl.c:72
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
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
In security/keys/keyctl.c (ffffffff814481e8)
Location: security/keys/keyctl.c:72
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_add_key(const char *_type, const char *_description, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81499b20)
Location: security/keys/keyctl.c:74
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff81499b20-ffffffff81499d35: __do_sys_add_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_add_key(const char *_type, const char *_description, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814b75b0)
Location: security/keys/keyctl.c:74
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff814b75b0-ffffffff814b77c5: __do_sys_add_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_add_key(const char *_type, const char *_description, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814bd420)
Location: security/keys/keyctl.c:74
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff814bd420-ffffffff814bd635: __do_sys_add_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_add_key(const char *_type, const char *_description, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81515ea0)
Location: security/keys/keyctl.c:74
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff81515ea0-ffffffff815160b5: __do_sys_add_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_add_key(const char *_type, const char *_description, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff815a8700)
Location: security/keys/keyctl.c:74
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff815a8700-ffffffff815a893e: __do_sys_add_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_add_key(const char *_type, const char *_description, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816525d0)
Location: security/keys/keyctl.c:74
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff816525d0-ffffffff8165280e: __do_sys_add_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_add_key(const char *_type, const char *_description, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8168adf0)
Location: security/keys/keyctl.c:74
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff8168adf0-ffffffff8168b02e: __do_sys_add_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_add_key(const char *_type, const char *_description, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816c72f0)
Location: security/keys/keyctl.c:74
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
**Symbols:**

```
ffffffff816c72f0-ffffffff816c752e: __do_sys_add_key (STB_LOCAL)
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
In security/keys/keyctl.c (ffff800010531da4)
Location: security/keys/keyctl.c:72
Inline: True
Inline callers:
  - security/keys/keyctl.c:__arm64_sys_add_key
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
In security/keys/keyctl.c (c06e97e0)
Location: security/keys/keyctl.c:72
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_add_key
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
In security/keys/keyctl.c (c00000000067f484)
Location: security/keys/keyctl.c:72
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_add_key
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
In security/keys/keyctl.c (ffffffe000392962)
Location: security/keys/keyctl.c:72
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_add_key
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
In security/keys/keyctl.c (ffffffff814407c8)
Location: security/keys/keyctl.c:72
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
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
In security/keys/keyctl.c (ffffffff81431238)
Location: security/keys/keyctl.c:72
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
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
In security/keys/keyctl.c (ffffffff8143c968)
Location: security/keys/keyctl.c:72
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
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
In security/keys/keyctl.c (ffffffff81453af8)
Location: security/keys/keyctl.c:72
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
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
