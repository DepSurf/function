# Function: <code>rtc_device_get_offset</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rtc_device_get_offset(struct rtc_device *rtc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff817cb5b0)
Location: drivers/rtc/class.c:214
Inline: True
Direct callers:
  - drivers/rtc/class.c:__rtc_register_device
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff817cb5b0-ffffffff817cb69c: rtc_device_get_offset (STB_LOCAL)
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
In drivers/rtc/class.c (ffffffff817f2c37)
Location: drivers/rtc/class.c:213
Inline: True
Inline callers:
  - drivers/rtc/class.c:__rtc_register_device
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
In drivers/rtc/class.c (ffffffff818338f7)
Location: drivers/rtc/class.c:208
Inline: True
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
In drivers/rtc/class.c (ffffffff81865286)
Location: drivers/rtc/class.c:208
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rtc_device_get_offset(struct rtc_device *rtc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81938a60)
Location: drivers/rtc/class.c:252
Inline: False
```
**Symbols:**

```
ffffffff81938a60-ffffffff81938b4d: rtc_device_get_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rtc_device_get_offset(struct rtc_device *rtc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff8193ec40)
Location: drivers/rtc/class.c:258
Inline: False
```
**Symbols:**

```
ffffffff8193ec40-ffffffff8193ed2d: rtc_device_get_offset (STB_LOCAL)
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
In drivers/rtc/class.c (ffffffff819224b2)
Location: drivers/rtc/class.c:260
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
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
In drivers/rtc/class.c (ffffffff819c5461)
Location: drivers/rtc/class.c:260
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
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
In drivers/rtc/class.c (ffffffff81b25f78)
Location: drivers/rtc/class.c:270
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
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
In drivers/rtc/class.c (ffffffff81cb954b)
Location: drivers/rtc/class.c:270
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
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
In drivers/rtc/class.c (ffffffff81d20c7b)
Location: drivers/rtc/class.c:270
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
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
In drivers/rtc/class.c (ffffffff81dd69ab)
Location: drivers/rtc/class.c:270
Inline: True
Inline callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
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
In drivers/rtc/class.c (ffff800010aa6d8c)
Location: drivers/rtc/class.c:208
Inline: True
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
In drivers/rtc/class.c (c0b85870)
Location: drivers/rtc/class.c:208
Inline: True
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
In drivers/rtc/class.c (c000000000b8781c)
Location: drivers/rtc/class.c:208
Inline: True
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
In drivers/rtc/class.c (ffffffe0006b2dd0)
Location: drivers/rtc/class.c:208
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
In drivers/rtc/class.c (ffffffff81817f36)
Location: drivers/rtc/class.c:208
Inline: True
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
In drivers/rtc/class.c (ffffffff817df626)
Location: drivers/rtc/class.c:208
Inline: True
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
In drivers/rtc/class.c (ffffffff81859416)
Location: drivers/rtc/class.c:208
Inline: True
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
In drivers/rtc/class.c (ffffffff818744f6)
Location: drivers/rtc/class.c:208
Inline: True
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
