# Function: <code>alloc_lookup_fw_priv</code>

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
In drivers/base/firmware_loader/main.c (ffffffff8169a8df)
Location: drivers/base/firmware_loader/main.c:209
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
In drivers/base/firmware_loader/main.c (ffffffff816bb13f)
Location: drivers/base/firmware_loader/main.c:209
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff816f59b9)
Location: drivers/base/firmware_loader/main.c:210
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff81719db9)
Location: drivers/base/firmware_loader/main.c:210
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d5743)
Location: drivers/base/firmware_loader/main.c:210
Inline: True
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
In drivers/base/firmware_loader/main.c (ffffffff817e9f50)
Location: drivers/base/firmware_loader/main.c:224
Inline: True
```
**Symbols:**

```
ffffffff817e9f50-ffffffff817ea1a2: alloc_lookup_fw_priv.constprop.0 (STB_LOCAL)
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
In drivers/base/firmware_loader/main.c (ffffffff817ce660)
Location: drivers/base/firmware_loader/main.c:225
Inline: True
```
**Symbols:**

```
ffffffff817ce660-ffffffff817ce8ae: alloc_lookup_fw_priv.constprop.0 (STB_LOCAL)
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
In drivers/base/firmware_loader/main.c (ffffffff81858f10)
Location: drivers/base/firmware_loader/main.c:226
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81858f10-ffffffff8185915b: alloc_lookup_fw_priv.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int alloc_lookup_fw_priv(const char *fw_name, struct firmware_cache *fwc, struct fw_priv **fw_priv, void *dbuf, size_t size, size_t offset, u32 opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8199f700)
Location: drivers/base/firmware_loader/main.c:167
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff8199f700-ffffffff8199f989: alloc_lookup_fw_priv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int alloc_lookup_fw_priv(const char *fw_name, struct firmware_cache *fwc, struct fw_priv **fw_priv, void *dbuf, size_t size, size_t offset, u32 opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b111a0)
Location: drivers/base/firmware_loader/main.c:167
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81b111a0-ffffffff81b11415: alloc_lookup_fw_priv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int alloc_lookup_fw_priv(const char *fw_name, struct firmware_cache *fwc, struct fw_priv **fw_priv, void *dbuf, size_t size, size_t offset, u32 opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5f430)
Location: drivers/base/firmware_loader/main.c:167
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_register
```
**Symbols:**

```
ffffffff81b5f430-ffffffff81b5f6ad: alloc_lookup_fw_priv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int alloc_lookup_fw_priv(const char *fw_name, struct firmware_cache *fwc, struct fw_priv **fw_priv, void *dbuf, size_t size, size_t offset, u32 opt_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb2e10)
Location: drivers/base/firmware_loader/main.c:168
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_register
```
**Symbols:**

```
ffffffff81bb2e10-ffffffff81bb30bc: alloc_lookup_fw_priv (STB_GLOBAL)
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
In drivers/base/firmware_loader/main.c (ffff80001090d534)
Location: drivers/base/firmware_loader/main.c:210
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (c09f656c)
Location: drivers/base/firmware_loader/main.c:210
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (c0000000009adab4)
Location: drivers/base/firmware_loader/main.c:210
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffe000591ff4)
Location: drivers/base/firmware_loader/main.c:210
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff816e00e9)
Location: drivers/base/firmware_loader/main.c:210
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff816ba729)
Location: drivers/base/firmware_loader/main.c:210
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff8170d663)
Location: drivers/base/firmware_loader/main.c:210
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff81728428)
Location: drivers/base/firmware_loader/main.c:210
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
