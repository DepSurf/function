# Function: <code>acpi_sysfs_add_hotplug_profile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8148a2e2)
Location: drivers/acpi/sysfs.c:825
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff8148a2e2-ffffffff8148a33a: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff814d90d0)
Location: drivers/acpi/sysfs.c:822
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff814d90d0-ffffffff814d9128: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff814fb85b)
Location: drivers/acpi/sysfs.c:901
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff814fb85b-ffffffff814fb8b3: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8150b080)
Location: drivers/acpi/sysfs.c:904
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff8150b080-ffffffff8150b0d8: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8154db10)
Location: drivers/acpi/sysfs.c:993
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff8154db10-ffffffff8154db68: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:983
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff815843cf-ffffffff815843e3: acpi_sysfs_add_hotplug_profile.cold.10 (STB_LOCAL)
ffffffff81584310-ffffffff8158435f: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:983
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff8159c4ff-ffffffff8159c513: acpi_sysfs_add_hotplug_profile.cold.9 (STB_LOCAL)
ffffffff8159c440-ffffffff8159c48f: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:986
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff815cdb81-ffffffff815cdb95: acpi_sysfs_add_hotplug_profile.cold (STB_LOCAL)
ffffffff815cdac0-ffffffff815cdb11: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:986
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff815eee01-ffffffff815eee15: acpi_sysfs_add_hotplug_profile.cold (STB_LOCAL)
ffffffff815eed40-ffffffff815eed91: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8169ad00)
Location: drivers/acpi/sysfs.c:986
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff8169ad00-ffffffff8169ad62: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff816b7d80)
Location: drivers/acpi/sysfs.c:986
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff816b7d80-ffffffff816b7de2: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81699de0)
Location: drivers/acpi/sysfs.c:967
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff81699de0-ffffffff81699e42: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8170fc80)
Location: drivers/acpi/sysfs.c:948
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff8170fc80-ffffffff8170fce2: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8183e7e0)
Location: drivers/acpi/sysfs.c:960
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff8183e7e0-ffffffff8183e851: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81974700)
Location: drivers/acpi/sysfs.c:961
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff81974700-ffffffff81974785: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff819baf20)
Location: drivers/acpi/sysfs.c:978
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff819baf20-ffffffff819bafa5: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81a05600)
Location: drivers/acpi/sysfs.c:978
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff81a05600-ffffffff81a05685: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
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
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffff8000107798d8)
Location: drivers/acpi/sysfs.c:986
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffff8000107798d8-ffff800010779950: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:986
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff815dda9c-ffffffff815ddab0: acpi_sysfs_add_hotplug_profile.cold (STB_LOCAL)
ffffffff815dda00-ffffffff815dda51: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:986
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff815c90dc-ffffffff815c90f0: acpi_sysfs_add_hotplug_profile.cold (STB_LOCAL)
ffffffff815c9040-ffffffff815c9091: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:986
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff815e30e1-ffffffff815e30f5: acpi_sysfs_add_hotplug_profile.cold (STB_LOCAL)
ffffffff815e3020-ffffffff815e3071: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void acpi_sysfs_add_hotplug_profile(struct acpi_hotplug_profile *hotplug, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:986
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
```
**Symbols:**

```
ffffffff815fcfa1-ffffffff815fcfb5: acpi_sysfs_add_hotplug_profile.cold (STB_LOCAL)
ffffffff815fcee0-ffffffff815fcf31: acpi_sysfs_add_hotplug_profile (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
