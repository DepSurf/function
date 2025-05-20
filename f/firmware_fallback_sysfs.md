# Function: <code>firmware_fallback_sysfs</code>

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
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, enum fw_opt opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:685
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff8169be34-ffffffff8169be54: firmware_fallback_sysfs.cold.9 (STB_LOCAL)
ffffffff8169b9f0-ffffffff8169be34: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, enum fw_opt opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:687
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff816bc6c5-ffffffff816bc6e8: firmware_fallback_sysfs.cold.9 (STB_LOCAL)
ffffffff816bc270-ffffffff816bc6c5: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, enum fw_opt opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:640
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff816f6d1d-ffffffff816f6d96: firmware_fallback_sysfs.cold (STB_LOCAL)
ffffffff816f68d0-ffffffff816f6caa: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, enum fw_opt opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:640
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff8171b12f-ffffffff8171b1ab: firmware_fallback_sysfs.cold (STB_LOCAL)
ffffffff8171acd0-ffffffff8171b0bc: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, u32 opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:644
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff817d7146-ffffffff817d7177: firmware_fallback_sysfs.cold (STB_LOCAL)
ffffffff817d6ff0-ffffffff817d709d: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, u32 opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:643
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81c0f299-ffffffff81c0f2ca: firmware_fallback_sysfs.cold (STB_LOCAL)
ffffffff817eba20-ffffffff817ebad2: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, u32 opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:645
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81c013f2-ffffffff81c01423: firmware_fallback_sysfs.cold (STB_LOCAL)
ffffffff817d0200-ffffffff817d02b2: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, u32 opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:645
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81d043cd-ffffffff81d04413: firmware_fallback_sysfs.cold (STB_LOCAL)
ffffffff8185aa30-ffffffff8185aaee: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, u32 opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:220
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81eccca9-ffffffff81eccd08: firmware_fallback_sysfs.cold (STB_LOCAL)
ffffffff819a0d70-ffffffff819a0efa: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, u32 opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:220
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff82098b91-ffffffff82098ba6: firmware_fallback_sysfs.cold (STB_LOCAL)
ffffffff81b12a10-ffffffff81b12be9: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, u32 opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:220
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff82119b48-ffffffff82119b5d: firmware_fallback_sysfs.cold (STB_LOCAL)
ffffffff81b60d00-ffffffff81b60ed9: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, u32 opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:224
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff821f7a35-ffffffff821f7a4a: firmware_fallback_sysfs.cold (STB_LOCAL)
ffffffff81bb4790-ffffffff81bb4969: firmware_fallback_sysfs (STB_GLOBAL)
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
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, enum fw_opt opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffff80001090e5a0)
Location: drivers/base/firmware_loader/fallback.c:640
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffff80001090e5a0-ffff80001090e9dc: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, enum fw_opt opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (c09f740c)
Location: drivers/base/firmware_loader/fallback.c:640
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
c09f740c-c09f784c: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, enum fw_opt opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (c0000000009af4b0)
Location: drivers/base/firmware_loader/fallback.c:640
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
c0000000009af4b0-c0000000009af688: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, enum fw_opt opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffe000592c2c)
Location: drivers/base/firmware_loader/fallback.c:640
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffe000592c2c-ffffffe000593042: firmware_fallback_sysfs (STB_GLOBAL)
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
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, enum fw_opt opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:640
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff816e145f-ffffffff816e14db: firmware_fallback_sysfs.cold (STB_LOCAL)
ffffffff816e1000-ffffffff816e13ec: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, enum fw_opt opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:640
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff816bba9f-ffffffff816bbb1b: firmware_fallback_sysfs.cold (STB_LOCAL)
ffffffff816bb640-ffffffff816bba2c: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, enum fw_opt opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:640
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff8170eb2f-ffffffff8170ebab: firmware_fallback_sysfs.cold (STB_LOCAL)
ffffffff8170e6d0-ffffffff8170eabc: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int firmware_fallback_sysfs(struct firmware *fw, const char *name, struct device *device, enum fw_opt opt_flags, int ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:640
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff8172974f-ffffffff817297cb: firmware_fallback_sysfs.cold (STB_LOCAL)
ffffffff817292f0-ffffffff817296dc: firmware_fallback_sysfs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum fw_opt opt_flags</code> ➡️ <code>u32 opt_flags</code>
</li>
</ul>
</details>
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
