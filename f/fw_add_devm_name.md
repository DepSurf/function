# Function: <code>fw_add_devm_name</code>

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
In drivers/base/firmware_class.c (ffffffff8155fb84)
Location: drivers/base/firmware_class.c:432
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
In drivers/base/firmware_class.c (ffffffff815b41fb)
Location: drivers/base/firmware_class.c:428
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
In drivers/base/firmware_class.c (ffffffff815e34a8)
Location: drivers/base/firmware_class.c:496
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
In drivers/base/firmware_class.c (ffffffff815f7a33)
Location: drivers/base/firmware_class.c:492
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:assign_firmware_buf
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
In drivers/base/firmware_class.c (ffffffff8165f9c9)
Location: drivers/base/firmware_class.c:496
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:assign_firmware_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81699d90)
Location: drivers/base/firmware_loader/main.c:411
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81699d90-ffffffff81699e40: fw_add_devm_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816ba670)
Location: drivers/base/firmware_loader/main.c:417
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816ba670-ffffffff816ba720: fw_add_devm_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f4950)
Location: drivers/base/firmware_loader/main.c:601
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816f4950-ffffffff816f4a02: fw_add_devm_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81718d50)
Location: drivers/base/firmware_loader/main.c:601
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81718d50-ffffffff81718e02: fw_add_devm_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d4ff4)
Location: drivers/base/firmware_loader/main.c:606
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff817d4840-ffffffff817d48c2: fw_add_devm_name.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817e9724)
Location: drivers/base/firmware_loader/main.c:641
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff817e9200-ffffffff817e9282: fw_add_devm_name.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817cdf24)
Location: drivers/base/firmware_loader/main.c:643
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff817cd9d0-ffffffff817cda52: fw_add_devm_name.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81858774)
Location: drivers/base/firmware_loader/main.c:644
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff818581c0-ffffffff81858249: fw_add_devm_name.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8199f530)
Location: drivers/base/firmware_loader/main.c:647
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff8199f530-ffffffff8199f5db: fw_add_devm_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b10f90)
Location: drivers/base/firmware_loader/main.c:647
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81b10f90-ffffffff81b1103b: fw_add_devm_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5f220)
Location: drivers/base/firmware_loader/main.c:656
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81b5f220-ffffffff81b5f2cb: fw_add_devm_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb2bd0)
Location: drivers/base/firmware_loader/main.c:657
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81bb2bd0-ffffffff81bb2c7b: fw_add_devm_name (STB_LOCAL)
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
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090c140)
Location: drivers/base/firmware_loader/main.c:601
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffff80001090c140-ffff80001090c20c: fw_add_devm_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f5568)
Location: drivers/base/firmware_loader/main.c:601
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
c09f5568-c09f561c: fw_add_devm_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009abec0)
Location: drivers/base/firmware_loader/main.c:601
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
c0000000009abec0-c0000000009abfd4: fw_add_devm_name (STB_LOCAL)
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
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:629
Inline: True
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
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816df080)
Location: drivers/base/firmware_loader/main.c:601
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816df080-ffffffff816df132: fw_add_devm_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816b96c0)
Location: drivers/base/firmware_loader/main.c:601
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816b96c0-ffffffff816b9772: fw_add_devm_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170ca10)
Location: drivers/base/firmware_loader/main.c:601
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff8170ca10-ffffffff8170cac2: fw_add_devm_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fw_add_devm_name(struct device *dev, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81727510)
Location: drivers/base/firmware_loader/main.c:601
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81727510-ffffffff817275c2: fw_add_devm_name (STB_LOCAL)
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
