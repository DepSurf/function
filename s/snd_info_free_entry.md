# Function: <code>snd_info_free_entry</code>

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
void snd_info_free_entry(struct snd_info_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In sound/core/info.c (c0c89040)
Location: sound/core/info.c:767
Inline: False
Direct callers:
  - sound/core/info.c:snd_info_free_entry
  - sound/core/info.c:snd_info_card_free
  - sound/core/info.c:snd_info_done
  - sound/core/info.c:snd_info_init
  - sound/core/info.c:create_subdir
  - sound/core/timer.c:alsa_timer_init
  - sound/core/timer.c:snd_timer_proc_done
  - sound/core/pcm.c:alsa_pcm_exit
  - sound/core/pcm.c:alsa_pcm_init
  - sound/core/pcm.c:snd_pcm_free_stream
  - sound/core/compress_offload.c:snd_compress_dev_free
  - sound/core/compress_offload.c:snd_compress_dev_free
```
**Symbols:**

```
c0c89040-c0c89120: snd_info_free_entry (STB_GLOBAL)
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
