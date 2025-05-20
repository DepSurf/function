# Function: <code>snd_interval_refine</code>

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
int snd_interval_refine(struct snd_interval *i, const struct snd_interval *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In sound/core/pcm_lib.c (c0c971e0)
Location: sound/core/pcm_lib.c:569
Inline: False
Direct callers:
  - sound/core/pcm_native.c:snd_pcm_hw_rule_buffer_bytes_max
  - sound/core/pcm_native.c:snd_pcm_hw_rule_sample_bits
  - sound/core/pcm_native.c:snd_pcm_hw_rule_mulkdiv
  - sound/core/pcm_native.c:snd_pcm_hw_rule_muldivk
  - sound/core/pcm_native.c:snd_pcm_hw_rule_div
  - sound/core/pcm_native.c:snd_pcm_hw_rule_mul
  - sound/core/pcm_lib.c:snd_pcm_hw_rule_ratdens
  - sound/core/pcm_lib.c:snd_pcm_hw_constraint_minmax
  - sound/core/pcm_lib.c:snd_interval_ranges
  - sound/core/pcm_lib.c:snd_interval_ranges
  - sound/core/pcm_lib.c:snd_interval_list
  - sound/core/pcm_lib.c:snd_interval_ratnum
  - sound/core/pcm_drm_eld.c:eld_limit_channels
```
**Symbols:**

```
c0c971e0-c0c97380: snd_interval_refine (STB_GLOBAL)
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
