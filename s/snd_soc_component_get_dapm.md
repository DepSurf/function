# Function: <code>snd_soc_component_get_dapm</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In sound/soc/soc-core.c (c0ca1190)
Location: include/sound/soc-component.h:179
Inline: True
Inline callers:
  - sound/soc/soc-core.c:snd_soc_register_dai
  - sound/soc/soc-core.c:soc_probe_component
  - sound/soc/soc-core.c:soc_cleanup_component
```
```
In sound/soc/soc-dapm.c (c0ca6a5c)
Location: include/sound/soc-component.h:179
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:dapm_widget_show
```
```
In sound/soc/soc-component.c (c0caea5c)
Location: include/sound/soc-component.h:179
Inline: True
Inline callers:
  - sound/soc/soc-component.c:snd_soc_component_force_enable_pin_unlocked
  - sound/soc/soc-component.c:snd_soc_component_force_enable_pin
  - sound/soc/soc-component.c:snd_soc_component_get_pin_status
  - sound/soc/soc-component.c:snd_soc_component_nc_pin_unlocked
  - sound/soc/soc-component.c:snd_soc_component_nc_pin
  - sound/soc/soc-component.c:snd_soc_component_disable_pin_unlocked
  - sound/soc/soc-component.c:snd_soc_component_disable_pin
  - sound/soc/soc-component.c:snd_soc_component_enable_pin_unlocked
  - sound/soc/soc-component.c:snd_soc_component_enable_pin
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
