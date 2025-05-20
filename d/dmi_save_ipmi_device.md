# Function: <code>dmi_save_ipmi_device</code>

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
In drivers/firmware/dmi_scan.c (ffffffff81fb5476)
Location: drivers/firmware/dmi_scan.c:302
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
In drivers/firmware/dmi_scan.c (ffffffff81fe2e0a)
Location: drivers/firmware/dmi_scan.c:302
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
In drivers/firmware/dmi_scan.c (ffffffff82020bd9)
Location: drivers/firmware/dmi_scan.c:302
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
In drivers/firmware/dmi_scan.c (ffffffff821032e7)
Location: drivers/firmware/dmi_scan.c:308
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
In drivers/firmware/dmi_scan.c (ffffffff8270c9c8)
Location: drivers/firmware/dmi_scan.c:308
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
In drivers/firmware/dmi_scan.c (ffffffff82736dbc)
Location: drivers/firmware/dmi_scan.c:300
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
In drivers/firmware/dmi_scan.c (ffffffff828f0ce8)
Location: drivers/firmware/dmi_scan.c:300
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
In drivers/firmware/dmi_scan.c (ffffffff8290c322)
Location: drivers/firmware/dmi_scan.c:301
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
In drivers/firmware/dmi_scan.c (ffffffff82915cf1)
Location: drivers/firmware/dmi_scan.c:301
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dmi_save_ipmi_device(const struct dmi_header *dm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff82d2776b)
Location: drivers/firmware/dmi_scan.c:334
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff82d2776b-ffffffff82d277e4: dmi_save_ipmi_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dmi_save_ipmi_device(const struct dmi_header *dm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff83015e83)
Location: drivers/firmware/dmi_scan.c:334
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff83015e83-ffffffff83015efc: dmi_save_ipmi_device (STB_LOCAL)
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
In drivers/firmware/dmi_scan.c (ffffffff83221b1b)
Location: drivers/firmware/dmi_scan.c:335
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
In drivers/firmware/dmi_scan.c (ffffffff8330b569)
Location: drivers/firmware/dmi_scan.c:335
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
In drivers/firmware/dmi_scan.c (ffffffff834c507a)
Location: drivers/firmware/dmi_scan.c:335
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dmi_save_ipmi_device(const struct dmi_header *dm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff83f048f0)
Location: drivers/firmware/dmi_scan.c:335
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff83f048f0-ffffffff83f049e0: dmi_save_ipmi_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dmi_save_ipmi_device(const struct dmi_header *dm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff8372a8b0)
Location: drivers/firmware/dmi_scan.c:335
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff8372a8b0-ffffffff8372a9a0: dmi_save_ipmi_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dmi_save_ipmi_device(const struct dmi_header *dm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff8395e870)
Location: drivers/firmware/dmi_scan.c:335
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff8395e870-ffffffff8395e960: dmi_save_ipmi_device (STB_LOCAL)
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
In drivers/firmware/dmi_scan.c (ffff8000114a3d40)
Location: drivers/firmware/dmi_scan.c:301
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
In drivers/firmware/dmi_scan.c (c15a6444)
Location: drivers/firmware/dmi_scan.c:301
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff828fb245)
Location: drivers/firmware/dmi_scan.c:301
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
In drivers/firmware/dmi_scan.c (ffffffff828f2ae1)
Location: drivers/firmware/dmi_scan.c:301
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
In drivers/firmware/dmi_scan.c (ffffffff82910326)
Location: drivers/firmware/dmi_scan.c:301
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
In drivers/firmware/dmi_scan.c (ffffffff82916d53)
Location: drivers/firmware/dmi_scan.c:301
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
