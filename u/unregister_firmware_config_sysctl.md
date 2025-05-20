# Function: <code>unregister_firmware_config_sysctl</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unregister_firmware_config_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback_table.c (ffffffff8199e720)
Location: drivers/base/firmware_loader/fallback_table.c:62
Inline: False
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:unregister_sysfs_loader
```
**Symbols:**

```
ffffffff8199e720-ffffffff8199e748: unregister_firmware_config_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unregister_firmware_config_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback_table.c (ffffffff81b10090)
Location: drivers/base/firmware_loader/fallback_table.c:62
Inline: False
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:unregister_sysfs_loader
```
**Symbols:**

```
ffffffff81b10090-ffffffff81b100b8: unregister_firmware_config_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unregister_firmware_config_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback_table.c (ffffffff81b5e150)
Location: drivers/base/firmware_loader/fallback_table.c:62
Inline: False
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:unregister_sysfs_loader
```
**Symbols:**

```
ffffffff81b5e150-ffffffff81b5e178: unregister_firmware_config_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unregister_firmware_config_sysctl();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback_table.c (ffffffff81bb1a60)
Location: drivers/base/firmware_loader/fallback_table.c:61
Inline: False
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:unregister_sysfs_loader
```
**Symbols:**

```
ffffffff81bb1a60-ffffffff81bb1a88: unregister_firmware_config_sysctl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
