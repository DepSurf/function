# Function: <code>_request_firmware_prepare</code>

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
In drivers/base/firmware_class.c (ffffffff8155f375)
Location: drivers/base/firmware_class.c:1039
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
In drivers/base/firmware_class.c (ffffffff815b39a0)
Location: drivers/base/firmware_class.c:1052
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
In drivers/base/firmware_class.c (ffffffff815e2d20)
Location: drivers/base/firmware_class.c:1087
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
In drivers/base/firmware_class.c (ffffffff815f7bb0)
Location: drivers/base/firmware_class.c:1127
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
In drivers/base/firmware_class.c (ffffffff8165fb50)
Location: drivers/base/firmware_class.c:1134
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
In drivers/base/firmware_loader/main.c (ffffffff8169a85f)
Location: drivers/base/firmware_loader/main.c:495
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
In drivers/base/firmware_loader/main.c (ffffffff816bb0bf)
Location: drivers/base/firmware_loader/main.c:501
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
In drivers/base/firmware_loader/main.c (ffffffff816f5933)
Location: drivers/base/firmware_loader/main.c:685
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
In drivers/base/firmware_loader/main.c (ffffffff81719d33)
Location: drivers/base/firmware_loader/main.c:685
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:689
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff817d5680-ffffffff817d594e: _request_firmware_prepare.constprop.0 (STB_LOCAL)
ffffffff817d63a3-ffffffff817d63c5: _request_firmware_prepare.constprop.0.cold (STB_LOCAL)
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
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:724
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff817ea1b0-ffffffff817ea352: _request_firmware_prepare.constprop.0 (STB_LOCAL)
ffffffff81c0f165-ffffffff81c0f187: _request_firmware_prepare.constprop.0.cold (STB_LOCAL)
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
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:726
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
**Symbols:**

```
ffffffff817ce8b0-ffffffff817cea51: _request_firmware_prepare.constprop.0 (STB_LOCAL)
ffffffff81c012d5-ffffffff81c012f7: _request_firmware_prepare.constprop.0.cold (STB_LOCAL)
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
In drivers/base/firmware_loader/main.c (ffffffff8185973f)
Location: drivers/base/firmware_loader/main.c:725
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff819a0269)
Location: drivers/base/firmware_loader/main.c:728
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff81b11dd9)
Location: drivers/base/firmware_loader/main.c:728
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff81b600c9)
Location: drivers/base/firmware_loader/main.c:737
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff81bb3ad8)
Location: drivers/base/firmware_loader/main.c:738
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffff80001090d4a8)
Location: drivers/base/firmware_loader/main.c:685
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
In drivers/base/firmware_loader/main.c (c09f649c)
Location: drivers/base/firmware_loader/main.c:685
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
In drivers/base/firmware_loader/main.c (c0000000009ad850)
Location: drivers/base/firmware_loader/main.c:685
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
In drivers/base/firmware_loader/main.c (ffffffe000591f50)
Location: drivers/base/firmware_loader/main.c:685
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
In drivers/base/firmware_loader/main.c (ffffffff816e0063)
Location: drivers/base/firmware_loader/main.c:685
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
In drivers/base/firmware_loader/main.c (ffffffff816ba6a3)
Location: drivers/base/firmware_loader/main.c:685
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
In drivers/base/firmware_loader/main.c (ffffffff8170d5df)
Location: drivers/base/firmware_loader/main.c:685
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
In drivers/base/firmware_loader/main.c (ffffffff817283a3)
Location: drivers/base/firmware_loader/main.c:685
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
</ul>

## Differences
