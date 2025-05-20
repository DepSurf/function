# Function: <code>devlink_flash_component_lookup_cb</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devlink_flash_component_lookup_cb(const char *version_name, enum devlink_info_version_type version_type, void *version_cb_priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81e2cc5e)
Location: net/core/devlink.c:5019
Inline: True
```
**Symbols:**

```
ffffffff81e2cc30-ffffffff81e2cc8f: devlink_flash_component_lookup_cb (STB_LOCAL)
ffffffff820acdb7-ffffffff820acdcc: devlink_flash_component_lookup_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devlink_flash_component_lookup_cb(const char *version_name, enum devlink_info_version_type version_type, void *version_cb_priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/dev.c (ffffffff82042d8e)
Location: net/devlink/dev.c:981
Inline: True
```
**Symbols:**

```
ffffffff82042d60-ffffffff82042dbf: devlink_flash_component_lookup_cb (STB_LOCAL)
ffffffff82136660-ffffffff82136675: devlink_flash_component_lookup_cb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devlink_flash_component_lookup_cb(const char *version_name, enum devlink_info_version_type version_type, void *version_cb_priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/dev.c (ffffffff8210210e)
Location: net/devlink/dev.c:1082
Inline: True
```
**Symbols:**

```
ffffffff821020e0-ffffffff8210213f: devlink_flash_component_lookup_cb (STB_LOCAL)
ffffffff82217fb9-ffffffff82217fce: devlink_flash_component_lookup_cb.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
