# Function: <code>snd_pcm_hw_rule_add</code>

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
int snd_pcm_hw_rule_add(struct snd_pcm_runtime *runtime, unsigned int cond, int var, snd_pcm_hw_rule_func_t func, void *private, int dep, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In sound/core/pcm_lib.c (c0c97d78)
Location: sound/core/pcm_lib.c:1108
Inline: False
Direct callers:
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_complete
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_complete
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_native.c:snd_pcm_hw_constraints_init
  - sound/core/pcm_lib.c:snd_pcm_hw_rule_noresample
  - sound/core/pcm_lib.c:snd_pcm_hw_constraint_pow2
  - sound/core/pcm_lib.c:snd_pcm_hw_constraint_step
  - sound/core/pcm_lib.c:snd_pcm_hw_constraint_msbits
  - sound/core/pcm_lib.c:snd_pcm_hw_constraint_ratdens
  - sound/core/pcm_lib.c:snd_pcm_hw_constraint_ratnums
  - sound/core/pcm_lib.c:snd_pcm_hw_constraint_ranges
  - sound/core/pcm_lib.c:snd_pcm_hw_constraint_list
```
**Symbols:**

```
c0c97d78-c0c97e8c: snd_pcm_hw_rule_add (STB_GLOBAL)
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
