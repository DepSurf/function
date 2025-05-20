# Function: <code>__fw_entry_found</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8155e210)
Location: drivers/base/firmware_class.c:1436
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff8155e210-ffffffff8155e25e: __fw_entry_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815b2750)
Location: drivers/base/firmware_class.c:1484
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff815b2750-ffffffff815b279e: __fw_entry_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815e1a50)
Location: drivers/base/firmware_class.c:1519
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff815e1a50-ffffffff815e1a9e: __fw_entry_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f67b0)
Location: drivers/base/firmware_class.c:1519
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/base/firmware_class.c:assign_firmware_buf
```
**Symbols:**

```
ffffffff815f67b0-ffffffff815f67fe: __fw_entry_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8165e710)
Location: drivers/base/firmware_class.c:1526
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/base/firmware_class.c:assign_firmware_buf
```
**Symbols:**

```
ffffffff8165e710-ffffffff8165e75e: __fw_entry_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81699cc0)
Location: drivers/base/firmware_loader/main.c:943
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81699cc0-ffffffff81699d0e: __fw_entry_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816ba510)
Location: drivers/base/firmware_loader/main.c:952
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816ba510-ffffffff816ba55e: __fw_entry_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f47f0)
Location: drivers/base/firmware_loader/main.c:1142
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816f47f0-ffffffff816f483e: __fw_entry_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81718bf0)
Location: drivers/base/firmware_loader/main.c:1142
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81718bf0-ffffffff81718c3e: __fw_entry_found (STB_LOCAL)
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
In drivers/base/firmware_loader/main.c (ffffffff817d5158)
Location: drivers/base/firmware_loader/main.c:1173
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:fw_cache_piggyback_on_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817e9a28)
Location: drivers/base/firmware_loader/main.c:1246
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:fw_cache_piggyback_on_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ce218)
Location: drivers/base/firmware_loader/main.c:1250
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81858ab8)
Location: drivers/base/firmware_loader/main.c:1249
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8199f448)
Location: drivers/base/firmware_loader/main.c:1274
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b10e98)
Location: drivers/base/firmware_loader/main.c:1274
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5f128)
Location: drivers/base/firmware_loader/main.c:1329
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb2ad8)
Location: drivers/base/firmware_loader/main.c:1330
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
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
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090bf68)
Location: drivers/base/firmware_loader/main.c:1142
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffff80001090bf68-ffff80001090bfe0: __fw_entry_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f5250)
Location: drivers/base/firmware_loader/main.c:1142
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
c09f5250-c09f52b0: __fw_entry_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009ab780)
Location: drivers/base/firmware_loader/main.c:1142
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
c0000000009ab780-c0000000009ab9c0: __fw_entry_found (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816def20)
Location: drivers/base/firmware_loader/main.c:1142
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816def20-ffffffff816def6e: __fw_entry_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816b9560)
Location: drivers/base/firmware_loader/main.c:1142
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816b9560-ffffffff816b95ae: __fw_entry_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170c8b0)
Location: drivers/base/firmware_loader/main.c:1142
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff8170c8b0-ffffffff8170c8fe: __fw_entry_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __fw_entry_found(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81727260)
Location: drivers/base/firmware_loader/main.c:1142
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81727260-ffffffff817272ae: __fw_entry_found (STB_LOCAL)
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
