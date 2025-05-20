# Function: <code>keyctl_restrict_keyring</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81392b40)
Location: security/keys/keyctl.c:1595
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff81392b40-ffffffff81392c29: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff813b81a0)
Location: security/keys/keyctl.c:1596
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff813b81a0-ffffffff813b827c: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff813e8d80)
Location: security/keys/keyctl.c:1596
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff813e8d80-ffffffff813e8e66: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81403580)
Location: security/keys/keyctl.c:1596
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81403580-ffffffff81403666: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814301b0)
Location: security/keys/keyctl.c:1653
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814301b0-ffffffff8143028a: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81449f10)
Location: security/keys/keyctl.c:1653
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81449f10-ffffffff81449fea: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8149b910)
Location: security/keys/keyctl.c:1724
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8149b910-ffffffff8149ba17: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814b93b0)
Location: security/keys/keyctl.c:1724
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814b93b0-ffffffff814b94b7: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814bf200)
Location: security/keys/keyctl.c:1724
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814bf200-ffffffff814bf307: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81517c20)
Location: security/keys/keyctl.c:1724
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81517c20-ffffffff81517d27: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff815aa6a0)
Location: security/keys/keyctl.c:1724
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff815aa6a0-ffffffff815aa7de: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816549b0)
Location: security/keys/keyctl.c:1724
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff816549b0-ffffffff81654aee: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8168d1f0)
Location: security/keys/keyctl.c:1729
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8168d1f0-ffffffff8168d32e: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816c96e0)
Location: security/keys/keyctl.c:1728
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff816c96e0-ffffffff816c981e: keyctl_restrict_keyring (STB_GLOBAL)
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
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffff800010533d10)
Location: security/keys/keyctl.c:1653
Inline: False
Direct callers:
  - security/keys/keyctl.c:__arm64_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
```
**Symbols:**

```
ffff800010533d10-ffff800010533e08: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (c06eb4fc)
Location: security/keys/keyctl.c:1653
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
c06eb4fc-c06eb5f0: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (c000000000681bd0)
Location: security/keys/keyctl.c:1653
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
```
**Symbols:**

```
c000000000681bd0-c000000000681d0c: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffe000394040)
Location: security/keys/keyctl.c:1653
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
ffffffe000394040-ffffffe0003940f4: keyctl_restrict_keyring (STB_GLOBAL)
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
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814424f0)
Location: security/keys/keyctl.c:1653
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814424f0-ffffffff814425ca: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81432f40)
Location: security/keys/keyctl.c:1653
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81432f40-ffffffff8143301a: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8143e690)
Location: security/keys/keyctl.c:1653
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8143e690-ffffffff8143e76a: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int keyctl_restrict_keyring(key_serial_t id, const char *_type, const char *_restriction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81455840)
Location: security/keys/keyctl.c:1653
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81455840-ffffffff8145591a: keyctl_restrict_keyring (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
