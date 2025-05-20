# Function: <code>response_get_string</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8145e6f0)
Location: block/sed-opal.c:859
Inline: True
```
**Symbols:**

```
ffffffff8145e6f0-ffffffff8145e798: response_get_string.constprop.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8148a5b0)
Location: block/sed-opal.c:871
Inline: True
```
**Symbols:**

```
ffffffff8148a5b0-ffffffff8148a658: response_get_string.constprop.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff814c0d40)
Location: block/sed-opal.c:868
Inline: True
```
**Symbols:**

```
ffffffff814c0d40-ffffffff814c0e1f: response_get_string.constprop.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff814d3660)
Location: block/sed-opal.c:868
Inline: True
```
**Symbols:**

```
ffffffff814d3660-ffffffff814d373f: response_get_string.constprop.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff815003e0)
Location: block/sed-opal.c:915
Inline: True
Direct callers:
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff815003e0-ffffffff81500479: response_get_string.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8151e340)
Location: block/sed-opal.c:913
Inline: True
Direct callers:
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff8151e340-ffffffff8151e3d9: response_get_string.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t response_get_string(const struct parsed_resp *resp, int n, const char **store);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8157c890)
Location: block/sed-opal.c:915
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key_cont
```
**Symbols:**

```
ffffffff8157c890-ffffffff8157c933: response_get_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t response_get_string(const struct parsed_resp *resp, int n, const char **store);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815998d0)
Location: block/sed-opal.c:915
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key_cont
```
**Symbols:**

```
ffffffff815998d0-ffffffff81599973: response_get_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t response_get_string(const struct parsed_resp *resp, int n, const char **store);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a0570)
Location: block/sed-opal.c:915
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff815a0570-ffffffff815a0613: response_get_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t response_get_string(const struct parsed_resp *resp, int n, const char **store);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81608d80)
Location: block/sed-opal.c:915
Inline: False
Direct callers:
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff81608d80-ffffffff81608e1d: response_get_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t response_get_string(const struct parsed_resp *resp, int n, const char **store);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816bcc00)
Location: block/sed-opal.c:915
Inline: False
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff816bcc00-ffffffff816bcca3: response_get_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t response_get_string(const struct parsed_resp *resp, int n, const char **store);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8177d690)
Location: block/sed-opal.c:955
Inline: False
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff8177d690-ffffffff8177d735: response_get_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t response_get_string(const struct parsed_resp *resp, int n, const char **store);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817bd090)
Location: block/sed-opal.c:963
Inline: False
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff817bd090-ffffffff817bd135: response_get_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t response_get_string(const struct parsed_resp *resp, int n, const char **store);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81801750)
Location: block/sed-opal.c:1080
Inline: False
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff81801750-ffffffff818017f5: response_get_string (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffff800010626e30)
Location: block/sed-opal.c:913
Inline: True
Direct callers:
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffff800010626e30-ffff800010626f2c: response_get_string.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (c07cec98)
Location: block/sed-opal.c:913
Inline: True
Direct callers:
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
c07cec98-c07ced7c: response_get_string.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (c0000000007c83e0)
Location: block/sed-opal.c:913
Inline: True
Direct callers:
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
c0000000007c83e0-c0000000007c8518: response_get_string.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffe000458a7c)
Location: block/sed-opal.c:913
Inline: True
Direct callers:
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffe000458a7c-ffffffe000458b50: response_get_string.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff81516920)
Location: block/sed-opal.c:913
Inline: True
Direct callers:
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff81516920-ffffffff815169b9: response_get_string.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff81506c30)
Location: block/sed-opal.c:913
Inline: True
Direct callers:
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff81506c30-ffffffff81506cc9: response_get_string.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff815129b0)
Location: block/sed-opal.c:913
Inline: True
Direct callers:
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff815129b0-ffffffff81512a49: response_get_string.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8152c170)
Location: block/sed-opal.c:913
Inline: True
Direct callers:
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff8152c170-ffffffff8152c209: response_get_string.constprop.0 (STB_LOCAL)
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
