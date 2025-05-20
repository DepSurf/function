# Function: <code>fw_get_filesystem_firmware</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8155f659)
Location: drivers/base/firmware_class.c:325
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815b3bce)
Location: drivers/base/firmware_class.c:318
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815e2e6c)
Location: drivers/base/firmware_class.c:386
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f7dc3)
Location: drivers/base/firmware_class.c:382
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8165fd94)
Location: drivers/base/firmware_class.c:386
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8169aa39)
Location: drivers/base/firmware_loader/main.c:290
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff816bb23e)
Location: drivers/base/firmware_loader/main.c:296
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:457
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff816f4ac0-ffffffff816f4d2d: fw_get_filesystem_firmware (STB_LOCAL)
ffffffff816f6010-ffffffff816f6029: fw_get_filesystem_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:457
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81718ec0-ffffffff8171912d: fw_get_filesystem_firmware (STB_LOCAL)
ffffffff8171a410-ffffffff8171a429: fw_get_filesystem_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:462
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff817d4940-ffffffff817d4bca: fw_get_filesystem_firmware (STB_LOCAL)
ffffffff817d638a-ffffffff817d63a3: fw_get_filesystem_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:483
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff817e9300-ffffffff817e9594: fw_get_filesystem_firmware (STB_LOCAL)
ffffffff81c0f14b-ffffffff81c0f165: fw_get_filesystem_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:484
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff817cdad0-ffffffff817cdd93: fw_get_filesystem_firmware (STB_LOCAL)
ffffffff81c012bb-ffffffff81c012d5: fw_get_filesystem_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:485
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff818582c0-ffffffff818585ea: fw_get_filesystem_firmware (STB_LOCAL)
ffffffff81d04225-ffffffff81d0423f: fw_get_filesystem_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:488
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff8199ecc0-ffffffff8199f001: fw_get_filesystem_firmware (STB_LOCAL)
ffffffff81eccb5b-ffffffff81eccb76: fw_get_filesystem_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b106d0)
Location: drivers/base/firmware_loader/main.c:488
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81b106d0-ffffffff81b10a17: fw_get_filesystem_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5e8f0)
Location: drivers/base/firmware_loader/main.c:488
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81b5e8f0-ffffffff81b5eca7: fw_get_filesystem_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb2260)
Location: drivers/base/firmware_loader/main.c:489
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81bb2260-ffffffff81bb2617: fw_get_filesystem_firmware (STB_LOCAL)
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
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090c2d0)
Location: drivers/base/firmware_loader/main.c:457
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffff80001090c2d0-ffff80001090c564: fw_get_filesystem_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f57dc)
Location: drivers/base/firmware_loader/main.c:457
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
c09f57dc-c09f5aa8: fw_get_filesystem_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009ac100)
Location: drivers/base/firmware_loader/main.c:457
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
c0000000009ac100-c0000000009ac484: fw_get_filesystem_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe00059162e)
Location: drivers/base/firmware_loader/main.c:457
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffe00059162e-ffffffe000591864: fw_get_filesystem_firmware (STB_LOCAL)
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
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:457
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff816df1f0-ffffffff816df45d: fw_get_filesystem_firmware (STB_LOCAL)
ffffffff816e0740-ffffffff816e0759: fw_get_filesystem_firmware.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:457
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff816b9830-ffffffff816b9a9d: fw_get_filesystem_firmware (STB_LOCAL)
ffffffff816bad80-ffffffff816bad99: fw_get_filesystem_firmware.cold (STB_LOCAL)
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
In drivers/base/firmware_loader/main.c (ffffffff8170d77a)
Location: drivers/base/firmware_loader/main.c:457
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fw_get_filesystem_firmware(struct device *device, struct fw_priv *fw_priv, const char *suffix, int (*decompress)(struct device *, struct fw_priv *, size_t, const void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:457
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81727680-ffffffff817278ed: fw_get_filesystem_firmware (STB_LOCAL)
ffffffff81728a80-ffffffff81728a99: fw_get_filesystem_firmware.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
