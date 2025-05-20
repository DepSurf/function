# Function: <code>hw_param_interval</code>

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
In sound/core/pcm_native.c (c0c91694)
Location: include/sound/pcm.h:886
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_hw_rule_buffer_bytes_max
  - sound/core/pcm_native.c:snd_pcm_hw_rule_rate
  - sound/core/pcm_native.c:snd_pcm_hw_rule_sample_bits
  - sound/core/pcm_native.c:snd_pcm_hw_rule_mulkdiv
  - sound/core/pcm_native.c:snd_pcm_hw_rule_muldivk
  - sound/core/pcm_native.c:snd_pcm_hw_rule_div
  - sound/core/pcm_native.c:snd_pcm_hw_rule_mul
```
```
In sound/core/pcm_lib.c (c0c98708)
Location: include/sound/pcm.h:886
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:snd_pcm_hw_param_last
  - sound/core/pcm_lib.c:snd_pcm_hw_param_first
  - sound/core/pcm_lib.c:snd_pcm_hw_rule_noresample_func
  - sound/core/pcm_lib.c:snd_pcm_hw_rule_pow2
  - sound/core/pcm_lib.c:snd_pcm_hw_rule_step
  - sound/core/pcm_lib.c:snd_pcm_hw_rule_ratdens
  - sound/core/pcm_lib.c:snd_pcm_hw_rule_ratnums
  - sound/core/pcm_lib.c:snd_pcm_hw_rule_ranges
  - sound/core/pcm_lib.c:snd_pcm_hw_rule_list
```
```
In sound/core/pcm_drm_eld.c (c0c9c36c)
Location: include/sound/pcm.h:886
Inline: True
Inline callers:
  - sound/core/pcm_drm_eld.c:eld_limit_channels
  - sound/core/pcm_drm_eld.c:eld_limit_rates
```
```
In sound/soc/soc-dapm.c (0)
Location: include/sound/pcm.h:886
Inline: True
```
```
In sound/soc/soc-pcm.c (0)
Location: include/sound/pcm.h:886
Inline: True
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
