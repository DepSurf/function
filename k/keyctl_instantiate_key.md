# Function: <code>keyctl_instantiate_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81332eb0)
Location: security/keys/keyctl.c:1085
Inline: True
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff81332eb0-ffffffff81332f31: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81367d00)
Location: security/keys/keyctl.c:1113
Inline: True
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff81367d00-ffffffff81367d81: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8137e510)
Location: security/keys/keyctl.c:1113
Inline: True
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff8137e510-ffffffff8137e591: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81392390)
Location: security/keys/keyctl.c:1116
Inline: True
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff81392390-ffffffff81392411: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff813b79e0)
Location: security/keys/keyctl.c:1120
Inline: True
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff813b79e0-ffffffff813b7a61: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff813e85b0)
Location: security/keys/keyctl.c:1120
Inline: True
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff813e85b0-ffffffff813e8631: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81402db0)
Location: security/keys/keyctl.c:1120
Inline: True
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81402db0-ffffffff81402e31: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8142fa00)
Location: security/keys/keyctl.c:1176
Inline: True
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8142fa00-ffffffff8142fa86: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81449760)
Location: security/keys/keyctl.c:1176
Inline: True
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81449760-ffffffff814497e6: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8149b060)
Location: security/keys/keyctl.c:1244
Inline: True
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8149b060-ffffffff8149b0e6: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814b8af0)
Location: security/keys/keyctl.c:1244
Inline: True
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814b8af0-ffffffff814b8b76: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814be940)
Location: security/keys/keyctl.c:1244
Inline: True
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814be940-ffffffff814be9c6: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81517360)
Location: security/keys/keyctl.c:1244
Inline: True
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81517360-ffffffff815173e6: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff815a9ce0)
Location: security/keys/keyctl.c:1244
Inline: True
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff815a9ce0-ffffffff815a9da8: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81653f60)
Location: security/keys/keyctl.c:1244
Inline: True
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81653f60-ffffffff81654028: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8168c7a0)
Location: security/keys/keyctl.c:1249
Inline: True
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8168c7a0-ffffffff8168c868: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816c8ca0)
Location: security/keys/keyctl.c:1249
Inline: True
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff816c8ca0-ffffffff816c8d51: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffff8000105333c8)
Location: security/keys/keyctl.c:1176
Inline: True
Direct callers:
  - security/keys/keyctl.c:__arm64_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
```
**Symbols:**

```
ffff8000105333c8-ffff800010533484: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (c06eac3c)
Location: security/keys/keyctl.c:1176
Inline: True
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
c06eac3c-c06eace8: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (c000000000681070)
Location: security/keys/keyctl.c:1176
Inline: True
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
```
**Symbols:**

```
c000000000681070-c000000000681140: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffe0003939ca)
Location: security/keys/keyctl.c:1176
Inline: True
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
ffffffe0003939ca-ffffffe000393a48: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81441d40)
Location: security/keys/keyctl.c:1176
Inline: True
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81441d40-ffffffff81441dc6: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814327b0)
Location: security/keys/keyctl.c:1176
Inline: True
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814327b0-ffffffff81432836: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8143dee0)
Location: security/keys/keyctl.c:1176
Inline: True
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8143dee0-ffffffff8143df66: keyctl_instantiate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_instantiate_key(key_serial_t id, const void *_payload, size_t plen, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81455060)
Location: security/keys/keyctl.c:1176
Inline: True
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81455060-ffffffff814550e6: keyctl_instantiate_key (STB_GLOBAL)
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
