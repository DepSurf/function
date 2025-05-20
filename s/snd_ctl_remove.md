# Function: <code>snd_ctl_remove</code>

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
int snd_ctl_remove(struct snd_card *card, struct snd_kcontrol *kcontrol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In sound/core/control.c (c0c8523c)
Location: sound/core/control.c:461
Inline: False
Direct callers:
  - sound/core/control.c:snd_ctl_dev_free
  - sound/core/control.c:snd_ctl_remove_user_ctl
  - sound/core/control.c:snd_ctl_remove_id
  - sound/core/control.c:__snd_ctl_add_replace
  - sound/core/jack.c:snd_jack_dev_free
  - sound/core/pcm.c:snd_pcm_dev_disconnect
  - sound/core/pcm.c:snd_pcm_dev_disconnect
  - sound/core/pcm.c:snd_pcm_free_stream
  - sound/soc/soc-topology.c:snd_soc_tplg_component_remove
  - sound/soc/soc-topology.c:snd_soc_tplg_component_remove
  - sound/soc/soc-topology.c:snd_soc_tplg_component_remove
  - sound/soc/soc-topology.c:remove_widget
  - sound/soc/soc-topology.c:remove_widget
```
**Symbols:**

```
c0c8523c-c0c85364: snd_ctl_remove (STB_GLOBAL)
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
