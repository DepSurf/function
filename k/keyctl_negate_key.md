# Function: <code>keyctl_negate_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff813330f0)
Location: security/keys/keyctl.c:1151
Inline: True
Inline callers:
  - security/keys/keyctl.c:SyS_keyctl
Direct callers:
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff813330f0-ffffffff81333107: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81368525)
Location: security/keys/keyctl.c:1179
Inline: True
Inline callers:
  - security/keys/keyctl.c:SyS_keyctl
Direct callers:
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff81367f50-ffffffff81367f67: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8137ed35)
Location: security/keys/keyctl.c:1179
Inline: True
Inline callers:
  - security/keys/keyctl.c:SyS_keyctl
Direct callers:
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff8137e760-ffffffff8137e777: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81392cad)
Location: security/keys/keyctl.c:1182
Inline: True
Inline callers:
  - security/keys/keyctl.c:SyS_keyctl
Direct callers:
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff81392600-ffffffff81392617: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff813b8303)
Location: security/keys/keyctl.c:1186
Inline: True
Inline callers:
  - security/keys/keyctl.c:SyS_keyctl
Direct callers:
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff813b7c50-ffffffff813b7c67: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff813e8f2a)
Location: security/keys/keyctl.c:1186
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff813e87f0-ffffffff813e8807: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8140380e)
Location: security/keys/keyctl.c:1186
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81402ff0-ffffffff81403007: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814304d1)
Location: security/keys/keyctl.c:1242
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8142fc40-ffffffff8142fc57: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8144a231)
Location: security/keys/keyctl.c:1242
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814499a0-ffffffff814499b7: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8149bec0)
Location: security/keys/keyctl.c:1310
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8149b2d0-ffffffff8149b2e7: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814b9960)
Location: security/keys/keyctl.c:1310
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814b8d60-ffffffff814b8d77: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814bf7cf)
Location: security/keys/keyctl.c:1310
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814bebb0-ffffffff814bebc7: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff815181ef)
Location: security/keys/keyctl.c:1310
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff815175d0-ffffffff815175e7: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff815aad4f)
Location: security/keys/keyctl.c:1310
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff815a9fe0-ffffffff815aa003: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816550cf)
Location: security/keys/keyctl.c:1310
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81654290-ffffffff816542b3: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8168d94e)
Location: security/keys/keyctl.c:1315
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8168cad0-ffffffff8168caf3: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816c9e9e)
Location: security/keys/keyctl.c:1314
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff816c8fc0-ffffffff816c8fe3: keyctl_negate_key (STB_GLOBAL)
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
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffff800010533f14)
Location: security/keys/keyctl.c:1242
Inline: True
Inline callers:
  - security/keys/keyctl.c:__arm64_sys_keyctl
Direct callers:
  - security/keys/compat.c:__arm64_compat_sys_keyctl
```
**Symbols:**

```
ffff800010533668-ffff8000105336b0: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (c06eb770)
Location: security/keys/keyctl.c:1242
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
c06eaeb8-c06eaedc: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (c000000000681f40)
Location: security/keys/keyctl.c:1242
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_keyctl
Direct callers:
  - security/keys/compat.c:__se_compat_sys_keyctl
```
**Symbols:**

```
c0000000006813b0-c0000000006813cc: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffe000394256)
Location: security/keys/keyctl.c:1242
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
ffffffe000393b90-ffffffe000393bce: keyctl_negate_key (STB_GLOBAL)
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
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81442811)
Location: security/keys/keyctl.c:1242
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81441f80-ffffffff81441f97: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81433261)
Location: security/keys/keyctl.c:1242
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814329f0-ffffffff81432a07: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8143e9b1)
Location: security/keys/keyctl.c:1242
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8143e120-ffffffff8143e137: keyctl_negate_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int keyctl_negate_key(key_serial_t id, unsigned int timeout, key_serial_t ringid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81455b61)
Location: security/keys/keyctl.c:1242
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814552a0-ffffffff814552b7: keyctl_negate_key (STB_GLOBAL)
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
