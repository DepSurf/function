# Function: <code>fw_load_from_user_helper</code>

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
In drivers/base/firmware_class.c (ffffffff8155f62f)
Location: drivers/base/firmware_class.c:966
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
In drivers/base/firmware_class.c (ffffffff815b3e77)
Location: drivers/base/firmware_class.c:979
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
In drivers/base/firmware_class.c (ffffffff815e3125)
Location: drivers/base/firmware_class.c:1037
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
In drivers/base/firmware_class.c (ffffffff815f7f69)
Location: drivers/base/firmware_class.c:1067
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
In drivers/base/firmware_class.c (ffffffff8165ff07)
Location: drivers/base/firmware_class.c:1074
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
In drivers/base/firmware_loader/fallback.c (ffffffff8169ba49)
Location: drivers/base/firmware_loader/fallback.c:600
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
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
In drivers/base/firmware_loader/fallback.c (ffffffff816bc2e8)
Location: drivers/base/firmware_loader/fallback.c:595
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
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
In drivers/base/firmware_loader/fallback.c (ffffffff816f694e)
Location: drivers/base/firmware_loader/fallback.c:548
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
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
In drivers/base/firmware_loader/fallback.c (ffffffff8171ad47)
Location: drivers/base/firmware_loader/fallback.c:548
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fw_load_from_user_helper(struct firmware *firmware, const char *name, struct device *device, u32 opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:551
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff817d6bc0-ffffffff817d6d2d: fw_load_from_user_helper (STB_LOCAL)
ffffffff817d70b8-ffffffff817d70d8: fw_load_from_user_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fw_load_from_user_helper(struct firmware *firmware, const char *name, struct device *device, u32 opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:549
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff817eb760-ffffffff817eb8c2: fw_load_from_user_helper (STB_LOCAL)
ffffffff81c0f279-ffffffff81c0f299: fw_load_from_user_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fw_load_from_user_helper(struct firmware *firmware, const char *name, struct device *device, u32 opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:551
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff817cff40-ffffffff817d00a2: fw_load_from_user_helper (STB_LOCAL)
ffffffff81c013d2-ffffffff81c013f2: fw_load_from_user_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fw_load_from_user_helper(struct firmware *firmware, const char *name, struct device *device, u32 opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:551
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff8185a760-ffffffff8185a8bb: fw_load_from_user_helper (STB_LOCAL)
ffffffff81d04398-ffffffff81d043b8: fw_load_from_user_helper.cold (STB_LOCAL)
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
In drivers/base/firmware_loader/fallback.c (ffffffff819a0df9)
Location: drivers/base/firmware_loader/fallback.c:126
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
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
In drivers/base/firmware_loader/fallback.c (ffffffff81b12a99)
Location: drivers/base/firmware_loader/fallback.c:126
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
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
In drivers/base/firmware_loader/fallback.c (ffffffff81b60d89)
Location: drivers/base/firmware_loader/fallback.c:126
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
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
In drivers/base/firmware_loader/fallback.c (ffffffff81bb4819)
Location: drivers/base/firmware_loader/fallback.c:130
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
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
In drivers/base/firmware_loader/fallback.c (ffff80001090e62c)
Location: drivers/base/firmware_loader/fallback.c:548
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
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
In drivers/base/firmware_loader/fallback.c (c09f749c)
Location: drivers/base/firmware_loader/fallback.c:548
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fw_load_from_user_helper(struct firmware *firmware, const char *name, struct device *device, enum fw_opt opt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (c0000000009aee30)
Location: drivers/base/firmware_loader/fallback.c:548
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
c0000000009aee30-c0000000009af2c4: fw_load_from_user_helper (STB_LOCAL)
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
In drivers/base/firmware_loader/fallback.c (ffffffe000592cc0)
Location: drivers/base/firmware_loader/fallback.c:548
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816e1077)
Location: drivers/base/firmware_loader/fallback.c:548
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
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
In drivers/base/firmware_loader/fallback.c (ffffffff816bb6b7)
Location: drivers/base/firmware_loader/fallback.c:548
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
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
In drivers/base/firmware_loader/fallback.c (ffffffff8170e747)
Location: drivers/base/firmware_loader/fallback.c:548
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
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
In drivers/base/firmware_loader/fallback.c (ffffffff81729367)
Location: drivers/base/firmware_loader/fallback.c:548
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
