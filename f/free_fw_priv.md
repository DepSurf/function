# Function: <code>free_fw_priv</code>

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
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8169a420)
Location: drivers/base/firmware_loader/main.c:263
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff8169a420-ffffffff8169a462: free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816bac80)
Location: drivers/base/firmware_loader/main.c:269
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff816bac80-ffffffff816bacc2: free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f51c0)
Location: drivers/base/firmware_loader/main.c:262
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff816f51c0-ffffffff816f5207: free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817195c0)
Location: drivers/base/firmware_loader/main.c:262
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff817195c0-ffffffff81719607: free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d53c0)
Location: drivers/base/firmware_loader/main.c:264
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:__device_uncache_fw_images
```
**Symbols:**

```
ffffffff817d53c0-ffffffff817d541d: free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817e9c90)
Location: drivers/base/firmware_loader/main.c:285
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:__device_uncache_fw_images
```
**Symbols:**

```
ffffffff817e9c90-ffffffff817e9ced: free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ce3c0)
Location: drivers/base/firmware_loader/main.c:286
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff817ce3c0-ffffffff817ce41d: free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81858c70)
Location: drivers/base/firmware_loader/main.c:287
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff81858c70-ffffffff81858ccd: free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8199f990)
Location: drivers/base/firmware_loader/main.c:224
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/sysfs.c:fw_dev_release
```
**Symbols:**

```
ffffffff8199f990-ffffffff8199f9fa: free_fw_priv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b11430)
Location: drivers/base/firmware_loader/main.c:224
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff81b11430-ffffffff81b1149a: free_fw_priv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5f6c0)
Location: drivers/base/firmware_loader/main.c:224
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/sysfs_upload.c:fw_upload_free
```
**Symbols:**

```
ffffffff81b5f6c0-ffffffff81b5f72a: free_fw_priv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb30d0)
Location: drivers/base/firmware_loader/main.c:225
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/sysfs_upload.c:fw_upload_free
```
**Symbols:**

```
ffffffff81bb30d0-ffffffff81bb313a: free_fw_priv (STB_GLOBAL)
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
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090ca08)
Location: drivers/base/firmware_loader/main.c:262
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffff80001090ca08-ffff80001090cb40: free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f5aa8)
Location: drivers/base/firmware_loader/main.c:262
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
c09f5aa8-c09f5bc4: free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009ac490)
Location: drivers/base/firmware_loader/main.c:262
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
c0000000009ac490-c0000000009ac660: free_fw_priv (STB_LOCAL)
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
In drivers/base/firmware_loader/main.c (ffffffe0005919d4)
Location: drivers/base/firmware_loader/main.c:262
Inline: True
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
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816df8f0)
Location: drivers/base/firmware_loader/main.c:262
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff816df8f0-ffffffff816df937: free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816b9f30)
Location: drivers/base/firmware_loader/main.c:262
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff816b9f30-ffffffff816b9f77: free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170d010)
Location: drivers/base/firmware_loader/main.c:262
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff8170d010-ffffffff8170d057: free_fw_priv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_fw_priv(struct fw_priv *fw_priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81727c40)
Location: drivers/base/firmware_loader/main.c:262
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff81727c40-ffffffff81727c85: free_fw_priv (STB_LOCAL)
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
