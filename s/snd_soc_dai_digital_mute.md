# Function: <code>snd_soc_dai_digital_mute</code>

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
int snd_soc_dai_digital_mute(struct snd_soc_dai *dai, int mute, int direction);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In sound/soc/soc-dai.c (c0cae0e0)
Location: sound/soc/soc-dai.c:243
Inline: False
Direct callers:
  - sound/soc/soc-core.c:soc_resume_deferred
  - sound/soc/soc-core.c:snd_soc_suspend
  - sound/soc/soc-dapm.c:snd_soc_dai_link_event
  - sound/soc/soc-dapm.c:snd_soc_dai_link_event
  - sound/soc/soc-pcm.c:soc_pcm_hw_free
  - sound/soc/soc-pcm.c:soc_pcm_prepare
  - sound/soc/soc-pcm.c:soc_pcm_prepare
  - sound/soc/soc-pcm.c:soc_pcm_close
  - sound/soc/soc-compress.c:soc_compr_trigger
  - sound/soc/soc-compress.c:soc_compr_trigger
  - sound/soc/soc-compress.c:soc_compr_free
```
**Symbols:**

```
c0cae0e0-c0cae138: snd_soc_dai_digital_mute (STB_GLOBAL)
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
