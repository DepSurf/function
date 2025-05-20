# Function: <code>snd_soc_component_update_bits</code>

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
<summary>In <code>armhf</code>: ✅</summary>

```c
int snd_soc_component_update_bits(struct snd_soc_component *component, unsigned int reg, unsigned int mask, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In sound/soc/soc-io.c (c0cb56dc)
Location: sound/soc/soc-io.c:109
Inline: False
Direct callers:
  - sound/soc/soc-dapm.c:dapm_power_widgets
  - sound/soc/soc-dapm.c:dapm_power_widgets
  - sound/soc/soc-dapm.c:dapm_seq_run_coalesced
  - sound/soc/soc-ops.c:snd_soc_put_strobe
  - sound/soc/soc-ops.c:snd_soc_put_strobe
  - sound/soc/soc-ops.c:snd_soc_put_xr_sx
  - sound/soc/soc-ops.c:snd_soc_put_volsw_range
  - sound/soc/soc-ops.c:snd_soc_put_volsw_range
  - sound/soc/soc-ops.c:snd_soc_put_volsw_sx
  - sound/soc/soc-ops.c:snd_soc_put_volsw_sx
  - sound/soc/soc-ops.c:snd_soc_put_volsw
  - sound/soc/soc-ops.c:snd_soc_put_volsw
  - sound/soc/soc-ops.c:snd_soc_put_volsw
  - sound/soc/soc-ops.c:snd_soc_put_enum_double
  - sound/soc/soc-ac97.c:snd_soc_ac97_gpio_direction_out
  - sound/soc/soc-ac97.c:snd_soc_ac97_gpio_direction_in
  - sound/soc/codecs/sgtl5000.c:sgtl5000_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_probe
  - sound/soc/codecs/sgtl5000.c:sgtl5000_pcm_hw_params
  - sound/soc/codecs/sgtl5000.c:sgtl5000_pcm_hw_params
  - sound/soc/codecs/sgtl5000.c:sgtl5000_set_clock
  - sound/soc/codecs/sgtl5000.c:sgtl5000_set_clock
  - sound/soc/codecs/sgtl5000.c:sgtl5000_set_clock
  - sound/soc/codecs/sgtl5000.c:sgtl5000_digital_mute
  - sound/soc/codecs/sgtl5000.c:vag_and_mute_control
  - sound/soc/codecs/sgtl5000.c:vag_and_mute_control
  - sound/soc/codecs/sgtl5000.c:vag_and_mute_control
  - sound/soc/codecs/sgtl5000.c:vag_and_mute_control
  - sound/soc/codecs/sgtl5000.c:vag_and_mute_control
  - sound/soc/codecs/sgtl5000.c:mic_bias_event
  - sound/soc/codecs/sgtl5000.c:mic_bias_event
```
**Symbols:**

```
c0cb56dc-c0cb576c: snd_soc_component_update_bits (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
