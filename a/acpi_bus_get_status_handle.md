# Function: <code>acpi_bus_get_status_handle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8147ea46)
Location: drivers/acpi/bus.c:91
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff8147ea46-ffffffff8147ea7f: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814cd2a7)
Location: drivers/acpi/bus.c:95
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff814cd2a7-ffffffff814cd2da: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814ef1d5)
Location: drivers/acpi/bus.c:95
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff814ef1d5-ffffffff814ef208: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814fc188)
Location: drivers/acpi/bus.c:95
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff814fc1d0-ffffffff814fc206: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8153defb)
Location: drivers/acpi/bus.c:122
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff8153dff0-ffffffff8153e026: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81572f60)
Location: drivers/acpi/bus.c:122
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff81572f60-ffffffff81572f96: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8158ab50)
Location: drivers/acpi/bus.c:91
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff8158ab50-ffffffff8158ab86: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815bb8e0)
Location: drivers/acpi/bus.c:78
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff815bb8e0-ffffffff815bb916: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815dcba0)
Location: drivers/acpi/bus.c:78
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff815dcba0-ffffffff815dcbd6: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816872b0)
Location: drivers/acpi/bus.c:78
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff816872b0-ffffffff816872ec: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816a4fc0)
Location: drivers/acpi/bus.c:78
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff816a4fc0-ffffffff816a4ffc: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81687d40)
Location: drivers/acpi/bus.c:76
Inline: True
```
**Symbols:**

```
ffffffff81687d40-ffffffff81687d7c: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816fdfb8)
Location: drivers/acpi/bus.c:78
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
```
**Symbols:**

```
ffffffff816fd1e0-ffffffff816fd21c: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8182b94e)
Location: drivers/acpi/bus.c:79
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
```
**Symbols:**

```
ffffffff8182a970-ffffffff8182a9c4: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8195e2ef)
Location: drivers/acpi/bus.c:80
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
```
**Symbols:**

```
ffffffff8195cf00-ffffffff8195cf54: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819a46df)
Location: drivers/acpi/bus.c:77
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
```
**Symbols:**

```
ffffffff819a33b0-ffffffff819a3404: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819ed02f)
Location: drivers/acpi/bus.c:77
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
```
**Symbols:**

```
ffffffff819eba60-ffffffff819ebab4: acpi_bus_get_status_handle (STB_GLOBAL)
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
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffff800010768ea8)
Location: drivers/acpi/bus.c:78
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffff800010768e00-ffff800010768e64: acpi_bus_get_status_handle (STB_GLOBAL)
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
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815cf1f0)
Location: drivers/acpi/bus.c:78
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff815cf1f0-ffffffff815cf226: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815b8db0)
Location: drivers/acpi/bus.c:78
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff815b8db0-ffffffff815b8de6: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815d0e80)
Location: drivers/acpi/bus.c:78
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff815d0e80-ffffffff815d0eb6: acpi_bus_get_status_handle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_bus_get_status_handle(acpi_handle handle, long long unsigned int *sta);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815ead40)
Location: drivers/acpi/bus.c:78
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff815ead40-ffffffff815ead76: acpi_bus_get_status_handle (STB_GLOBAL)
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
