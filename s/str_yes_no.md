# Function: <code>str_yes_no</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff815f58d3)
Location: include/linux/string_helpers.h:109
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/common.c (ffffffff815fa51f)
Location: include/linux/string_helpers.h:109
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff816a63d3)
Location: include/linux/string_helpers.h:111
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/common.c (ffffffff816ab24f)
Location: include/linux/string_helpers.h:111
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff816dedb3)
Location: include/linux/string_choices.h:39
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/common.c (ffffffff816e3c4b)
Location: include/linux/string_choices.h:39
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8171b9c3)
Location: include/linux/string_choices.h:40
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/common.c (ffffffff817208fb)
Location: include/linux/string_choices.h:40
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_print_condition
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
  - security/tomoyo/common.c:tomoyo_read_profile
```
```
In drivers/gpu/drm/drm_client_modeset.c (ffffffff81c842d5)
Location: include/linux/string_choices.h:40
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe
```
```
In drivers/gpu/drm/drm_edid.c (ffffffff81c937bf)
Location: include/linux/string_choices.h:40
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext
  - drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9daec)
Location: include/linux/string_choices.h:40
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_print_info
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
