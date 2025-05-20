# Function: <code>__acpi_osi_setup_darwin</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff81fccc26)
Location: drivers/acpi/osi.c:131
Inline: True
Direct callers:
  - drivers/acpi/osi.c:dmi_enable_osi_darwin
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff81fccc26-ffffffff81fccc7c: __acpi_osi_setup_darwin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff82009c20)
Location: drivers/acpi/osi.c:131
Inline: True
Direct callers:
  - drivers/acpi/osi.c:dmi_enable_osi_darwin
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff82009c20-ffffffff82009c76: __acpi_osi_setup_darwin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff820eb2f8)
Location: drivers/acpi/osi.c:131
Inline: True
Direct callers:
  - drivers/acpi/osi.c:dmi_enable_osi_darwin
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff820eb2f8-ffffffff820eb358: __acpi_osi_setup_darwin (STB_LOCAL)
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
In drivers/acpi/osi.c (ffffffff826f4383)
Location: drivers/acpi/osi.c:132
Inline: True
Inline callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:acpi_osi_setup_darwin
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff8271e181)
Location: drivers/acpi/osi.c:149
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff8271e181-ffffffff8271e1e0: __acpi_osi_setup_darwin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff828d61ac)
Location: drivers/acpi/osi.c:156
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff828d61ac-ffffffff828d620b: __acpi_osi_setup_darwin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff828f0008)
Location: drivers/acpi/osi.c:143
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff828f0008-ffffffff828f0067: __acpi_osi_setup_darwin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff828f9179)
Location: drivers/acpi/osi.c:143
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff828f9179-ffffffff828f91d8: __acpi_osi_setup_darwin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff82d1034c)
Location: drivers/acpi/osi.c:143
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff82d1034c-ffffffff82d103ab: __acpi_osi_setup_darwin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff82ffde1c)
Location: drivers/acpi/osi.c:143
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff82ffde1c-ffffffff82ffde7b: __acpi_osi_setup_darwin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff83208b49)
Location: drivers/acpi/osi.c:143
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff83208b49-ffffffff83208ba4: __acpi_osi_setup_darwin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff832f0dc5)
Location: drivers/acpi/osi.c:143
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff832f0dc5-ffffffff832f0e20: __acpi_osi_setup_darwin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff834a8d91)
Location: drivers/acpi/osi.c:143
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff834a8d91-ffffffff834a8df6: __acpi_osi_setup_darwin (STB_LOCAL)
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
In drivers/acpi/osi.c (ffffffff83ee0763)
Location: drivers/acpi/osi.c:119
Inline: True
Inline callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
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
In drivers/acpi/osi.c (ffffffff83706203)
Location: drivers/acpi/osi.c:119
Inline: True
Inline callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
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
In drivers/acpi/osi.c (ffffffff83939783)
Location: drivers/acpi/osi.c:119
Inline: True
Inline callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
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
In drivers/acpi/osi.c (ffff80001147c41c)
Location: drivers/acpi/osi.c:143
Inline: True
Inline callers:
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff828e1ee5)
Location: drivers/acpi/osi.c:143
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff828e1ee5-ffffffff828e1f44: __acpi_osi_setup_darwin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff828d9f15)
Location: drivers/acpi/osi.c:143
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff828d9f15-ffffffff828d9f74: __acpi_osi_setup_darwin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff828f4d75)
Location: drivers/acpi/osi.c:143
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff828f4d75-ffffffff828f4dd4: __acpi_osi_setup_darwin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __acpi_osi_setup_darwin(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff828fa1cd)
Location: drivers/acpi/osi.c:143
Inline: False
Direct callers:
  - drivers/acpi/osi.c:early_acpi_osi_init
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff828fa1cd-ffffffff828fa22c: __acpi_osi_setup_darwin (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
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
