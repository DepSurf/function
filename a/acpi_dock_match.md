# Function: <code>acpi_dock_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814803df)
Location: drivers/acpi/scan.c:1086
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff814803df-ffffffff814803f6: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814ced5a)
Location: drivers/acpi/scan.c:1106
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff814ced5a-ffffffff814ced71: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814f0cc4)
Location: drivers/acpi/scan.c:1107
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff814f0cc4-ffffffff814f0cdb: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814ff33a)
Location: drivers/acpi/scan.c:1098
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff814fe350-ffffffff814fe367: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81541422)
Location: drivers/acpi/scan.c:1102
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff81540160-ffffffff81540177: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815772f2)
Location: drivers/acpi/scan.c:1103
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff815760c0-ffffffff815760d7: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8158eef6)
Location: drivers/acpi/scan.c:1103
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff8158dce0-ffffffff8158dcf7: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bfc79)
Location: drivers/acpi/scan.c:1101
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff815bea60-ffffffff815bea77: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815e0f39)
Location: drivers/acpi/scan.c:1101
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff815dfd20-ffffffff815dfd37: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168b335)
Location: drivers/acpi/scan.c:1110
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init_hotplug
  - drivers/acpi/scan.c:acpi_set_pnp_ids
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff8168b780-ffffffff8168b797: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a9155)
Location: drivers/acpi/scan.c:1179
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init_hotplug
  - drivers/acpi/scan.c:acpi_set_pnp_ids
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff816a9570-ffffffff816a9587: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168c676)
Location: drivers/acpi/scan.c:1179
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_set_pnp_ids
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff8168bd00-ffffffff8168bd17: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81701eb6)
Location: drivers/acpi/scan.c:1187
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_set_pnp_ids
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff81701480-ffffffff81701497: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182fb80)
Location: drivers/acpi/scan.c:1217
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_set_pnp_ids
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:is_dock_device
```
**Symbols:**

```
ffffffff8182f0e0-ffffffff8182f0ff: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81962c20)
Location: drivers/acpi/scan.c:1200
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_set_pnp_ids
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:is_dock_device
```
**Symbols:**

```
ffffffff81962070-ffffffff8196208f: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a9069)
Location: drivers/acpi/scan.c:1202
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_set_pnp_ids
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:is_dock_device
```
**Symbols:**

```
ffffffff819a8470-ffffffff819a848f: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819f1aa8)
Location: drivers/acpi/scan.c:1205
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_set_pnp_ids
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:is_dock_device
```
**Symbols:**

```
ffffffff819f0e90-ffffffff819f0eaf: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076d774)
Location: drivers/acpi/scan.c:1101
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffff80001076c588-ffff80001076c5bc: acpi_dock_match (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d3267)
Location: drivers/acpi/scan.c:1101
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff815d2130-ffffffff815d2147: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bce27)
Location: drivers/acpi/scan.c:1101
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff815bbcf0-ffffffff815bbd07: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d5219)
Location: drivers/acpi/scan.c:1101
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff815d4000-ffffffff815d4017: acpi_dock_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dock_match(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815ef0d9)
Location: drivers/acpi/scan.c:1101
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
Direct callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
**Symbols:**

```
ffffffff815edec0-ffffffff815eded7: acpi_dock_match (STB_GLOBAL)
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
