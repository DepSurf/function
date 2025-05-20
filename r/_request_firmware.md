# Function: <code>_request_firmware</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, unsigned int opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8155f340)
Location: drivers/base/firmware_class.c:1118
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:request_firmware
  - drivers/base/firmware_class.c:request_firmware_direct
  - drivers/base/firmware_class.c:request_firmware_work_func
```
**Symbols:**

```
ffffffff8155f340-ffffffff8155fe31: _request_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, unsigned int opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815b3920)
Location: drivers/base/firmware_class.c:1133
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:request_firmware_work_func
  - drivers/base/firmware_class.c:request_firmware_into_buf
  - drivers/base/firmware_class.c:request_firmware_direct
  - drivers/base/firmware_class.c:request_firmware
```
**Symbols:**

```
ffffffff815b3920-ffffffff815b4451: _request_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, unsigned int opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815e2ca0)
Location: drivers/base/firmware_class.c:1168
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:request_firmware_work_func
  - drivers/base/firmware_class.c:request_firmware_into_buf
  - drivers/base/firmware_class.c:request_firmware_direct
  - drivers/base/firmware_class.c:request_firmware
```
**Symbols:**

```
ffffffff815e2ca0-ffffffff815e36f1: _request_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, unsigned int opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f7b30)
Location: drivers/base/firmware_class.c:1191
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:request_firmware_work_func
  - drivers/base/firmware_class.c:request_firmware_into_buf
  - drivers/base/firmware_class.c:request_firmware_direct
  - drivers/base/firmware_class.c:request_firmware
```
**Symbols:**

```
ffffffff815f7b30-ffffffff815f83d8: _request_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, unsigned int opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8165fad0)
Location: drivers/base/firmware_class.c:1198
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:request_firmware_work_func
  - drivers/base/firmware_class.c:request_firmware_into_buf
  - drivers/base/firmware_class.c:request_firmware_direct
  - drivers/base/firmware_class.c:request_firmware
```
**Symbols:**

```
ffffffff8165fad0-ffffffff816603d7: _request_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, enum fw_opt opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8169a7e0)
Location: drivers/base/firmware_loader/main.c:559
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
```
**Symbols:**

```
ffffffff8169a7e0-ffffffff8169ad62: _request_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, enum fw_opt opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816bb040)
Location: drivers/base/firmware_loader/main.c:567
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
```
**Symbols:**

```
ffffffff816bb040-ffffffff816bb5e8: _request_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, enum fw_opt opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:751
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
```
**Symbols:**

```
ffffffff816f58d0-ffffffff816f5cdd: _request_firmware (STB_LOCAL)
ffffffff816f6079-ffffffff816f60bc: _request_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, enum fw_opt opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:751
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
```
**Symbols:**

```
ffffffff81719cd0-ffffffff8171a0dd: _request_firmware (STB_LOCAL)
ffffffff8171a479-ffffffff8171a4bc: _request_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, u32 opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:755
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:cache_firmware
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
```
**Symbols:**

```
ffffffff817d5e60-ffffffff817d5fe0: _request_firmware (STB_LOCAL)
ffffffff817d6414-ffffffff817d6433: _request_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, size_t offset, u32 opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:790
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:cache_firmware
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
```
**Symbols:**

```
ffffffff817ea880-ffffffff817eaa12: _request_firmware (STB_LOCAL)
ffffffff81c0f1d6-ffffffff81c0f1f0: _request_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, size_t offset, u32 opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:794
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
```
**Symbols:**

```
ffffffff817cefd0-ffffffff817cf1a4: _request_firmware (STB_LOCAL)
ffffffff81c01347-ffffffff81c0136a: _request_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, size_t offset, u32 opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:793
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
```
**Symbols:**

```
ffffffff818596c0-ffffffff818599bd: _request_firmware (STB_LOCAL)
ffffffff81d042c3-ffffffff81d04300: _request_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, size_t offset, u32 opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:796
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
```
**Symbols:**

```
ffffffff819a01d0-ffffffff819a0589: _request_firmware (STB_LOCAL)
ffffffff81eccbf0-ffffffff81eccc64: _request_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, size_t offset, u32 opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b11d40)
Location: drivers/base/firmware_loader/main.c:796
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
```
**Symbols:**

```
ffffffff81b11d40-ffffffff81b12119: _request_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, size_t offset, u32 opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b60030)
Location: drivers/base/firmware_loader/main.c:849
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
```
**Symbols:**

```
ffffffff81b60030-ffffffff81b6040c: _request_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, size_t offset, u32 opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb3a40)
Location: drivers/base/firmware_loader/main.c:850
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
```
**Symbols:**

```
ffffffff81bb3a40-ffffffff81bb3e4c: _request_firmware (STB_LOCAL)
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
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, enum fw_opt opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090d438)
Location: drivers/base/firmware_loader/main.c:751
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
```
**Symbols:**

```
ffff80001090d438-ffff80001090d88c: _request_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, enum fw_opt opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f6444)
Location: drivers/base/firmware_loader/main.c:751
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
```
**Symbols:**

```
c09f6444-c09f68a4: _request_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, enum fw_opt opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009ad7c0)
Location: drivers/base/firmware_loader/main.c:751
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
```
**Symbols:**

```
c0000000009ad7c0-c0000000009adeb0: _request_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, enum fw_opt opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe000591ee8)
Location: drivers/base/firmware_loader/main.c:751
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
```
**Symbols:**

```
ffffffe000591ee8-ffffffe000592332: _request_firmware (STB_LOCAL)
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
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, enum fw_opt opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:751
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
```
**Symbols:**

```
ffffffff816e0000-ffffffff816e040d: _request_firmware (STB_LOCAL)
ffffffff816e07a9-ffffffff816e07ec: _request_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, enum fw_opt opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:751
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
```
**Symbols:**

```
ffffffff816ba640-ffffffff816baa4d: _request_firmware (STB_LOCAL)
ffffffff816bade9-ffffffff816bae2c: _request_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, enum fw_opt opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:751
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
```
**Symbols:**

```
ffffffff8170d560-ffffffff8170db20: _request_firmware (STB_LOCAL)
ffffffff8170de50-ffffffff8170deb5: _request_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int _request_firmware(const struct firmware **firmware_p, const char *name, struct device *device, void *buf, size_t size, enum fw_opt opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:751
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
```
**Symbols:**

```
ffffffff81728340-ffffffff81728742: _request_firmware (STB_LOCAL)
ffffffff81728ae9-ffffffff81728b2c: _request_firmware.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *buf</code>
</li>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param reordered. </b>
<code>firmware_p, name, device, opt_flags</code> ➡️ <code>firmware_p, name, device, buf, size, opt_flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int opt_flags</code> ➡️ <code>enum fw_opt opt_flags</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>size_t offset</code>
</li>
<li>
<b>Param reordered. </b>
<code>firmware_p, name, device, buf, size, opt_flags</code> ➡️ <code>firmware_p, name, device, buf, size, offset, opt_flags</code>
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
