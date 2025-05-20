# Function: <code>__do_sys_request_key</code>

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
In security/keys/keyctl.c (ffffffff813e6f74)
Location: security/keys/keyctl.c:158
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
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
In security/keys/keyctl.c (ffffffff81401774)
Location: security/keys/keyctl.c:158
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
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
In security/keys/keyctl.c (ffffffff8142e294)
Location: security/keys/keyctl.c:168
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
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
In security/keys/keyctl.c (ffffffff81448044)
Location: security/keys/keyctl.c:168
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_request_key(const char *_type, const char *_description, const char *_callout_info, key_serial_t destringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81499920)
Location: security/keys/keyctl.c:167
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff81499920-ffffffff81499adc: __do_sys_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_request_key(const char *_type, const char *_description, const char *_callout_info, key_serial_t destringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814b73b0)
Location: security/keys/keyctl.c:167
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff814b73b0-ffffffff814b756c: __do_sys_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_request_key(const char *_type, const char *_description, const char *_callout_info, key_serial_t destringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814bd210)
Location: security/keys/keyctl.c:167
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff814bd210-ffffffff814bd3cc: __do_sys_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_request_key(const char *_type, const char *_description, const char *_callout_info, key_serial_t destringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81515c90)
Location: security/keys/keyctl.c:167
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff81515c90-ffffffff81515e4c: __do_sys_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_request_key(const char *_type, const char *_description, const char *_callout_info, key_serial_t destringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff815a84a0)
Location: security/keys/keyctl.c:167
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff815a84a0-ffffffff815a8691: __do_sys_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_request_key(const char *_type, const char *_description, const char *_callout_info, key_serial_t destringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816528c0)
Location: security/keys/keyctl.c:167
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff816528c0-ffffffff81652ab1: __do_sys_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_request_key(const char *_type, const char *_description, const char *_callout_info, key_serial_t destringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8168b0e0)
Location: security/keys/keyctl.c:167
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff8168b0e0-ffffffff8168b2d1: __do_sys_request_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_request_key(const char *_type, const char *_description, const char *_callout_info, key_serial_t destringid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816c75e0)
Location: security/keys/keyctl.c:167
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
```
**Symbols:**

```
ffffffff816c75e0-ffffffff816c77d1: __do_sys_request_key (STB_LOCAL)
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
In security/keys/keyctl.c (ffff800010531a64)
Location: security/keys/keyctl.c:168
Inline: True
Inline callers:
  - security/keys/keyctl.c:__arm64_sys_request_key
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
In security/keys/keyctl.c (c06e9a30)
Location: security/keys/keyctl.c:168
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_request_key
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
In security/keys/keyctl.c (c00000000067f268)
Location: security/keys/keyctl.c:168
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_request_key
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
In security/keys/keyctl.c (ffffffe000392ae4)
Location: security/keys/keyctl.c:168
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_request_key
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
In security/keys/keyctl.c (ffffffff81440624)
Location: security/keys/keyctl.c:168
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
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
In security/keys/keyctl.c (ffffffff81431094)
Location: security/keys/keyctl.c:168
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
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
In security/keys/keyctl.c (ffffffff8143c7c4)
Location: security/keys/keyctl.c:168
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
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
In security/keys/keyctl.c (ffffffff81453954)
Location: security/keys/keyctl.c:168
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
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
