# Function: <code>__fw_state_wait_common</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __fw_state_wait_common(struct fw_state *fw_st, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815e1ac0)
Location: drivers/base/firmware_class.c:130
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff815e1ac0-ffffffff815e1bd2: __fw_state_wait_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __fw_state_wait_common(struct fw_state *fw_st, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f6820)
Location: drivers/base/firmware_class.c:129
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff815f6820-ffffffff815f685a: __fw_state_wait_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __fw_state_wait_common(struct fw_state *fw_st, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8165e780)
Location: drivers/base/firmware_class.c:131
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff8165e780-ffffffff8165e7ba: __fw_state_wait_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8169a91e)
Location: drivers/base/firmware_loader/firmware.h:88
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8169bbaa)
Location: drivers/base/firmware_loader/firmware.h:88
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816bb38a)
Location: drivers/base/firmware_loader/firmware.h:88
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bc5a1)
Location: drivers/base/firmware_loader/firmware.h:88
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f5b86)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816f6ab7)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81719f86)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8171aea5)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d57d8)
Location: drivers/base/firmware_loader/firmware.h:94
Inline: True
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817d6a8f)
Location: drivers/base/firmware_loader/firmware.h:94
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ea2cc)
Location: drivers/base/firmware_loader/firmware.h:99
Inline: True
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817eb639)
Location: drivers/base/firmware_loader/firmware.h:99
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ce9cc)
Location: drivers/base/firmware_loader/firmware.h:99
Inline: True
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817cfe03)
Location: drivers/base/firmware_loader/firmware.h:99
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81859869)
Location: drivers/base/firmware_loader/firmware.h:99
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8185a613)
Location: drivers/base/firmware_loader/firmware.h:99
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff819a048f)
Location: drivers/base/firmware_loader/firmware.h:100
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff819a0b04)
Location: drivers/base/firmware_loader/firmware.h:100
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b1201a)
Location: drivers/base/firmware_loader/firmware.h:98
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81b1272a)
Location: drivers/base/firmware_loader/firmware.h:98
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b6030a)
Location: drivers/base/firmware_loader/firmware.h:98
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81b60a1a)
Location: drivers/base/firmware_loader/firmware.h:98
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb3d4a)
Location: drivers/base/firmware_loader/firmware.h:99
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81bb4474)
Location: drivers/base/firmware_loader/firmware.h:99
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090d77c)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffff80001090e758)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f675c)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (c09f75f4)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009adcd4)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (c0000000009aefc4)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe0005921f2)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffe000592dfc)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816e02b6)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816e11d5)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816ba8f6)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bb815)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170d8f8)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8170e8a5)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817285ed)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817294c5)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
