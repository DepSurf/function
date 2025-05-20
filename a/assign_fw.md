# Function: <code>assign_fw</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device, enum fw_opt opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8169a670)
Location: drivers/base/firmware_loader/main.c:445
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff8169a670-ffffffff8169a7d3: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device, enum fw_opt opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816baed0)
Location: drivers/base/firmware_loader/main.c:451
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff816baed0-ffffffff816bb033: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device, enum fw_opt opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f5770)
Location: drivers/base/firmware_loader/main.c:635
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff816f5770-ffffffff816f58cf: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device, enum fw_opt opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81719b70)
Location: drivers/base/firmware_loader/main.c:635
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff81719b70-ffffffff81719ccf: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device, u32 opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d5d20)
Location: drivers/base/firmware_loader/main.c:640
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
```
**Symbols:**

```
ffffffff817d5d20-ffffffff817d5e5a: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ea730)
Location: drivers/base/firmware_loader/main.c:675
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
```
**Symbols:**

```
ffffffff817ea730-ffffffff817ea875: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817cedd0)
Location: drivers/base/firmware_loader/main.c:677
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
```
**Symbols:**

```
ffffffff817cedd0-ffffffff817cefce: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff818594e0)
Location: drivers/base/firmware_loader/main.c:678
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
```
**Symbols:**

```
ffffffff818594e0-ffffffff818596ba: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff819a0010)
Location: drivers/base/firmware_loader/main.c:681
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff819a0010-ffffffff819a01c1: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b11b70)
Location: drivers/base/firmware_loader/main.c:681
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff81b11b70-ffffffff81b11d21: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5fe60)
Location: drivers/base/firmware_loader/main.c:690
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff81b5fe60-ffffffff81b60011: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb3870)
Location: drivers/base/firmware_loader/main.c:691
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff81bb3870-ffffffff81bb3a21: assign_fw (STB_GLOBAL)
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
int assign_fw(struct firmware *fw, struct device *device, enum fw_opt opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090d270)
Location: drivers/base/firmware_loader/main.c:635
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffff80001090d270-ffff80001090d438: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device, enum fw_opt opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f62d4)
Location: drivers/base/firmware_loader/main.c:635
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
c09f62d4-c09f6444: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device, enum fw_opt opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009ad5a0)
Location: drivers/base/firmware_loader/main.c:635
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
```
**Symbols:**

```
c0000000009ad5a0-c0000000009ad7b4: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device, enum fw_opt opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe000591e6e)
Location: drivers/base/firmware_loader/main.c:635
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffe000591e6e-ffffffe000591ee8: assign_fw (STB_GLOBAL)
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
int assign_fw(struct firmware *fw, struct device *device, enum fw_opt opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816dfea0)
Location: drivers/base/firmware_loader/main.c:635
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff816dfea0-ffffffff816dffff: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device, enum fw_opt opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816ba4e0)
Location: drivers/base/firmware_loader/main.c:635
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff816ba4e0-ffffffff816ba63f: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device, enum fw_opt opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170d400)
Location: drivers/base/firmware_loader/main.c:635
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff8170d400-ffffffff8170d55f: assign_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int assign_fw(struct firmware *fw, struct device *device, enum fw_opt opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817281d0)
Location: drivers/base/firmware_loader/main.c:635
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff817281d0-ffffffff81728336: assign_fw (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 opt_flags</code>
</li>
</ul>
</details>
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
