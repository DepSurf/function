# Function: <code>security_kernel_post_load_data</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_kernel_post_load_data(char *buf, loff_t size, enum kernel_load_data_id id, char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6310)
Location: security/security.c:1924
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff814c6310-ffffffff814c6377: security_kernel_post_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_kernel_post_load_data(char *buf, loff_t size, enum kernel_load_data_id id, char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc5c0)
Location: security/security.c:1974
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff814cc5c0-ffffffff814cc627: security_kernel_post_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_kernel_post_load_data(char *buf, loff_t size, enum kernel_load_data_id id, char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525450)
Location: security/security.c:1982
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff81525450-ffffffff815254b7: security_kernel_post_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_kernel_post_load_data(char *buf, loff_t size, enum kernel_load_data_id id, char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b9440)
Location: security/security.c:1987
Inline: False
Direct callers:
  - kernel/module/main.c:__do_sys_init_module
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
**Symbols:**

```
ffffffff815b9440-ffffffff815b94cc: security_kernel_post_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_kernel_post_load_data(char *buf, loff_t size, enum kernel_load_data_id id, char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81664c00)
Location: security/security.c:2034
Inline: False
Direct callers:
  - kernel/module/main.c:__do_sys_init_module
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81664c00-ffffffff81664c8c: security_kernel_post_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_kernel_post_load_data(char *buf, loff_t size, enum kernel_load_data_id id, char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169d0e0)
Location: security/security.c:3268
Inline: False
Direct callers:
  - kernel/module/main.c:__do_sys_init_module
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
**Symbols:**

```
ffffffff8169d0e0-ffffffff8169d16c: security_kernel_post_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_kernel_post_load_data(char *buf, loff_t size, enum kernel_load_data_id id, char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d9bc0)
Location: security/security.c:3340
Inline: False
Direct callers:
  - kernel/module/main.c:__do_sys_init_module
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
**Symbols:**

```
ffffffff816d9bc0-ffffffff816d9c4c: security_kernel_post_load_data (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
