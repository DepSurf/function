# Function: <code>fw_cache_piggyback_on_request</code>

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
In drivers/base/firmware_class.c (ffffffff8155fc5b)
Location: drivers/base/firmware_class.c:1448
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
In drivers/base/firmware_class.c (ffffffff815b430e)
Location: drivers/base/firmware_class.c:1496
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
In drivers/base/firmware_class.c (ffffffff815e357d)
Location: drivers/base/firmware_class.c:1531
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
In drivers/base/firmware_class.c (ffffffff815f79ee)
Location: drivers/base/firmware_class.c:1531
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
In drivers/base/firmware_class.c (ffffffff8165f97e)
Location: drivers/base/firmware_class.c:1538
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:assign_firmware_buf
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
In drivers/base/firmware_loader/main.c (ffffffff8169a703)
Location: drivers/base/firmware_loader/main.c:955
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
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
In drivers/base/firmware_loader/main.c (ffffffff816baf63)
Location: drivers/base/firmware_loader/main.c:964
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
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
In drivers/base/firmware_loader/main.c (ffffffff816f57ff)
Location: drivers/base/firmware_loader/main.c:1154
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
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
In drivers/base/firmware_loader/main.c (ffffffff81719bff)
Location: drivers/base/firmware_loader/main.c:1154
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fw_cache_piggyback_on_request(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d5230)
Location: drivers/base/firmware_loader/main.c:1185
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff817d5230-ffffffff817d52ee: fw_cache_piggyback_on_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fw_cache_piggyback_on_request(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817e9b00)
Location: drivers/base/firmware_loader/main.c:1258
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff817e9b00-ffffffff817e9bbe: fw_cache_piggyback_on_request (STB_LOCAL)
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
In drivers/base/firmware_loader/main.c (ffffffff817cee74)
Location: drivers/base/firmware_loader/main.c:1262
Inline: True
Inline callers:
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
In drivers/base/firmware_loader/main.c (ffffffff81859574)
Location: drivers/base/firmware_loader/main.c:1261
Inline: True
Inline callers:
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
In drivers/base/firmware_loader/main.c (ffffffff819a00aa)
Location: drivers/base/firmware_loader/main.c:1286
Inline: True
Inline callers:
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
In drivers/base/firmware_loader/main.c (ffffffff81b11c0a)
Location: drivers/base/firmware_loader/main.c:1286
Inline: True
Inline callers:
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
In drivers/base/firmware_loader/main.c (ffffffff81b5fefa)
Location: drivers/base/firmware_loader/main.c:1341
Inline: True
Inline callers:
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
In drivers/base/firmware_loader/main.c (ffffffff81bb390a)
Location: drivers/base/firmware_loader/main.c:1342
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
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
In drivers/base/firmware_loader/main.c (ffff80001090d320)
Location: drivers/base/firmware_loader/main.c:1154
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
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
In drivers/base/firmware_loader/main.c (c09f6368)
Location: drivers/base/firmware_loader/main.c:1154
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
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
In drivers/base/firmware_loader/main.c (c0000000009ad698)
Location: drivers/base/firmware_loader/main.c:1154
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
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
Location: drivers/base/firmware_loader/main.c:1403
Inline: True
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
In drivers/base/firmware_loader/main.c (ffffffff816dff2f)
Location: drivers/base/firmware_loader/main.c:1154
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
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
In drivers/base/firmware_loader/main.c (ffffffff816ba56f)
Location: drivers/base/firmware_loader/main.c:1154
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
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
In drivers/base/firmware_loader/main.c (ffffffff8170d48f)
Location: drivers/base/firmware_loader/main.c:1154
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
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
In drivers/base/firmware_loader/main.c (ffffffff8172825d)
Location: drivers/base/firmware_loader/main.c:1154
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
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
</ul>
