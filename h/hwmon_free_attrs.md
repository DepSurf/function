# Function: <code>hwmon_free_attrs</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hwmon_free_attrs(struct attribute **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81884400)
Location: drivers/hwmon/hwmon.c:99
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_dev_release
```
**Symbols:**

```
ffffffff81884400-ffffffff8188443a: hwmon_free_attrs (STB_LOCAL)
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
In drivers/hwmon/hwmon.c (ffffffff81953283)
Location: drivers/hwmon/hwmon.c:100
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
  - drivers/hwmon/hwmon.c:hwmon_dev_release
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
In drivers/hwmon/hwmon.c (ffffffff819580f3)
Location: drivers/hwmon/hwmon.c:100
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
  - drivers/hwmon/hwmon.c:hwmon_dev_release
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
In drivers/hwmon/hwmon.c (ffffffff8193bed3)
Location: drivers/hwmon/hwmon.c:100
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:hwmon_dev_release
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
In drivers/hwmon/hwmon.c (ffffffff819e0753)
Location: drivers/hwmon/hwmon.c:100
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:hwmon_dev_release
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
In drivers/hwmon/hwmon.c (ffffffff81b454c3)
Location: drivers/hwmon/hwmon.c:114
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:hwmon_dev_release
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
In drivers/hwmon/hwmon.c (ffffffff81cdc673)
Location: drivers/hwmon/hwmon.c:115
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:hwmon_dev_release
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
In drivers/hwmon/hwmon.c (ffffffff81d44b43)
Location: drivers/hwmon/hwmon.c:115
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:hwmon_dev_release
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
In drivers/hwmon/hwmon.c (ffffffff81dfb704)
Location: drivers/hwmon/hwmon.c:115
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
  - drivers/hwmon/hwmon.c:hwmon_dev_release
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
void hwmon_free_attrs(struct attribute **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffff800010ad0f90)
Location: drivers/hwmon/hwmon.c:99
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_dev_release
```
**Symbols:**

```
ffff800010ad0f90-ffff800010ad0fdc: hwmon_free_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hwmon_free_attrs(struct attribute **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (c0bb1a40)
Location: drivers/hwmon/hwmon.c:99
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
  - drivers/hwmon/hwmon.c:hwmon_dev_release
```
**Symbols:**

```
c0bb1a40-c0bb1a84: hwmon_free_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hwmon_free_attrs(struct attribute **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (c000000000bb5440)
Location: drivers/hwmon/hwmon.c:99
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_dev_release
```
**Symbols:**

```
c000000000bb5440-c000000000bb54c4: hwmon_free_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hwmon_free_attrs(struct attribute **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffe0006cd8ce)
Location: drivers/hwmon/hwmon.c:99
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_dev_release
```
**Symbols:**

```
ffffffe0006cd8ce-ffffffe0006cd918: hwmon_free_attrs (STB_LOCAL)
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
void hwmon_free_attrs(struct attribute **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff8182a280)
Location: drivers/hwmon/hwmon.c:99
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_dev_release
```
**Symbols:**

```
ffffffff8182a280-ffffffff8182a2ba: hwmon_free_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hwmon_free_attrs(struct attribute **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff817f1910)
Location: drivers/hwmon/hwmon.c:99
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_dev_release
```
**Symbols:**

```
ffffffff817f1910-ffffffff817f194a: hwmon_free_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hwmon_free_attrs(struct attribute **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff818798b0)
Location: drivers/hwmon/hwmon.c:99
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_dev_release
```
**Symbols:**

```
ffffffff818798b0-ffffffff818798ea: hwmon_free_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hwmon_free_attrs(struct attribute **attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff818952b0)
Location: drivers/hwmon/hwmon.c:99
Inline: False
Direct callers:
  - drivers/hwmon/hwmon.c:hwmon_dev_release
```
**Symbols:**

```
ffffffff818952b0-ffffffff818952ea: hwmon_free_attrs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
